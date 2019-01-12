---

layout:     post                    # 使用的布局（不需要改） 

title:      HCTF总结反思               # 标题  

subtitle:    #副标题 

date:       2018-11-11              # 时间 

author:     xyeee                      # 作者 

header-img: img/post-bg-universe.jpg    #这篇文章标题背景图片 

catalog: true                       # 是否归档 

tags:                               #标签     

- ctf

---
# HCTF总结反思

​	

​	过了将近两周之后，准备柏鹭杯比赛的时候才真正的静下来，反思最近的两场比赛，让自己在柏鹭杯中能吸取这两次比赛中心态上或者是知识上的经验与教训。

​	在HCTF比赛中，48个小时，我大概有30小时在思考比赛的题目，而结果也没有令我失望，做出参赛以来做多的题目，在web和crypto中都有收获。

​	warmup这道题是一开始看到不少人做出来了，赌气一定要做出来，也是看过源码之后，发现有地方过滤decode，就想到了二次编码，之后不断地试试试试，终于找到文件目录

payload

```
http://warmup.2018.hctf.io/index.php?file=hint.php%253f/../../../../ffffllllaaaagggg
```

![warmup.png](https://i.loli.net/2018/11/21/5bf4f7448a8c8.png)

​	ok，再说一道crypto，这道题整整让我思考了24小时，有点坑，后来主办方又加上了一道sha256的爆破（是觉得做出来的人有点多吗），我特别欣慰的是，我坚持了下来，我在比赛结束前的两个小时成功地拿到了flag，自信心与毅力耐心都有极大的提升

![QQ截图20181111185243.png](https://i.loli.net/2018/11/21/5bf4f744d6378.png)

​	就这些吧，我觉得HCTF真的给了我很多心态上的提升，让我不会轻易放弃暂时没做出来的题目，柏鹭杯加油。