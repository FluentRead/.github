<div align="center">

<img src="https://raw.githubusercontent.com/FluentRead/FluentRead/main/assets/brand/icon-512.png" alt="FluentRead logo" width="96" />

# FluentRead · 流畅阅读

**让语言更近，让世界更大。**<br />**Closer languages. A bigger world.**

一款开源的浏览器双语翻译插件。<br />An open-source browser extension for bilingual translation.

[安装 / Install](#安装--install) · [官网](https://read.thinkstu.com/) · [English website](https://read.thinkstu.com/en/) · [使用指南](https://read.thinkstu.com/guide/) · [Source code](https://github.com/FluentRead/FluentRead) · [Issues](https://github.com/FluentRead/FluentRead/issues)

</div>

FluentRead 将翻译、理解与学习带进日常阅读：在原网页中对照原文与译文，读不懂时查看上下文讲解，遇到想记住的表达就收藏，再在阅读与复习中使用它们。图片、漫画、文档、视频字幕与写作也可以使用相应的翻译工具。

[![FluentRead 网页双语对照效果](https://raw.githubusercontent.com/FluentRead/FluentRead/main/docs/public/screenshots/translation.webp)](https://read.thinkstu.com/guide/webpage-translation)

## 阅读、理解与表达

| 功能 | 可以做什么 |
| --- | --- |
| 网页双语翻译 | 全文双语对照、悬浮段落翻译与划词翻译，随时恢复原文，并按网站设置自动翻译规则。 |
| AI 阅读卡片 | 结合允许参考的原文语境解释含义、分析句子、说明用法与生成练习，支持连续追问。 |
| 学习中心 | 收藏单词、短语和句子并保留语境，进行听读、学习与间隔复习，也可导出到 Anki。 |
| 图片、漫画与圈选 | 识别图片或选定区域中的文字，切换原图与译图；在已适配的漫画阅读器中连续翻译。 |
| 文档翻译 | 导入 PDF、ePub、DOCX、Markdown 和字幕等文件，双语阅读、校订译文，并导出双语或仅译文结果。 |
| 视频与会议字幕 | 翻译 YouTube、X 等支持平台的可读取字幕，以及 Google Meet、Teams、Zoom 网页会议字幕。 |
| 输入框与写作助手 | 翻译输入框中的文字，或在 Gmail、GitHub 中起草、完善回复，检查后由你插入与发送。 |
| 服务与个性化 | 使用免费翻译服务、DeepL、AI 服务或本地 Ollama，配置术语库、译文样式、快捷键和菜单布局。 |

AI 阅读卡片接入 **DeepSeek Harness 会话内核的浏览器适配**，连接网页选区、允许参考的段落和所选模型服务。AI 讲解和写作需要配置可用的 AI 服务；普通网页翻译可使用免费翻译服务。FluentRead 免费开源，第三方服务的费用、额度与可用性由服务商决定。

[翻译卡片指南](https://read.thinkstu.com/guide/deepseek-harness) · [学习中心](https://read.thinkstu.com/guide/vocabulary-book) · [图片与漫画翻译](https://read.thinkstu.com/guide/image-translation) · [完整使用指南](https://read.thinkstu.com/guide/)

## 安装 / Install

| 浏览器 / Browser | 安装入口 / Install |
| --- | --- |
| Chrome | [Chrome Web Store](https://chromewebstore.google.com/detail/djnlaiohfaaifbibleebjggkghlmcpcj) |
| Edge | [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/kakgmllfpjldjhcnkghpplmlbnmcoflp) |
| Firefox | [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/%E6%B5%81%E7%95%85%E9%98%85%E8%AF%BB/) |
| 油猴脚本 / Userscript | [Greasy Fork](https://greasyfork.org/scripts/482986) |

安装后刷新网页，打开 FluentRead，确认目标语言并点击“翻译当前网页”。源语言默认自动检测，其他工具按需开启。

各商店更新可能存在时间差，具体功能以所安装版本和[使用指南](https://read.thinkstu.com/guide/getting-started)为准。油猴脚本提供核心网页翻译能力。视频和会议翻译需要平台提供可读取的字幕；漫画连续翻译的支持范围见指南。

## English

FluentRead brings translation, understanding, and learning into everyday reading. Read original text and translations on the same webpage, ask contextual questions, and save useful expressions with their original context for study and review.

- **Bilingual webpages:** whole-page, hover, and selection translation, with original-text restoration and website rules.
- **AI reading and learning:** contextual explanations and follow-up questions through a browser adaptation of the DeepSeek Harness session core; word, phrase, and sentence collections, listening, spaced review, and Anki export.
- **Images, comics, and documents:** image and area text recognition, continuous comic translation in adapted readers, and bilingual document reading, editing, and export.
- **Video and meeting subtitles:** translate readable captions on supported platforms, including YouTube, X, Google Meet, Teams, and the Zoom web client.
- **Writing and customization:** input translation, draft assistance in Gmail and GitHub, multiple translation services, local Ollama models, glossaries, and configurable appearance and shortcuts.

AI explanations and writing require a configured AI service. Third-party pricing, quotas, and availability depend on the provider. Store versions may differ; the userscript provides core webpage translation features. See the [English user guide](https://read.thinkstu.com/en/guide/) for setup and supported formats and platforms.

## 开源、隐私与社区 / Open source, privacy, and community

FluentRead 按 [GPL-3.0](https://github.com/FluentRead/FluentRead/blob/main/LICENSE) 开源。设置与学习记录默认保存在本机；使用云端翻译或 AI 时，相关文字会发送给你选择的服务。配置云备份由你主动开启，支持范围和数据处理方式见[隐私政策](https://read.thinkstu.com/guide/privacy)。

FluentRead is released under GPL-3.0. Settings and learning records stay local by default; cloud translation and AI send the relevant text to your selected provider. Configuration cloud backup is optional. See the [privacy policy](https://read.thinkstu.com/en/guide/privacy) and [third-party notices](https://github.com/FluentRead/FluentRead/tree/main/public/third-party-notices/) for details.

感谢每一位贡献者、支持者和用户。欢迎通过 [Issue](https://github.com/FluentRead/FluentRead/issues) 反馈问题，通过 Pull Request 改进代码、文档、界面翻译与[网站适配](https://github.com/FluentRead/FluentRead/blob/main/docs/contributing/site-adaptation.md)。社区的慷慨支持让项目持续成长，也欢迎[自愿支持项目](https://github.com/FluentRead/FluentRead#support)。

Thank you to every contributor, supporter, and user. Bug reports, ideas, and pull requests are welcome. Community support helps keep FluentRead growing.

<div align="center">

**让语言更近，让世界更大。**<br />**Closer languages. A bigger world.**

</div>
