

## 雨云自动签到
1. Fork此仓库
2. 在你自己fork的仓库的Settings - Secrets and variables - Actions - Repository secrets中创建一个名为RAINYUN_API_KEY的Repository secret，值为你获取的雨云apikey。
3. 为这个仓库启用Github Actions。然后运行一次测试。如果返回"未达成条件"，或者"任务成功"为正确配置。此后这个workflow将定时执行。如果返回需要登录，请检查你的api密钥是否填写在了正确的位置，你是否正确填写apikey。 


注意⚠️ 每日上海时间0:00整自动签到。









