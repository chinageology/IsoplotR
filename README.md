# IsoplotR

**IsoplotR** 是一个自由的开源软件,用于同位素地球化学和地质年代学数据处理,由[Pieter Vermeesch](http://ucl.ac.uk/~ucfbpve)开发, 是对 Kenneth Ludwig 当年所开发的 Excel 插件 **Isoplot** 的替代品.  本项目包含有 IsoplotR 的核心命令. 图形界面版本在另外一个单独的项目中:
[https://github.com/pvermees/IsoplotRgui](https://github.com/pvermees/IsoplotRgui).

## 预先需求

你首先需要在电脑里安装好**R**(参考
[http://r-project.org](http://r-project.org)).  另外要想从 Github 来安装 IsoplotR, 你还需要安装 **devtools** 包.
在 R 命令行提示符下输入下面的命令就可以安装这个包:

```
install.packages('devtools')
```

## 安装

最新的稳定版的 IsoplotR 可以在 **CRAN** 中找到
[https://cran.r-project.org/package=IsoplotR](https://cran.r-project.org/package=IsoplotR),通过如下命令即可安装:

```
install.packages('IsoplotR')
```

另外还可以从 Github 来安装当前的开发版本:

```
library(devtools)
install_github('pvermees/IsoplotR')
```

## 更多信息

请访问 [http://isoplotr.london-geochron.com](http://ucl.ac.uk/~ucfbpve/isoplotr)

[Vermeesch, P., 2018, IsoplotR: a free and open toolbox for
geochronology. Geoscience Frontiers, v.9, p.1479-1493, doi:
10.1016/j.gsf.2018.04.001.](http://www.ucl.ac.uk/~ucfbpve/papers/VermeeschGSF2018/)

## 作者

[Pieter Vermeesch](http://ucl.ac.uk/~ucfbpve)

###### 中文翻译  [CycleUser](https://www.zhihu.com/people/cycleuser/columns)

## 授权协议

本项目使用 GPL-3 协议.
