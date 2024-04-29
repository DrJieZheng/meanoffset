A fast photometric image alignment algorithm with row and column means 

By Dr Jie Zheng, Dr Lin-Qiao Jiang, and Dr Jian-Feng Tian

### Publication

+ ADS:2024NewA..11002224Z
+ arxiv:2404.09912
+ doi:10.1016/j.newast.2024.102224

### Installation

`pip3 install qmatch`

### Usage

```py
import qmatch
# prepare the x,y means of the images
mxa, mya = qmatch.mean_xy(imga)
mxb, myb = qmatch.mean_xy(imgb)
# find the offset of x,y
dxab = qmatch.mean_offset1d(mxa, mxb)
dyab = qmatch.mean_offset1d(mya, myb)
```
