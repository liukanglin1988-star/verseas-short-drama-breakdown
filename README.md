# 海外 AI 短剧 / 短剧爆款内容拆解

一个面向 Codex 的中文 Skill。适用于海外 AI 短剧、竖屏微短剧和剧情类短视频。输入视频链接或上传视频，输出有证据的逐段拆解和可直接填用的中文脚本框架。

## 安装和使用

1. [下载 ZIP](https://github.com/liukanglin1988-star/verseas-short-drama-breakdown/archive/refs/heads/main.zip) 并解压。将解压得到的 `verseas-short-drama-breakdown-main` 文件夹改名为 `overseas-short-drama-breakdown`。
2. 将该文件夹整个移入 `~/.agents/skills/`。Windows 上对应 `%USERPROFILE%\.agents\skills\`。如果目录不存在，可以创建。安装后应能看到 `~/.agents/skills/overseas-short-drama-breakdown/SKILL.md`，同一文件夹下还应有 `agents/` 和 `references/`。
3. 在 Codex 中输入 `$overseas-short-drama-breakdown` 并附上链接或视频。如果技能未出现在列表中，重启 Codex 后重试。 [Codex 官方技能文档](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills)

- 链接用法：“用 `$overseas-short-drama-breakdown` 打开这条短剧链接，拆一下每一段如何留住观众，再给我可套用的复仇短剧框架。”
- 附件用法：“用 `$overseas-short-drama-breakdown` 读取我上传的视频，分析前半段埋了哪些线索，以及结尾如何承接下一集。”

## 交付内容

- 中文拆解报告，覆盖标题与开场承诺、带因果说明的节拍链、全片逐段作用、内容节奏与可迁移写法。
- 中文脚本框架，含标题公式、设定槽位、建议时长、可拍动作、可填对白和结尾承接。

链接需要当前 Codex 环境具有浏览器访问能力。读取视频需要可用的媒体能力，或可读取的关键帧、音轨、字幕等证据。遇到不可播放或只读到局部的素材，报告会标注覆盖范围。

## 开源许可

本项目采用 MIT 许可证，详见 [LICENSE](LICENSE)。
