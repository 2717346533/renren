# renren
使用scrapy发送一个post请求模拟登陆人人网
1.想要发送post请求，那么推荐使用 scrapy.FormRequest方法，可以方便的指定表单数据
2.如果想在爬虫一开始的时候就发送post请求，那么应该重写 start_requests方法.在这个方法中，发送post请求
