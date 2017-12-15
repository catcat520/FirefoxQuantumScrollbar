# FirefoxQuantumScrollbar

three ways to tweaks Firefox Quantum Scrollbar after version 57<br>
(火狐 57 之后的版本，有三种方法可以调整 滚动条)

i recommend to use the first way or the second way(我建议使用第一种或者第二种方法)

1.use windows origin regedit(原生接口注册表接口)


    Scroll Height/按钮高度 : HKEY_CURRENT_USER\Control Panel\Desktop\WindowMetrics\ScrollHeight
    Scroll Width/滚动条宽度 : HKEY_CURRENT_USER\Control Panel\Desktop\WindowMetrics\ScrollWidth
    Value Convert/转换数值 : ?px=-15*?px，example/例如 10px=15*10=-150， the system default is -260
     
you have to reboot or logout PC to make regedit work(请重启或注销电脑使注册表生效)

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/%E6%B3%A8%E5%86%8C%E8%A1%A8%E8%B0%83%E6%95%B4%E6%BB%9A%E5%8A%A8%E6%9D%A1.png>
<br>
2.use userChrome.css and stylus/xstyle/stylish<br>
(使用 userChrome.css 和 stylus/xstyle/stylish)<br><br>
put userChrome.css in a folder called "chrome" in your profile folder.<br>
(把 userChrome.css 放到配置文件目录 chrome)<br><br>
you could found chrome use about:profiles protocol on root dir(if not create it)<br>
(地址栏输入 about:profiles 可以打开根目录 找到 chrome，如果没有则创建它)<br><br>
like this(像这样)

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/userChrome.css.jpg>

and use stylus/xstyle/stylish load FixMargin.css(然后再用 FixMargin.css 进行微调)

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/stylus.jpg>

<br>
3.only use stylus/xstyle/stylish(只使用 stylus/xstyle/stylish)<br><br>
install styles https://userstyles.org/styles/149652/<br>
(安装样式 https://userstyles.org/styles/149652/)<br><br>
thie way can use on Microsoft Edge too(这种方法也可用在 Edge 上)<br><br>
i don't recommend this way(我不推荐使用这种方法)<br><br>
Result(效果演示)

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/result.jpg>


