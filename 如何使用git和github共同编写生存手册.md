# 教程：git和GitHub



为了让对编程开发0基础的小伙伴们尽快上手使用github和git版本控制工具。在这里，我们使用一个情景故事教大家如何快速上手使用。

由于github.com有图形化界面，所以对于初学者来说，为了快速上手，可以暂时不学git命令行，只需要在github网站上用鼠标点击操作就行。



# 情景故事

小明写完了一篇论文，命名为”毕业论文.doc“，为了方便论文进行版本管理，小明注册了github账号，创建了一个Repositories。填写名字，然后点击最下面的Creat repositories。

![image-20221122153952010](https://github.com/sennkuwu/survival-manual/blob/main/image-20221122153952010.png)

然后github有个提示：
![image-20221122154312764](https://github.com/sennkuwu/survival-manual/blob/main/image-20221122154312764.png)



小明点击蓝色的uploading an exitsting file，上传了自己电脑中的”毕业论文.doc“文件。
![image-20221122154312764](https://github.com/sennkuwu/survival-manual/blob/main/image-20221122154618077.png)


点击Commit changes 就大功告成啦。自此，”毕业论文.doc“文件就托管在了github网站上，以后再也不用担心文件丢失和搞不清修改的内容问题了。



第二天，小明发现论文标题要修改。小明登录github项目，找到昨天上传的”毕业论文.doc“，点击图标进行下载。

下载完之后进行修改标题，修改完，登录github论文项目，和第一天一样上传文件即可。上传选项中有注释框，小明填写了”更改了标题“。

这样，每次修改都可以这样进行，这是最简单明了的方式。通过点击时间回溯功能，就可以查看每次的更改了。如图部分是时间回溯功能。
![image-20221122154312764](https://github.com/sennkuwu/survival-manual/blob/main/20221122160025.png)





第三天，小明的老师想给小明修改校对论文，小明的老师点击了右上角的Fork图标，意思是老师把小明的论文放到了自己github的空间里。然后点击main图标，创建了一个分支，名称为”by xiaoming's teacher“，如图所示：
![image-20221122161438297](https://github.com/sennkuwu/survival-manual/blob/main/image-20221122161438297.png)


这样，小明老师就在这个分支上修改小明的论文了。

修改完成之后，小明老师就在github上提交了，操作和小明第二天上传文件一样，并提交了修改注释。

但是这一步，小明老师只是把论文在自己的github空间上更新了，没有同步到小明github空间上，所以，还需要做的一个步骤就是：

在页面顶部选择 Pull request 标签，提交，点击Create pull request按钮，小明就可以看到修改了。

最后，小明使用Merge pull request按钮，就可以把老师的修改版变成自己的最新论文版本。



# 参考教程

git: https://guides.github.com/introduction/git-handbook/
GitHub: https://guides.github.com/activities/hello-world/

简易csdn教程：http://t.csdn.cn/kIaNr

希望新手在熟悉GitHub后尽快过渡到使用git命令行。





# 如何共同编写《生存手册》

有两种方法来共同参与我们的项目。

1. 按照以上教程，做小明的老师，给《生存手册》进行校对。

2. 在Issues选项中，找到《生存手册讨论或补充》，留下你的评论。你也可以创建新的Issues，提出新的问题。
![image-20221122163339329](https://github.com/sennkuwu/survival-manual/blob/main/image-20221122163339329.png)




有人留下建议或评论后，我会选择合理的条例，合并到正式的《生存手册》中。



各位开始提交自己的代码吧！0基础的新手也可以多测试GitHub的功能！
