# pixiv-

p站小虫子~

---


A simple Pixiv Spider

It can download picture of your book mark member on your account

set your account at the bottom of the code

```
Pixiv_Scrapy(Pixiv_Login('ACCOUNT','PASSWORD').get_cookie()).get_users()
```

run this 

```
python pixiv_scrapy.py
```

Then It Run like This


![finder](https://github.com/moriW/moriWorkFlow/blob/master/donwonloading@2x.png?raw=true)


![finder](https://github.com/moriW/moriWorkFlow/blob/master/how%20it%20look%20like.png?raw=true)

dependency:

1. lxml
2. requests
3. python 2.7.10

It is multi

PS:
It couldn't work via python 3 , lxml have a encoder error. [reason](https://github.com/lorien/grab/issues/199)


PPS:
It didn't work well , if you network is bad /(ㄒoㄒ)/ , it almost 3 picture / s 

PPPS: if you have a proxy , and you want use it on this spider , you gonna need those command (Mac/Linux)


```
pip install requests[socks] 
//this make your requests use socks5
```

```
export all_proxy=socks5://127.0.0.1:1080
//this make your proxy at socks5://127.0.0.1:1080
```

I still got some problem tha didn't solve

if you wanna help , [moridisa@moridisa.cn](mailto:moridisa@moridisa.cn)

---

一个P站虫子的简单实现

通过Pixiv账户，下载你全部的关注的用户的图片

在代码底部设置账户

```
Pixiv_Scrapy(Pixiv_Login('账户','密码').get_cookie()).get_users()
```

运行

```
python pixiv_scrapy.py
```

需要:

1. lxml
2. requests
3. python 2.7.10

PS: 在python3 中，lxml会编码错误 [原因](https://github.com/lorien/grab/issues/199)

PPS: 如果网络不是很好的情况下，可能会有问题，我这里差不多 一秒三张图

PPPS: 如果你用了网络代理，想在这个python中使用代理 ，使用一下两条指令(Mac/Linux)

```
pip install requests[socks] 
//这一句可以让request使用socks代理
```

```
export all_proxy=socks5://127.0.0.1:1080
//这一句让网络转发通过你的代理地址
```

目前仍有一些问题 还未解决 如果你想帮助，[moridisa@moridisa.cn](mailto:moridisa@moridisa.cn)
