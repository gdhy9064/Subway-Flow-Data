 - 该数据源自天池举办的全球城市计算AI挑战赛，点击[此处](https://pan.baidu.com/s/1iLHomv5NRodB_3jr7FcFow)下载原数据
提取码: arse

 - 这里的数据由原数据经过统计而来，数据格式如下

|数据列名|数据描述|
|:-:|:-:|
|stationID|地铁站ID(编号为0-80，其中54号数据缺失)|
|hour|小时编号(0~23)|
|per_ten_minute|十分钟段编号，共144(24x6)个，编号为0~143|
|outNums|当前十分钟段内的出站总人次|
|inNums|当前十分钟段内的入站总人次|
|day|天数编码，编码为1~当月最后一天|

 - test.csv为测试用数据，可无视
