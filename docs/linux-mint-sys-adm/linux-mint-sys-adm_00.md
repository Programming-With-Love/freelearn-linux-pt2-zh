# 前言

在过去的 5 年中，基于 Linux 的操作系统的用户数量显著增加。许多计算机用户希望了解更多关于 Linux 的信息，并且许多人正在从 Windows 和 Mac OS X 等其他系统迁移过来。目前，Linux Mint 是最广泛使用的基于 Linux 的操作系统之一，许多用户需要提高他们使用该操作系统执行高级任务的能力。这些任务包括通过 FTP 连接到其他计算机、创建 shell 脚本以及将用户组织成组。

*Linux Mint 系统管理员初学者指南*提供了一套实用的食谱，帮助你成为 Linux 系统管理员。通过这本书，你将学习 Linux 系统管理员需要了解和执行的基本概念和操作。我们将从基本操作开始，例如安装 Linux Mint，并逐步学习更高级的主题，如安全和监控。

尽管我们将使用 Linux Mint 进行工作，但本书中描述的大多数概念和操作都可以应用于其他 Linux 发行版，如 Ubuntu、Debian 和 Fedora。

# 本书内容

第一章，*Linux Mint 简介*，是本书的“入门”章节。它解释了 Linux Mint 是什么，有哪些版本，以及 Linux Mint 与其他 Linux 发行版有何不同。

第二章，*安装 Linux Mint*，教你如何在你的计算机上安装 Linux Mint。它提供了一个简单易懂的逐步指南，用于安装和启动这个操作系统。

第三章，*基本 Shell*，向你介绍 Linux Shell。你将学习如何处理基本操作和动作，例如找出当前目录、设置环境变量以及创建简单的 Shell 脚本。

第四章，*账户配置*，涵盖了你需要操作用户账户的所有内容，包括如何创建用户和组，以及如何更改用户的权限。

第五章，*安装、卸载和升级软件*，教你如何执行基本操作以使软件在你的计算机上运行。

第六章，*配置硬件*，提供了检测和配置硬件设备（如键盘、鼠标、显示器和声卡）的过程的覆盖。

第七章，*网络*，专注于有线和无线网络。你将学习如何配置你的网络并使用 FTP 协议连接到其他服务器。

第八章，*存储和备份*，涵盖了不同的文件系统类型。它教你如何查看磁盘使用空间，以及如何创建和恢复重要数据的备份。

第九章，*安全*，探讨了运行安全 Linux Mint 计算机所需了解的基本概念。本章包括安装和配置防火墙的步骤，使用内核的安全模块，并解释了如何构建一个简单而有效的安全检查清单。

第十章，*监控你的系统*，涵盖了操作系统监控的主要方面。你将学习如何管理计算机上运行的服务和进程，以及内存、CPU 和网络的使用情况。

第十一章，*故障排除*，帮助你识别问题，检查你的硬件、网络、内核、进程和文件系统。

# 本书所需

显然，你需要一台基于 Intel 的计算机。市场上大多数计算机，包括不同品牌的笔记本电脑和台式机，都属于这一类别。为了安装 Linux Mint，你需要一个至少 1GB 容量的 USB 闪存驱动器。此外，建议使用宽带互联网连接以下载、安装和升级软件。

# 本书适合谁

本书适合对学习 Linux 系统管理感兴趣的计算机用户。你应该熟悉基于 Linux 的操作系统以及基本概念，如目录、文件、命令和进程。那些已经尝试过 Linux 的用户以及*高级用户*可以通过本书提升他们的知识，成为系统管理员。

# 约定

在本书中，你将发现几个频繁出现的标题。

为了给出完成一个过程或任务的清晰指令，我们使用：

# 行动时间 – 标题

1.  行动 1

1.  行动 2

1.  行动 3

指令通常需要一些额外的解释，以便它们有意义，因此它们后面跟着：

## *刚刚发生了什么？*

本标题解释了你刚刚完成的任务或指令的工作原理。

你还会在书中找到一些其他的学习辅助工具，包括：

## 动手实践 – 标题

这些实际挑战为你提供了实验所学知识的想法。

你还会发现许多不同类型的文本样式，用于区分不同类型的信息。以下是这些样式的一些示例，以及它们的含义解释。

文本中的代码词如下所示："将 ISO 镜像，`linuxmint-13-mate-dvd-32b.iso`保存到你的硬盘上。"

任何命令行输入或输出都如下所示：

```
arturo@han-solo ~ $ cd /tmp

```

**新术语**和**重要词汇**以粗体显示。您在屏幕上看到的单词，例如在菜单或对话框中，会以这种方式出现在文本中：“点击 **磁盘映像** 选项，并使用带有标签的按钮选择下载的 ISO 映像”。

### 注意

警告或重要提示会以这样的方框形式出现。

### 提示

提示和技巧会以这种方式呈现。

# 读者反馈

我们始终欢迎读者的反馈。请告诉我们您对这本书的看法——您喜欢或可能不喜欢的地方。读者反馈对我们开发您真正能从中受益的书籍至关重要。

若要向我们发送一般反馈，只需向 `<feedback@packtpub.com>` 发送电子邮件，并在邮件主题中提及书名。

如果您在某个领域具有专长，并且有兴趣撰写或参与撰写一本书，请查看我们在 [www.packtpub.com/authors](http://www.packtpub.com/authors) 上的作者指南。

# 客户支持

既然您已经是 Packt 书籍的自豪拥有者，我们有一系列服务帮助您从购买中获得最大收益。

## 勘误

尽管我们已经尽一切努力确保内容的准确性，但错误仍然会发生。如果您在我们的书中发现错误——可能是文本或代码中的错误——如果您能向我们报告，我们将不胜感激。这样做，您可以避免其他读者感到沮丧，并帮助我们改进这本书的后续版本。如果您发现任何勘误，请通过访问 [`www.packtpub.com/support`](http://www.packtpub.com/support)，选择您的书，点击 **勘误提交表** 链接，并输入您的勘误详情来报告它们。一旦您的勘误得到验证，您的提交将被接受，勘误将被上传到我们的网站，或添加到该标题的勘误部分中的任何现有勘误列表中。

## 盗版

互联网上版权材料的盗版是所有媒体持续存在的问题。在 Packt，我们非常认真地保护我们的版权和许可。如果您在网上遇到我们作品的任何非法副本，请立即向我们提供位置地址或网站名称，以便我们采取补救措施。

请通过 `<copyright@packtpub.com>` 与我们联系，并提供涉嫌盗版材料的链接。

我们感谢您帮助保护我们的作者，并使我们能够为您带来有价值的内容。

## 问题

如果您在书的任何方面遇到问题，可以通过 `<questions@packtpub.com>` 与我们联系，我们将尽力解决。
