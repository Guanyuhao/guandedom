
前后端分离，本地前端开发调用接口会有跨域问题，一般有以下3种解决方法：

1. 后端接口打包到本地运行（缺点：每次后端更新都要去测试服下一个更新包，还要在本地搭建java运行环境，麻烦）

2. CORS跨域：后端接口在返回的时候，在header中加入'Access-Control-Allow-origin':* 之类的（有的时候后端不方便这样处理，前端就蛋疼了）

3. 用nodejs搭建本地http服务器，并且判断访问接口URL时进行转发，完美解决本地开发时候的跨域问题。webpack-dev 代理

4. 使用谷歌的插件解决:https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi

5. 或者谷歌开启允许跨域,参考 http://camnpr.com/archives/chrome-args-disable-web-security.html

1.公司是否前后端分离 是否使用构建工具 是否使用git
2.spa页面
```
问题=》 seo搜索拦路虎  Prerender 预渲染 当搜索引擎后者蜘蛛爬虫访问网站的时候在服务器端对其转接js渲染完成的页面
单页面的用户体验 ↑↑↑
```
3.前端性能优化
```
从两方面去说一方面是页面优化，还有就是服务端优化。
1.页面加载性能优化，html中内联脚本异步加载，防止阻塞页面加载。

```
