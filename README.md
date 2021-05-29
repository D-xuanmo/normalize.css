# normalize.css CSS默认样式重置

## 安装
```bash
$ yarn add @xuanmo/normalize.css
```

## 使用
```scss
@import "@xuanmo/normalize.css";

// 引入公用 class
@import "@xuanmo/normalize.css/class.scss";

// 引入变量
@import "@xuanmo/normalize.css/var.scss";
```

## 替换默认变量
```scss
// 当默认的变量不满足情况时，可以使用以下方式替换
// 替换内外边距的生成尺寸
$--margin: (
  top: 5 10 15 20,
  right: 5 10 15 20,
  bottom: 5 10 15 20,
  left: 5 10 15 20
);
@import "@xuanmo/normalize.css/class.scss";
```
