# Matrix — Downloads

> **Strategic Personal Professional System** — an all-in-one desktop app for developers to
> organize ideas, projects, planning, roadmaps, tasks, passwords, and development metrics.

This repository hosts the **downloadable installers** for Matrix Desktop.
The application source code lives in a separate private repository — only release binaries
are published here.

---

## 📥 Download

Get the latest version from the **[Releases](https://github.com/bpstack/matrix-releases/releases/latest)** page.

| Platform                 | File                 | How to install                                                                                          |
| ------------------------ | -------------------- | ------------------------------------------------------------------------------------------------------ |
| 🪟 **Windows**           | `Matrix-*.Setup.exe` | Double-click to install. SmartScreen may warn _"unknown publisher"_ — click **More info → Run anyway**. |
| 🐧 **Linux** (Debian/Ubuntu) | `matrix_*.deb`   | `sudo dpkg -i matrix_*.deb`, then launch **Matrix** from your app menu or run `matrix`.                 |

> 🍎 macOS is not packaged yet — planned for a future release.

### ⚠️ About the Windows SmartScreen warning

The Windows installer is not code-signed yet, so SmartScreen shows an _"unknown publisher"_
notice. This is expected and does not mean the app is unsafe. To proceed: **More info → Run anyway**.

---

## ✨ What is Matrix?

A local-first desktop app (Electron) that brings together everything a developer juggles:

- 💡 **Ideas** — capture, score, and promote ideas into actionable items
- 📁 **Projects** — track multiple projects with real progress metrics (lines of code, deps, git status)
- 📋 **Planning** — Mission → Objectives → Plans → Tasks hierarchy with automatic progress roll-up
- ✅ **Tasks** — Kanban board + list views
- 🔐 **Passwords** — local vault encrypted with AES-256-GCM, master-password protected
- 📝 **Docs** — nested markdown documentation
- 📊 **Metrics** — development analytics and dashboards

Everything runs **offline** and stays **on your machine** — no account, no cloud required.

---

## 🔒 Privacy

Matrix is local-first. Your data lives in a local SQLite database on your computer; the
password vault is encrypted with AES-256-GCM. Nothing is sent to any server.

---

## 📦 Releases

Each release includes the Windows installer (`.exe` + `.nupkg` + `RELEASES` for future
auto-updates) and the Linux `.deb`. See the
[Releases page](https://github.com/bpstack/matrix-releases/releases) for version history.
