# 入门指南第四部分

### 第四部分：快速恢复

您可能已经注意到，当您之前将文件 _favicon.ico_ 保存到桌面文件夹时，Sandboxie 提供了该文件的[即时恢复](ImmediateRecovery.md)选项。但是，当您将 _test1.txt_ 保存到 C 盘根目录时，却没有这样的提示。

这是因为桌面文件夹（默认情况下）被配置为"可恢复"的文件夹位置，您通常会想要从中恢复文件。而 C 盘根目录不被视为可恢复位置。

[快速恢复](QuickRecovery.md)命令会扫描可恢复文件夹并显示所有可恢复文件的摘要：

![](../Media/QuickRecoverSandbox.png)

您可以通过以下方式调用**快速恢复**命令：

* 从 Sandboxie 控制器主窗口的[沙盒菜单](SandboxMenu.md)中。

* 通过右键点击屏幕角落的[托盘图标菜单](TrayIconMenu.md)。

* * *

上图显示 _favicon.ico_ 是唯一的可恢复文件，因为它是唯一保存到可恢复位置的文件——在这种情况下是桌面文件夹。

默认情况下，其他被设置为可恢复文件夹的位置包括您的"文档"文件夹、Windows 的"收藏夹"文件夹。在适用的情况下，您的"下载"文件夹也被视为可恢复文件夹。由于这些文件夹中没有任何符合恢复条件的文件，所以它们在上图中完全没有列出。

您可以使用"添加文件夹"按钮向快速恢复添加更多文件夹。

* 您可以将 [Sandboxie 控制器](SandboxieControl.md)切换到[文件和文件夹视图](FilesAndFoldersView.md)，以查看和恢复沙盒中任何位置的文件。

* * *

在恢复文件（或文件夹）时，您可以选择将文件恢复到沙盒外的对应位置——例如，从沙盒化的桌面文件夹恢复到真实的桌面。"恢复到相同文件夹"命令（在上图中显示为按钮）就是这样做的。

或者，您可以使用"恢复到任意文件夹"命令，它可以将沙盒中的文件移动到计算机系统中的任何文件夹位置。

* * *

### 即时恢复

[即时恢复](ImmediateRecovery.md)功能，在本指南的上一部分中简要提到过，是[快速恢复](QuickRecovery.md)的扩展。即时恢复会持续扫描相同的可恢复文件夹集合，并让您能够在文件创建后立即恢复它们：

![](../Media/ImmediateRecoverFavIcon.png)

与快速恢复一样，您可以"恢复到相同文件夹"或"恢复到任意文件夹"。

* * *

总结：

* 如果要让文件被[快速恢复](QuickRecovery.md)和[即时恢复](ImmediateRecovery.md)注意到，文件必须创建在可恢复文件夹中。

* 您可以自定义可恢复文件夹集合。

* 您可以使用[文件和文件夹视图](FilesAndFoldersView.md)来恢复不在任何可恢复文件夹中的文件。

* * *

教程继续在[入门指南第五部分](GettingStartedPartFive.md)。 