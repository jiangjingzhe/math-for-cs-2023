# math-for-cs-2023
neuq 计算机数学基础学习仓库

## 一些必会工具
不只是对于这门课，无论你以后打算学习计算机的什么方向，这些工具都可以帮助你许多。

**刚开始入门这些工具你可能要花一点时间，但请不要着急，多花点时间，因为这些工具太重要了！**

### GitHub/Git
#### GitHub 是什么？
> 从功能上来说，GitHub 是一个在线代码托管平台。你可以将你的本地 Git 仓库托管到 GitHub 上，供多人同时开发浏览。但现如今 GitHub 的意义已远不止如此，它已经演变为一个非常活跃且资源极为丰富的开源交流社区。全世界的软件开发者在 GitHub 上分> 享各式各样种类繁多的开源软件。大到工业级的深度学习框架 PyTorch, TensorFlow，小到几十行的实用脚本，既有硬核的知识分享，也有保姆级的教程指导，甚至很多技术书籍也在 GitHub上开源

#### 如何使用Github
如果你还从未在 GitHub 上建立过自己的远程仓库，也没有克隆过别人的代码，那么我建议你从[GitHub](https://docs.github.com/zh/get-started) 的官方教程开始自己的开源之旅！

*注意：如果你连不上GitHub，或者无法 `git clone`  下载仓库，那么你可能需要一点魔法。*

#### 你需要完成的任务
1.注册一个你的GitHub账号，创建一个你的 **math-for-cs-2023** 仓库.
2.下载安装并初始化[Git](https://docs.github.com/zh/get-started/quickstart/set-up-git)，并尝试使用`git clone`命令下载此仓库到你的本地计算机，以后你都可以用`git pull`命令来更新此仓库的新内容。

同时尝试自己学习一下git的用法，这对你也十分有帮助。[git教程](https://www.runoob.com/git/git-install-setup.html)


### Conda
#### Conda是什么？
Conda是在Windows、macOS和Linux上运行的开源软件包管理系统和环境管理系统。Conda可以快速安装、运行和更新软件包及其依赖项。Conda可以轻松地在本地计算机上的环境中创建，保存，加载和切换。它是为Python程序创建的，但可以打包和分发适用于任何语言的软件。

Conda作为软件包管理器，可以帮助您查找和安装软件包。如果您需要一个能够使用不同版本Python的软件包，则无需切换到其他环境管理器，因为conda也是环境管理器。仅需几个命令，您就可以设置一个完全独立的环境来运行不同版本的Python，同时继续在正常环境中运行喜欢的Python版本。

#### 下载conda
在[官网下载](https://docs.conda.io/projects/miniconda/en/latest/)即可


安装后在命令行中输入`conda`,出现提示结果，表示安装成功：


conda 的教程网上有很多，如anaconda与miniconda都可以，同学可以自己找基础安装。

### cvxpy
cvxpy是python中一款支持凸优化的强大工具包，学习使用它可以让你实现这门课中的各种算法。
让我们开始吧！进入官网[cvxpy](https://www.cvxpy.org/install/index.html)

选择conda下载方式，创建一个名为cvxpy_env的虚拟环境，激活（activate），并在里面下载好cvxpy包。


