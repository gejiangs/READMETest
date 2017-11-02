大标题
===
小标题
------
aa<br>bb
[baidu](http://www.baidu.com '这是baidu')
![](http://upload.jianshu.io/users/upload_avatars/1767337/d6598cf01cbc.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/300/h/300)
#一级标题
##二级标题

普通文本
换行<br>这里是下一行
不转义换行\\\<br>

文字`高亮`
* 姓名：xxx
* 年龄：xxx
    * 二级圆点
        * 三级圆点

>数据结果
>>2级树
>>>3级树
>>>>4
>>>>>5

        aaaa
        bbbb
        cccc
```c
-(id)init
{
    if (self = [super init]) {
        self.connectedArray = [NSMutableArray array];
        self.manager = [[CBCentralManager alloc] initWithDelegate:self queue:nil];
        self.manager2 = [[CBCentralManager alloc] initWithDelegate:self queue:nil];
        self.state = ConnectStateNone;
    }
    return self;
}
```

*斜体*
**粗体**
***斜粗体***
__粗体2__
___斜粗体2___
~~删除线~~


