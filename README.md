## 通过http api 接口 方式 获取股票 macd


接口示例：http://47.92.152.143/api/tech/indicators/macd?code=600460&interval=5


参数说明：
code 股票代码，
interval  最近多少天的每天的macd

返回结果：

[
{
dateStr: "2019-09-16",
dea: 0.3996,
diff: 0.7197,
macd: 0.6403,
macdDate: 1568563200000
},
{
dateStr: "2019-09-12",
dea: 0.3191,
diff: 0.5474,
macd: 0.4568,
macdDate: 1568217600000
},
{
dateStr: "2019-09-11",
dea: 0.2625,
diff: 0.4578,
macd: 0.3906,
macdDate: 1568131200000
},
{
dateStr: "2019-09-10",
dea: 0.2136,
diff: 0.4096,
macd: 0.392,
macdDate: 1568044800000
},
{
dateStr: "2019-09-09",
dea: 0.1647,
diff: 0.3962,
macd: 0.463,
macdDate: 1567958400000
}
]

 如果要查询其他股票的macd 请访问接口 api

http://47.92.152.143/api/tech/indicators/macd?code=002447&interval=5&key=


key是必填项，
如果需要使用，请捐赠5-8元（一瓶红牛），备注邮箱地址，收到立马回复key。
http://album.sina.com.cn/pic/001mRFe3zy7x48nbFh963
