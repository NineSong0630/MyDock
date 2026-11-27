# Changelog

All versions are on the [Releases](https://github.com/NineSong0630/MyDock/releases) page. MyDock updates itself, so you don't need to download them by hand.

## 1.0.2 — 2026-11-27

- **Fixed a crash when adding a program** (or picking a file / colour in a Windows dialog). MyDock's crash logger treated harmless errors inside Windows' own dialogs as crashes and, by recording every thread hundreds of times, crashed MyDock itself.
  修复添加程序（或在 Windows 对话框里选文件 / 选颜色）时 MyDock 闪退：崩溃记录器把 Windows 对话框内部无害的错误当成崩溃，反复记录所有线程，结果自己把 MyDock 弄崩了。
- **Starts faster:** the Dock shows first and everything else loads right after; the app is about 45 MB smaller (unused parts of Qt left out), so there's less to read and scan when Windows starts. Installer 47 → 33 MB.
  启动更快：先显示 Dock，其他部分随后加载；去掉用不到的 Qt 组件，程序小了约 45 MB，开机时要读取和扫描的文件更少。安装包从 47 MB 降到 33 MB。
- crash.log no longer grows forever.
  crash.log 不再无限变大。

## 1.0.1 — 2026-11-27

- **Dock no longer vanishes when you switch apps.** On some PCs (older Windows, Wallpaper Engine) the Dock, widgets, notes and boxes could slip behind the wallpaper; they now stay right above the desktop and are put back after every switch. Alt+Tab, Task View and Start are no longer mistaken for a fullscreen game.
  切换应用时 Dock 不会再消失一下：在一些电脑上（较旧的 Windows、Wallpaper Engine）Dock、组件、便利贴、收纳格会被压到壁纸后面，现在始终贴在桌面上方，切换后自动归位；Alt+Tab、任务视图、开始菜单不再被当成全屏游戏。
- **No more flashing windows at start-up** on PCs where Windows was still loading.
  开机启动时不再闪出一堆小黑窗。
- **Folders and desktop boxes:** search (including subfolders), at most 4 rows with scrolling, open folders inside the pop-up, drag files out, arrow keys and Enter.
  文件夹 / 收纳格弹窗：可以搜索（包括子文件夹）、最多 4 行可滚动、文件夹直接在里面打开、文件可以拖出来、方向键和回车。
- **Dock background gradient**, and one click to give every widget the same background (*Use on all widgets* / *Match the Dock*).
  Dock 背景可以双色渐变；所有组件一键同一个背景颜色（「套用到全部组件」/「用 Dock 的颜色」）。
- **Song island:** optionally click it to jump to the app or web page that's playing (off by default).
  歌曲灵动岛：可以开启「点提示打开播放器」，跳到正在放歌的 App 或网页（默认关闭）。
- Wallpaper Engine layout templates now also switch video and web wallpapers.
  布局模板现在也能切换 Wallpaper Engine 的视频和网页壁纸。
- **Less memory:** window snapshots for the minimise animation used to pile up all day; now only a few are kept.
  更省内存：最小化动画用的窗口截图以前会越存越多，现在最多只留几张。
- All dialogs now use MyDock's dark style (no more white Windows boxes), and a double click can't open the same dialog twice.
  所有弹窗统一成 MyDock 的深色样式，连点两下也不会叠出两个。
- Settings pages line up after resizing or maximising the window; icons on Windows 10; fewer old backups kept; small fixes.
  设置窗口放大或最大化后每页都对齐；Windows 10 图标显示修正；旧备份自动精简；其他小修正。

## 1.0.0 — 2026-11-25

First official release. 第一个正式版本。

- **Auto-update:** a note slides in when there's a new version; one click installs it.
  自动更新：有新版本时屏幕上方弹出提示，点「更新」就自动下载安装。
- **Music card:** playlist switcher (name, colour and icon for each playlist), YouTube full shuffle, and *Change the speaker for music only*.
  音乐卡片：歌单切换器（可改名字、颜色、图标）、YouTube 完整随机播放、「只换音乐的音响」。
- **Shorter, animated right-click menus** and new pop-ups and dialogs.
  全部右键菜单精简，并加上动画；新的弹窗和对话框。
- Dock, beat bar, widgets (clock, calendar, weather, system monitor, sticky notes), desktop boxes, volume ball, desktop skins and layout templates.
  Dock、律动条、小组件（时钟、日历、天气、系统监控、便利贴）、收纳格、音量球、桌面皮肤、布局模板。
- Previous / next now also work for a single YouTube video in a browser (previous = back to the start, next = YouTube's *Up next*).
  上一首 / 下一首在浏览器里看单个 YouTube 视频时也能用（上一首 = 回到开头，下一首 = YouTube 自动播放的下一个）。
- Clearer, step-by-step guide for the YouTube key.
  YouTube 密钥的设置向导改成一步一步、写清楚每个按钮。
- Changing the language asks first, then MyDock restarts by itself and shows "back in a moment".
  换语言会先问你，然后自动重启，屏幕上方显示「马上回来」。
- **Beat bar shape:** number of bars (up to 160), length and thickness; turn it across, upright on the left / right edge, upside down or to any angle (Shift + scroll on it).
  律动条形状：可以调条数（最多 160）、长度、粗细；横放、竖着贴左边 / 右边、倒过来，或者斜着放任何角度（在频谱上 Shift + 滚轮）。
- **Livelier beat bar:** it follows each song's own loudness, so quiet songs and low volume jump just as high; low, mid and high bars all move, and every beat drops back crisply.
  律动条更灵敏：自动跟着每首歌的音量调整，小声的歌和低音量也一样跳得高；低音、中音、高音都会动，每个节拍落下得更干脆。
- Music cards change their layout when you make them bigger (big vinyl or cover on top, song below).
  音乐卡片拉大后排版会跟着变（大唱片或大封面在上面，歌名在下面）。
- Volume ball and music card: switch speakers from a button; play and pause now have different icons.
  音量球和音乐卡片：有按钮可以切换音响；播放和暂停的图标不再一样。
- The language picked in the installer is used by MyDock; the installer is fully translated.
  安装时选的语言就是 MyDock 的语言；安装程序也全部翻译好了。
