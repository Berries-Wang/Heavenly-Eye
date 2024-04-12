# mysqld_exporter
```txt
  1. mysqld_exporter 启动配置文件编写
      见:  000.Prometheus/005.MYSQLD_EXPORTER/000.STU.my.cnf
  2. 启动 mysqld_exporter 
     ./mysqld_exporter  --config.my-cnf=/home/wei/WorkSpace/open_source/Heavenly-Eye/000.Prometheus/005.MYSQLD_EXPORTER/000.STU.my.cnf
       OR 
     ./mysqld_exporter --web.listen-address=":9105" --config.my-cnf=/home/wei/WorkSpace/open_source/Heavenly-Eye/000.Prometheus/005.MYSQLD_EXPORTER/000.STU3310.my.cnf
  3. 从grafana dashboard 寻找对应模板即可查看MySQL指标
```