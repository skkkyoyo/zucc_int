# zucc_int
浙江大学城市学院同时上内外网
---
先打开默认网关获取在里面找到一个10.xx.xx.x的一个地址

【如下方的 `默认网关. . . . . . . . . . . . . : 10.64.65.1` 其中`10.64.65.1`就是那个地址】

复制下来

```dos
以太网适配器 以太网:

   连接特定的 DNS 后缀 . . . . . . . :
   本地链接 IPv6 地址. . . . . . . . : fe80::1825:23d0:b809:dd82%21
   IPv4 地址 . . . . . . . . . . . . : 10.64.65.200
   子网掩码  . . . . . . . . . . . . : 255.255.255.0
   默认网关. . . . . . . . . . . . . : 10.64.65.1
```

然后右键链接内外网，选择编辑
将里面的10.64.66.1改为你刚才获取的地址
然后保存

最后右键链接内外网，选择以管理员方式运行
弹出窗口点确定

然后有一个黑框出来显示连接成功
就可以关掉了

现在你就可以内外网一起上了

*注意这个我只在南校区测试过
不知道北校区是否能成功*

---
##注：
---
Zucc_L2tp_Client文件夹中为学校闪讯·移动·联通客户端

客户端有更新可以将安装包上传到[lessues](https://github.com/skkkyoyo/zucc_int/issues)里面告诉我

寝室路由器使用方法[点击这里查看](https://github.com/skkkyoyo/zucc_int/issues/2)
