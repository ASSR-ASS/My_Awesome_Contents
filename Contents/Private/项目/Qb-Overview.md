---
ProjectScale: ML
ProjectExecTags: p
---

```mermaid
---
config:
  kanban:
    ticketBaseUrl: ''
    useMaxWidth: false
---
kanban
	Planned["已计划"]
		NapCat["NapCat"]@{assigned: 'ProtImp',priority: '',ticket: }
		QQoffi["QQ官方"]@{assigned: 'ProtImp',priority: '',ticket: "官网配置"}
		llBot["LLBot"]@{assigned: 'ProtImp',priority: '',ticket: }
		Mahirobot["真寻Bot"]@{assigned: 'FuncDirect',priority: '',ticket: }
		ZeroBotPl["ZeroBot-Plugin"]@{assigned: 'FuncDirect',priority: '',ticket: }
		DDbotse["DDbot"]@{assigned: 'Frame',priority: '',ticket: }
		Koishise["Koishi"]@{assigned: 'Frame',priority: '',ticket: }
		AstrBotse["Astrbot"]@{assigned: 'Frame',priority: '',ticket: }
		NB2se["NoneBot2"]@{assigned: 'Frame',priority: '',ticket: }
		OpenClawse["OpenClaw"]@{assigned: 'Frame',priority: '',ticket: "独立程序"}
		ATRIse["ATRI"]@{assigned: 'Frame',priority: '',ticket: }
		Kovise["Kovi"]@{assigned: 'Frame',priority: '',ticket: }
		Miraise["Mirai"]@{assigned: 'Frame',priority: '',ticket: }
		YunZaise["云崽"]@{assigned: 'Frame',priority: '',ticket: }
	Installed["已安装"]
	Configured["已配置"]
	Deployed["已部署"]
	Running["运行中"]
	
	%% priority: 'Very High' -->Rolling Back
	%% priority: 'High' -->Have Problems
	%% priority: 'Low' -->Action Paused
	%% priority: 'Very Low' -->Pushing forward
	%% priority: '' -->Not Started
```

```mermaid-next
architecture-beta
	group Prot(cloud)["ONEbot11/QQ官方协议"]
    group ProtImp(cloud)["协议实现层"] in Prot
    group Frame(cloud)["框架层"] in Prot
    group Func(cloud)["功能集/功能层"] in Prot
    
    group FuncDirect(cloud)["直接与协议实现层对接"] in Func
    group Kovi(cloud)["Kovi"] in Func
    group ATRI(cloud)["ATRI"] in Func
    group Mirai(cloud)["Mirai"] in Func
    group NB2(cloud)["NoneBot2"] in Func
    group Koishi(cloud)["Koishi"] in Func
    group DDbot(cloud)["DDbot"] in Func
    group OpenClaw(cloud)["OpenClaw"] in Func
    group Astrbot(cloud)["Astrbot"] in Func
    group YunZai(cloud)["云崽"] in Func
    
    
    service NapCat(disk)["NapCat"] in ProtImp
    service QQoffi(disk)["QQ官方"] in ProtImp
    service llBot(disk)["LLBot"] in ProtImp
    
    service Mahirobot(database)["真寻Bot"] in FuncDirect
    service ZeroBotPl(database)["ZeroBot-Plugin"] in FuncDirect
    
    service DDbotse(server)["DDbot"] in Frame
    service Koishise(server)["Koishi"] in Frame
    service AstrBotse(server)["Astrbot"] in Frame
    service NB2se(server)["NoneBot2"] in Frame
    service OpenClawse(server)["OpenClaw"] in Frame
    service ATRIse(server)["ATRI"] in Frame
    service Kovise(server)["Kovi"] in Frame
    service Miraise(server)["Mirai"] in Frame
    service YunZaise(server)["云崽"] in Frame
    
    service Protse(server)["协议组占位符"] in Prot
    
    %% group的代表service应该是目前用的最多的那个
	Mahirobot:R -- L:llBot
	ZeroBotPl:R -- L:llBot
	NB2se:R -- L:Protse
	NB2se{group}:R -- L:QQoffi{group}
    
```

```mermaid-next
venn-beta
	title 框架支持的协议实现端
	set N["NapCat"]:13
		text Mirai
		text Kovi
		text ATRI
	set Q["QQ官方"]
	set L["LLbot"]:15
		text YunZai["云崽"]
		text DDbot
		text Mahirobot["真寻Bot"]
		text ZerobotPlugin["Zerobot-Plugin"]
	
	union N,Q[""]
	union N,L[""]
		text Koishi
	union Q,L[""]
		text OpenClaw
	union N,Q,L[""]:13
		text NoneBot2
		text Astrbot
	style N fill:#9BCAF9
	style Q fill:#99EFCF
	style L fill:#BCA4FD
```


```mermaid
gantt
	title Qbot演变图
    dateFormat YY-MM-DD
    axisFormat %y-%m-%d
    
    section 功能集层
    %% 单独的功能（插件）太多了，不记了喵
       
    section 框架层
    
    section 协议实现层
    
    
    %% Tag: active -->future use
	%% Tag: done -->pending
	%% Tag: crit -->active
	%% Tag: milestone -->version tags
	%% Tag:  -->backup
```