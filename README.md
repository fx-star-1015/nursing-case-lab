# 护理研习室

内外科护理案例学习网站。纯静态 HTML、CSS 和 JavaScript，无需 GPT 账号、API Key 或构建工具。

## 功能

16 个专题、关键词搜索、案例作答、参考解析、自评、复盘笔记、待复习清单和学习进度。记录保存在访问者自己的浏览器中，可导出和导入。

## 发布到 GitHub Pages

将本目录内容放到仓库根目录，进入仓库 Settings → Pages，在 Build and deployment 中选择 Deploy from a branch，选择 main 分支和 /(root)，保存。发布地址以 Pages 页面显示的地址为准。

所有资源均使用相对路径，兼容用户名.github.io/仓库名/这样的项目地址。

## 本地运行

直接打开 index.html，或在本目录运行 python -m http.server 8000 后访问 http://localhost:8000。

## 学习记录迁移

在原站点导出学习记录，再在新站点导入。不同域名的浏览器存储不会自动共享。

## 内容边界

16 个新编教学案例，来自讲义正文定向蒸馏；非学校官方题库，未覆盖全部PDF和图片病例。来源与核对信息可在网站的“内容与来源”中查看。仅供学习，非临床诊疗建议。

## 托管边界

此版本是免费学习静态站，没有服务器账号体系、云端笔记或付费权限。GitHub Pages 不应用于运营主要提供商业交易或商业SaaS的网站；若升级收费服务，保留GitHub作源码管理，另选后台托管。

https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

未附开源许可证；不代表原始讲义版权已获公开再利用授权。仓库不包含原始讲义、身份信息或任何服务密钥。
