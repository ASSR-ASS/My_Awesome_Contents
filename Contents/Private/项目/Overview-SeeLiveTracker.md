---
ProjectScale: M
ProjectExecTags: pf*
---
## Todos：
### Live-Dashboard
- *以**二次元风格**视监电脑的部分，兼职监控手机的**在线状态***
#### Server
- [x] 重新拉取docker-compose.example.yml作为本地备份
- [x] 添加并正式化Victus by HP Gaming Laptop 16-r0xxx的token链
- [x] 添加并正式化BLK-AL80的token链
- [x] 添加并正式化AUM-TL20的token链
- [x] 添加并正式化nabu的token链
- [x] 正式化\${HASH_SECRET},以及# Optional site customization下的内容
#### Client
##### Victus by HP Gaming Laptop 16-r0xxx
- [x] 安装并配置Agent
	```json
	{
  "server_url": "https://live.maw.moe",
  "token": "***",
  "interval_seconds": 10,
  "heartbeat_seconds": 30,
  "idle_threshold_seconds": 300,
  "enable_log": true
	}
	```
- [x] 设置开机自启
##### BLK-AL80
- [x] 安装并配置Agent
	配置见上
- [x] 安装health-connect应用
	本地已有安装包，直接使用即可
- [x] 设置后台常启
##### AUM-TL20
- [x] 安装并配置Agent
	配置见上
- [x] 设置后台常启
##### nabu
- [x] 安装并配置Agent
	配置见上
- [x] 安装health-connect应用
	本地已有安装包，直接使用即可
- [x] 设置后台常启
### Schedule-calender
- *与MSTD+Outlook形成联动（前端-中间件关系）*
#### MSTD
- [x] 将时光序内所有任务迁移至MSTD
- [x] 这个Vault中进行替换
	- [x] 特别注意：MoC
- [x] 在3台设备上安装MSTD
	- [x] Victus by HP Gaming Laptop 16-r0xxx
	- [x] BLK-AL80
	- [x] nabu
#### Outlook Calendar
- [x] 从MSTD中进行任务分配
- [x] 正式化Calendar的名称
#### maw.moe./schedule-calendar
- [x] 将转换后的Outlook Calendar订阅链接填入schedule-calendar

