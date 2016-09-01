
欧海涛  

吕周能


临
龙玖兰
jiulan_long@kingdee.com
龙玖兰
=======================================
BBC商城后台：
http://172.20.135.222:8089/
BBC商城门户：
http://172.20.135.222:8086
需求文档：
http://172.20.135.222:8090

demo1
test
test01
nsmd
administrator　111111；
用户名 test 密码111111
=======================================
k3cloud端
http://172.20.135.222:83/k3cloud/html5/
用户名，密码。
前台

后台

数据库
172.20.135.222
jdbc2.url = jdbc:sqlserver://172.20.135.222:1433;database=o2o_developer;integratedSecurity=false;autoReconnect=true 

172.20.135.130/view.jhtml?page=b2b_direct

业务对象
/dynamicForm/view.jhtml?id=MetaDataListView
菜单
/dynamicForm/view.jhtml?id=MenuListView
商品标签
/dynamicForm/view.jhtml?id=GoodsLabelListView
菜单分组
/dynamicForm/view.jhtml?id=MenuGroupListView
---f7配置
superselectDefine.xml views\system\admin\core

http://localhost:8080/dynamicForm/view.jhtml?id=ShuDemoList


//===========
View的分层。
重启插件

表　－－　配置 
USE [o2o_developer]
GO

/****** Object:  Table [dbo].[T_ESS_COMPANY]    Script Date: 2016/8/30 15:42:38 ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

SET ANSI_PADDING ON
GO

CREATE TABLE [dbo].[T_ESS_SHUDemo](
	[fid] [bigint] IDENTITY(1,1) NOT NULL,
	[fnumber] [nvarchar](255) NOT NULL,
	[fname] [nvarchar](255) NOT NULL,
	[FCREATETIME] [datetime] NULL,
 CONSTRAINT [T_ESS_SHUDemo] PRIMARY KEY NONCLUSTERED 
) ON [PRIMARY]

GO





