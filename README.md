# Js-magnifying_glass
:hushed: Js模拟放大镜
##### 利用原生JS写的放大镜
###### 截图
<img src="magnifying_glass\example.png" />
###### 主要代码
```Js
移动的比例  把X值和Y值换算成比例;
var proportionX = left / (oS_box.offsetWidth - oS_position.offsetWidth);
var proportionY = top / (oS_box.offsetHeight - oS_position.offsetHeight);
利用比例去算出大小不同的元素的偏移距离
oB_box_all.style.left = -proportionX * (oB_box_all.offsetWidth - oB_box.offsetWidth) + "px";
oB_box_all.style.top = -proportionY * (oB_box_all.offsetHeight - oB_box.offsetHeight) + "px";
```
