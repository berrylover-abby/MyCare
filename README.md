# MyCare

**A gentle personal growth app for starting tasks, building routines, and making room for self-care.**

MyCare helps people begin, focus, recover, and reflect when their energy changes. Its design centers on one clear next step, low-pressure participation, and a calm bilingual experience.

## Interface preview

![MyCare notes interface in the lavender theme](screenshots/notes-preview.png)

*An earlier interface preview of notes for your future self. The product continues to evolve.*

## What it does

- **Daily care:** morning and bedtime routines, with a low-energy mode.
- **Focus and goals:** timed focus sessions, breaks, categories, deadlines, and completion reflections.
- **Habit Garden:** gentle habit tracking with low-energy alternatives.
- **Notes for your future self:** private reflections and mood notes.
- **Personal insights:** lightweight charts for routines, focus, habits, and goals.
- **Family sharing:** shared goals and optional sharing of selected summary statistics, separate from private personal records.
- **Health imports:** manual CSV, JSON, and Apple Health XML imports for local trend exploration. Direct wearable API synchronization is not available yet.
- **Personalization:** Chinese and English, visual themes, custom categories, and editable morning quotes.

## Technical highlights

**Built with:** HTML, CSS, JavaScript, and Supabase Auth/Postgres.

- **Local-first storage:** personal changes are saved on the device first; account login and cloud synchronization are optional.
- **Cross-device synchronization:** revision checks detect outdated writes, and queued saves preserve changes made during an upload.
- **Recovery:** portable JSON backups and cloud version history support restoring previous personal state.
- **Separate sharing boundaries:** family features use separate data structures; shared statistics are opt-in summaries.
- **Responsive, bilingual interface:** calm visuals and clear interactions support desktop and mobile use.

Imported health records currently stay local and do not sync across devices. MyCare is a self-management and reflection tool, not a medical service.

## Project status

MyCare is an independently developed project under active development. This repository is a portfolio showcase containing project documentation and interface imagery. Application source code is maintained separately in a private repository.

## Source availability

Source code is not distributed in this showcase. No open-source license is granted for the MyCare application by this repository. Third-party materials retain their respective rights.

---

## 中文介绍

MyCare 是一款温柔的个人成长与自我照顾应用，帮助用户在不同精力状态下开始任务、保持专注、建立日常习惯，并记录自己的感受。

核心功能包括晨间与睡前流程、专注计时、个人与家庭目标、习惯花园、写给未来自己的小纸条，以及轻量统计。支持中英文切换与个性化主题。

项目采用 HTML、CSS、JavaScript 和 Supabase，优先保存本地数据，并提供可选云同步、备份与历史恢复。家庭统计分享需要主动选择，分享内容以摘要为主。

本仓库仅用于作品展示，不提供应用源代码。
