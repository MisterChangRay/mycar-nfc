# mycar-nfc
车载NFC卡片贴实现


你导航是不是有以下麻烦， 车载导航很卡。打开手机导航需要点几步才能到地址选择页面， 然后才能点击导航并投递到车载导航页面。
最困难的是有时候跑往返路线， 当跑到目的地后


本应用主要解决这个问题， 项目实质上是一个地址管理网页，每次nfc打卡后将会展示一个H5的地址页面, 并在后台记录当前打卡地址。直接点击地址即可进行导航，简单方便。


## 部署实现
下载 nfc-tools-pro 写入卡片贴访问数据, 操作为: 任务 -> 添加任务 -> 网络 -> httpget -> 填入部署或公用服务器地址（格式如下）

服务器地址格式: http://xxxx/mycar/识别编码/经度/维度

公用服务器地址: http://gank.cc/mycar/test/经度/维度

然后即可将NFC标签贴到你的车上，用户扫描即可使用了
