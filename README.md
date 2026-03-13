游戏内容解包来的，解包工具推荐FModel_v4.4.1.1，千万不要用最新版，会报错；
这里提到我遇到的一个导出失败原因：缺少oo2core_9_win64.dll导致无法解压，下载一个放C:\Windows\System32目录下就行；
顺便一提，游戏没有加密，不需要AES秘钥，虚幻引擎版本是4.27.2，查看游戏运行的exe详细信息可得；
Phoenix/Content/Localization/WIN64是对话和任务文本所在路径，都是bin后缀，导出后可用parseltongue软件转换成JSON，两个JSON里都是中英文对照，将文本文件的后缀从json改为csv更方便筛选所需要的行；
Phoenix/Content/SQLiteDB是数据库所在路径，查看数据库文件的软件可以直接去SQLiteStudio官网下，我用的就是这个。
