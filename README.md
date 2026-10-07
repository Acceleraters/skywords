# SkyWords V0.11

可直接发布到 GitHub Pages 的背单词网页。词库、音标、图片与程序均包含在 index.html 中，发音数据的来源和许可证也内嵌于文件源码。

## 首次发布（无需命令行）

1. 登录 GitHub，新建名为 skywords 的 Public（公开）仓库。可以勾选添加 README，创建 main 分支。
2. 在仓库中选择 Add file → Upload files，将此文件夹内的 index.html、.nojekyll、README.md 上传到仓库根目录，提交到 main。不要上传 ZIP，也不要再套一层文件夹。
3. 打开仓库 Settings → Pages。
4. Source 选择 Deploy from a branch，Branch 选择 main，目录选择 / (root)，点击 Save。
5. 等待部署完成，使用 Pages 页面显示的 Visit site 链接。通常地址为 https://你的用户名.github.io/skywords/。

首次发布还未完成时可能暂时出现 404。检查 Actions 中部署是否成功、main 根目录是否直接存在 index.html，以及 Pages 是否选择 main / (root)。

## 使用与数据迁移

网页可通过电脑或 iPhone 浏览器访问。线上发布没有添加自动离线缓存，因此第一次访问需要联网，断网后可用性不保证；仍可下载 index.html 在支持 JavaScript 的本地 HTML 环境中运行。

学习记录和个人单词仍保存在每个浏览器中，不会因为部署到 GitHub 就自动跨设备同步。先在原 V0.11 设置页导出完整备份，再在新网址的设置页恢复完整备份。个人备份文件保留在自己设备上，不需要上传仓库。

朗读使用设备英文语音，没有内置真人 MP3；可用性和音色取决于设备及浏览器。

## 后续更新

将新版部署文件覆盖到同一仓库的 main 分支，GitHub Pages 会重新发布。更新前建议导出完整备份，继续使用原网址。

## 官方说明

- [设置发布分支](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [网页上传文件](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
