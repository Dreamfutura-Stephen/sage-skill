<p align="center">
  <img src="demo.png" alt="Wise Sage — Socratic Thinking Companion" width="780">
</p>

<h1 align="center">智者 Skill — Wise Sage</h1>

<p align="center">
  <b>其他 Skill 是"帮你做决策"——智者 Skill 是"让你自己想明白"。</b><br>
  <i>Not a chatbot. Not a quote search engine. A Socratic thinking trainer.</i>
</p>

<p align="center">
  <a href="#english">🇬🇧 English</a> •
  <a href="#简体中文">🇨🇳 简体中文</a> •
  <a href="#繁體中文">🇭🇰 繁體中文</a> •
  <a href="#日本語">🇯🇵 日本語</a> •
  <a href="#한국어">🇰🇷 한국어</a> •
  <a href="#français">🇫🇷 Français</a> •
  <a href="#latina">🏛️ Latina</a>
</p>

---

## English

> Wise Sage distills history's greatest thinkers into **conversational thinking companions**. It questions your assumptions, exposes your blind spots, gives you new cognitive frameworks, and lets you find your own answers.

### The Core Idea

Every other Claude Code skill is designed to **give you an answer** — generate code, write a doc, design a prototype. Wise Sage is the opposite. It **teaches you how to think** by putting you in conversation with the greatest minds in history.

When you talk to a sage, they won't tell you what to do. They'll ask you better questions.

### Four Modes

| Mode | Usage | What It Does |
|------|-------|--------------|
| 🧪 **Distill** | `distill Socrates` | Generates a complete cognitive profile: first principles, core thinking frameworks, internal tensions, boundary statements, intellectual genealogy, and known criticisms. Each profile is built through a rigorous 6-dimension research pipeline. |
| 💬 **Dialogue** | `talk to Confucius` | Socratic Q&A in 4 escalating tiers: **rebound** (ask you to clarify first) → **expose assumptions** (challenge unexamined premises) → **inject framework** (reframe through the sage's thinking model) → **boundary reminder** (always disclose the sage's era and limitations). |
| ⚖️ **Compare** | `compare Nietzsche vs Camus on freedom` | Places two thinkers side by side on the same question. Reveals where their frameworks align, where they diverge, and what each would ask you to reconsider. |
| 🪑 **Roundtable** | `roundtable "meaning of life" invite Zhuangzi Camus Wang Yangming` | Cross-temporal intellectual collision. Multiple sages respond to the same question from their own frameworks. Watch history's greatest minds debate — and find your own synthesis. |

> **Don't know whom to talk to?** Just state your dilemma (e.g., "I keep hesitating on decisions"). The skill diagnoses your situation across 8 dilemma dimensions and recommends 2–3 sages best suited to help.

### 18 Sages

| Domain | Sages |
|--------|-------|
| 🏯 Eastern Philosophy | Laozi, Zhuangzi, Confucius, Wang Yangming |
| 🏛️ Classical Western | Socrates, Plato, Aristotle |
| 🌆 Modern Western | Nietzsche, Wittgenstein, Foucault |
| 🔬 Science & Mathematics | Einstein, Feynman, Darwin |
| 📖 Literature & Humanity | Lu Xun, Shakespeare, Dostoevsky |
| 💼 Business & Leadership | Charles Munger, Kazuo Inamori |

Each sage has a complete cognitive archive in the `archives/` directory, built through a v2 distillation framework with 6-dimension parallel research, 4-layer verification, and 3-tier screening.

### Core Principles

1. **No answers, only mirrors and ladders** — your困惑 can only be resolved by you. The sage provides cognitive tools, not conclusions.
2. **Quote original texts when fitting; think within the framework when not** — if a relevant passage exists, cite it with source (e.g., 《述而》30). If not, respond through the sage's core thinking patterns (e.g., Confucius' "叩其两端", Zhuangzi's "齐物", Socrates' elenchus).
3. **Always expose boundaries** — every response includes: what era this sage lived in, what they never encountered in their lifetime, and what uncertainties they themselves acknowledged. No exceptions.
4. **5 hard restrictions:**
   - No political topics — redirect to the underlying life dilemma
   - No fabricating quotes or positions the sage never held
   - No packaging common sense as the sage's "unique insight"
   - No hiding controversies or negative evaluations
   - No forced generation when data is insufficient — admit ignorance honestly

### How It's Different

