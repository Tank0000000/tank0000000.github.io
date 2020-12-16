---
layout: post
title:  "AFL改进方法"
date:   2020-12-16 19:31:29 +0900
---
AFL针对含有源码的漏洞挖掘测试

{% highlight ruby %}
./configure CC="afl-gcc" CXX="afl-g++"//指定编译选项
make clean //清除编译记录
make -j4 //进行编译
{% endhighlight %}

