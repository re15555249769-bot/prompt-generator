# 提示词生成器网站发布说明

这个文件夹用于发布 GitHub Pages 网站。当前配置对应仓库：

```text
https://github.com/249769/prompt-generator
```

网站地址：

```text
https://249769.github.io/prompt-generator/
```

软件下载文件已经放在 GitHub Releases，网页下载按钮会指向：

```text
https://github.com/249769/prompt-generator/releases/latest/download/PromptGenerator-Setup.exe
https://github.com/249769/prompt-generator/releases/latest/download/PromptGenerator-Portable.zip
```

## 上传到 GitHub Pages

上传到仓库根目录的是本文件夹里的内容，不是整个 `website` 文件夹。

需要上传：

- `index.html`
- `robots.txt`
- `sitemap.xml`
- `site.webmanifest`
- `checksums.txt`
- `README.md`
- `assets/app_icon.png`

不需要上传 `downloads` 文件夹，因为安装器和便携包已经由 GitHub Releases 提供下载。

## 开启 Pages

1. 打开仓库 `Settings`。
2. 左侧点击 `Pages`。
3. `Source` 选择 `Deploy from a branch`。
4. `Branch` 选择 `main`，文件夹选择 `/(root)`。
5. 点击 `Save`。

等待 1 到 10 分钟后，访问：

```text
https://249769.github.io/prompt-generator/
```

## 搜索引擎提交

网站上线后，可以提交 sitemap：

```text
https://249769.github.io/prompt-generator/sitemap.xml
```

提交入口：

- Google Search Console: https://search.google.com/search-console
- Bing Webmaster Tools: https://www.bing.com/webmasters
