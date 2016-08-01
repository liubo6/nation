## 中国省市区代码
来源  [中国人民共和国国家统计局](http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/)

## SQL 查询示例[中华人名共和国 id 为 1]
### 查询所有省份
```
SELECT
	*
FROM
	bank_nation
WHERE
	parent = 1
```
![](http://ww4.sinaimg.cn/mw690/69045600gw1f6e8sccgh1j20e60lxaaf.jpg)
### 根据省份查询所有市[浙江省 id 为 1001]
```
SELECT
	*
FROM
	bank_nation
WHERE
	parent = 1001
```
![](http://ww1.sinaimg.cn/mw690/69045600gw1f6e8scrfsyj20d807fglj.jpg)
### 根据城市代码查询区信息[杭州市 id 为 1002]
```
SELECT
	*
FROM
	bank_nation
WHERE
	parent = 1002
```
![](http://ww2.sinaimg.cn/mw690/69045600gw1f6e8sd3siij20da09fgll.jpg)
