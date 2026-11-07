# Maple Studios

Maple is a retro-computer desktop for making games with Claude Code. Pick a project folder, and Maple opens a Claude Code terminal bound to that project, with her own memory of the work.

This repo only hosts the installer and updates. The source is private.

## Install

1. Download **Maple-Studios-Setup-x.y.z.exe** from [Releases](../../releases/latest) and run it. No admin rights needed.
   Windows may show "Windows protected your PC" because the installer isn't code-signed. Click **More info → Run anyway**.
2. Start Maple from the desktop shortcut. On first start she shows her **starter pack**: Godot (the game engine), Claude Code and Git are installed if missing, plus free extras you can untick (ffmpeg, GitHub CLI, ImageMagick, GIMP). Already have one installed somewhere unusual? Click **Locate…** next to it.
3. Double-click **New game**, type a name, and Maple creates the project in `Documents\Maple Projects`. (Have a game already? Use **Add project** on its git folder.)
4. The first time, Claude Code asks you to sign in with a Claude account (Pro or Max) or paste an Anthropic API key.
5. Describe your game. Maple asks a few questions, writes a plan, then builds it step by step.

Requires Windows 10 or 11, 64-bit.

## Install on a Mac

1. Download **Maple-Studios-x.y.z-mac.dmg** from [Releases](../../releases/latest). It works on Apple silicon and Intel Macs (macOS 12 or newer).
2. Open the .dmg and drag **Maple Studios** into **Applications**.
3. Open Maple from Applications. The first time, macOS says it can't check the app for malware because it isn't signed by an Apple developer. Press **Done**, then open **System Settings → Privacy & Security**, scroll down and press **Open Anyway** next to Maple Studios (you may need your Mac password). You only do this once.
4. The starter pack installs Godot, Claude Code and Git, plus the extras you leave ticked. Git and the extras come from Homebrew; if you don't have it, Homebrew's installer runs in Maple's screen and asks you to press Return and type your Mac password (nothing shows while you type).
5. Then it's the same as on Windows: **New game**, sign in to Claude, describe your game. Games go in `Documents/Maple Projects`.

## Updates

Every time Maple boots she checks for a new version and asks: **[Y] INSTALL UPDATE** or **[N] LATER**. Yes downloads it, installs it and restarts Maple. Your projects, sessions and Maple's memory are kept (they live in `%APPDATA%\Maple Studios`).

On a Mac, **Y** opens the new version's download page: open the .dmg, drag Maple Studios into Applications and choose **Replace**. Your data in `~/Library/Application Support/Maple Studios` is kept.

## Uninstall

Settings → Apps → Maple Studios → Uninstall. Your data in `%APPDATA%\Maple Studios` is left in place; delete that folder too if you want everything gone.

On a Mac, drag Maple Studios from Applications to the Trash. Your data stays in `~/Library/Application Support/Maple Studios` until you delete it.