| | Regular Skill | **Wise Sage** |
|---|---|---|
| Role | Advisor (tells you what to do) | **Sparring partner** (helps you think) |
| Output | Gives you answers | **Gives you questions** |
| Interaction | Executes commands | **Challenges your assumptions** |
| Boundaries | Optional, may be omitted | **Always exposed, never optional** |
| Knowledge | Static instructions | **Living cognitive frameworks** |

### Installation

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

Usage in Claude Code:

```
💬 talk to Zhuangzi
🧪 distill Nietzsche
⚖️ compare Confucius vs Wang Yangming on "unity of knowledge and action"
🪑 roundtable "meaning of life" invite Zhuangzi Camus Wang Yangming
💡 I keep hesitating on decisions — recommend a sage for me
```

### Project Structure

```
sage-skill/
├── SKILL.md              # Main skill definition (Phase 0-4 pipeline + dialogue protocol)
├── README.md             # This file (7 languages)
├── CHANGELOG.md          # Version history
├── LICENSE               # MIT
├── demo.html             # Interactive demo page (open in browser for full experience)
├── demo.png              # Demo screenshot
└── archives/             # 18 complete sage cognitive profiles
    ├── sage-zhuangzi/    # Zhuangzi
    ├── sage-kongzi/      # Confucius
    ├── sage-socrates/    # Socrates
    ├── sage-nietzsche/   # Nietzsche
    ├── sage-einstein/    # Einstein
    ├── ... and 13 more
```

---

## 简体中文

> 智者 Skill 把历史上的智者蒸馏为**可对话的思维训练伙伴**。不是聊天机器人，不是语录搜索引擎，而是苏格拉底式的思维陪练。

### 核心理念

所有其他 Claude Code Skill 都是"帮你做决策"——生成代码、写文档、做设计。智者 Skill 正好相反：**它教你如何思考**。

当你与一位智者对话，他不会告诉你该怎么做。他会问你更好的问题。

### 四种模式

| 模式 | 用法 | 说明 |
|------|------|------|
| 🧪 **蒸馏** | `蒸馏 庄子` | 生成完整的智者认知档案：第一性原理、核心思维框架、内在张力、边界声明、智识谱系、已知批评。通过六维并行调研 + 四重验证 + 三重筛选构建。 |
| 💬 **对话** | `与 孔子 对话` | 苏格拉底式问答，四层递进：**反弹**（让你先说）→ **暴露假设**（挑战未检验的前提）→ **框架注入**（用智者思维模型重新审视）→ **边界提醒**（永远披露时代局限）。 |
| ⚖️ **比较** | `比较 尼采 vs 加缪 关于自由` | 把两种思维框架放在同一问题下——哪里一致、哪里分歧、各自会让你追问什么。 |
| 🪑 **圆桌** | `圆桌 人生的意义 邀请 庄子 加缪 王阳明` | 跨时空思想碰撞。多位智者从各自框架出发回应同一问题——看历史上的伟大头脑如何交锋。 |

> **不知道找谁聊？** 直接说出你的困惑（如"我总是做不好决策"），Skill 会从 8 个困境维度诊断，推荐 2–3 位最适合的智者。

### 已覆盖智者（18 位）

| 领域 | 智者 |
|------|------|
| 🏯 东方哲学 | 老子、庄子、孔子、王阳明 |
| 🏛️ 西方古典 | 苏格拉底、柏拉图、亚里士多德 |
| 🌆 西方现代 | 尼采、维特根斯坦、福柯 |
| 🔬 科学思想 | 爱因斯坦、费曼、达尔文 |
| 📖 文学洞见 | 鲁迅、莎士比亚、陀思妥耶夫斯基 |
| 💼 商业智慧 | 查理·芒格、稻盛和夫 |

每位智者在 `archives/` 下有完整档案，通过 v2 蒸馏框架构建。

### 核心原则

1. **不给答案，给镜子和梯子**——你的困惑只有你自己能解开。智者提供的是认知工具，不是结论。
2. **合适时引用原典，不合适时按思维框架生成**——有切合场景的原典就引用并标注篇目；没有时，根据智者的核心思维模型（如孔子的叩其两端、庄子的齐物、苏格拉底的问答法）生成符合其人物特征的回应。
3. **永远暴露边界**——每次回答都附带该思想的局限。没有例外。
4. **五条硬限制**：不讨论政治敏感话题 → 不编造智者没说过的话 → 不把通用道理包装成独特见解 → 不忽略争议和负面评价 → 信息不足时不强行生成。

