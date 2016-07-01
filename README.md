# FinalSpeed备用安装方法


把这个源打包下载，将finalspeed_server.zip和install_fs.sh上传到主机，放在同一目录

chmod +x install_fs.sh

./install_fs.sh 2>&1 | tee install.log


debian,ubuntu下如果执行脚本出错,请切换到dash,
切换方法: sudo dpkg-reconfigure dash 选no


安装完后查看日志
tail -f /fs/server.log

