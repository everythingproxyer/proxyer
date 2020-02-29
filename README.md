
![proxyer](https://github.com/everythingproxyer/proxyer/blob/master/img/logo.png)

# 私有内网映射工具

现在市面上的内网映射工具，大部分都是收费的，收费的同时只能够提供有限的网络带宽。造成这个问题最主要的原因是流量本来就非常贵，无论是谁提供内网映射服务都绕不过这个问题，那些免费的内网映射工具，更无法保证提供优质的服务了。

当下互联网发展已经深入了各方面的生活，网络带宽小，会极大的影响很多应用的体验，例如远程桌面、文件传输、视频监控等应用，带宽小体验非常差。

而与此同时，云服务器的租用变得越来越简单，按流量收费的这种模式也逐渐兴起，在这种情况下，我们完全可以选择为自己或者团队搭建一个私有的内网映射服务。提供按质，按量的优质服务。所有的数据和流量都在自己的掌握之下，可大可小，将真正发挥远程的能力。

Proxyer是一个允许个人随意搭建的新一代的内网映射工具，借助于公网服务器和内网客户端，可以将内网电脑的任意IP地址和端口映射到公网服务器上。整个过程完全自动化，对内网的依赖极小，只要客户端能够连接外网服务器，就能够实现端口映射。

使用Proxyer，您可以
- 远程使用Windows远程桌面
- 远程GIT，SVN
- 远程访问Linux
- 视频监控
- 远程共享NAS存储、FTP
- ... ...

与其它的内网映射工具相比，Proxyer有三个显著的特点

1. Proxyer不提供公共映射服务器，Proxyer只提供安装包，您可以将Proxyer安装到自己的服务器上，数据和带宽是完全独占，数据是完全安全的。
    1. 企业内部可以自己搭建自己私有的服务器，这样就极其简单的为企业构建了一些场景下的远程办公能力。
    2. 企业某一些特殊产品，需要远程运维，也可以通过搭建自己的私有服务器提供简单高效的解决方案。
    3. 个人可以搭建自己私有的服务端为自己提供优质的内网映射服务。
2. Proxyer提供极简的安装使用方式。服务端Docker一键安装，客户端开箱即用、完全绿色，支持Windows端、macOS、Linux端
3. Proxyer所有的代码和协议都是全新的，不依赖任何开源库，保证了安全和后期功能扩展可持续性。

以花生壳相比，根据官方公布的价格，最便宜的套餐318元/1/年，只有1Mbps的共享带宽，而且只允许一个映射。最贵的企业版本4988元一年，独享5Mbps带宽，映射数量按需开通。

Proxyer完全免费。在阿里云环境下，一台最便宜的共享云服务器只需要24元一个月，开10M按流量收费的服务，您就可以任意映射端口，同时独占整个服务器资源和带宽。一个月成本不过30 - 40元，就可以获得比花生壳4988元套餐更好的服务。

如果您将proxyer用于远程办公，综合成本和用户体验整体核算下来，也会发现比目前Teamview和向日葵等软件低至少5 - 10倍的价格。

与其它类似的工具，例如[https://www.ngrok.cc/](https://www.ngrok.cc/)， [https://www.nsloop.com/](https://www.nsloop.com/)、[https://serveo.net/](https://www.nsloop.com/) 相比。

Proxyer依然有两个重要优势

1. 自己安装自己的服务器，低成本独享服务，不受其它客户影响，安全可靠。
2. 安装和配置极其简单，开箱即用。

# 安装和使用

- 安装使用可以查看[WIKI](https://github.com/everythingproxyer/proxyer/wiki)
- 有问题可以在本项目中的[Issues](https://github.com/everythingproxyer/proxyer/issues)提
- 如果有其它问题，可以发邮件咨询: runimgservices@163.com
