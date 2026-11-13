# ABS 信用研究报告技能

在 Codex 中根据同一期募集说明书和信用评级报告撰写中文 ABS／ABN 信用研究报告。可选择 Word 或纯文本。Word 版使用随附的通用模板，纯文本版在图表处标注来源、页码及编号。

## 下载和安装

1. 在 GitHub 仓库首页选择 **Code → Download ZIP**（或[直接下载](https://github.com/Chenoa047/abs-credit-report/archive/refs/heads/main.zip)） 并解压。
2. 把解压后的整个 `skills/abs-credit-report` 文件夹复制到 Codex 用户技能目录 `~/.agents/skills/`。安装后的入口应为 `~/.agents/skills/abs-credit-report/SKILL.md`。同名技能已存在时，可先备份原文件夹。
3. 打开 Codex，用 `$abs-credit-report` 调用。技能尚未显示时，重新启动 Codex。

也可以在 Codex 中输入：

    $skill-installer https://github.com/Chenoa047/abs-credit-report/tree/main/skills/abs-credit-report

## 用法

附上同一期的募集说明书和评级报告，然后输入：

- `$abs-credit-report 请写这期ABS的信用研究报告，生成Word版。`
- `$abs-credit-report 请写这期ABN的信用研究报告，生成纯文本版。`

未指定时生成 Word。可另附自用报告模板。仓库含技能、写作规则及通用模板，使用时请自行提供本期项目资料。

允许下载、安装及使用本仓库所含技能和通用模板，用于生成自己的报告。
