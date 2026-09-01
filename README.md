# Leise

## English

**Leise** is a 100 % local dictation app for macOS. **Your audio and your transcripts never leave your Mac.** It works with the network off.

### Before you download

- **Apple Silicon only** — a Mac with an M1 chip or newer. Intel Macs are not supported and there is no fallback.
- **macOS 14.4 or later.**
- **About 7 GB of free disk space.** The app is 409 MB; the speech models it downloads on first run are 5.9 GB.

### Install

1. Download `Leise-2.1.zip` from https://github.com/ramonfeng/leise/releases/latest.
2. Unzip it and drag **Leise.app** into your **Applications** folder.

### The first time you open it, macOS will refuse

This is expected. Leise is signed but not notarised by Apple, so Gatekeeper stops it once. You only go through this once, and updates never repeat it.

1. Double-click **Leise**. macOS says it cannot be opened.
2. Open **System Settings → Privacy & Security**.
3. Scroll down to the Security section. There is a line about Leise being blocked, with an **Open Anyway** button. Click it.
4. Double-click Leise again and confirm.

### First run

Leise asks for three permissions, one at a time — **Microphone**, **Accessibility** (it needs this to type into other apps), and **Screen Recording** (it reads the window you are dictating into so it can guess context). Then it downloads 5.9 GB of speech models with a progress bar. That download happens once.

It also asks, once, whether it may check for new versions. **The box is unchecked by default.** Leave it unchecked and Leise never contacts the network again.

### What Leise sends over the network

Nothing about you, ever. Audio and transcripts stay on the machine. There are exactly two network requests the app can make, both named above and both under your control:

- **Downloading the speech models** on first run.
- **Checking for a new version**, only if you opted in. It asks for a version number and sends nothing about you or your machine.

### Licence

GPL-3.0. The complete corresponding source for this build is in the same release, as
`leise-2.1-source.tar.gz` — the exact commit the download was built from.

---

## Deutsch

**Leise** ist eine zu 100 % lokale Diktier-App für macOS. **Deine Aufnahmen und deine Transkripte verlassen diesen Mac nie.** Sie funktioniert ohne Netzverbindung.

### Vor dem Download

- **Nur Apple Silicon** — ein Mac mit M1 oder neuer. Intel-Macs werden nicht unterstützt, einen Rückfallweg gibt es nicht.
- **macOS 14.4 oder neuer.**
- **Rund 7 GB freier Speicherplatz.** Die App ist 409 MB groß, die Sprachmodelle beim ersten Start weitere 5,9 GB.

### Installation

1. `Leise-2.1.zip` von https://github.com/ramonfeng/leise/releases/latest laden.
2. Entpacken und **Leise.app** in den Ordner **Programme** ziehen.

### Beim ersten Öffnen blockiert macOS die App

Das ist so erwartet. Leise ist signiert, aber nicht von Apple notarisiert — Gatekeeper hält sie einmal an. Das passiert genau einmal; Updates lösen es nicht erneut aus.

1. **Leise** doppelklicken. macOS meldet, die App lasse sich nicht öffnen.
2. **Systemeinstellungen → Datenschutz & Sicherheit** öffnen.
3. Nach unten zum Abschnitt Sicherheit scrollen. Dort steht, dass Leise blockiert wurde, daneben der Knopf **Dennoch öffnen**. Draufklicken.
4. Leise erneut doppelklicken und bestätigen.

### Erster Start

Leise fragt nacheinander drei Berechtigungen ab — **Mikrofon**, **Bedienungshilfen** (nötig, um in andere Apps zu schreiben) und **Bildschirmaufnahme** (liest das Fenster, in das du diktierst, um den Kontext zu erkennen). Danach lädt sie 5,9 GB Sprachmodelle mit Fortschrittsanzeige. Dieser Download passiert einmal.

Außerdem wird einmal gefragt, ob sie nach neuen Versionen sehen darf. **Das Häkchen ist standardmäßig nicht gesetzt.** Ohne Häkchen geht Leise nie wieder ins Netz.

### Was Leise über das Netz sendet

Nichts über dich. Aufnahmen und Transkripte bleiben auf dem Gerät. Es gibt genau zwei Netzanfragen, beide oben genannt und beide von dir gesteuert:

- **Laden der Sprachmodelle** beim ersten Start.
- **Prüfen auf eine neue Version**, nur nach ausdrücklicher Zustimmung. Dabei wird eine Versionsnummer abgefragt und nichts über dich oder deinen Mac gesendet.

### Lizenz

GPL-3.0. Der vollständige zugehörige Quelltext liegt im selben Release als
`leise-2.1-source.tar.gz` — genau der Commit, aus dem dieser Download gebaut wurde.

---

## 简体中文

**Leise**（德语「轻声」）是一个 100% 本地运行的 macOS 语音听写 App。**你的音频与转写文本永不离开这台 Mac**，断网全功能可用。

### 下载之前

- **仅支持 Apple Silicon** —— M1 及以上芯片的 Mac。Intel 机型不支持，也没有回退方案。
- **macOS 14.4 或更高。**
- **约 7 GB 可用磁盘空间。** App 本体 409 MB，首次运行还要下载 5.9 GB 语音模型。

### 安装

1. 从 https://github.com/ramonfeng/leise/releases/latest 下载 `Leise-2.1.zip`。
2. 解压，把 **Leise.app** 拖进**应用程序**文件夹。

### 第一次打开时 macOS 会拦下来

这是预期行为。Leise 有签名但没有经过 Apple 公证，Gatekeeper 会拦一次。只拦这一次，之后的更新不会再触发。

1. 双击 **Leise**，macOS 提示无法打开。
2. 打开**系统设置 → 隐私与安全性**。
3. 向下滚动到「安全性」一节，那里写着 Leise 被阻止，旁边有一个**仍要打开**按钮，点它。
4. 再次双击 Leise 并确认。

### 首次运行

Leise 会逐个申请三项权限 —— **麦克风**、**辅助功能**（用来把文字写进其他 App）、**屏幕录制**（读取你正在输入的那个窗口以判断上下文）。随后下载 5.9 GB 语音模型，带进度条。这个下载只发生一次。

它还会问一次是否允许检查新版本。**默认不勾。** 不勾，Leise 此后永不联网。

### Leise 会往网上发什么

关于你的，什么都不发。音频与转写始终留在本机。App 能发起的网络请求只有两个，都在上面写明，都由你控制：

- **首次运行下载语音模型。**
- **检查新版本**，仅在你明确勾选后。它只要一个版本号，不附带任何关于你或这台机器的信息。

### 许可

GPL-3.0。本次构建对应的完整源码就在同一个 Release 里，文件名 `leise-2.1-source.tar.gz`，
即这个安装包所构建自的那个 commit。
