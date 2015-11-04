# autoLuckyMoney
2015双11天猫自动抢红包脚本

# Usage
> 首先打开浏览器（非IE），然后按F12调出开发者工具（或ctrl + shift + i），然后在面板中的 console 选项卡中输入脚本，然后回车。有更新可 PR 可 issues

# [红包链接1](https://hbao.tmall.com/pc)
```js
(function(){var mbgf = setInterval(function(){document.getElementById('J_click_red_core').click();document.querySelector('[clk]').click()}, 500)})()
```

# [红包链接2](https://www.tmall.com/wow/act/14700/huabei-hdc1111)
```js
(function(){var mbgf = setInterval(function(){document.getElementById('J_LotteryBTN').click();document.querySelector('.J_Close').click()}, 3000)})()
```