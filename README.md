#/etc/asterisk/#
	这个文件目录存放Asterisk的配置文件
#/usr/lib/asterisk/modules/#
	这个目录包含所有可加载的Asterisk模块。在这个目录中有许多应用程序、编码器、格式和有用的通道。启动Asterisk时将加载这些模块。可以在*modules.conf*这个文件中禁止不使用的模块。
#/var/lib/asterisk#
	/var/lib/asterisk/这个目录包含了 astdb 这个文件和许多子目录。astdb 这个文件包含了许多 Asterisk 当地数据库的信息,有点像微软的 Windows 系统的注册。
###sounds/###
	所有用到的声音提示文件都放在这个目录下
###moh/###
	如果你配置了 Asterisk 音乐保持,应用程序会在 mohmp3 这个目录下寻找
MP3 文件。Asterisk 对 MP3 的格式要求相当严格,所以你可以用 CBR 从你的文
件中去掉身份标签。
#/var/spool/asterisk/#
	Asterisk spool 目录中包含了许多子目录,包括 outgoing/、gcall/、tmp/和voicemail/。Asterisk 监控 outgoing 和 qcall 目录将所有的呼叫请
求信息以文本方式保存。这些文件允许你通过拷贝或者移动正确格式的文件到
outgoing/目录中发起一个简单的呼叫。
######extensions.conf######
  我们创建的拨号方案会比较粗糙,但是它们将证明系统
可用。
######sip.conf ######
  我们配置SIP协议的文件。
######iax.conf
  我们配置呼入和呼出IAX通道的文件。
