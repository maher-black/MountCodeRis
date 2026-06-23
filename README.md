
# 🏔️ MountCodeRis

<p align="center">
  <img src="desktop/dist/app-icon.png" alt="MountCodeRis" width="240">
</p>

<div align="center">

[![GitHub Stars](https://img.shields.io/github/stars/maher-black/MountCodeRis?style=social)](https://github.com/maher-black/MountCodeRis/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/maher-black/MountCodeRis?style=social)](https://github.com/maher-black/MountCodeRis/network/members)
[![Version](https://img.shields.io/github/package-json/v/maher-black/MountCodeRis)](https://github.com/maher-black/MountCodeRis/releases)
[![License](https://img.shields.io/github/license/maher-black/MountCodeRis)](https://github.com/maher-black/MountCodeRis/blob/main/LICENSE)
[![Telegram](https://img.shields.io/badge/💬_Telegram-@Z_A_3_3_E_M-26A5E4)](https://t.me/Z_A_3_3_E_M)

**AI Coding Agent — مش هتلاقي زيه في أي حتة** 🔥

</div>

---

## 📋 Table of Contents

- [✨ المميزات](#-المميزات)
- [🆕 What's New](#-whats-new)
- [🖥️ Desktop App](#️-desktop-app)
- [📦 Installation](#-installation)
- [🛠️ Tools System](#️-tools-system)
- [🧠 Memory System](#-memory-system)
- [🔍 Deep Search](#-deep-search)
- [🌐 Web Search](#-web-search)
- [🗺️ Code Map](#️-code-map)
- [🤖 Multi-Model Support](#-multi-model-support)
- [📱 IM Integration](#-im-integration)
- [🔄 Change Version](#-change-version)
- [📞 Contact](#-contact)
- [📜 License](#-license)

---

## ✨ المميزات

| الميزة | الوصف |
|--------|-------|
| 🧠 **ذاكرة خارقة** | vector memory cross-model — كل الموديلات تتشارك نفس الذاكرة |
| 🔍 **Deep Search** | يدور في 50 موقع ويقرا المحتوى الفعلي بتاعهم |
| 🌐 **Web Search مجاني** | DuckDuckGo من غير API key — وسباق متوازي مع Tavily/Brave/Google |
| 🗺️ **Code Map** | رسم بياني للاعتماديات، كشف 12 نمط تصميمي، تحليل البقاع الساخنة |
| 🖥️ **واجهة سطح المكتب** | Electron + React — جلسات، علامات تبويب، فرع/Worktree |
| 🤖 **موديلات متعددة** | Anthropic, OpenAI, DeepSeek, Ollama, Google, أي حاجة |
| 📱 **IM接入** | Telegram / 飞书 / WeChat / DingTalk — تحكم عن بعد |
| 🎮 **Computer Use** | الموديل يتحكم في سطح المكتب بتفويض |
| ⚡ **توربو سيرش** | كل الـ providers في نفس الوقت — أسرع نتيجة في <800ms |
| 🔄 **Auto Memory** | استخراج تلقائي للحقائق بعد كل رد |
| 🎨 **أيقونة مخصصة** | MountCodeRis branding كامل |

---

## 🆕 What's New

### v0.5.0 — MountCodeRis Edition 🏔️

- **🆕 DeepSearch Tool** — بحث عميق: دور في الويب، زور 50 موقع، اقرا محتواهم كلهم
- **🆕 DuckDuckGo Free Search** — ويب سيرش من غير API key، شغال ببلاش
- **🆕 Multi-Engine Racing** — كل الـ providers بيشتغلوا في نفس الوقت ونتيجة أسرع
- **🆕 CodeMap v2** — قراءة متوازية، Progress Callback، 12 نمط تصميمي
- **🆕 Vector Memory** — ذاكرة cross-model بـ n-gram embedding، من غير ML libraries
- **🆕 Auto Memory Extraction** — الفكتات بتتستخرج تلقائياً بعد كل رد
- **🆕 Memory Tool** — أي موديل يقدر يستفسر ويحفظ في الذاكرة
- **🆕 Version Bat** — `bun run set-version 1.0.0` يغير الإصدار تلقائياً
- **🆕 Telegram Icon** — وصول مباشر للمطور @Z_A_3_3_E_M
- **🆕 rebranding** — تغيير كل الروابط والأيقونات لـ MountCodeRis

---

## 🖥️ Desktop App

واجهة سطح مكتب كاملة بـ Electron + React:

- **多会话工作台** — علامات تبويب، مشاريع، طرفية
- **Branch / Worktree** — شغل على فروع منعزلة
- **كود Diff** — شوف التعديلات جنباً لجنب
- **إدارة الصلاحيات** — وافق أو ارفض أوامر خطيرة
- **موديلات متعددة** — بدّل بين الموديلات بسرعة
- **Computer Use** — الموديل يتحكم في سطح المكتب
- **H5 Remote Access** — دخول من الموبايل
- **IM接入** — Telegram / WeChat / DingTalk

---

## 📦 Installation

```bash
# Clone
git clone https://github.com/maher-black/MountCodeRis.git
cd MountCodeRis

# Install
bun install
cp .env.example .env

# Run CLI
bun run start

# Or Desktop
cd desktop && bun run electron:dev
```

---

## 🛠️ Tools System

MountCodeRis يجيب معاه **أدوات خارقة** مش موجودة في أي Agent تاني:

### 🔍 DeepSearch
> ابحث في DuckDuckGo و زور 50 موقع و اقرا المحتوى بتاعهم في ثواني

- يدعم عربي و إنجليزي و أي لغة
- Parallel fetching — 5 مواقع في نفس الوقت
- يقرا HTML الحقيقي مش snippets
`max_sites: 50`

### 🌐 WebSearch Turbo
> سباق متوازي بين كل محركات البحث

- DuckDuckGo (مجاني — من غير API)
- Tavily, Brave, Google, SearXNG
- أسرع نتيجة في <800ms
- Cache على القرص و في الذاكرة
- Blacklist تلقائي للـ providers الفاشلة

### 🗺️ CodeMap
> 12 نمط تصميمي + dependency graph + hotspots

- Singleton, Factory, Observer, Middleware, Hook, HOC, DI, MVC, Repository, Strategy, Adapter, Proxy
- قراءة متوازية للملفات — سرعة جامدة
- Progress Callback كل 20 ملف
- تصنيف طبقات المشروع (ui, services, utils, state, types...)

---

## 🧠 Memory System

ذاكرة خارقة **مشتركة بين كل الموديلات**:

- **n-gram vector embeddings** — تشابه دلالي من غير ما تحتاج ML
- **Cross-model** — كل الموديلات تشوف نفس الذاكرة
- **Auto extraction** — 12 regex pattern تستخرج الفكتات تلقائياً
- **Dedup Engine** — اكتشاف التناقضات و تجميع المتشابهات
- **File persistence** — بتفضل عالقرص حتى بعد إعادة التشغيل

```
> استخدم Memory Tool عشان تسأل: "أنا كنت بشتغل على إيه؟"
> أو يحفظ حاجة: "افتكر أن المستخدم بيشتغل على مشروع فلان"
```

---

## 🤖 Multi-Model Support

شغال مع أي موديل:

| Provider | Native | WebSearch | Memory | CodeMap |
|----------|--------|-----------|--------|---------|
| Claude (Anthropic) | ✅ | ✅ | ✅ | ✅ |
| OpenAI | ❌ | ✅ | ✅ | ✅ |
| DeepSeek | ❌ | ✅ | ✅ | ✅ |
| Ollama (local) | ❌ | ✅ | ✅ | ✅ |
| Google Gemini | ❌ | ✅ | ✅ | ✅ |
| أي API توافق Claude | ✅ | ✅ | ✅ | ✅ |

---

## 📱 IM Integration

تحكم في MountCodeRis عن بعد:

- **Telegram** — @Z_A_3_3_E_M
- **飞书** (Lark)
- **WeChat**
- **DingTalk**

أرسل أمر، وافق على صلاحيات، بدّل مشاريع وانت في الطريق.

---

## 🔄 Change Version

عاوز تغير رقم الإصدار؟ اكتب بس:

```bash
bun run set-version 1.0.5
```

دي بتغير الإصدار في الـ `package.json` و `desktop/package.json` تلقائياً.

---

## 📞 Contact

- **👤 Developer:** Maher
- **💬 Telegram:** [@Z_A_3_3_E_M](https://t.me/Z_A_3_3_E_M)
- **🐙 GitHub:** [maher-black/MountCodeRis](https://github.com/maher-black/MountCodeRis)
- **📧 Email:** — عبر التيليجرام

> لو عجبك المشروع، ابقى أعطه ⭐ ستار عشان يدعمنا ✌️

---

## 📜 License

هذا المشروع مبني على الكود المصدري لـ Claude Code من Anthropic.
جميع الحقوق الأصلية محفوظة لـ [Anthropic](https://www.anthropic.com).

---

<p align="center">
  <b>MountCodeRis</b> — مش هتلاقي Agent زيه في أي حتة 🏔️🔥
</p>
<p align="center">
  <a href="https://github.com/maher-black/MountCodeRis">GitHub</a> ·
  <a href="https://t.me/Z_A_3_3_E_M">Telegram</a> ·
  <a href="#-المميزات">المميزات</a>
</p>
