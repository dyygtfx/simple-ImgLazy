# simple-imgLazy

>这是一个非常简单的图片延迟加载的脚本，没有其他多余的功能，只能加载 img 图片，背景图片无效，也不支持 R 屏，在 ipad 上滚动事件也无效，建议如果只在 PC 上使用的产品可以试试这个。
如果你想用更多功能的 imglazy loading ，可以考虑使用 [Imglazy.js](https://github.com/dyygtfx/ImgLazy)

## Usage

#### html结构
```html
 <ul>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg" alt="" class="imglazy"></li>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg"  alt="" class="imglazy"></li>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg" alt="" class="imglazy"></li>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg" alt="" class="imglazy"></li>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg" alt="" class="imglazy"></li>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg" alt="" class="imglazy"></li>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg" alt="" class="imglazy"></li>
  <li><img src="media/0.png" width="612" height="612" data-src="media/1.jpg" alt="" class="imglazy"></li>
</ul>
```

#### 引入 js

`<script src="simple-imgLazy.js"></script>`

##### 没了，就是这么简单

## DEMO

http://dyygtfx.github.io/simple-imgLazy/demo/index.html