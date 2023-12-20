# 目录架构说明
* pkebook.tex是书的封面及目录文件, 包含指向各章节的入口
* elegantbook.cls是本书使用的ElegantBook模板的样式文件
* mybooksetting-cn.tex是样式文件, 包含了需要包含的头文件和一些命令的缩写, 可以根据需要编辑
* mycrypto.bib是参考文献文件, 在添加之前可以查查是否已有, 条目命名格式是姓氏首字母缩写+发表期刊会议+年份
* figure: 存放所有插图的文件夹

- 如果本地编译不成功或者字体显示有问题, 需要对以下命令进行修改, 在本地安装相应字体
\setCJKmainfont{STSongti-SC-Regular}

# 云端与本地的同步
* 首次: 在本地某处运行以下命令克隆项目到本地

``` 
   git clone https://github.com/yuchen1024/pkebook.git
```
* 本地可以修改编辑, 完成后执行以下命令将本地修改同步至远程库

```
   git add .
   git commit -m "brief summary of your modification"
   git push -u origin main
```

* 下次再进行本地更新之前, 一定先去执行以下命令拉取远程库的最新内容(合作者可能又更新了)

```
   git pull
```

