# Leise

## English

**Leise** is a 100 % local dictation app for macOS. **Your audio and your transcripts never leave your Mac.** It works with the network off.

### Before you download

- **Apple Silicon only** — a Mac with an M1 chip or newer. Intel Macs are not supported.
- **macOS 14.4 or later.**
- **About 7 GB of free disk space** — 409 MB for the app, 5.9 GB for the speech models it downloads on first run.
- **Ten minutes**, most of it waiting for that download.

### 1. Install

1. Download `Leise-2.1.zip` from https://github.com/ramonfeng/leise/releases/latest.
2. Double-click the zip to unpack it.
3. **Drag `Leise.app` into your Applications folder in Finder.** Do this by dragging — macOS runs a copied-in app from a temporary read-only location instead, and it will not work properly from there.

### 2. macOS blocks it — twice, and the safe button is never the blue one

Leise is signed, but not notarised by Apple, so Gatekeeper stops it. This happens **once**, on the very first launch; updates never repeat it.

> ⛔ **Both dialogs make "Move to Trash" the blue default button.** Pressing Return, or clicking the obvious one, deletes the app you just downloaded. Read the button labels.

1. Double-click **Leise**. A dialog says *"Leise" Not Opened*. There is no way to open it from here — click **Done**. (⛔ Not *Move to Trash*.)
2. Open **System Settings → Privacy & Security** and scroll down to the **Security** section. There is a line saying Leise was blocked, with an **Open Anyway** button. Click it.
3. A second dialog asks *Open "Leise"?* — click **Open Anyway**, the middle button. (⛔ Again, not the blue *Move to Trash*.)
4. Confirm with Touch ID or your password.

### 3. First run: three permissions

Leise asks for them one at a time, and each one explains itself first.

| | What it is for | What you do |
|---|---|---|
| **Microphone** | Recording what you say | Click **Allow Access**, then **Allow** in the macOS dialog |
| **Accessibility** | Watching for your shortcut key, and typing the result where your cursor is | Click **Allow Access**. macOS opens System Settings — **switch Leise on in the list yourself**; there is no one-click dialog for this one |
| **Screen Recording** | Reading which app you are dictating into, for context | Switch Leise on in the same System Settings list, then **quit Leise and open it again** — this grant only takes effect on a fresh start |

Onboarding picks up where it left off after that restart.

### 4. The speech models — 5.9 GB, once

Leise transcribes and polishes entirely on your Mac, so the models have to be on your Mac. The progress bar shows how much is left. You cannot skip this step; nothing can be transcribed without them. It happens once — updates do not re-download them.

### 5. Updates

Leise asks once whether it may check for new versions. **The box is unchecked, and leaving it unchecked is a complete answer** — Leise then never contacts the network again. You can change it later in Settings.

### What Leise sends over the network

Nothing about you, ever. Audio and transcripts stay on the machine. There are exactly two requests the app can make, both named above and both under your control: downloading the speech models on first run, and checking for a new version if you opted in — which asks for a version number and sends nothing about you or your Mac.

### Licence

GPL-3.0. The complete corresponding source for this build is in the same release, as `leise-2.1-source.tar.gz` — the exact commit the download was built from.

---

## Deutsch

**Leise** ist eine zu 100 % lokale Diktier-App für macOS. **Deine Aufnahmen und deine Transkripte verlassen diesen Mac nie.** Sie funktioniert ohne Netzverbindung.

### Vor dem Download

- **Nur Apple Silicon** — ein Mac mit M1 oder neuer. Intel-Macs werden nicht unterstützt.
- **macOS 14.4 oder neuer.**
- **Rund 7 GB freier Speicherplatz** — 409 MB für die App, 5,9 GB für die Sprachmodelle beim ersten Start.
- **Zehn Minuten**, größtenteils Wartezeit für diesen Download.

### 1. Installation

1. `Leise-2.1.zip` von https://github.com/ramonfeng/leise/releases/latest laden.
2. Zum Entpacken doppelklicken.
3. **`Leise.app` im Finder in den Ordner „Programme" ziehen.** Bitte wirklich ziehen — eine anders hineinkopierte App startet macOS aus einem temporären, schreibgeschützten Ort, und von dort funktioniert sie nicht richtig.

### 2. macOS blockiert sie — zweimal, und der sichere Knopf ist nie der blaue

Leise ist signiert, aber nicht von Apple notarisiert, deshalb hält Gatekeeper sie an. Das passiert **einmal**, beim allerersten Start; Updates lösen es nicht erneut aus.

> ⛔ **In beiden Dialogen ist „In den Papierkorb legen" der blaue Standardknopf.** Wer die Eingabetaste drückt oder den naheliegenden Knopf nimmt, löscht die gerade geladene App. Bitte die Beschriftungen lesen.

1. **Leise** doppelklicken. Ein Dialog meldet *„Leise" wurde nicht geöffnet*. Öffnen lässt sie sich hier nicht — auf **Fertig** klicken. (⛔ Nicht *In den Papierkorb legen*.)
2. **Systemeinstellungen → Datenschutz & Sicherheit** öffnen und nach unten zum Abschnitt **Sicherheit** scrollen. Dort steht, dass Leise blockiert wurde, daneben der Knopf **Dennoch öffnen**. Draufklicken.
3. Ein zweiter Dialog fragt *„Leise" öffnen?* — auf **Dennoch öffnen** klicken, den mittleren Knopf. (⛔ Wieder nicht der blaue.)
4. Mit Touch ID oder Passwort bestätigen.

### 3. Erster Start: drei Berechtigungen

Leise fragt sie einzeln ab und erklärt jede vorher.

