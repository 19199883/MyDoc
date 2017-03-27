金瑞期货生产环境备份：
1. 实盘脚本、配置备份
	sh [exchange]_backup_scripts.sh
2. 服务器备份
	tar -cvzf zce_trade.tar.gz ~/
3. crontab备份
	crontab -l > zce_crontab.txt
4. xshell会话配置
