# by
* 这是为本次冰岩招新创建的仓库
* 其中每日总结文件夹中放置着每日的总结文档

### 3.9

* 晚上选好题后非常激动,爆肝到11:30.完成了首页nav和下面主界面除了轮播图的制作.除此之外还在网上查了一下`js`的相关知识,应该几天后可以实现动效.布局上,查了一些教程,发现用一个版心可以很好的控制网页等宽,这个技巧真的很好用
* 被浮动的高度坍塌折磨了很久,查了很多资料后才算用伪元素选择器消除了浮动影响,这个脱标是真的坑爹.
* 发现一个小软件`snipaste`可以量图片的长宽,还可以看颜色,这个真的好用,感觉自己还原度还是挺高的.

### 3.10 

* 下午时间比较充足,主要用在了学习上,`js`的各种写法真的神奇,尤其是定时器实现动画.而在学习中也总算解决了`hover`只能选择父盒子的问题,还有利用昨天晚上看的动画教程,利用`transform`完成了三角形的旋转功能,两者一结合,实现了,放上去转向的效果,但如果想要保持,可能还要再用js
* 学习了`flex`布局的使用,明天可以试试加在页面里
* 还有就是解决了给三角形添加阴影后导致整个正方形都有阴影的问题,通过添加旋转的方式
* 晚上 完成了对下拉栏的制作,之后应该可以用学会的js实现下拉效果了.

### 3.11

* 上午8:00-9:30 没有课,就对主要界面进行了一下优化
* 下午3:30-5:30 两天假期开始,进行了最后一部分排行的制作的一半,中间第一次尝试了`flex`感觉是真的好用,要是早点在前面的开发中用上,那可以省很多功夫,而且适配性也会更好,很可惜
* 晚上6:30-11:30 主要是做了一个侧边栏和学习js,侧边栏一开始打算用图片,但发现还有变色效果,最后还是找了半天的`iconfont`找了几个相似的,不然通过js切换图片变色太麻烦了.经过前几天的准备,总算是对移动动画有了一定的把握,而且在学习中发现了无缝切换的做法,真的奇妙,添加一张新图片简直就是天才!虽然原版的可以通过改变透明度实现,但总感觉差点味道,还是选择了无缝滚动(顺便一说,原版居然不能点小按钮切换,难以理解).而其他的几个转换模块也是大同小异的

### 3.12

* 说真的,我到现在才看到文档中讲实习笔记的写法(真的我哭死).我就只能按照今天的进度开始补了,之前的我只能凭借记忆补上了.
* 8:15-9:30 虽然昨天熬夜了,但是写了一半的程序让我感觉**很不爽**,所以起床写一下昨天的网站.首先利用css实现了课程的下拉栏,利用`transition`实现`main-left`的下拉栏.
* 9:30-11:30 这个时间写了一下登录栏,同时发现侧边栏忘记放上二维码了,就补充了一下.然后关键地方来了,我本来以为底部那个切换栏实现很简单,后来发现加上了隐藏后问题很大,改了好久才弄好
* 11:30-2:30 吃完中饭趟床上摆烂
* 2:30 -5:00 完成了利用localstorage实现的注册功能
* 5:00-8:30 部门开会加聚餐
* 9:00 -11:30 完成了界面中的登录部分,用了一些`alert`感觉有点`low`,如果有时间的话,希望可以改一下,改成提示性的样式.除此之外,还制作了搜索栏,用了添加节点的方式,完成了提示栏.

* 总结:到目前为止,`level1`也完成了!进度远远超出了我的预期,也就是说明天我可以去攀登我从未涉及过的后端领域,作为一个只会把nginx里面,`index.html`改成自己的网页,再用公共ip访问的人来说,这是一个很艰巨的事情,而且明天下午我也需要去图书馆自习,因为自己这星期忙于网页开发,课程有些拉下了,所以只能明天早起,在周一到周四努力挤时间出来,但无论如何,我已经在这些过程中,超越了自己原先设想的上限了,无论结果如何,我相信这一次春招一定会是我大学里一份难忘的记忆!

### 3.13

* 9:00-11:00 调试了一上午,终于用nodejs发送出了第一个数据,虽然进度拉下很多了,但至少是一个好的开始,下午继续学习,争取到晚上把登录注册部署到云端

* 3:00-4:00 在网上漫无目的的搜索了半天,什么都没搞懂,最后沉下心来找一个b站教程从头开始看,总算是利用express框架和ajax传输了我的第一个数据,说真的,进度非常慢,但是至少比没有强,可能今晚要熬夜了(悲)
* ![1647159833839](C:\Users\fanzhijie\AppData\Roaming\Typora\typora-user-images\1647159833839.png)放一张图片记录一下这个激动人心的瞬间

* 5:00-9:40 漫长的补作业和学习时间
* 9:50 -11:00 经过漫长的摸索,总算实现在服务器云端设置数据然后,通过ajax进行get请求,总算是实现了,登录的效果,但是数据仍然只是通过数组而不是数据库储存的,明天打算利用数据库实现登录和注册功能.但不管怎么说,我总算是迈出了第一步了.不说了,脸还没洗呢.

### 3.14

* 上午漫长的课程,还是重要的微积分和电路理论,不得不认真听
* 12:20-12:40 根据教程实现了nodejs对url的解析,这样就可以利用ajax传输数据到服务器了,接下来只要学习数据库的使用,就可以实现登录注册效果了!!!
* 2:00-4:30 军理课摸鱼做完了作业,今晚就不去自习开发一整晚吧!难受的是我的机械键盘好像在我之前几天的高强度摧残下寄了,唉.

* 6:00-9:30 在重装5次系统,百度不下30次后,我终于!终于!终于!实现了利用服务器登录的功能!!!!!!在这三个小时里,我简直是受尽了折磨.一开始想用`mongodb`来写后端注册,但是服务器的`yum`里没有`mongodb`

  在查了一个小时多的教程后,我终于还是放弃了.改用`mysql`数据库了,然后又经历了漫长的配置后总算是可以用了.然后又花了一个小时学了怎么用`mysql`然后又看了很多`ajax`和`nodejs`教程(b站,菜鸟教程,w3school,csdn,个人博客),搞明白了怎么处理.其中如何判断对象是空对象用JSON方法是真的没想到.

* (换个行慢慢说),然后总算开始在服务器端写代码了,但这个`vim`简直是一言难尽,反人类的没有代码自动提示功能(没有说这个大佬专用编辑器不好的意思),只能现在`vscode`里写好代码,再放到服务器端里,没有光标的操作方式也很难接受(键盘的按键太多了记不住).不过很意外的是代码基本上不需要调试就`ac`了算是最好的一件事吧.

* 总之到现在位置,我完成了对登录注册功能的云端部署.本来还想实现一下实现真实搜索的功能,但看了一下发现发的是`post`请求,感觉有点难搞(就学了个`get`请求)打算先退而求其次,在自己服务器里实现这个搜索提示功能吧.