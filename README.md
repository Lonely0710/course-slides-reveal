# Get a Quick Start

Forked from: [TonyCrane's Slide Template](https://github.com/TonyCrane/slide-template)

> [!note]
> 预览参考TonyCrane's Slide Template：https://slides.tonycrane.cc/RevealmdTemplate
> - Simple Theme: [reveal-md](https://github.com/webpro/reveal-md)
> - Reference: [jyywiki](https://jyywiki.cn)

## 构建与部署

>[!Important]
> - `custom.css`：亮色主题，载入即可
> - `dark.css`：暗色配置，使用需附带在 custom.css 后面

<details>
<summary>旧版指南（不推荐）</summary>

1. 安装 reveal-md
    ```sh 
    $ npm install -g reveal-md
    ```
2. 在浏览器中实时预览
    ```sh 
    $ reveal-md main.md -w
    ```
3. 构建静态文件
    ```sh 
    $ reveal-md main.md --static site --assets-dir assets
    ```
    - 生成 pdf 版：在 url 后面加上 `?print-pdf` 使用浏览器打印
4. 部署
    - 很蠢的一个实现，总之就是用 Action 把 site 文件夹中的内容复制到我的另一个私有 repo 中，然后在那个 repo 里部署 GitHub Pages
    - 构建出 site 文件夹后 commit & push，message 需要以 `[deploy]` 开头

</details>

使用 Makefile 来辅助预览与构建

1. 安装 reveal-md
    ```sh 
    $ npm install -g reveal-md
    ```
2. 开启本地实时预览
    ```sh
    $ make  # or make live
    ```
3. 构建静态文件
    ```sh
    $ make build
    ```
    - 生成 pdf 版：在 url 后面加上 `?print-pdf` 使用浏览器打印

## 用法

和 `reveal-js` 的快捷键一致，在页面中按下 `?` 可以查看所有快捷键。常用的：

| 按键 | 功能 |
|------|------|
| <key>N</key> / <key>SPACE</key> | 下一页 |
| <key>P</key> / <key>Shift</key> <key>SPACE</key> | 上一页 |
| <key>←</key> / <key>H</key> | 翻到左边页面 |
| <key>→</key> / <key>L</key> | 翻到右边页面 |
| <key>↑</key> / <key>K</key> | 翻到上边页面 |
| <key>↓</key> / <key>J</key> | 翻到下边页面 |
| <key>B</key> / <key>.</key> | 暂停（黑屏） |
| <key>F</key> | 全屏 |
| <key>ESC</key> / <key>O</key> | 显示概览 |
| <key>S</key> | 打开演讲者窗口 |
