##Speed up

* 如果在用Shadowsocks的话可以给Android studio也加上proxy来加快Gradle的下载，在preference里面修改http Proxy方式为socks并且设置ip：127.0.0.1， 端口1080，也就是用本机来代理。
* 用Gradle下载一些新的库时候，如果觉得慢你可以建立另外一个project， 在另外一个project来下载maven库，下载好了开启offline模式一键同步另外工程下好的库，再也不用浪费时间在等库下载了。
* 在写企业项目适合尽量每个文件名加上企业缩写前缀，用Android studio为每个Java文件加上头标注。
* 用ButterKnife和ButterKnife Zelezny搭配起来让你写完布局时候快速生成View的Java代码。
* 抽象类BaseActivity和BaseFragment等，尽量省去onCreate（）等方法，能减少很多多余的代码。
* 打Log的时候可以直接用logd + logt来快速实现，在自己不太确定的时候得先打开log，当然也可以自己规范Logger类。
* 合理利用Gradle的动态任务来做一些事情，能加速很多操作，比如说生成临时的变量等。
