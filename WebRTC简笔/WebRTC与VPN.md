> WebRTC是一种P2P的通信方式，为了穿透NAT设备，因此在建立通信通道之前，会先互相知道对方的公网IP地址和端口，而浏览器则利用`STUN`或者`TURN`服务获取到公网的IP，这就会导致公网IP泄露。

## VPN
VPN是虚拟专用网络，也就是在一个网络环境中建立一个专用网络，进行加密通讯。vpn网关通过对数据包的加密和数据包目标地址的转换实现远程访问。当你接入了一个专网，你访问网络都是从这个专网的网络出口出去。
> 至于为什么能够改变网络出口地址，这是更底层的东西
因此，`WebRTC`是无法绕过真正的`VPN`的
## WebRTC通信方式
![250050215053233.png](http://images.cnitblog.com/blog2015/57211/201503/250050215053233.png)
实现方式为非直连P2P
## P2P通信机制
* 直连通信
* STUN/TURN方式

# 参考资料
[P2P技术详解](http://www.52im.net/thread-557-1-1.html)
[P2P实现方式](https://blog.csdn.net/phunxm/article/details/27977783)
