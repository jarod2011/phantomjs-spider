# phantomjs-spider

### 本例子主要演示如何，使用phantomjs来抓取js渲染的页面

[测试页面](https://jarod2011.github.io/phantomjs-spider/)使用js渲染了一个简单的输出
```
Your can see me if your are not spider.
```
当使用curl来尝试获取页面时，获取结果中body中为空
```
curl https://jarod2011.github.io/phantomjs-spider/
```
得到结果如下图
![curl获取结果](https://i2.wp.com/www.developerhome.net/wp-content/uploads/2018/01/WX20180131-170949@2x.png)

而使用Phantomjs环境来执行spider.js，却能得到解析后的结果，如下图
![Phantomjs来获取页面body并输出](https://i2.wp.com/www.developerhome.net/wp-content/uploads/2018/01/WX20180131-171158@2x.png?ssl=1)

### 后面将陆续更新如何爬取React等复杂渲染方式的页面，敬请期待
