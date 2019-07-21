# condarc

### A config to change conda channel to mirrors.tuna.tsinghua.edu.cn

Many online tutorials tell us changing `channels` or `channel_alias`.

But this is not a good practice, because `mirrors.tuna.tsinghua.edu.cn` does not mirror all the channels of `conda.anaconda.org`.
A better way to improve compatibility is to change `default_channels` and set `custom_channels`.


---

#### Chinese translation
### 设置mirrors.tuna.tsinghua.edu.cn作为conda的channel

网上很多教程都是说改`channels`或者`channel_alias`。
但这样做并不是很好，因为`mirrors.tuna.tsinghua.edu.cn`并没有镜像`conda.anaconda.org`的全部的channel。
兼容性比较好的做法是改`default_channels`和设置`custom_channels`。

针对使用Windows的同学，如果anaconda安装时候选择了单独用户，替换文件的路径应该是(直接贴在资源管理器的地址栏打开): `%userprofile%\.condarc`

