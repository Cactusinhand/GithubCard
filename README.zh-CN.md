# GitHubCard Showcase

GitHubCard is a drag-and-drop GitHub profile README and repo card generator — one live card instead of a stack of README embeds.

这个公开仓库展示 GitHubCard 的个人主页卡片和仓库卡片。`showcase/` 目录直接复制自主项目当前的 `public/showcase`，后续可以继续补充。

## 快速开始

1. 打开 [Profile Card 生成器](https://githubcard.com/~profile-card) 或 [Repo Card 生成器](https://githubcard.com/~repo-card)。
2. 输入 GitHub 用户名或 owner/repository，选择需要的组件。
3. 把下面这一行 Markdown 粘贴到 README：

```md
[![GitHubCard](https://githubcard.com/<username>.svg?d=<design-id>)](https://githubcard.com/<username>/card?utm_source=github&utm_medium=readme)
```

仓库中的每张卡片只保留一个 PNG 文件。`showcase/manifest.json` 记录 32 个 profile 条目和 32 个 repo 条目，README 会展示全部条目。

## 目录

- `showcase/profile/`：个人主页卡片
- `showcase/repo/`：仓库卡片
- `showcase/manifest.json`：素材清单

## 相关链接

- [GitHubCard](https://githubcard.com/)
- [博客](https://githubcard.com/blog)
- [Profile Card 生成器](https://githubcard.com/~profile-card)
- [Repo Card 生成器](https://githubcard.com/~repo-card)

图片来自 GitHubCard 当前公开 showcase。需要移除或修正素材时，请提交 issue 并写明文件路径。
