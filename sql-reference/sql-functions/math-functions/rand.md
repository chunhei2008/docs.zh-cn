# rand, random

## 功能

返回 0 到 1 的随机数

## 语法

```Haskell
RAND();

RAND(x);
```

## 参数说明

`x`: 支持的数据类型为 BIGINT

## 返回值说明

返回值的数据类型为 DOUBLE

## 示例

```Plain Text
mysql> select rand();
+--------------------+
| rand()             |
+--------------------+
| 0.9393535880089522 |
+--------------------+
1 row in set (0.01 sec)

mysql> select rand(3);
+--------------------+
| rand(3)            |
+--------------------+
| 0.6659865964511347 |
+--------------------+
1 row in set (0.00 sec)
```

## 关键词

RAND, RANDOM
