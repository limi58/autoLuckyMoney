# autoLuckyMoney
2015双11天猫自动抢红包脚本（用计时器反复在指定 DOM 节点模拟点击）

# Usage
* 首先打开浏览器（非IE），点击下方的红包链接，可传送到红包页面。
* 然后按F12调出开发者工具（或ctrl + shift + i），然后在面板中的 console 选项卡中输入对应的脚本，然后回车。

# 红包链接及对应脚本

## [红包链接1](https://hbao.tmall.com/pc)
js脚本：
```js
(function(){
  var mbgf = setInterval(function(){
    document.getElementById('J_click_red_core').click()
    document.querySelector('[clk]').click()}, 500)
})()
```

## [红包链接2](https://www.tmall.com/wow/act/14700/huabei-hdc1111)
js脚本：
```js
(function(){
  var mbgf = setInterval(function(){
  document.getElementById('J_LotteryBTN').click()
  document.querySelector('.J_Close').click()}, 3000)
})()
```

# Help
* 有遇到其他红包页面可 PR 可 issues 提示更新 :)
* 刷新或关闭页面即失效
