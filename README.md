# real-time-choose-seats
模拟电影院在线选座

## 要求
* 绘制30*30个座位
* 点击座位时会有座位被选中/取消效果

## 优化
* 为了优化加载,这里采用了惰性加载,即用定时器实现每100ms创建100个节点,这里只创建了900个节点,不过测试了下当创建9000个元素时加载速度也很快.


展示地址 : https://icebale.github.io/real-time-choose-seats/choose-seats.html
