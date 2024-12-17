

## 雨云签到
1. Fork此仓库
2. 在fork的仓库的Settings - Secrets and variables - Actions - Repository secrets中创建一个名为RAINYUN_API_KEY的Repository secret，值为雨云api key。
3. 为这个仓库启用Github Actions,然后运行一次,如果返回"未达成条件"，或者"任务成功"为正确配置。此后这个workflow将定时执行。如果返回需要登录，请检查你的api key是否正确配置。 









