
ŷ����  

������


��
������
jiulan_long@kingdee.com
������
=======================================
BBC�̳Ǻ�̨��
http://172.20.135.222:8089/
BBC�̳��Ż���
http://172.20.135.222:8086
�����ĵ���
http://172.20.135.222:8090

demo1
test
test01
nsmd
administrator��111111��
�û��� test ����111111
=======================================
k3cloud��
http://172.20.135.222:83/k3cloud/html5/
�û��������롣
ǰ̨

��̨

���ݿ�
172.20.135.222
jdbc2.url = jdbc:sqlserver://172.20.135.222:1433;database=o2o_developer;integratedSecurity=false;autoReconnect=true 

172.20.135.130/view.jhtml?page=b2b_direct

ҵ�����
/dynamicForm/view.jhtml?id=MetaDataListView
�˵�
/dynamicForm/view.jhtml?id=MenuListView
��Ʒ��ǩ
/dynamicForm/view.jhtml?id=GoodsLabelListView
�˵�����
/dynamicForm/view.jhtml?id=MenuGroupListView
---f7����
superselectDefine.xml views\system\admin\core

http://localhost:8080/dynamicForm/view.jhtml?id=ShuDemoList


//===========
View�ķֲ㡣
�������

������������ 
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





