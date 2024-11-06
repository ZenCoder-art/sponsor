# Playing-reward

一个简单的打赏小组件, 修改自 [donate-page](https://github.com/Kaiyuan/sponsor-page)

## 使用

1. 更换 `index.html` 内的链接

```html
<!-- 修改href属性为你自己的github项目 -->
<a id="github" href="https://github.com/ZenCoder-art/sponsor" target="_blank" class="pos-f tr3" title="Github"></a>
<!-- 修改href属性 -->
<a href="https://imdnspod.top" target="_blank" style="position: fixed;">
    <div id="DonateText" class="tr3">Sponsor</div>
</a>
<!-- 修改为你自己的paypal链接 -->
<li id="PayPal">
    <a href="https://www.paypal.com/paypalme/zhouweinuo" target="_blank">PayPal</a>
</li>
```
2. 更换`script.js`的图片为你自己的打赏图片

```javascript
// 更改为你自己的图片
const qqr = 'images/QQ.png'
const aqr = 'images/alipay.jpg'
const wqr = 'images/wechat.png'
```

> 使用 iframe 嵌入页面的代码，高度至少 `240px` ，宽度至少 `310px`

```html
<iframe src="https://pay.imdnspod.top" style="overflow-x:hidden;overflow-y:hidden; border:0xp none #fff; min-height:240px; width:100%;"  frameborder="0" scrolling="no"></iframe>
```

## MIT LICENSE

MIT License

Copyright (c) 2024 ZenCoder-art

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
