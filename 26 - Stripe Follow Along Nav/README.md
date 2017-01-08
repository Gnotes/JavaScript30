隐藏显示型导航菜单

<img src="./01.gif" width="400">

**原理** 子菜单或选项初始化隐藏`display: none` ，通过判断鼠标进入事件`mouseenter` 动态改变样式`dispaly:block` 并设置透明`opacity` 和过渡`transition`,在鼠标离开时`mouseleave` 还原