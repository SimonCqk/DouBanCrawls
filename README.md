### DouBan Crawler Series 
> 参考了别人的code，做了一些改进和版本迁移，完成豆瓣读书/电影相关的爬取，更多信息待加入补充。

### 豆瓣图书爬虫    [Python 3.6.1]
> 爬取结果在`Result_Book`文件夹，可直接查看  <br>

#### 实现功能： 
 - 按标签名称进行相关图书信息的抓取，排序后存入本地excel，可自行进行进一步筛选，按`Tag`存取在不同的`Sheet`
 - 使用`User Agent`伪装成不同的浏览器进行爬取，并加入随机延时来更好的模仿浏览器行为，避免爬虫被封
    
##### 豆瓣页面截图：

![Page](https://github.com/SimonCqk/DouBanCrawls/blob/master/ScreenShots/doubanpage.jpg?raw=true)

##### 运行时截图：

![Running](https://github.com/SimonCqk/DouBanCrawls/blob/master/ScreenShots/running.jpg?raw=true)

##### Excel结果截图：

![Excel](https://github.com/SimonCqk/DouBanCrawls/blob/master/ScreenShots/excel.jpg?raw=true)

### 豆瓣电影爬虫
> 爬取结果在`Result_Movie`文件夹，可直接查看 <br>
#### 实现功能： 
 - 按标签名称进行相关电影信息的抓取，排序后存入本地excel，可自行进行进一步筛选，按`Tag`存取在不同的`Sheet`
 - 使用`User Agent`伪装成不同的浏览器进行爬取，并加入随机延时来更好的模仿浏览器行为，避免爬虫被封
   
   
##### 豆瓣页面截图：

![Page](https://github.com/SimonCqk/DouBanCrawls/blob/master/ScreenShots/movie_page.jpg?raw=true)

##### 运行时截图：

![Running](https://github.com/SimonCqk/DouBanCrawls/blob/master/ScreenShots/movie_running.jpg?raw=true)

##### Excel结果截图：

![Excel](https://github.com/SimonCqk/DouBanCrawls/blob/master/ScreenShots/movie_excel.jpg?raw=true)


> 欢迎 Star / PR.
