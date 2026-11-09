传奇开服雷达 · 静态站点包
================================

域名：https://playermir.github.io
核心词：传奇发布网新开服
首页标题：传奇发布网新开服_今日新开传奇开服表_版本与开服时间速查

一、文件结构（全部平铺在根目录，与 index.html 同级）
  index.html          首页（含今日/明日/后日开服表）
  kaifubiao.html      开服表整页
  kaifu.html          栏目：开服动态（10 篇）
  banben.html         栏目：版本速查（9 篇）
  gonglue.html        栏目：玩法攻略（11 篇）
  gushi.html          栏目：玩家故事（7 篇）
  rumen.html          栏目：新手入门（7 篇）
  art01.html ... art44.html   44 篇独立文章页
  about.html          关于与免责声明
  search.html         站内搜索（noindex）
  404.html            404 页（noindex）
  style.css           唯一一份样式文件
  favicon.svg
  sitemap.xml
  robots.txt
  .nojekyll           告诉 GitHub Pages 不要跑 Jekyll

二、部署到 playermir.github.io
  1. 把本目录全部文件上传到 playermir.github.io 仓库的默认分支根目录。
  2. 仓库 Settings → Pages → Source 选择 Deploy from a branch，分支默认、目录 /(root)。
  3. 等待 1—2 分钟，访问 https://playermir.github.io/ 即可。
  4. 站点根路径无需任何子目录，所有链接都是同级 .html。

三、上线后的 SEO 动作（需要你自己执行）
  1. 百度搜索资源平台添加站点 playermir.github.io，完成 HTML 标签或文件验证。
  2. 提交 sitemap：https://playermir.github.io/sitemap.xml
  3. 用平台“普通收录”手动提交首页与新文章 URL；若有 API 推送权限，可配置推送脚本。
  4. 后续更新文章后，重新提交 sitemap 并在平台观察抓取与索引量。

四、说明
  站内区服与开服时间为示例整理，用于演示开服表结构，不提供客户端下载、充值或交易入口。
  文章内容为游戏资讯与玩家经验整理，可自行替换为真实运营信息后再发布。