### 与常规 Skill 的区别

| | 常规 Skill | **智者 Skill** |
|---|---|---|
| 角色 | 顾问（告诉你怎么做） | **陪练（帮你思考）** |
| 输出 | 给你答案 | **给你问题** |
| 交互 | 执行指令 | **挑战你的假设** |
| 边界 | 可选，可能略过 | **强制暴露，必有** |
| 知识 | 静态指令 | **活的思维框架** |

### 安装

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

在 Claude Code 中使用：

```
💬 与庄子对话
🧪 蒸馏尼采
⚖️ 比较孔子 vs 王阳明 关于知行合一
🪑 圆桌 人生的意义 邀请 庄子 加缪 王阳明
💡 我总是纠结选择——有没有合适的智者可以帮我看看
```

---

## 繁體中文

> 智者 Skill 將歷史上的智者蒸餾為**可對話的思維訓練夥伴**——不是聊天機器人，不是語錄搜尋引擎，而是蘇格拉底式的思維陪練。

### 四種模式

| 模式 | 用法 | 效果 |
|------|------|------|
| 🧪 **蒸餾** | `蒸餾 莊子` | 生成完整的智者認知檔案 |
| 💬 **對話** | `與 孔子 對話` | 蘇格拉底式問答：反彈→暴露假設→框架注入→邊界提醒 |
| ⚖️ **比較** | `比較 尼采 vs 卡繆 關於自由` | 兩種思維框架的同與異 |
| 🪑 **圓桌** | `圓桌 人生的意義 邀請 莊子 卡繆 王陽明` | 跨時空思想碰撞 |

### 覆蓋智者（18 位）

| 領域 | 智者 |
|------|------|
| 🏯 東方哲學 | 老子、莊子、孔子、王陽明 |
| 🏛️ 西方古典 | 蘇格拉底、柏拉圖、亞里斯多德 |
| 🌆 西方現代 | 尼采、維根斯坦、傅柯 |
| 🔬 科學思想 | 愛因斯坦、費曼、達爾文 |
| 📖 文學洞見 | 魯迅、莎士比亞、杜斯妥也夫斯基 |
| 💼 商業智慧 | 查理·芒格、稻盛和夫 |

### 安裝

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

---

## 日本語

> 智者 Skill（ワイズセージ）は、歴史上の賢人たちを**対話可能な思考トレーニングパートナー**として蒸留します。チャットボットでも名言検索エンジンでもなく、ソクラテス式の思考トレーナーです。

### 4つのモード

| モード | 使い方 | 効果 |
|--------|--------|------|
| 🧪 **蒸留** | `蒸留 荘子` | 賢者の完全な認知プロファイルを生成 |
| 💬 **対話** | `孔子 と対話` | ソクラテス式問答：跳ね返し→前提暴露→枠組み注入→境界提醒 |
| ⚖️ **比較** | `比較 ニーチェ vs カミュ 自由について` | 二つの思考枠組みの比較 |
| 🪑 **円卓** | `円卓 人生の意味 招待 荘子 カミュ 王陽明` | 時空を超えた思想の衝突 |

### カバーする賢人（18名）

| 領域 | 賢人 |
|------|------|
| 🏯 東洋哲学 | 老子、荘子、孔子、王陽明 |
| 🏛️ 西洋古典 | ソクラテス、プラトン、アリストテレス |
| 🌆 西洋現代 | ニーチェ、ウィトゲンシュタイン、フーコー |
| 🔬 科学思想 | アインシュタイン、ファインマン、ダーウィン |
| 📖 文学 | 魯迅、シェイクスピア、ドストエフスキー |
| 💼 ビジネス | チャーリー・マンガー、稲盛和夫 |

### インストール

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

---

## 한국어

> 지혜자 Skill（와이즈 세이지）은 역사상의 현인들을 **대화 가능한 사고 훈련 파트너**로 증류합니다. 챗봇도 명언 검색 엔진도 아닌, 소크라테스식 사고 훈련 도구입니다.

### 4가지 모드

| 모드 | 사용법 | 효과 |
|------|--------|------|
| 🧪 **증류** | `증류 장자` | 현인의 전체 인지 프로필 생성 |
| 💬 **대화** | `공자와 대화` | 소크라테스식 문답 |
| ⚖️ **비교** | `비교 니체 vs 카뮈 자유에 대하여` | 두 사고 체계 비교 |
| 🪑 **원탁** | `원탁 인생의 의미 초대 장자 카뮈 왕양명` | 시공간 초월 사상 충돌 |

