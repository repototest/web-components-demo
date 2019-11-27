
## 说明

本文是在阮一峰老师的[Web Components 入门实例教程](http://www.ruanyifeng.com/blog/2019/08/web_components.html)基础上扩展而来，
想要了解Web Components的同学可以去看一下

本文主要针对阮老师没讲得slot、import、css进行补充



## slot
web components里的slot与vue中的slot类似，事实上vue是参考web components标准进行设计的

### 用法

在组建中用slot进行占位，name用于标识不同的slot，与引入时的slot的属性一一对应
没有设置name就表示默认的slot，用于存放没有组件内没有设置
```
<slot name="header"></slot>
```

引入时，

## import


## css


## 参考资料

* [w3c webcomponents](https://github.com/w3c/webcomponents)
* [Web Components 是个什么样的东西](https://juejin.im/post/57c40fd3128fe1005fd4629a)
* [Web Components 入门实例教程](http://www.ruanyifeng.com/blog/2019/08/web_components.html)
* [polymer](https://github.com/Polymer/polymer)