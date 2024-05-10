# PG插件
1. 配置一下PG安装的路径到环境变量中。
2. 执行编译和安装。
```sh
make && sudo make install
```

## 添加插件
```sh
CREATE extension pg_hello; 
SELECT hello('world');
```