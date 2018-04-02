# yo-CSS

## 目录

1. [编码指导（规范）](#编码指导（规范）)
2. [练习册](#练习册)
3. [不错的网站](#不错的网站)
4. [工具](#工具)
    - [常用代码](#code-snippet)
    - [在线工具](#online-tool)

## 1. 编码指导（规范）

1. [Airbnb CSS / Sass编码规范](https://github.com/NoName4Me/yo-CSS/issues/1)

## 2. 练习册

1. [100 Days CSS Challenge](https://codepen.io/collection/XgmakG/)

## 3. 不错的网站

1. [CSS tricks](https://css-tricks.com/)

CSS的各种常规的、神奇的操作。

## 4. 工具

<a id="code-snippet" href="#code-snippet">

### 4.1 常用代码

* 随机颜色

```scss
// hsl
$s-min: 0;
$s-max: 100;
$l-min: 30;
$l-max: 60;

@for $i from 1 through 20 {
    #dot-#{$i} {
        background-color: hsl(random(360),$s-min+random($s-max+-$s-min),$l-min+random($l-max+-$l-min));
    }
}
```

<a id="online-tool" href="#online-tool">

### 4.2在线工具

1. [CSS triggers](https://csstriggers.com/)

在特定的浏览器内核下，一个CSS属性的改变是否会引起*Layout*、*Paint*、*Composite*。

2. [Can I Use](https://caniuse.com/)

查看JS、CSS、HTML等的浏览器兼容状况。