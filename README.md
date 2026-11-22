# 寰美海外 · 美国合作企业面板（雏形预览）

这是给手机和电脑打开、并可安装到主屏幕的静态预览页。页面只包含虚构的「示例数据」，填写内容保存在你自己的浏览器里，没有接到线上业务系统。

目标地址（需先在仓库开启 GitHub Pages）：https://tonyshangwu.github.io/hm-us-partner-panel-preview/

仓库已公开，这样链接不用登录就能打开。搜索引擎已用 `noindex` 和 `robots.txt` 声明不要收录。

## 第一次发布

当前仓库里的预览文件和发布流程已经就绪。GitHub 不允许用 Actions 令牌第一次创建 Pages 站点，需要仓库拥有者用 GitHub 账号 **tonyshangwu** 登录后操作一次：

1. 打开 [Pages 设置](https://github.com/tonyshangwu/hm-us-partner-panel-preview/settings/pages)
2. Build and deployment 里把 Source 设为 **GitHub Actions**
3. 保存。保存后会自动（或手动 Re-run）「Deploy GitHub Pages」工作流，一两分钟后上述地址可用。

## 如何下线

在 GitHub 打开本仓库，选择 Settings → Danger zone → Delete this repository，删除后链接即失效。也可以只关闭 Settings → Pages，页面会停止发布，仓库仍保留。
