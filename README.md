TimeLine example
================

## libs

- [jQuery](https://jquery.com/) : v1.6.1
- [jQuery Masonry](https://masonry.desandro.com) : v2.0.110901

## ChangeLog

- 2019-01-08 创建项目

## 创建过程

### step.1 创建项目

- 创建基本目录结构

``` bash
mkdir -p timeline-example/{libs/{jquery,masonry},src/{css,js,images},example}
```

项目目录树如下:

```
.
└── timeline-example
    ├── libs
    │   ├── jquery
    │   └── masonry
    └── src
        ├── css
        ├── images
        └── js
cd timeline-example
```

- 使用 WebStorm 打开项目文件夹，创建 `.gitignore` 与 `README.md` 文件

### step.1 下载引用的 js 库与资源

``` bash
cd libs/jquery
wget https://code.jquery.com/jquery-1.6.1.js
wget https://code.jquery.com/jquery-1.6.1.min.js
cd -

wget https://demos.9lessons.info/timeline/jquery.masonry.min.js \
- O libs/masonry/jquery.masonry.min.js

mkdir -p src/images
cd src/images
wget https://demos.9lessons.info/timeline/images/left.png
wget https://demos.9lessons.info/timeline/images/left.png
wget https://demos.9lessons.info/timeline/images/left.png
cd -
```

## 参考文档

- [Srinivas Tamada](http://www.9lessons.info/). [9lessons.info](https://www.9lessons.info/). [Facebook Timeline Design using JQuery and CSS.](https://www.9lessons.info/2012/01/facebook-timeline-design-using-jquery.html) 2012-01-30. [2019-01-08].
- [大漠](https://www.w3cplus.com/blogs/airen). [w3cplus](https://www.w3cplus.com). [jQuery制作Facebook Timeline](https://www.w3cplus.com/jquery/facebook-timeline-design-using-jquery). 2012-03-20. [2019-01-08].
