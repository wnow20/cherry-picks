# cherry-picks
Git拉取某个分支的某段提交

现在有两个分支，分别为分支A、分支B。每个分支上都有若干次提交；
分支A的提交commits有 a1, a2, a3, a4, a5，一共有五次提交；
分支B的提交commits有 b1, b2, b3, b4, b5，一共有五次提交；
当前位于分支A。

注：以上10次提交的hash值不一样。

请问：怎么只拉取分支B的 b2, b3, b4 提交节点到 分支A？ 

答案：
```shell
$ cherry-picks B b2 b5
```
