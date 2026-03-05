<!-- Auto-generated from comments JSON — do not edit manually -->
# Comments: README.md

Repo: zh3036/awesome-cli-apps-in-a-csv | Branch: master
View: https://md-comment.fly.dev/zh3036/awesome-cli-apps-in-a-csv/blob/master/README.md

---

## zh3036 — 2026-03-05 15:57

> "Email](#email) (18) * [File and file system handling](#file-handling) (29), [File deletion and trash bin (alternatives to rm)](#rm) (14), [File explorer and tree visualization](#file-explorer) (11), […"

good

Status: Open

---

## claude — 2026-03-05 16:13

> "Email](#email) (18)"

📧 这个分类里最值得关注的：Himalaya（Rust写的纯CLI邮件工具，完全stateless且pipeline友好）和 pop（Charmbracelet出品，stdin管道直接发邮件）。两者都能被Claude Code直接调用实现自动化邮件通知，集成成本几乎为零。aerc则是hacker风格邮件客户端，内嵌终端支持git-email工作流。

Status: Open

---

## claude — 2026-03-05 16:13

> "File and file system handling](#file-handling) (29)"

📁 ouch：自动识别压缩格式一键解压，Claude Code不需要记tar/unzip/7z各种flag。PathPicker（Facebook出品）：把任意命令输出变成文件选择器。Yazi：全异步Rust文件管理器，内置图片预览+语法高亮。vidir：用编辑器批量重命名文件。xplr：LuaJIT可编程的文件浏览框架。这些工具和Claude Code配合最好的是ouch——无歧义的CLI接口。

Status: Open

---

## zh3036 — 2026-03-05 15:57

> "Games](#games) (63), [Git and accessories](#git) (69), [Graphics](#graphics) (50) * [History management](#history) (5) * [Learning and didactic tools](#learning) (5) * [Markdown](#markdown) (10) * [Ne…"

good

Status: Open

---

## claude — 2026-03-05 16:14

> "Games](#games) (63)"

🎮 rpg-cli 最有创意——把cd命令变成地牢探索，每次切目录可能触发随机战斗。terminal-doom 在终端里流畅运行完整DOOM，技术上是工程奇迹。不过这些和Claude Code没啥关系，纯粹好玩。

Status: Open

---

## claude — 2026-03-05 16:14

> "Git and accessories](#git) (69)"

🔥 这是和Claude Code协作潜力最大的分类。git-cliff：基于conventional commits自动生成CHANGELOG，Claude Code写规范commit信息→git-cliff自动转化发布记录，完美流水线。onefetch：--output json获取仓库元数据，自动生成README。sad：带diff预览的批量搜索替换，比手写sed安全。Lazygit/GitUI：交互式git TUI，适合人工复核Claude Code的改动。forgit：fzf加持的git操作。gh-dash：终端GitHub仪表盘。tig：20年老工具依然是SSH环境最佳git可视化。

Status: Open

---

## claude — 2026-03-05 16:14

> "Graphics](#graphics) (50)"

🎨 有几个意外实用的：D2——文本转图表的脚本语言，Claude Code可以直接生成D2代码来画架构图。pastel——命令行颜色工具，分析/转换/生成配色方案。MapSCII——终端里的世界地图（Braille字符渲染）。chafa——21世纪的终端图形引擎，把图片用Unicode字符渲染到终端。textual-paint——终端里的MS Paint，纯TUI画图。

Status: Open

---

## zh3036 — 2026-03-05 15:58

> "Markdown](#markdown) (10) * [Networking](#networking) (89), [Note taking](#note-taking) (30) * [Office tools](#office) (21), [Online search and resources](#online) (29), [Organizers and calendars](#or…"

good

Status: Open

---

## claude — 2026-03-05 16:15

> "Markdown](#markdown) (10)"

📝 glow（Charmbracelet出品）：终端渲染Markdown，Claude Code生成文档后可直接调用预览。mdcat：更轻量的选择，支持Sixel协议甚至能内联渲染图片。mdBook：Rust官方文档工具，Claude Code生成SUMMARY.md+各章节内容后一键build出文档网站。Frogmouth（Textualize出品）：像浏览器一样在Markdown文档间跳转。这个小分类的工具和AI写作流程天然契合。

Status: Open

---

## claude — 2026-03-05 16:15

> "Networking](#networking) (89)"

🌐 bore：400行Rust代码的极简内网穿透，一条命令把localhost暴露到公网，测试webhook/OAuth回调必备。mosh：UDP版SSH，断网自动恢复，远程跑Claude Code不怕网络波动。sshx：一条命令生成浏览器可访问的协作终端，多人同时观察AI操作过程。ttyd：终端变Web应用。mitmproxy：交互式HTTPS拦截代理，Claude Code可以生成其Python插件脚本。posting：终端版Postman，YAML存请求（git友好），Claude Code可直接读写。

Status: Open

---

## zh3036 — 2026-03-05 16:00

> "Todo managers"

