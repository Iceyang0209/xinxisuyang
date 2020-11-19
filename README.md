# xinxisuyang
4-张天洋   2020012233
# 我对信息素养实践课程的认识
## 简单介绍
&emsp;  ** 《信息素养实践》** 课程作为软件工程专业的入门课程，任务是使学生掌握计算机的基本使用以及常见应用软件的使用，* 属于专业必修课。 *

## 成绩评定
&emsp;  为了确保教学质量、公平有效的评价学生的学习效果，该课程采用的过程化考核方案为：** 雪梨（平台）作业占55%，平时成绩占15%，期末考核占30%。 **

## 主要课程
### 常见DOS命令的使用
Backspace   向前删
Delete       向后删
D:\>    根目录（D盘打开表面的文件夹
盘符   光标  目录
md      创建目录（文件夹）
cd       能进入该盘下的目录
cd..      回到上一级目录
cd\       回到根目录
dir       检索显示目录
dir /p     一页一页检索
dir /o     有规律排序显示    后面+ :n  是按名称
                                + :s   是按大小排序
                                + :d   是按修改日期
                                + :e   是按后缀名  如 .doc   .pdf  .exe
.exe     可执行命令
.bat     放的成型的doc命令
rd       删掉空目录
del      删掉文件
上下键  可以找之前打开的文件
copy + con  创建文件
Ctrl+c   完成文件创建
copy        复制文件
attrib        检索文件
cls         清屏
ren         重命名(必须把名字写全，加上后缀)
### markdown文档
- 超链接  [百度](https://www.baidu.com)
- 代码段
```
sum=0
for i in range(1,11)
    sum=sum+i
    print(sum)
```
- 代码块   `[ ]`
- 表格
|章节|名称|
| :-: | :- | -: | :-: |
|第一章|常见DOS命令的使用|
|第二章|markdown文档|
|第三章|Github的使用及命令|
|第四章|思维导图|
|第五章|word应用技巧|
|第六章|word应用技巧|

### Github的使用及命令
cd  进入目录              
mkdir  创建目录    
copy  复制  
显示当前的 Git 配置
git config --list
设置提交仓库时的用户名信息
Git  config  --global  user.name  "YangWeiBin" 
设置提交仓库时的邮箱信息
git  config  --global  user.email   "863255386@qq.com"
* 新建代码仓库
在当前目录新建一个 Git 代码库
git init
下载一个项目和它的整个代码历史
 url 格式: https://github.com/[userName]/reposName
git clone [url]
- 添加与提交文件
添加指定文件到暂存区
git add [file1] [file2]
提交暂存区到仓库
git commit –m [message]
 直接从工作区提交到仓库
 前提该文件已经有仓库中的历史版本
git commit –a –m [message]
+ 删除和重命名
 改名文件，并且将这个改名放入暂存区
git mv [file-origin] [file-renamed]
删除工作区文件，并且将这次删除放入暂存区
git rm [file1][file2]

### 思维导图的使用
+ 主题插入
+ 备注插入
+ 图片，图标
+ 超链接
+ 任务信息 
### word应用技巧
### excel应用技巧
