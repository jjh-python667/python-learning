# Changelog

记录这个仓库里值得留下的改动。本仓库还没有发布版本号，所以下面用日期作为条目。

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
This repo has no release version yet, so the entry below is dated instead of numbered.

小节标题：Added 是新增，Changed 是修改。

## [Unreleased]

## [2026-11-11]

### Added

- 新增 `LICENSE`（MIT）。仓库里原来没有许可证文件。
- 新增本更新日志。
- `.gitignore` 补充系统自动生成的文件（`.DS_Store`、`Thumbs.db`、`desktop.ini`），并在开头和密钥一节加上简短中文说明。原来的 Python 忽略规则保留。

### Changed

- 重写 `README.md`：中文和英文简介、仓库里实际有的文件、练习索引，以及用 `python hello.py` 运行的方法。
- `hello.py` 增加一行中文注释，并补上文件末尾换行。`print("hello github")` 没有改。
- `.gitattributes` 补了一句中文说明，换行规则没有改。

目前能运行的练习仍然只有 `hello.py`。