good

Status: Open

---

## claude — 2026-03-05 16:15

> "Todo managers"

✅ TaskWarrior：20年历史的命令行todo王者，task add/list/done完全可脚本化，Claude Code完成子任务后可自动更新状态。dstask：每个任务是Markdown文件+git同步，与Claude Code的git操作习惯天然契合。boards：文件系统目录=看板列，mv命令就能更新任务状态，最低摩擦自动化。taskell：Haskell写的看板，数据用Markdown存储。Dooit：颜值在线的TUI todo，vim键位。

Status: Open

---

## zh3036 — 2026-03-05 16:01

> "Web browser"

very cool

Status: Open

---

## claude — 2026-03-05 16:16

> "Web browser"

🌍 carbonyl：真正fork了Chromium源码在终端60fps渲染完整网页（WebGL、视频），近年终端工具里最震撼的黑科技。browsh：headless Firefox驱动，5MB网页压缩到15KB通过SSH传输。w3m：25年历史的文本浏览器，w3m -dump URL一行提取网页纯文本，Claude Code可以直接调用来抓取静态页面内容，启动快输出稳定。这个分类'very cool'实至名归。

Status: Open

---

## zh3036 — 2026-03-05 16:01

> "Writing"

inteersting

Status: Open

---

## claude — 2026-03-05 16:16

> "Writing"

✍️ write-good：用lint的方式检查英文写作——被动语态、模糊词、冗余表达一网打尽。Claude Code生成README后pipe给它做自动检查，形成'生成→检查→修订'闭环。Translate Shell：支持Google/Bing/Yandex多引擎翻译的终端瑞士军刀，批量翻译文档片段时可作为Claude Code的补充管道工具。Grammatical：ChatGPT做语法纠错的CLI，但功能和Claude Code自身能力高度重叠。

Status: Open

---

## claude — 2026-03-05 16:18

> "rpg-cli"

🎮 最有创意的CLI工具之一——把cd命令变成地牢探索，每次切换目录都可能触发随机战斗，文件系统就是你的冒险地图。纯粹好玩，把枯燥的终端操作变成JRPG。

Status: Open

---

## claude — 2026-03-05 16:17

> "bore"

⭐ 400行Rust代码的极简内网穿透。bore local 8080 --to bore.pub 一条命令把本地dev server暴露到公网。Claude Code开发阶段测试webhook、OAuth回调等需要公网URL的场景时，可以自动调用bore完成。

Status: Open

---

## claude — 2026-03-05 16:16

> "git-cliff"

⭐ Claude Code最佳搭档之一。Claude Code生成符合conventional commits规范的提交→git-cliff自动转化为CHANGELOG→完整的发布自动化流水线。用Tera模板引擎控制输出格式，高度可定制。

Status: Open

---

## claude — 2026-03-05 16:17

> "Lazygit"

⭐ 面板式git TUI，交互式rebase、逐行stage、一键undo，把最复杂的git操作变得可视化且可撤销。和Claude Code的最佳搭配方式：Claude Code写代码→Lazygit里人工review和选择性stage→Claude Code生成commit message。

Status: Open

---

## claude — 2026-03-05 16:17

> "onefetch"

⭐ neofetch风格展示git仓库统计——语言分布、贡献者、提交数。关键是支持 --output json，Claude Code可以调用获取结构化仓库元数据，自动生成README概述或项目报告。

Status: Open

---

## claude — 2026-03-05 16:19

> "D2"

⭐ 文本转图表的脚本语言，Claude Code可以直接生成D2代码来画架构图、流程图、序列图。比Mermaid更强大的布局引擎，输出PNG/SVG。AI+D2=自动化文档图表生成。

Status: Open

---

## claude — 2026-03-05 16:18

> "glow"

⭐ Charmbracelet出品，终端Markdown渲染器。Claude Code生成文档后直接glow README.md预览效果，还能从URL/GitHub直接拉取渲染。颜值和实用性兼备，和AI写作流程天然契合。

Status: Open

---

## claude — 2026-03-05 16:18

> "sshx"

⭐ 一条命令生成浏览器可访问的协作终端，支持多人共享+无限画布+端对端加密。Claude Code运行在sshx session中时，多人可以同时观察AI操作过程，非常适合pair programming或演示调试。

Status: Open

---

## claude — 2026-03-05 16:18

> "TaskWarrior"

⭐ 命令行todo管理的王者，20年历史。task add/list/done完全可脚本化，支持优先级、标签、项目、过滤器、自定义报告。Claude Code可以在完成子任务后自动调用task done更新状态，实现开发进度与任务管理的联动。还有专门的同步服务器。

Status: Open

---

## claude — 2026-03-05 16:17

> "carbonyl"

⭐ 近年终端工具里最震撼的黑科技——真正fork了Chromium源码，在终端里以60fps渲染完整网页，包括WebGL和视频。虽然作为工程工具集成度不高，但证明了'终端能做任何事'。

Status: Open
