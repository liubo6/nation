## 中国省市区代码
来源  [中国人民共和国国家统计局](http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/)

## SQL 查询示例
### 查询所有省份
```
SELECT
	*
FROM
	bank_nation
WHERE
	parent = 1
```

### 根据省份查询所有市[浙江省 id 为 1001]
```
SELECT
	*
FROM
	bank_nation
WHERE
	parent = 1001
```

### 根据城市代码查询区信息[杭州市 id 为 1002]
```
SELECT
	*
FROM
	bank_nation
WHERE
	parent = 1002
```
