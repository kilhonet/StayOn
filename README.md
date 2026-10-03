# StayOn

**A free Windows tool that keeps your screen and PC awake — click the little cat on your desktop.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/stayon?lang=en)

![StayOn screen](images/stayon-ko.webp)

## Overview

You've probably had it happen: a presentation is up, a long download is running, or you're reading a document — and a few minutes later the screen goes dark and the PC falls asleep. On a work PC you often can't change the power settings at all.

StayOn puts a small pixel‑art cat in the corner of your desktop. **Click the sleeping cat and it wakes up**; while the cat is awake, the screen won't turn off and the PC won't go to sleep. Click again and the cat goes back to sleep, and everything returns to normal.

Windows power and sleep settings are never touched. It only has an effect while it is running, and leaves no trace when you quit or reboot. It is a single file under 100 KB.

## Features

- **One click** — Click the cat to turn sleep prevention on or off. The right‑click menu works too.
- **Prevents screen‑off, sleep and lock** — The screen saver, screen timeout, sleep mode and auto‑lock don't kick in. It also keeps messengers such as Teams from showing you as "Away".
- **No Windows settings changed** — Power options and group policies are left alone. No administrator rights needed.
- **A cat you can put anywhere** — Drag it where you like; the position is remembered. It can't leave the screen.
- **Size 100 % · 200 % · 400 %** — Pick a cat size to suit your monitor. Crisp on high‑resolution (HiDPI) displays too.
- **Run at boot** — The cat appears when Windows starts (installer version).
- **Light and simple** — Rewritten in C: an 83 KB executable, no setup or settings window. Always on top, yet never in the taskbar or the Alt+Tab list.
- **7 languages** — Korean · English · Japanese · Chinese · Russian · Italian · French, following the Windows display language.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/stayon?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/stayon?lang=en&nosetup) |

With the installer, the cat appears as soon as installation finishes. For the portable version, unzip and run `StayOn.exe`.

Difference between the two: **Run at boot** can be turned on only in the installer version (in the portable version the menu item is grayed out).

## Usage

### Getting started

1. Launch StayOn. A **sleeping cat** appears at the bottom right of the screen, just above the taskbar.
2. **Click** the cat. It stretches and wakes up; from now on the screen won't turn off and the PC won't sleep.
3. Do your work. The cat stays on screen while it is awake.
4. When you're done, **click the cat again**. It goes back to sleep and your sleep settings return to normal.

The cat **always starts asleep** when the program launches. Even if you left it awake yesterday, it won't switch itself on at the next launch — so the screen is never kept on when you didn't mean it to be.

### Screen layout

There is no window or settings screen — just the cat and its **right‑click menu**.

| Menu | What it does |
|---|---|
| **Run** / **Stop** | Turn sleep prevention on/off — same as clicking the cat |
| **Size** › 100% · 200% · 400% | Cat size. Default is 200% |
| **Run at boot** (check) | Start automatically with Windows (installer version) |
| **Crafted by Kilho** | Open the website |
| **Exit** | Quit the program — sleep prevention turns off too |

- **Sleeping cat** = sleep prevention off, **awake cat** = sleep prevention on. No separate indicator needed; the cat tells you.
- **Drag to move** — Press and drag the cat to move it. A tiny movement counts as a click.

### How do I…

**Keep the screen on during a presentation or meeting**
Click the cat once to wake it before you open your slides. Click again when you're done. No need to touch the power settings on a projector or meeting‑room PC.

**Leave a long download or job running while away**
Wake the cat and the PC won't sleep while you're gone, so the job keeps going. Put the cat back to sleep when you return. This has nothing to do with shutting the PC down — shut it down yourself once the job is finished.

**Teams · Slack keeps switching me to "Away"**
If you only read or listen in a meeting without moving the mouse, messengers mark you as away. With the cat awake, that doesn't happen.

**I can't change the power settings on my work PC**
StayOn doesn't change Windows settings and doesn't use administrator rights. Even on a PC where the screen‑off time is fixed by group policy, the screen stays on while the cat is awake.

**The cat gets in the way**
- **Drag** it wherever you like. The position is remembered.
- Right‑click → **Size** → **100%** makes it barely noticeable.
- The cat can't be pushed off the screen; it stops at the monitor edge.

**The cat is too small (4K monitor, etc.)**
Right‑click → **Size** → **400%**. It is multiplied by the Windows scaling setting, so it stays crisp at any resolution.

**Have the cat appear every time the PC starts**
In the installer version, right‑click → check **Run at boot**. From the next boot, the cat appears asleep after logon. In the portable version this item is locked — use the installer version.

**I can't see the cat**
- If it is already running, launching it a second time does nothing (only one cat at a time). Check the screen corners and other monitors.
- If your monitor setup changed and the saved position is now off‑screen, it returns automatically to the default position (bottom right of the main monitor).

**Quit StayOn completely**
Right‑click → **Exit**. If the cat was awake, sleep prevention turns off with it. If you only put the cat to sleep, the program stays so you can wake it again right away next time.

**Check that sleep prevention is working**
If the cat is awake, it is. To be sure, wait past the screen‑off time in Windows Settings → System → Power and see that the screen stays on.

**Use the same position and size on another PC**
Settings are stored in your user account and survive updates. On a new PC, move the cat once and pick a size, and it is remembered from then on.

## Configuration

There is no settings window; everything is changed from the right‑click menu and saved immediately.

| Item | Default |
|---|---|
| Size | 200% |
| Cat position | Bottom right of the main monitor (above the taskbar) |
| Run at boot | Off |
| Sleep‑prevention state | Not saved — always starts asleep |

The display language follows the Windows display language (Korean · English · Japanese · Chinese · Russian · Italian · French; otherwise English).

## Requirements

- Windows 10 or Windows 11 (32‑bit and 64‑bit)
- No administrator rights and no additional runtime required.
- An internet connection is used only to check for new‑version notices. It works offline.

## Updates

StayOn does **not** update itself. At launch it checks whether a new version exists and shows a notice; pressing **Yes** opens the download page and quits the program. New versions are released manually after internal verification and announced on the [StayOn page](https://kilho.net/stayon). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

## License

StayOn is **freeware**. Use it anywhere — at the office, at home, in government offices, at school — free of charge and without restriction, and redistribute it freely.

## Links

- Website: <https://kilho.net/stayon>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
