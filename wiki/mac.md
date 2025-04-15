# Mac平台使用教程

## **前言**

您在配置碰见任何问题，可以[『点我提交问题』](https://www.lengjiao.me/submitticket.php)或者联系[『官网』](https://www.lengjiao.me)下方在线客服。如果您没有购买服务，请先[『点我购买』](https://www.lengjiao.me/cart.php)服务



如果你的<mark style="color:red;">Mac型号</mark>是<mark style="color:red;">M1/M2/M3</mark>，强烈建议参照 [**Ios/M1/M2/M3平台使用教程**](ios.md) 配置，更加稳定

## 下载软件

[『点我下载』](https://alumninpustedutw-my.sharepoint.com/:u:/g/personal/empty_alumni_npust_edu_tw/Ef9oLbJa45NIqlAXVNHN_KYBpvtZRC8i427m1HhtvrGqjw?download=1)软件，打开软件，如果提示恶意软件(如下图)：

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65e098cb9f345e8d03cb62af.png" alt=""><figcaption></figcaption></figure></div>

请在『启动台』-『其他』-『终端』粘贴以下命令，并回车

```
sudo spctl --master-disable
```

{% hint style="info" %}
<mark style="color:blue;">输入mac密码(密码不显示)，并回车，再次打开软件即可</mark>
{% endhint %}

## 配置软件

&#x20;1\. [『点我登录』](https://www.lengjiao.me/clientarea.php)客户区— 点开『已激活的产品/服务』— 点击『节点订阅』

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65a2ba22871b83018ad1a7ea.png" alt=""><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65a2ba22871b83018ad1a874.png" alt=""><figcaption></figcaption></figure></div>

2.打开软件后，<mark style="color:red;">鼠标左键</mark>点<mark style="color:red;">屏幕右上角</mark>软件图标，粘贴订阅地址

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65e092489f345e8d03b35aad.png" alt=""><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65e2875f9f345e8d030d7795.png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
<mark style="color:blue;">每次购买新的服务，订阅地址会改变，需要重新添加订阅地址，续费的不需要，请参考</mark>[『重新购买服务后操作』](../chang-jian-wen-ti/zhong-xin-gou-mai-fu-wu-hou-cao-zuo.md)
{% endhint %}

3.更新订阅

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65e0926d9f345e8d03b3dfdd.png" alt=""><figcaption></figcaption></figure></div>

4.选择合适的服务器

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65e0926d9f345e8d03b3e0af.png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
<mark style="color:blue;">每次重新打开软件后，务必再次选择节点</mark>
{% endhint %}

5.打开软件，您就能愉快的上网啦

<div align="left"><figure><img src="https://pic.imgdb.cn/item/65e0926d9f345e8d03b3e125.png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
<mark style="color:blue;">每次重新打开软件后，务必再次启动开关</mark>
{% endhint %}

## 常见故障

打开软件提示如下：

<div align="left"><figure><img src="https://pic.imgdb.cn/item/6752bf48d0e0a243d4deb81c.png" alt=""><figcaption></figcaption></figure></div>

请在『启动台』-『其他』-『终端』粘贴以下命令，并回车

```
rm -rf ~/.config/trojan-qt5/
```
