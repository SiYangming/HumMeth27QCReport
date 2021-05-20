# HumMeth27QCReport
重新整理DESCRIPTION，以便能在最新的R上安装运行。

https://cran.r-project.org/src/contrib/Archive/HumMeth27QCReport/

## 安装依赖包

```R
BiocManager::install(c("",""))
install.packages(c("amap", "tcltk2"))
BiocManager::install(c("IlluminaHumanMethylation27k.db","FDb.InfiniumMethylation.hg18","FDb.InfiniumMethylation.hg19"))
```
## 安装HumMeth27QCReport

### 安装源码包

```R
install.packages("path/to/HumMeth27QCReport_1.2.14.tar.gz", repos = NULL, type = "source")
```

### 安装Windows二进制包

```R
install.packages("path/to/HumMeth27QCReport_1.2.15.zip", repos = NULL, type = "win.binary")
```
