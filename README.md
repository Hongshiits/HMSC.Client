# HMSC.Client
与HMSC_Server对应，目前用于管理客户端Minecraft mod，确保客户端mod与服务端一致，排除因mod缺失而导致无法进入服务器
带有黑名单mod删除功能，保证游戏公平性

使用：
在网页服务器上建立两个文本文档，在WpfApp2.exe.config中将对应路径改为两个文本文档链接即可。
black_list.txt存储黑名单mod，mods_list.txt存储登入服务器所需mod
格式：
mods_list.txt
第一行 mod下载链接|mod文件名
第二行 ...
........
black_list.txt:
第一行 黑名单mod文件名
第二行 ....
.....
