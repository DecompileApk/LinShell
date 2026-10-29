# Frequently asked questions

[← Home](../README.md)

## What device does LinShell support?

An **ARM64 device running Android 11.0 or later**. No root is required. Open the app and tap **Start terminal**.

## What can I do with LinShell?

Use a local Debian 13 terminal to run commands, edit files, write scripts, work with Git and use command-line development tools. Git, Python, tmux, nano, curl, an SSH client, rsync and jq are included.

LinShell focuses on terminal use. For a graphical Linux desktop, see [LinDesk](https://github.com/DecompileApk/LinDesk).

## Does it work offline?

The initial Linux setup runs locally. Installed command-line tools can work offline when their task does not need a network connection. Downloading packages, connecting to remote machines and using online AI services require internet access.

## How do I open or switch between terminals?

Tap **+** in the terminal toolbar to open another session. Tap the current terminal's name to switch sessions, then touch and hold a session in the list to rename it. You can have up to eight terminals open.

All sessions share your Linux files and software. Closing one terminal leaves the others running.

## How do I use the keyboard and shortcuts?

Tap the **keyboard icon** in the terminal toolbar to show or hide your Android keyboard. The shortcut rows provide keys such as **Esc**, **Enter**, **Tab**, **Ctrl**, **Alt** and the arrows.

Tap **Combos** for key combinations. Tap a modifier for the next key, or hold it to lock it. Use the **…** menu for more keys and shortcut customization.

## How do I copy and paste text?

Use **Select** in the terminal key controls, drag across the text, then tap **Copy**. Use **Paste** to insert text from your Android clipboard. The shortcut row scrolls horizontally to reveal additional controls.

Swiping up or down in the terminal scrolls through output. You can keep the keyboard hidden while reading.

## How do I install more tools?

Open **Settings → Recommended tools**, select the categories you want, then tap **Install selection**.

| Category | Main tools |
| --- | --- |
| AI coding with Codex | Codex CLI |
| Python tools & automation | pip, venv and pipx; Python itself is already included |
| Web development | Node.js and npm |
| Java apps & coding | OpenJDK, java and javac |
| Build Linux apps | GCC, G++, Make, CMake, Ninja and pkg-config |
| Network troubleshooting | ping, ifconfig, tracepath, netcat and Nmap |
| Media conversion | FFmpeg and ImageMagick |

LinShell updates the package lists before installing your selection. You can leave the installation page and continue using your terminals. Completed tools remain installed if you cancel or a later item fails; retry unfinished items from the same page.

You can also use Debian's `apt` package manager from a terminal.

## How do I open Codex after installing it?

Choose **AI coding with Codex** in **Settings → Recommended tools** and complete installation. Return to a terminal, run `codex` and follow its sign-in prompts using your own account.

## How do I change the app language or use full screen?

Open **Settings → App language** to choose a language or follow your system language. Linux command output remains in English.

Turn on **Settings → Full screen** to use the status bar area for the terminal.

## How do I return to Home or stop Linux?

Tap the **back arrow** in the terminal toolbar to return to LinShell's Home while Linux keeps running. To end all sessions, save your work and tap **Stop Linux** on Home.

## What if a download fails or Linux stops in the background?

For installation failures, check your internet connection and available storage, then retry the unfinished tools. For background interruptions, open **Settings → Allow background use** and review your phone's battery restrictions for LinShell.

Still having trouble? [Open an issue](https://github.com/DecompileApk/LinShell/issues) with your device model, Android and LinShell versions, the steps you took and a screenshot of the error. Remove private information from logs or screenshots before posting.