### 현인 목록 (18명)

| 영역 | 현인 |
|------|------|
| 🏯 동양 철학 | 노자, 장자, 공자, 왕양명 |
| 🏛️ 서양 고전 | 소크라테스, 플라톤, 아리스토텔레스 |
| 🌆 서양 현대 | 니체, 비트겐슈타인, 푸코 |
| 🔬 과학 | 아인슈타인, 파인만, 다윈 |
| 📖 문학 | 루쉰, 셰익스피어, 도스토옙스키 |
| 💼 비즈니스 | 찰리 멍거, 이나모리 가즈오 |

### 설치

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

---

## Français

> Wise Sage distille les plus grands penseurs de l'histoire en **compagnons de pensée conversationnels** — pas un chatbot, pas un moteur de citations, mais un véritable entraîneur de pensée socratique.

### Quatre modes

| Mode | Utilisation | Effet |
|------|-------------|-------|
| 🧪 **Distiller** | `distiller Tchouang-tseu` | Générer un profil cognitif complet du sage |
| 💬 **Dialoguer** | `dialoguer avec Confucius` | Dialogue socratique en 4 niveaux |
| ⚖️ **Comparer** | `comparer Nietzsche vs Camus sur la liberté` | Comparer deux cadres de pensée |
| 🪑 **Table ronde** | `table ronde "sens de la vie" inviter Tchouang-tseu Camus Wang Yangming` | Confrontation trans-temporelle |

### Sages couverts (18)

| Domaine | Sages |
|---------|-------|
| 🏯 Philosophie orientale | Lao Tseu, Tchouang-tseu, Confucius, Wang Yangming |
| 🏛️ Philosophie classique | Socrate, Platon, Aristote |
| 🌆 Philosophie moderne | Nietzsche, Wittgenstein, Foucault |
| 🔬 Science | Einstein, Feynman, Darwin |
| 📖 Littérature | Lu Xun, Shakespeare, Dostoïevski |
| 💼 Sagesse d'entreprise | Charles Munger, Kazuo Inamori |

### Installation

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

---

## Latina

> Sapiens Ars clarissimos cogitatores historiae in **meditationis socios** excoquit — non automaton loquax, non quaestor sententiarum, sed meditationis Socraticae exercitator.

### Quattuor modi

| Modus | Usus | Effectus |
|-------|------|----------|
| 🧪 **Excoquere** | `excoquere Tschuang-tzu` | Plenum cognitum profile generare |
| 💬 **Colloqui** | `colloqui cum Confuci` | Interrogatio Socratica |
| ⚖️ **Comparare** | `comparare Nietzsche et Camus de libertate` | Duas compages cogitandi comparare |
| 🪑 **Mensa rotunda** | `mensa rotunda "sensus vitae" invita Tschuang-tzu Camus Wang Yangming` | Cogitationum concursus trans tempora |

### Sapientes (XVIII)

| Regio | Sapientes |
|-------|-----------|
| 🏯 Philosophia orientalis | Laotius, Tschuang-tzu, Confucius, Wang Yangming |
| 🏛️ Philosophia classica | Socrates, Plato, Aristoteles |
| 🌆 Philosophia moderna | Nietzsche, Wittgenstein, Foucault |
| 🔬 Scientia | Einstein, Feynman, Darwin |
| 📖 Litterae | Lu Xun, Shakespeare, Dostoevskij |
| 💼 Prudentia mercatoria | Carolus Munger, Kazuo Inamori |

### Installatio

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

---

## Project Structure

```
sage-skill/
├── SKILL.md              # Main skill definition
├── README.md             # This file (7 languages)
├── CHANGELOG.md          # Version history
├── LICENSE               # MIT
├── demo.html             # Interactive demo page
├── demo.png              # Demo screenshot
└── archives/             # 18 sage cognitive profiles
    ├── sage-zhuangzi/    # 庄子 / Zhuangzi
    ├── sage-kongzi/      # 孔子 / Confucius
    ├── sage-socrates/    # Σωκράτης / Socrates
    ├── sage-nietzsche/   # 尼采 / Nietzsche
    ├── sage-einstein/    # Einstein
    ├── ... and 13 more
```

---

## License

MIT — 2026 Dreamfutura-Stephen
