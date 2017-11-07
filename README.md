# FirefoxQuantumScrollbar

three ways to tweaks Firefox Quantum Scrollbar after version 57<br>
火狐 57 之后的版本，有三种方法可以调整 滚动条

i recommend to use first way or second way

1.use windows origin regedit/原生接口注册表接口


    Scroll Height/按钮高度 : HKEY_CURRENT_USER\Control Panel\Desktop\WindowMetrics\ScrollHeight
    Scroll Width/滚动条宽度 : HKEY_CURRENT_USER\Control Panel\Desktop\WindowMetrics\ScrollWidth
    Value Convert/转换数值 : ?px=-15*?px，example/例如 10px=15*10=-150
    
<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/%E6%B3%A8%E5%86%8C%E8%A1%A8%E8%B0%83%E6%95%B4%E6%BB%9A%E5%8A%A8%E6%9D%A1.png>
<br>
2.use userChrome.css and stylus/xstyle/stylish
<br>
put userChrome.css in a folder called "chrome" in your profile folder.

like this

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/userChrome.css.jpg>

and use stylus/xstyle/stylish load FixMargin.css

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/stylus.jpg>

<br>
3.only use stylus/xstyle/stylish
<br>
install styles https://userstyles.org/styles/149652/

Result

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/result.jpg>


