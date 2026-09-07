韦诺中文本地化项目
-----------------------------------------------

此项目是回合制战略游戏[韦诺之战](https://wesnoth.org)的简体中文本地化项目。按照韦诺之战社区的规定，游戏的本地化由各语言的维护者进行维护，并提交翻译给官方本地化维护者。此项目用于各翻译者提交修改给简体中文本地化维护者。

# 如何参与

欢迎大家参与韦诺之战的本地化。

本项目各分支对应相应的韦诺之战分支。目前主线 1.18 版本已经翻译完成，开始翻译 master 分支。由于未翻译部分比较多，为了避免多人重复在相同的部分工作，建议翻译者先开一个 issue 说明准备翻译的部分。

当前正在进行文字翻译，对应 translations/wesnoth/po/ 的子目录下的 .po 文件。

当前 vimacs 的工作流程是先用AI机翻，然后人工校对。目前 vimacs 采用工具 [ollama-translate](https://codeberg.org/vimacs/ollama-translate) 进行机器翻译，在 .po 文件的同级目录下有 prompt.txt 作为这个 .po 文件的翻译指引。推荐使用 [Poedit](https://poedit.net/) 编辑 .po 文件。

翻译进度参见此[翻译统计信息](https://gettext.wesnoth.org/?view=langs&version=branch&lang=zh_CN)页面。

# 地图本地化

TBD

# 参考资料

* 韦诺之战官方网站：https://wesnoth.org
* Github 上的韦诺之战代码：https://github.com/wesnoth
* 官方翻译指导：https://wiki.wesnoth.org/WesnothTranslationsHowTo
* 官方地图本地化指导：https://wiki.wesnoth.org/MapLocalization
* 百度贴吧韦诺之战吧：https://tieba.baidu.com/f?kw=%E9%9F%A6%E8%AF%BA%E4%B9%8B%E6%88%98&ie=utf-8

# 项目历史

项目历史见此前的 README 文档： https://github.com/CloudiDust/wesnoth-cn/blob/17c197618f096969689ffa11e77158604604877b/README.md

> Cloudidust: Back in 2010 the work on Wesnoth's zh_CN localization was kind of in a hiatus and not quite coordinated, so I (Cloudidust), with the permission of then zh_CN translation maintainer *sylecn*, started this project and hosted it on Google Code, in a [Mercurial repository](https://code.google.com/p/wesnoth-translation-cn). In 2015 this project was moved to [Github](https://github.com/CloudiDust/wesnoth-cn), but I made a mistake: starting a new git repo instead of importing the hg one. I regret it, but if interested you can browse/download the hg repo archive for history.

目前 vimacs 是本项目的维护者。
