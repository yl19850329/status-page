<p align="center">
  <img width="150px" alt="Logo" src="public/logo.svg" />
</p>

<h1 align="center">Status Page</h1>
<p align="center">一个基于 UptimeRobot API 的状态监控页面</p>
<p align="center"><a href="README.md">English</a> | 中文</p>

## 演示

演示地址：[https://status.lifeni.life](https://status.lifeni.life) 。

## 部署

### 部署在 Vercel 上

点击下面的按钮部署。

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2FLifeni%2Fstatus-page&env=NEXT_PUBLIC_KEY&envDescription=UptimeRobot%20API%20Key&envLink=https%3A%2F%2Fuptimerobot.com%2Fdashboard.php%23mySettings&demo-title=Status%20Page&demo-description=A%20demo%20site%20for%20Status%20Page.&demo-url=https%3A%2F%2Fstatus.lifeni.life&demo-image=https%3A%2F%2Ffile.lifeni.life%2Fstatus%2Fexample.jpg)

你需要在环境变量中配置 [UptimeRobot 的 Key](https://uptimerobot.com/dashboard.php#mySettings) 。

### 手动部署

1. Fork 这个仓库
2. 修改项目根目录下的 `config.ts` 文件，不要忘记替换 [UptimeRobot 的 Key](https://uptimerobot.com/dashboard.php#mySettings)
3. 提交并推送你的修改
4. 部署到 Vercel 或者其他平台

## 开源协议

MIT License