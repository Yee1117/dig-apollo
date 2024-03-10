# 深入探究 Apollo (阿波罗) ![GitHub](https://img.shields.io/github/license/daohu527/Dig-into-Apollo.svg?style=popout) [![Documentation Status](https://readthedocs.org/projects/dig-into-apollo/badge/?version=latest)](https://dig-into-apollo.readthedocs.io/en/latest/?badge=latest)

“深入探究阿波罗” 主要旨在协助学习 [Apollo](https://github.com/ApolloAuto/apollo)自动驾驶系统。 首先我们将详细介绍每个模块的功能，然后分析每个模块的代码。如果你对自动驾驶感兴趣并想学习它，让我们开始这个项目并讨论你想知道的任何内容！

#### readthedocs
- [dig-into-apollo](https://dig-into-apollo.readthedocs.io/en/latest/index.html#)

#### google groups
- [disscuss-apollo](https://groups.google.com/g/d-apollo)

## 友情提示

* 如果在github上使用"git clone"太慢，请尝试使用阿波罗 **[镜像](https://gitee.com/baidu/apolloauto)**。 
* 如果您有任何问题，请随时在 **[git问题](https://github.com/daohu527/dig-into-apollo/issues)**  中提问。
* 如果您需要添加新文档或提供建议，欢迎参与 **[git讨论](https://github.com/daohu527/dig-into-apollo/discussions)**。

## 目录

- [Apollo是什么](what_is_apollo)
- [如何构建](how_to_build)
- [代码学习](code_learning)
    - [网络](cyber)
    - [容器](docker)
    - [模块](modules)
        - [音频](modules/audio)
        - [桥接](modules/bridge)
        - [车载网络](modules/canbus)
        - [数据](modules/data)
        - [驱动程序](modules/drivers)
        - [梦幻视图](modules/dreamview)   
        - [地图](modules/map)
        - [定位](modules/localization)
        - [感知](modules/perception)
        - [预测](modules/prediction)
        - [路由](modules/routing)
        - [规划](modules/planning)
        - [控制](modules/control)
        - [变换](modules/transform)
        - [工具](modules/tools)
        - [车对车/车对设施通信](modules/v2x)
- [性能](performance)
- [仿真](simulation)
- [库](library)
- [论文](papers)
- [问题](questions)


## 入门指南

如果你像之前的我一样不知道如何开始阿波罗项目，这里有一些建议。  

1. 首先了解基本模块功能。如果你对模块的一般功能不清楚，你会发现很难理解代码在做什么。这里有一个初学者级别的[教程](https://apollo.auto/devcenter/coursetable_cn.html?target=1) 。  
2. 然后你需要掌握每个模块特定的操作方法，这些方法将在本教程中详细说明。我们将在后续的内容中深度剖析代码。你可以按照我们的教程，逐步学习。
3. 我明白这个过程可能会有些困难，尤其当你刚开始学习Apollo的时候。但只要你不断思考并勤奋学习，一到两个月后，一切都会变得简单许多。
4. 最后要说的是，虽然Apollo的技术几乎十分完善了，但难免还是会遇到一些问题。尝试去实际操作并改进它，查阅相关的论文，试验最新的技术方法，去提升你的技能。我相信你会享受这个过程的。


## 如何学习？

**基础学习**  

1. 观看一些入门教程将帮助你更快地理解Apollo自动驾驶系统。我强烈推荐这个[教程](https://apollo.auto/devcenter/coursetable_cn.html?target=1)  
2. 尝试提一些问题，阅读一些博客、论文，或者到github上提一些[问题](https://github.com/ApolloAuto/apollo/issues).  
3. 如果你没有自驾车，可以尝试部署一个仿真环境，我强烈推荐使用[lgsvl](https://github.com/lgsvl/simulator)。它的社区非常友好！ 
4. 如果仿真环境出现任何问题，比如创建地图或其他问题，欢迎加入我们的Flycars项目。我们会尽可能提供帮助！ 

**代码学习**  

1. 首先，你必须了解C++。如果你对它不是很熟悉，我推荐 **"c++ primer"** 这本书，但它有点厚。如果你想快速开始，那么可以尝试找一些简单的教程， 比如[侯捷](https://search.bilibili.com/all?keyword=%E4%BE%AF%E6%8D%B7)老师的课程。
2. 在理解了C++之后，最好对一些模块有一定的基本了解，这将帮助你更好的阅读代码。
3. 使用代码阅读工具来帮助你阅读代码。我强烈推荐使用[vscode](https://code.visualstudio.com/)。 它支持Windows和Linux，并有很多插件，可以帮助你跟踪代码、搜索和找到函数调用关系。
4.当然，这个领域还有众多的专业知识和资源库。我没办法逐个去介绍它们，但我可以推荐一些优秀的资源，例如， [李宏毅的深度学习课程](https://www.bilibili.com/video/BV1JE411g7XF?p=1), 以及[3Blue1Brown的数学视频](https://space.bilibili.com/88461692/)教程
5. “动手实践”：用模拟器做一些实验。你不能只停留在看，你可以尝试修改一下配置并检测是否有效。如果可能的话，你也可以尝试回答一些问题。
6. 多读一些论文，因为自动驾驶远未成熟。我读了很多[论文](https://github.com/daohu527/awesome-self-driving-car#papers-blogs)，这对我帮助很大。

希望你有个愉快的学习之旅!  

## 贡献
本项目欢迎任何形式的贡献和建议。请查看我们的贡献指南。  


## 参考与资源
- [apollo](https://github.com/ApolloAuto/apollo)  
- [自动驾驶汽车资源集](https://github.com/daohu527/awesome-self-driving-car)    
