

## 雨云签到
### Action
1. Fork此仓库
2. 在fork的仓库的Settings - Secrets and variables - Actions - Repository secrets中创建一个名为RAINYUN_API_KEY的Repository secret，值为雨云api（需要在个人中心的api处获取key）。
3. 启用Actions后运行一次“每日签到”任务,如果返回"未达成条件"，或者"任务成功"即为正确配置，此后任务会自动定时执行。如果返回需要登录，请检查你的api key是否正确配置。 

### 宝塔
  "curl -s -X POST \"
         " -H "Content-Type: application/json" \"
         " -H "x-api-key: 此处填你的API" \"
        "  -d '{"task_name": "每日签到"}' \"
         " https://api.v2.rainyun.com/user/reward/tasks""

          
![Uploading image.png…]()







