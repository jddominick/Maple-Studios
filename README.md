# Maple Studios

Maple is a retro-computer desktop for making games with Claude Code. Pick a project folder, and Maple opens a Claude Code terminal bound to that project, with her own memory of the work.

This repo only hosts the installer and updates. The source is private.

## Install

1. Download **Maple-Studios-Setup-x.y.z.exe** from [Releases](../../releases/latest) and run it. No admin rights needed.
   Windows may show "Windows protected your PC" because the installer isn't code-signed. Click **More info → Run anyway**.
2. Install [Git for Windows](https://git-scm.com/download/win) if you don't have it.
3. Start Maple from the desktop shortcut. If Claude Code isn't installed yet, double-click **Install Claude Code** on Maple's desktop.
4. Double-click **Add project** and choose a folder that is a git repository (for a new game: make a folder, then run `git init` in it, or create the repo on GitHub and clone it).
5. Double-click the project. The first time, Claude Code asks you to sign in with a Claude account (Pro or Max) or paste an Anthropic API key.

Requires Windows 10 or 11, 64-bit.

## Updates

Every time Maple boots she checks for a new version and asks: **[Y] INSTALL UPDATE** or **[N] LATER**. Yes downloads it, installs it and restarts Maple. Your projects, sessions and Maple's memory are kept (they live in `%APPDATA%\Maple Studios`).

## Uninstall

Settings → Apps → Maple Studios → Uninstall. Your data in `%APPDATA%\Maple Studios` is left in place; delete that folder too if you want everything gone.
