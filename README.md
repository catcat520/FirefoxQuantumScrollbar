# FirefoxQuantumScrollbar

three ways to tweaks Firefox Quantum Scrollbar after version 57<br>
火狐 57 之后的版本，有三种方法可以调整 滚动条

1.windows origin/原生接口


    ScrollHeight/按钮高度 : HKEY_CURRENT_USER\Control Panel\Desktop\WindowMetrics\ScrollHeight
    ScrollWidth/滚动条宽度 : HKEY_CURRENT_USER\Control Panel\Desktop\WindowMetrics\ScrollWidth
    value convert/转换数值 : ?px=-15*?px，example/例如 10px=15*10=-150

put userChrome.css in a folder called "chrome" in your profile folder.

like this

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/userChrome.css.jpg>

and use stylus/stylish/xstyle load FixMargin.css

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/stylus.jpg>

Result

<img src=https://raw.githubusercontent.com/catcat520/FirefoxQuantumScrollbar/master/img/result.jpg>
