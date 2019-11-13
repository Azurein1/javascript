## 浏览器事件循环

#### 浏览器多进程

```js
    主要包含主进程和多个渲染进程。主进程主要负责对其他进程的管理，包括创建和销毁，以及将渲染进程返回的位于内存中的Bitmap渲染到显示器上，同时负责网络资源的下载等等。而每个渲染进程则对应于一个标签页，负责管理当前标签页打开的页面DOM结构解析，JavaScript脚本执行等
```

#### 单线程
>
    JS引擎线程
    GUI渲染线程
    事件触发线程
>