| | Wofür | Was du tust |
|---|---|---|
| **Mikrofon** | Aufnehmen, was du sagst | **Zugriff erlauben** klicken, dann im macOS-Dialog **Erlauben** |
| **Bedienungshilfen** | Auf deine Taste hören und das Ergebnis an der Cursorposition einsetzen | **Zugriff erlauben** klicken. macOS öffnet die Systemeinstellungen — **Leise in der Liste selbst einschalten**; für diese gibt es keinen Ein-Klick-Dialog |
| **Bildschirmaufnahme** | Erkennen, in welche App du diktierst | Leise in derselben Liste einschalten, dann **Leise beenden und neu öffnen** — diese Freigabe wirkt erst nach einem Neustart |

Nach dem Neustart macht der Einrichtungsablauf dort weiter, wo er war.

### 4. Die Sprachmodelle — 5,9 GB, einmalig

Leise transkribiert und poliert vollständig auf deinem Mac, also müssen die Modelle auf deinem Mac liegen. Der Fortschrittsbalken zeigt, wie viel noch fehlt. Dieser Schritt lässt sich nicht überspringen; ohne die Modelle wird nichts transkribiert. Er passiert einmal — Updates laden sie nicht erneut.

### 5. Updates

Leise fragt einmal, ob sie nach neuen Versionen sehen darf. **Das Häkchen ist nicht gesetzt, und es nicht zu setzen ist eine vollständige Antwort** — dann geht Leise nie wieder ins Netz. Später in den Einstellungen änderbar.

### Was Leise über das Netz sendet

Nichts über dich. Aufnahmen und Transkripte bleiben auf dem Gerät. Es gibt genau zwei Anfragen, beide oben genannt und beide von dir gesteuert: das Laden der Sprachmodelle beim ersten Start und, nach ausdrücklicher Zustimmung, die Prüfung auf eine neue Version — dabei wird eine Versionsnummer abgefragt und nichts über dich oder deinen Mac gesendet.

### Lizenz

GPL-3.0. Der vollständige zugehörige Quelltext liegt im selben Release als `leise-2.1-source.tar.gz` — genau der Commit, aus dem dieser Download gebaut wurde.

---

## 简体中文

**Leise**（德语「轻声」）是一个 100% 本地运行的 macOS 语音听写 App。**你的音频与转写文本永不离开这台 Mac**，断网全功能可用。

### 下载之前

- **仅支持 Apple Silicon** —— M1 及以上芯片的 Mac，Intel 机型不支持。
- **macOS 14.4 或更高。**
- **约 7 GB 可用磁盘空间** —— App 本体 409 MB，首次运行下载的语音模型 5.9 GB。
- **十分钟**，大部分时间在等那个下载。

### 1. 安装

1. 从 https://github.com/ramonfeng/leise/releases/latest 下载 `Leise-2.1.zip`。
2. 双击解压。
3. **在访达里把 `Leise.app` 拖进「应用程序」文件夹。** 请务必用拖的 —— 用别的方式拷进去，macOS 会把它放到一个临时的只读位置运行，那样它工作不正常。

### 2. macOS 会拦两次，而安全的那个键从来不是蓝色的

Leise 有签名，但没有经过 Apple 公证，所以 Gatekeeper 会拦。**只在第一次启动时发生**，之后的更新不会再触发。

> ⛔ **两个对话框都把「移到废纸篓」设成了蓝色默认按钮。** 直接回车、或者顺手点最显眼的那个，会把你刚下载的 App 删掉。请看清按钮上的字。

1. 双击 **Leise**，弹出「未打开"Leise"」。这一屏没有任何打开的办法 —— 点 **Done / 完成**。（⛔ 不是「移到废纸篓」。）
2. 打开**系统设置 → 隐私与安全性**，向下滚动到**安全性**一节。那里写着 Leise 被阻止，旁边有 **Open Anyway / 仍要打开** 按钮，点它。
3. 第二个对话框问「打开"Leise"？」—— 点**中间**那个 **Open Anyway / 仍要打开**。（⛔ 又一次，不是蓝色那个。）
4. 用触控 ID 或密码确认。

### 3. 首次运行：三个权限

Leise 逐个申请，每个都先解释用途。

| | 用来做什么 | 你要做的 |
|---|---|---|
| **麦克风** | 录下你说的话 | 点 **Allow Access**，再在 macOS 弹窗里点 **Allow** |
| **辅助功能** | 监听你的快捷键，并把结果打到光标所在处 | 点 **Allow Access**。macOS 会打开系统设置 —— **需要你自己在列表里把 Leise 的开关打开**，这一个没有一键弹窗 |
| **屏幕录制** | 识别你正在往哪个 App 里口述，用于判断上下文 | 在同一个系统设置列表里打开 Leise，然后**退出 Leise 再打开一次** —— 这个授权要重启才生效 |

重启之后引导会从中断的那一步接着走。

### 4. 语音模型 —— 5.9 GB，只下一次

Leise 的识别和润色全部在你的 Mac 上跑，所以模型必须在你的 Mac 上。进度条显示还差多少。这一步不能跳过，没有模型就无法转写。只发生一次，之后的更新不会重新下载。

### 5. 更新

Leise 会问一次是否允许检查新版本。**勾选框默认是空的，不勾也是一个完整的答案** —— 不勾，Leise 此后永不联网。以后可以在设置里改。

### Leise 会往网上发什么

关于你的，什么都不发。音频与转写始终留在本机。App 能发起的网络请求只有两个，都在上面写明、都由你控制：首次运行下载语音模型，以及你明确勾选后的检查新版本 —— 后者只要一个版本号，不附带任何关于你或这台机器的信息。

### 许可

GPL-3.0。本次构建对应的完整源码就在同一个 Release 里，文件名 `leise-2.1-source.tar.gz`，即这个安装包所构建自的那个 commit。
