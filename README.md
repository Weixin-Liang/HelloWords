# HelloWords 单词记忆APP功能展示及使用手册
---
    
HelloWords是一个基于Django开发的在线背单词网站，我们都知道，几乎每一门编程语言的第一个程序都是向世界问好——hello，world！英语也不例外，要想学好英语，积累词汇量，那就从HelloWords开始吧！

## HelloWords功能概述
HelloWords主要为广大英语学习爱好者提供了五大主要功能：
    
    1. 单词学习及打卡
    2. 单词类别选择
    3. 查看单词例句及同义词
    4. 创建学习笔记、查看个人笔记及他人共享笔记
    5. 设置每日单词学习量

## HelloWords各部分功能描述及使用
### 1.单词学习及打卡
##### 1.单词学习
HelloWords为用户提供了简约的单词测试界面，通过选择你所认为的正确选项进行记忆单词，每个单词有一个正确释义，另外三个为错误选项。当使用者选择了单词正确释义时，该选项会标绿以示正确，同时右上角绿色勾图标的计数加1，表示当前选对数目；当使用者选择了错误释义时，该选项会标红以示错误，同时正确选项会标绿以示为正确答案，供学习者学习新词汇，右上角红叉图标的计数加1，表示当前选错数目。下方进度条会标识出当前单词学习进度。

这是正确选择效果图：
![这是正确选择效果图](http://i.imgur.com/ENXPPOY.png)
这是错误选择效果图：
![这是错误选择效果图](http://i.imgur.com/DAoQDvS.png)

##### 2.打卡
使用者结束当前单词学习后，可以点击“**打卡**”保存当前学习进度，下一次在该进度上继续学习，点击打卡后“**打卡**”后界面会给出简单学习统计提示。

这是打卡效果图：
![这是打卡效果图](http://i.imgur.com/9opb5bk.png)

### 2.单词类别选择
HelloWords目前为广大英语学习爱好者提供四类（主要针对英语考试学习）词汇，分别是四级、六级、托福及雅思，以供测试。单击导航栏中不同的类别可以选择不同的词汇进行学习。

比如，选择四级：
![这是四级效果图](http://i.imgur.com/BRp6Rif.png)
或者，选择六级：
![这是六级效果图](http://i.imgur.com/VI61zUz.png)

### 3.查看单词例句及同义词
HelloWords在使用者学习单词过程中提供了展示单词使用例句及同义词汇功能，使用者在界面上点击“**词汇详解**”按钮，即可展开该单词的使用例句及同义词汇（注：目前系统中所导入数据为测试数据）。
![这是同义词例句效果图](http://i.imgur.com/nZjqQgr.png)

### 4.创建学习笔记、查看个人笔记及他人共享笔记
HelloWords为使用者提供了灵活的笔记功能。使用者可以在学习过程中，添加词汇笔记，也可以查看自己总结的笔记，甚至可以看到他人共享的关于当前学习的那个词汇的笔记。

##### 1.创建个人笔记
点开HelloWords学习界面左上角展开按钮，可以看到“**我的学习笔记**”界面，界面默认展示“**添加笔记**”内容，如果选择了其他项，也可以点击“**添加笔记**”导航回到该界面，在该界面录入归纳笔记的词汇及笔记内容，并且可选择是否共享笔记，如果选择共享笔记，那么其他使用者在学习该词汇时可以通过“**共享笔记**”界面查看到分享的笔记。
![这是添加笔记效果图](http://i.imgur.com/isXlQ7G.png)

##### 2.查看个人笔记
点击“**我的笔记**”，可以看到使用者以往总结的所有词汇笔记，通过下拉框选择所要查看词汇，在下方笔记展示框里可以看到所选单词的笔记内容。
![这是我的笔记效果图](http://i.imgur.com/rAEwB5B.png)

##### 3.查看共享笔记
点开“**共享笔记**”，可以查看到他人对当前所学单词的共享笔记。同时，使用者在创建笔记时，选中“**是否共享笔记**”，也可以将自己的笔记共享以供他人学习查看，共享笔记以列表与滚动条的形式展示了所有该词汇的共享笔记以及笔记作者。
![这是共享笔记效果图](http://i.imgur.com/BuyNOxo.png)

### 5.设置每日单词学习量
点击右上角“**用户图标**”下拉按钮，选择“**学习设置**”，可以跳转到每日单词学习量设置页面，使用者设置该参数后，系统会根据上次使用者背单词的记录以及用户的设置，返回当次使用者所选类别当前所应学习量。
![](http://i.imgur.com/uRlB0Cz.png)
![](http://i.imgur.com/SZ8ldw7.png)

### 用户相关
用户在未登陆情况下，无法使用HelloWords的单词学习功能，系统会禁用部分功能，比如“**词汇扩展**”、点击下一个单词等，并提示用户登陆。
![](http://i.imgur.com/JZXsT3y.png)
用户点开界面右上角“**用户图标**”，选择“**登陆**”，可以返回到登录界面进行登陆（如果已登录该按钮会变为“**退出**”）。
![](http://i.imgur.com/uheRDWl.png)
用户登陆成功后，会返回之前的学习界面，此时右上角会有“**欢迎您，XX**”登陆成功的标语提示。
![](http://i.imgur.com/fiiiHE8.png)
如果当前没有注册HelloWords账号，可从登录界面跳转到注册界面进行账号注册，注册成功后会有成功提醒。
![](http://i.imgur.com/iGnneLp.png)

### 结语：欢迎大家使用HelloWords，祝大家学习愉快，谢谢！
