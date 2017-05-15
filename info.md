### html

```haml
meta
```

### css 
html 和 body 必须要放 100% 的效果
```css
html, body {width:100%; height: 100%; overflow: hidden; }
.container {width: 100%; height: 100%; position: absolute; left :0; top:0; }
```

### js

使用 jQuery 的 animate 动画属性
```javascript

$(".container").animate({"top": nowpage * -100 + '%'}, 400);

```
