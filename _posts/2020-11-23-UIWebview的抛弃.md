---
layout: post
title: 放弃UIwebview的理由
featured-img: shane-rounce-205187
---
# 关于UIwebview的放弃，从今年开始苹果已经完全禁止代码里用到UIWebview了，因此用一下方法可检测项目里用到webview的文件


1.打开终端，cd + 把项目的工程文件所在文件夹拖入终端（即 得到项目的工程文件所在的路径）

2.输入以下命令（注意最后有个点号，而且点号和 UIWebView 之间必须有一个空格）：

grep -r UIWebView .

3.以上操作都正确的话，会马上出现工程中带有 UIWebView 的文件的列表（包括在工程中无法搜索到的 .a 文件中对UIWebView 的引用）

注：引用AFNetWorking可以直接把AFNetWorking 里面的 UIWebView+AFNetworking 扩展删掉就可以了，没影响的

###  




