# RotateUI
原生改编jquery-gman-circle.js

[演示地址](http://www.wuweierwei.com/demo/RotateUI.html)

![](https://github.com/anderpang/RotateUI/blob/master/a.gif)

```js
new RotateUI({
    el:DOM,
    width:300,
    height:300,
    value:-Math.PI/2,
    slide:function(e,u){
        console.log(u);
    }
});
```
or

```js
var ui=new RotateUI({
  slide:function(e,u){
  }
});
document.appendChild(ui.dom);
```
