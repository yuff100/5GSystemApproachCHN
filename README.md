# 关于本书
本书的Github仓库<sup>[1]</sup>提供了*5G移动网络:一种系统方法*的源代码，遵循知识共享协议(CC BY-NC-ND 4.0)<sup>[2]</sup>许可条款。我们邀请社区一起在相同的条件下更正、改进、更新本书以及为本书提供新的素材。

如果你打算使用本书内容，请保留以下信息:
*Title: 5G Mobile Networks: A Systems Approach*
*Authors: Larry Peterson and Oguz Sunay*
*Source:* https://github.com/SystemsApproach/5G
*License:* CC BY-NC-ND 4.0<sup>[2]</sup>

# 阅读本书
本书是系统方法系列<sup>[3]</sup>的一部分，在线版本在https://5G.systemsapproach.org上发布。

要跟踪项目进展并收到关于新版本的通知，可以在Facebook<sup>[4]</sup>和Twitter<sup>[5]</sup>上跟踪项目。要跟踪关于互联网如何发展的讨论，请在Substack上订阅系统方法<sup>[6]</sup>。

# 构建本书
你可以下载源代码，从而构建一个Web版本：
```
$ mkdir ~/5G
$ cd ~/5G
$ git clone https://github.com/SystemsApproach/5G.git
```
构建依赖Python，构建过程定义在Makefile中。Makefile将创建一个虚拟环境（doc_venv），用于安装文档生成工具集。

要生成HTML，请在```_build/html```下面执行```make html```。

检查本书的格式，执行```make lint```。

执行```make```可以看到还支持哪些输出格式。

# 为本书做出贡献
如果你使用本书提供的内容，那我们希望你也愿意作出为本书做出贡献。如果您对开源项目不熟悉，可以查看“如何为开源项目做出贡献”指南<sup>[7]</sup>。除了其他事情，你还将学到如何发布你希望得到解决的*问题（Issues）*，并学会如何发出*Pull Requests*将你的改动合并到GitHub。

如果你想要投稿，并且正在寻找一些需要关注的事情，请查看wiki<sup>[8]</sup>上当前的待办事项列表。

> **Reference:**
> [1] https://github.com/SystemsApproach/5G
> 
> [2] https://creativecommons.org/licenses/by-nc-nd/4.0
> 
> [3] https://www.systemsapproach.org/
> 
> [4] https://www.facebook.com/Computer-Networks-A-Systems-Approach-110933578952503/
> 
> [5] https://twitter.com/SystemsAppr
> 
> [6] https://systemsapproach.substack.com/
> 
> [7] https://opensource.guide/how-to-contribute/
> 
> [8] https://github.com/SystemsApproach/5G/wiki
