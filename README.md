# netdata.shangxian.app

基于 [netdata](https://github.com/titpetric/netdata) 的性能监控，使用 Jenkins Pipeline 向 sg02 推送 Docker Compose 配置文件，并推送 `nginx.conf` 到 sg02 的虚拟主机目录中实现反向代理。