# Donate-Page

在[Kaiyuan Xie](https://github.com/Kaiyuan)的[捐赠按钮样式](https://github.com/Kaiyuan/donate-page)基础上，考虑到天朝国情，使用PayPal的人相对不是那么多，而且直接通过二维码支付BitCoin(比特币)的方式也不太现实，所以去除了这两项捐赠条目，只保留支付宝和微信。效果如下：
![donate-page](https://raw.githubusercontent.com/DonQvixote/donate-page/master/donate-page.gif)

#### Fork 之后需要修改以下内容

* 在images/下替换成你自己的AliPayQR和WeChatQR

#### 使用 `iframe` 嵌入页面的代码，高度至少 `200px`，宽度至少 `350px`！

```
<iframe src="/donate-page" style="overflow-x: hidden; overflow-y: hidden; border: 0xp none #fff; min-height: 200px; min-width: 350px;" frameborder="0" scrolling="no"></iframe>
```
### License

Released under the MIT license.


