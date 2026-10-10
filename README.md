<div align="center">

# 博客

用 Markdown 写作，按主题归档。仓库本身就是成品 —— 在网页上直接读，克隆下来就是一堆纯文本。

[![文章](https://img.shields.io/badge/%E6%96%87%E7%AB%A0-1%20%E7%AF%87-18794e?style=flat-square)](#目录)
[![许可](https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF-Unlicense-565a5f?style=flat-square)](LICENSE)

</div>

---

## 目录

| # | 文章 | 主题 |
| --- | --- | --- |
| 0001 | [示例文章](articles/0001-示例文章.md) | 格式说明 |

## 怎么用这个仓库

- **读**：在 GitHub 网页上点开 `articles/` 里的文件就能读，不需要任何工具。克隆到本地就是一堆 `.md`。
- **写**：复制 `templates/文章模板.md` 到 `articles/`，命名成 `编号-标题.md`，再回到上面「目录」表里加一行。
- **命名规则**：编号四位、递增、不复用（`0001`、`0002`……）。编号只负责排序，和发布日期无关；标题用中文没问题，GitHub 会自己处理链接编码。
- **配图**：图片放 `assets/`，正文里用相对路径引用，例如 `![说明](../assets/图片.png)`。

## 结构

```
blog/
├── README.md          # 你正在看的这一页，也是总目录
├── articles/          # 文章正文，一篇一个文件
├── templates/         # 新文章模板
├── assets/            # 文章用到的图片等附件
├── LICENSE
├── .gitignore
└── .gitattributes     # 换行统一成 LF
```

## 许可

[Unlicense](LICENSE) —— 公有领域，随便用。
