# Internet-companies-of-China

数据来源: [拉钩网](lagou.com)

采集方法: [viking](https://github.com/maguowei/viking)

采集时间: 2016-02-26

```
导入MongoDB
mongoimport -d lg -c company --file=company.json

按指定字段导出csv格式
mongoexport -d lg -c company --type=csv --fieldFile fields.txt -o company.csv
```
