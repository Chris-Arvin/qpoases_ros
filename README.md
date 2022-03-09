# qpoases_ros
A completement of qpoases_ros: 对qpoases(https://github.com/SemRoCo/qpOASES)这个c++下的二次优化的包的安装和使用进行详细说明。
## Installation
把本git中的qpoases这个pkg直接下载下来，正常编译即可

## Include
新建你进行功能实现的功能包，按照https://blog.csdn.net/qq_34935373/article/details/97374396 修改cmakelist.txt和package.xml（把博客中所有的msgfile改成qpoases）
在cpp文件中，只需
```
#include<qpoases/qpoases.hpp>
```

## Implementation
参照https://projects.coin-or.org/qpOASES 中的example来实现自己的算法即可
