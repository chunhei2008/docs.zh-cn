# DOUBLE

## 描述

DOUBLE

8 字节浮点数

## 示例

创建表时指定字段类型为 DOUBLE。

```sql
CREATE TABLE doubleDemo (
    pk BIGINT(20) NOT NULL COMMENT "",
    income DOUBLE COMMENT "8 bytes"
) ENGINE=OLAP 
DUPLICATE KEY(pk)
COMMENT "OLAP"
DISTRIBUTED BY HASH(pk) BUCKETS 4;
```

## 关键字

DOUBLE
