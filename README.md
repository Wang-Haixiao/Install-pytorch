# Install-pytorch

# 1 安装CUDA
教程：https://zhuanlan.zhihu.com/p/94220564?utm_source=wechat_session

查看CUDA版本：命令行输入`nvcc --version`

# 2 安装pytorch

## 1 在pytorch官网寻找对应版本下载链接
网址：https://pytorch.org/get-started/locally/
![](/IMG/1.jpg)
（使用pip）

## 2 在命令后跟随镜像设置
`-i https://pypi.tuna.tsinghua.edu.cn/simple some-package`（清华源，已挂）

豆瓣(douban) `http://pypi.douban.com/simple/`

清华大学 `https://pypi.tuna.tsinghua.edu.cn/simple/`

阿里云 `http://mirrors.aliyun.com/pypi/simple/`

中国科学技术大学 `https://pypi.mirrors.ustc.edu.cn/simple/`

## 3 命令行输入命令运行即可
如果仅需要下载对应的包，在控制台运行上述命令后，复制其显示的下载链接即可

# 3 查看pytorch版本
命令行输入
`python -c "import torch; print(torch.__version__)"`
