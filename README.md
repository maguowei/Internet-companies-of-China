# Internet-companies-of-China

```
导入MongoDB
mongoimport -d lg -c company --file=company.json

按指定字段导出csv格式
mongoexport -d lg -c company --type=csv --fieldFile fields.txt -o company.csv
```

* 数据来源: [拉勾网](http://www.lagou.com/)

* 采集方法: [viking](https://github.com/maguowei/viking)

* 采集时间: 2016-02-26

* 数据格式:

```
> db.company.findOne({'short_name': '拉勾网'})
{
	"_id" : ObjectId("56cf365a8883cd0076a49202"),
	"history" : [
		{
			"url" : "",
			"date" : "2015 Aug",
			"day" : "11",
			"title" : "拉勾移动App上线",
			"content" : "拉勾推出了移动版App，可以随时在手机上查看好机会，同时跟踪你的简历机会。",
			"type" : "其他"
		},
		{
			"url" : "",
			"date" : "2015 Mar",
			"day" : "09",
			"title" : "全民跳槽月",
			"content" : "“10万个offer”—全民跳槽月，首日投递量超过33万。",
			"type" : "数据"
		},
		{
			"url" : "",
			"date" : "2014 Dec",
			"day" : "08",
			"title" : "互联网招聘风暴周",
			"content" : "拉勾网举办史上最大规模互联网招聘周",
			"type" : "其他"
		},
		{
			"url" : "",
			"date" : "2014 Aug",
			"day" : "20",
			"title" : "获得B轮融资",
			"content" : "融资机构：启明创投，贝塔斯曼",
			"type" : "资本"
		},
		{
			"url" : "",
			"date" : "2014 Apr",
			"day" : "23",
			"title" : "获得A轮融资",
			"content" : "融资机构：贝塔斯曼",
			"type" : "资本"
		},
		{
			"url" : "",
			"date" : "2013 July",
			"day" : "20",
			"title" : "拉勾网正式上线",
			"content" : "",
			"type" : "产品"
		},
		{
			"url" : "",
			"date" : "",
			"day" : "",
			"title" : "获得天使轮融资",
			"content" : "融资机构：东方弘道,真格基金",
			"type" : "资本"
		},
		{
			"url" : "http://www.lieyunwang.com/archives/12924",
			"date" : "",
			"day" : "",
			"title" : "3w咖啡推创新型IT招聘网站拉勾网",
			"content" : "",
			"type" : "其他"
		},
		{
			"url" : "http://news.zol.com.cn/article/144500.html",
			"date" : "",
			"day" : "",
			"title" : "拉勾网：用垂直细分颠覆平台巨头？",
			"content" : "",
			"type" : "其他"
		},
		{
			"url" : "http://www.36kr.com/p/207756.html",
			"date" : "",
			"day" : "",
			"title" : "拉勾：用互联网思维做招聘",
			"content" : "",
			"type" : "其他"
		}
	],
	"href" : "http://www.lagou.com",
	"short_name" : "拉勾网",
	"company_word" : "帮用户找到满意的工作",
	"basic" : {
		"process" : "B轮",
		"type" : "企业服务,招聘",
		"address" : "北京",
		"number" : "150-500人"
	},
	"identification" : 1,
	"logo" : "http://www.lagou.com/image1/M00/25/D4/Cgo8PFVS2SeAWgf8AACUSzhxomw100.png",
	"company_img" : [
		"http://www.lagou.com/image1/M00/41/AE/Cgo8PFXJZk-AbPT4AACmh1YI1hM381.jpg",
		"http://www.lagou.com/image1/M00/41/AE/Cgo8PFXJZoiAf48TAAEAkhuG1JE138.jpg",
		"http://www.lagou.com/image1/M00/41/AE/Cgo8PFXJZo-AYdjxAADoHbvNPPM711.jpg",
		"http://www.lagou.com/image1/M00/41/AE/Cgo8PFXJZpWAex03AAGGCz47jYM686.jpg",
		"http://www.lagou.com/image1/M00/41/AE/Cgo8PFXJZpuAfnX2AAD7QBxFL3s964.jpg",
		"http://www.lagou.com/image1/M00/41/AE/Cgo8PFXJZqCAaUMiAADoC5cl5HE402.jpg",
		"http://www.lagou.com/image1/M00/41/AF/CgYXBlXJZsSASUhaAACbc9xtjk8497.jpg"
	],
	"name" : "北京拉勾网络技术有限公司",
	"lagou_url" : "http://www.lagou.com/gongsi/147.html",
	"manager_list" : [
		{
			"content" : "2006年毕业于北京邮电大学工业设计专业，随后加入腾讯CDC，参与过腾讯公司07版QQ的研发，后供职于百度等顶级互联网企业。马德龙擅长在产品的用户体验和技术实现之间寻找平衡点，目前在公司里负责产品和团队管理。",
			"weibo" : "http://weibo.com/banlon",
			"title" : "CEO",
			"photo" : "http://www.lagou.com/image2/M00/04/B4/CgpzWlXyoUiAVKFRAAOb73RQbg4170.jpg",
			"name" : "马德龙"
		},
		{
			"content" : "2005年毕业于武汉理工大学，曾就职于腾讯、搜狐等多家顶级知名互联网企业，拥有丰富的互联网产品推广经验，曾参与创立了3W传媒，并担任CEO。她精通市场和运营，目前在拉勾网主要负责市场推广。",
			"weibo" : "http://weibo.com/10110806",
			"title" : "CMO",
			"photo" : "http://www.lagou.com/image1/M00/00/BA/Cgo8PFTUYDaAE-0dAAAVAxML288111.jpg",
			"name" : "鲍艾乐"
		},
		{
			"content" : "2007年于北京大学硕士毕业后，先后供职于腾讯集团、平安证券和华夏基金等顶级互联网公司和金融机构，擅长互联网公司的战略分析与制定。",
			"weibo" : "http://weibo.com/xddpku",
			"title" : "董事长",
			"photo" : "http://www.lagou.com/image1/M00/00/BA/CgYXBlTUYDaAAdrjAAESyIsBsj4122.png",
			"name" : "许单单"
		}
	],
	"address" : [
		"北京市海淀区海淀大街34号海置创投大厦4层",
		"海淀西大街36号海淀图书城昊海楼608室",
		"深圳市南山区深圳市软件产业基地4栋-c座10楼",
		"黄浦区瑞金南路1号海兴广场18楼E座",
		"广州市天河区富力·公园28 B2栋2101"
	],
	"company_intro_text" : "拉勾网是专注于互联网行业招聘的网站。|拉勾网拥有优质互联网资源，收集和发布圈内招聘信息，为求职者提供人性化、个性化的信息服务，以让优质人才和优秀企业及时相遇为己任。从拉勾网上线至今已有超过80000家互联网公司入驻，这其中既有百度、腾讯、阿里巴巴、新浪、优酷土豆、乐视网等成熟稳重的大企业，也有去哪儿、聚美优品、锤子科技、小米、豌豆荚等高速成长的行业新秀。企业覆盖领域包括互联网、移动互联网、电子商务、游戏、O2O、大数据、云计算、社交网络、互联网金融、在线教育、在线旅游等25个互联网细分市场。|拉勾网垂直细分的特点，大大降低了求职者简历的误投率，同时也改变了“求职者—招聘网站—用人企业”的传统模式，让求职者直接面对用人企业，极大提高了企业的招聘效率。|拉勾网相信：相对于传统招聘模式，撬动互联网职场的杠杆在求职者一端。只有首先汇聚大量的优质求职者，才能真正满足用人单位的需求，才能真正服务好用人单位。所以，拉勾网立志于解决传统招聘行业低效、不尊重求职者的痛点，保护求职者的利益，专注于为求职者提供更人性化、专业化的服务。"
}
```
