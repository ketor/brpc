parallel_http能同时访问大量的http服务（几万个），适合在命令行中查询线上所有server的内置信息，供其他工具进一步过滤和聚合。curl很难做到这点，即使多个curl以后台的方式运行，并行度一般也只有百左右，访问几万台机器需要等待极长的时间。