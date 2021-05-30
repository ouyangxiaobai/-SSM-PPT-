下载地址：http://ym.maptoface.com/2021/05/31/%e5%9f%ba%e4%ba%8essm%e7%9a%84%e5%9b%be%e4%b9%a6%e6%8e%a8%e8%8d%90%e5%b1%95%e7%a4%ba%e7%b3%bb%e7%bb%9f%e8%ae%be%e8%ae%a1%e4%b8%8e%e5%ae%9e%e7%8e%b0-%e6%af%95%e4%b8%9a%e8%ae%ba%e6%96%87%e4%bb%bb/
摘　　要

推荐系统是目前互联网中最常见的智能产品形式。由于网络中信息量的增长以及图书出版行业出版量的攀升，人们需要一种办法，来解决信息过载的问题。同时，用户访问网络是为了获取信息，而并不是所有的访问都有很强的目的性，所以就需要系统智能地把一些用户可能感兴趣的信息推送给用户。这就使得图书网站的推荐功能变得非常重要。

本文首先对图书推荐系统发展历史做了介绍，之后又对开发过程中用到的项目管理工具：Maven、Git，数据持久化工具：MyBatis，Spring MVC框架，Bootstrap前端开发框架进行了简要讲解，最后，设计并开发了一套基于Web的图书推荐系统展示平台。该项目主要工作如下：

(1) 总体设计。总体设计阶段，对系统结构做了设计，主要是在Spring MVC框架的基础上，将系统分为了三层：Web层、服务与模块层、数据层，对每层的结构与需要完成的功能做了定义。

(2) 详细设计。详细设计完成了数据库表的设计、页面设计两大部分。库表设计按照总体设计的思想，分为三部分，共15张表。页面设计分成了首页、搜索、展示、登录、注册几个主要的页面，通过快速原型工具设计出。

(3) 系统开发。根据设计结果，下载工具，搭建环境，进行开发。开发过程中，参考敏捷开发的理念，按照模块，制定计划，在完成一个模块后，与原先设计进行验证，然后在这基础上进行修改，以达到最终目标，之后开始下一个模块的计划与开发。

经过后期的数据库优化与功能测试，系统与同类网站相比，性能良好。

关键词：基于Web的图书推荐系统；展示平台；MVC框架

Display Platform of Web-based Book Recommender System

Abstract

Recommender system is the most common intelligent product form in the internet recently. Since the growth of the information in the network as well as the growth of the amount of books, people need to solve the problem of information overload. Meanwhile, the users access to the network to obtain information, but not all have a strong purpose. So the system must push some information to user that he might be interested in. That is why it is important for website to provide recommendation information.

First of all, described the history of book recommender system. Then, made an introductory of the tool and frameworks used in development: Maven, the project management tool, Git, the version control system, MyBatis, the SQL Mapping Framework for Java, Spring MVC framework and Bootstrap, the front-end framework. Finally, designed and developed a display platform of web-based book recommender system. The main work is as follows.

(1) Overall design. In the overall design phase, made the system architecture design. Divided the system into three level: the web level, the service and model level and the data level based on the Spring MVC framework. Made the definition of the structure and functions to be done on each layer.

(2) Detail design. The detailed design do the job of designing the database and the webpage. Database is divided into three parts, 15 tables in total, according to the overall design. Pages have been divided into index, search, display and login and register parts that were designed using rapid prototyping tools.

(3) System development. According to the design, download tools, deploy environment for development. In the development phase, make every model to be a unit, finish them one by one and verify with the original design after model finished referring agile development. If the model is not as the original intent, make some modification and verify it again.

After database optimization and functional testing, system performs good compared with similar sites.

Key Words：Web-based Book Recommender System; Display Platform; MVC Framework




目　　录

摘　　要 1

Abstract 2

引　　言 1

1文献综述 2

1.1课题背景 2

1.1.1图书推荐系统发展背景 2

1.1.2主要技术发展背景 3

1.2开展研究的意义 4

1.3论文研究内容 4

1.4论文的组织结构 5

2理论与工具介绍 6

2.1 Maven介绍 6

2.1.1 Maven概述 6

2.1.2 Maven概念 6

2.2 Git介绍 8

2.2.1 Git概述 8

2.2.2 Git特性 9

2.3 MVC模式与Spring Framework框架 11

2.3.1 MVC模式 11

2.3.2 Spring MVC框架 11

2.4 MyBatis介绍 15

2.5 Bootstrap介绍 16

2.5.1 Bootstrap概述 16

2.5.2 结构和功能 16

2.6 jQuery介绍 17

2.7 小结 18

3 基于Web的图书推荐系统展示平台设计 20

3.1 系统总体设计 20

3.1.1 总体功能描述 20

3.1.2 系统模块组成 20

3.2 模块详细设计 23

3.2.1 数据库设计 23

3.2.2 页面原型设计 27

3.3 小结 28

4 基于Web的图书推荐系统展示平台实现 29

4.1 环境的搭建 29

4.1.1 数据库的建立与数据的导入 29

4.1.2 工程建立 29

4.1.3 版本控制 31

4.1.4 MyBatis配置 31

4.2 数据的清洗 33

4.3 系统开发 35

4.3.1 控制器类 35

4.3.2 模块类 37

4.3.3 视图类 38

4.4 分析及调优 39

4.5 小结 41

结　　论 42

参 考 文 献 43

附 录 44

附录A 外文参考文献原文 44

附录B 外文参考文献译文 53

在 学 取 得 成 果 61

致　　谢 62

              
