

## 使用Action自动签到
1. Fork此仓库
2. 在你自己fork的仓库的Settings - Secrets and variables - Actions - Repository secrets中创建一个名为RAINYUN_API_KEY的Repository secret，值为你获取的雨云apikey。
3. 为这个仓库启用Github Actions。然后运行一次测试。如果返回"未达成条件"，或者"任务成功"为正确配置。此后这个workflow将定时执行。如果返回需要登录，请检查你的api密钥是否填写在了正确的位置，你是否正确填写apikey。 
4. （可选）在Repository secret中新建两个Secret，分别名为TELEGRAM_CHAT_ID和TELEGRAM_BOT_TOKEN。填入你的tgchatid和对应通知机器人的token，保存。运行action时选取带tg通知版本的运行就可以收到通知了。
至于为什么我要分开两个文件 后面会合并的（当我抽风了).
注意⚠️ 你需要先給你創建的bot隨便發點消息機器人才能對你進行消息推送。









