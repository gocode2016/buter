# BUTER

注：

1. `Controller`统一以 XXXController 的命名格式
2. Flask 的 BluePrint 以 `xxxBp` 命名格式, 如`mainBp`

## Logger
> 日志保存到 `./logs/buter.log` 文件中，默认每天产生一个文件

默认日志相关的配置如下：

```python
LOG_LEVEL = logging.DEBUG
LOG_FORMAT = '%(asctime)s %(levelname)s %(process)d - %(filename)s (%(lineno)d) : %(message)s'
LOG_FILE = "./logs/buter.log"
# 默认保留15天内的日志
LOG_BACKUP = 15
LOG_ENCODING = 'utf-8'
```

## Models
> 此处定义了数据相关的实体类

详见 [/docs/db.md](../docs/db.md)
