
## # scss 语法

**变量**
```scss
// $变量名:变量值
$primary-color: green;
```

**模块化**
```scss
// 模块文件名
_base.scss; 

// 主文件引入模块
@use 'base'; 
```

**混合**
```scss
// 定义函数体（默认变量参数 $theme）
@mixin theme($theme: DarkGray) { 
  background: $theme;
}

// 混入函数体
@include theme;
@include theme($theme: DardRed);
```

**继承**
```scss
// 定义复用样式
%message-shared { ... }

// 使用复用样式
@extend %message-shared;
```

**操作符**
```scss
// 操作符
+、-、*、math.div()、%

// 除法运算
math.div(300px, 960px) * 100% --> 31.25%
```

