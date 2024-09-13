# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 11060ssm学生宿舍管理系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第1章 绪论
## 1.1背景及意义
系统管理也都将通过计算机进行整体智能化操作，对于学生宿舍管理系统所牵扯的管理及数据保存都是非常多的，例如管理员；首页、个人中心、宿舍信息管理、学生管理、宿舍报修管理、访客信息管理、水电费管理、管理员管理、交流论坛、系统管理，学生；首页、个人中心、宿舍报修管理、水电费管理，前台首页；首页、交流论坛、通知公告、个人中心、后台管理、在线沟通等，这给管理者的工作带来了巨大的挑战，面对大量的信息，传统的管理系统，都是通过笔记的方式进行详细信息的统计，后来出现电脑，通过电脑输入软件将纸质的信息统计到电脑上，这种方式比较传统，而且想要统计数据信息比较麻烦，还受时间和空间的影响，所以为此开发了学生宿舍管理系统 ；为学生提供了方便管理平台，方便管理员查看及维护，并且可以通过需求进行内容的编辑及维护等；对于学生而言，可以随时进行查询所需信息，管理员可以足不出户就可以获取到系统的数据信息等，而且还能节省学生很多时间，所以开发学生宿舍管理系统给管理者带来了很大的方便，同时也方便管理员对学生信息进行处理。

本论文学生宿舍管理系统主要牵扯到的程序，数据库与计算机技术等。覆盖知识面大，可以大大的提高工作人员的效率。

## 1.2 国内外研究概况
随着国内经济形势的不断发展，中国互联网进入了一个难得的高峰发展时期，这使得中外资本家纷纷转向互联网市场。 然而，许多管理领域的不合理结构，人员不足以及管理需求的增加使得更多的人具备了互联网管理的意识。

在当今高度发达的信息中，信息管理改革已成为一种更加广泛和全面的趋势。 “学生宿舍管理系统 ”是基于Mysql数据库，在SSM程序设计的基础上实现的。为确保中国经济的持续发展，信息时代日益更新，更是蓬勃发展。同时，随着信息社会的快速发展，学生宿舍管理系统 面临着越来越多的信息，因此很难获得他们对高效信息的需求，如何使用方便快捷的方式使查询者在广阔的海洋信息中查询，存储，管理和共享信息方面有效，对我们的工作和生活具有重要的现实意义。因此，国内外学术界对此进行了深入而广泛的研究，一个新的研究领域——学生宿舍管理系统 诞生了。
## 1.3 研究的内容
目前许多人仍将传统的纸质工具作为信息管理的主要工具，而网络技术的应用只是起到辅助作用。在对网络工具的认知程度上，较为传统的office软件等仍是人们使用的主要工具，而相对全面且专业的信息管理软件仍没有得到大多数人的了解或认可。本选题则旨在通过标签分类管理等方式，实现学生宿舍管理系统 的各种功能，从而达到对学生宿舍管理系统的管理。

详细内容介绍，将在以下六章中详细阐述：

第一章、绪论，介绍了研究课题选择的背景及意义、研究现状，简要介绍了本文的章节内容。

第二章、引入技术知识，通过引入关键技术进行开发，向系统中涉及直观表达的技术知识。

第三章、重点分析了系统的分析，从系统强大的供需市场出发，对系统开发的可行性，系统流程以及系统性能和功能进行了探讨。

第四章、介绍了系统的详细设计方案，包括系统结构设计和数据库设计。

第五章、系统设计的实现，通过对系统功能设计的详细说明，论证了系统的结构。

第六章、系统的整体测试，评判系统是否可以上线运行。




# 第2章 相关技术
## 2.1 JAVA简介
Java主要采用CORBA技术和安全模型，可以在互联网应用的数据保护。它还提供了对EJB（Enterprise JavaBeans）的全面支持，java servlet API，Java（java server pages），和XML技术。JAVA语言是一种面向对象的语言，它通过提供最基本的方法来完成指定的任务，开发者只需要知道一些概念就能够编写出一些应用程序。Java程序相对较小，其代码能够在小机器上运行。Java是一种计算机编程语言，具有封装、继承和多态性三个主要特性，广泛应用于学生Web应用程序开发和移动应用程序开发。

Java语言和一般编译器以及直译的区别在于，Java首先将源代码转换为字节码，然后将其转换为JVM的可执行文件，JVM可以在各种不同的JVM上运行。因此，实现了它的跨平台特性。虽然这使得Java在早期非常缓慢，但是随着Java的开发，它已经得到了改进。

## 2.2 SSM三大框架
1.Spring的优势:
通过Spring的IOC特性，将对象之间的依赖关系交给了Spring控制，方便解耦，简化了开发。

2.Spring MVC的优势:
SpringMVC是使用了MVC设计思想的轻量级web框架，对web层进行解耦，使我们的开发更简洁。

3.Mybatis的优势:

数据库的操作(sql)采用xml文件配置，解除了sql和代码的耦合，提供映射标签，支持对象和和数据库orm字段关系的映射，支持对象关系映射标签，支持对象关系的组建提供了xml标签，支持动态的sql。

## 2.3 MyEclipse开发环境
MyEclipse支持广泛、兼容性高并且功能强大，是一个Eclipse 插件集合，普遍适应于JAVA和J2EE的系统开发，支持 JDBC，Hibernate，AJAX，Struts，Java Servlet，Spring，EJB3等市面上存在的几乎所有数据库链接工具和主流Eclipse产品 开发工具。 

MyEclipse在业内是所熟知的开发工具，该平台在开发的过程中运用的就是该工具。MyEclipse又被称之为学生级的工作平台，它是以Eclipse IDE为基础的。MyEclipse可以帮助我们进行数据库的研发和J2EE的使用，除此之外，还可以提高系统的运营能力，这突出表现在服务器的整合过程中。MyEclipse的功能相当完备，能够为J2EE的集成提供必要的环境支持，从而完成编码、测试、调试及发布等功能。它可以支持Java，HTML，SQL，Javascript，Struts， CSS等。
## 2.4 Tomcat服务器
Tomcat属于一种轻型的服务器，所以说在中小学生中并不具有普适性。但是当程序员需要开发或调试Java 程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML 页面进行访问。Tomcat 虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML 页面的运行提供技术支持，Tomcat 的任务则是运行Servle和Java 页面。Tomca也具有一定的HTML页面处理功能。
## 2.5 MySQL数据库
Mysql的语言是非结构化的，学生可以在数据上进行工作。MySQL因为其速度、可靠性和适应性而备受关注。大多数人都认为在不需要[事务](https://baike.baidu.com/item/%E4%BA%8B%E5%8A%A1)化处理的情况下，MySQL是管理内容最好的选择。并且因为Mysql的语言和结构比较简单，但是功能和存储信息量很强大，所以得到了普遍的应用。

Mysql数据库在编程过程中的作用是很广泛的，为学生进行数据查询带来了方便。Mysql数据库的应用因其灵活性强，功能强大，所以在实现某功能时只需要一小段代码，而不像其他程序需要编写大段代码。总体来说，Mysql数据库的语言相对要简洁很多。 

数据流程分析主要就是数据存储的储藏室，它是在计算机上进行的，而不是现实中的储藏室。数据的存放是按固定格式，而不是无序的，其定义就是：长期有固定格式，可以共享的存储在计算机存储器上。数据库管理主要是数据存储、修改和增加以及数据表的建立。为了保证系统数据的正常运行，一些有能力的处理者可以进行管理而不需要专业的人来处理。数据表的建立，可以对数据表中的数据进行调整，数据的重新组合及重新构造，保证数据的安全性。介于数据库的功能强大等特点，本系统的开发主要应用了Mysql进行对数据的管理。
# 第3章 系统分析
## 3.1 需求分析
学生宿舍管理系统主要是为了学生方便对交流论坛、通知公告、在线沟通等信息进行查看，也是为了更好的让管理员进行更好存储所有数据信息及快速方便的检索功能，对系统的各个模块是通过许多今天的发达系统做出合理的分析来确定考虑学生的可操作性，遵循开发的系统优化的原则，经过全面的调查和研究。

系统所要实现的功能分析，对于现在网络方便的管理，系统要实现学生可以直接在平台上根据自己的需求可以进行查询信息等，这样既能节省学生的时间，不用在像传统的方式，需要查询、由于很多学生的时间的原因，真的很难去满足学生的各种需求。所以学生宿舍管理系统 的开发不仅仅是能满足学生的需求，还能提高管理员的工作效率，减少原有不必要的工作量。

任何一个项目在开发研究前，都需要对研发系统本身的需求做一个认真的分析，市场的调研是不可忽视的，从实际场景中确定使用人员的功能需求，从而明确目标，对整个系统的开发有一个更加准确的定位。在这个章节，需要对系统的性能分析，业务流程分析，和数据等进行分析，学生宿舍管理系统的整体界面简单，功能完善。

## 3.2 系统可行性分析
### 3.2.1技术可行性：技术背景     
本网站在Windows操作系统中进行开发，并且目前PC机的性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用SSM开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得网站运行更具有稳定性和安全性，从而完成实现网站的开发。

（1）硬件可行性分析

系统管理及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开网站必须顺畅，不能停顿太长时间；性价比高；安全性高。

（2）软件可行性分析

开发整个系统使用的是云计算，流量的可扩展性和基于流量的智能调整云计算的优点就是流量的可扩展性和基于流量的智能调整，保障系统的安全和数据信息的及时备份。

因此，我们从两个方面进行了可行性研究，可以看出系统的开发没有问题。
### 3.2.2经济可行性
在学生宿舍管理系统开发之前所做的市场调研及其他相关的管理系统，都是没有任何费用的，都是通过开发者自己的努力，所有工作都是自己亲力亲为，在碰到自己比较难以解决的问题，大多是通过同学和指导老师的帮助进行相关信息的解决，所以对于学生宿舍管理系统的开发在经济上是完全可行的，没有任何费用支出的。

使用比较成熟的技术，系统是基于SSM框架的开发，采用Mysql数据库。所以系统在开发人力、财力要求不高，具有经济可行性。
### 3.2.3操作可行性： 
可操作性主要是对学生宿舍管理系统 设计完成后，学生的使用体验度，以及管理员可以通过系统随时管理相关的数据信息，并且对于管理员、学生二个权限角色，都可以简单明了的进入到自己的系统界面，通过界面导航菜单可以简单明了地操作功能模块，方便学生信息的操作需求和管理员管理数据信息，对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以在系统的可操作性是完全可以的。本系统的操作过程使用的也是界面窗口进行登录，所以操作人员只要会简单的电脑操作就完全可以的。
## 3.3 项目设计目标与原则
1、关于学生宿舍管理系统的基本要求

（1）功能要求：可以管理首页、个人中心、宿舍信息管理、学生管理、宿舍报修管理、访客信息管理、水电费管理、管理员管理、交流论坛、系统管理等功能模块。

（2）性能：在不同操作系统上均能无差错实现在不同类型的学生登入相应界面后能不出差错、方便地进行预期操作。

（3）安全与保密要求：学生都必须通过注册、登录才能进入系统。

（4）环境要求：支持Windows系列、Vista系统等多种操作系统使用。

2、开发目标

学生宿舍管理系统的主要开发目标如下：

（1）实现管理系统信息关系的系统化、规范化和自动化；

（2）减少维护人员的工作量以及实现学生对信息的控制和管理；

（3）方便查询信息及管理信息等；

（4）通过网络操作，提高改善处理问题和操作人学生作的效率；

（5）考虑到学生多样性特点，要求界面和操作简便易懂。

3、设计原则

本学生宿舍管理系统采用SSM框架，Mysql数据库开发，充分保证了系统稳定性、完整性。 

学生宿舍管理系统的设计与实现的设计思想如下： 

1. 操作简单方便、系统界面安全良好、简单明了的页面布局、方便查询管理相关信息。

2、即时可见：对学生宿舍管理系统信息的处理将立马在对应地点可以查询到，从而实现“即时发布、即时见效”的系统功能。 

## 3.4系统流程分析
### 3.4.1操作流程
系统登录流程图，如图所示：

![](/md/blog.001.png)

图3-1登录流程图
### 3.4.2添加信息流程
添加信息流程图，如图所示：

![](/md/blog.002.png) 

图3-2添加信息流程图

### 3.4.3删除信息流程
删除信息流程图，如图所示：

![](/md/blog.003.png)

图3-3删除信息流程图



# 第4章 系统设计
## 4.1 系统体系结构
学生宿舍管理系统的结构图4-1所示：

网

络

管理员

服务器和程序

学生

![](/md/blog.004.png)

图4-1 系统结构

登录系统结构图，如图4-2所示：

Y

学生宿舍管理系统登录界面

用户登录

密码正确

管理员界面

学生界面

![](/md/blog.005.png)

图4-2 登录结构图

系统结构图，如图4-3所示。

![](/md/blog.006.png)

图4-3 系统结构图
## 4.2开发流程设计
系统流程的分析是通过调查系统所涉及问题的识别、可行性、可操作性、系统分析处理能力等具体环节来调节、整理系统的设计方案以确保系统能达到理想的状态。这些操作都要从注册、登录处着眼进行一系列的流程测试保证数据库的完整，从而把控系统所涉及信息管理的安全、保证信息输入、输出正常转换。然后，通过实际操作完成流程图的绘制工作。

学生宿舍管理系统 的开发对管理模块和系统使用的数据库进行分析，编写代码，系统测试，如图4-4所示。

![](/md/blog.007.png)

图4-4开发系统流程图
## 4.3 数据库设计原则
学习编程，我们都知道数据库设计是基于需要设计的系统功能，我们需要建立一个数据库关系模型，用于存储数据信息，这样当我们在程序中时，就没有必要为程序页面添加数据，从而提高系统的效率。数据库存储了很多信息，可以说是信息管理系统的核心和基础，数据库还为系统提供了添加、删除、修改和检查等操作模块，使系统能够快速找到自己想要的信息，而不是在程序代码中找到。数据库中信息表的每个部分根据一定的关系精确地组合，排列和组合成数据表。 

通过学生宿舍管理系统 的功能进行规划分成几个实体信息，实体信息将通过ER图进行说明，本系统的主要实体图如下：

管理员信息属性图如图4-5所示。

![](/md/blog.008.png)

图4-5 管理员信息实体属性图

宿舍信息实体属性图如图4-6所示。

![](/md/blog.009.png)

图4-6宿舍信息实体属性图

访客信息实体属性图如图4-7所示。

![](/md/blog.010.png)

图4-7访客信息实体属性图

宿舍报修信息实体属性图如图4-8所示。

![](/md/blog.011.png)

图4-8宿舍报修信息实体属性图

## 4.4 数据表
将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表名：fangkexinxi

功能：访客信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|fangkexingming|varchar|200|访客姓名|||
|dianhua|varchar|200|电话|||
|sushehao|varchar|200|宿舍号|||
|daofangyuanyin|varchar|200|到访原因|||
|laifangshijian|varchar|200|来访时间|||
|likaishijian|varchar|200|离开时间|||
|beizhu|varchar|200|备注|||




表名：shuidianfei

功能：水电费

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushehao|varchar|200|宿舍号|||
|yuefen|varchar|200|月份|||
|shoufeileixing|varchar|200|收费类型|||
|jine|date||金额|||




表名：sushebaoxiu

功能：宿舍报修

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|sushehao|varchar|200|宿舍号|||
|baoxiuwupin|varchar|200|报修物品|||
|baoxiuneirong|datetime||报修内容|||
|tupian|varchar|200|图片|||
|baoxiushijian|varchar|200|报修时间|||
|sfsh|varchar|200|是否审核|||
|shhf|varchar|200|审核回复|||




表名：sushexinxi

功能：宿舍信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushehao|varchar|200|宿舍号|||
|susheleixing|varchar|200|宿舍类型|||
|weizhi|varchar|200|位置|||
|kezhurenshu|varchar|200|可住人数|||
|yizhurenshu|varchar|200|已住人数|||
|beizhu|varchar|200|备注|||




表名：users

功能：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp|100|新增时间||CURRENT\_TIMESTAMP|




表名：xuesheng

功能：学生

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xuehao|varchar|200|学号|||
|mima|longtext|4294967295|密码|||
|xingming|date||姓名|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|xueyuan|varchar|200|学院|||
|zhuanye|varchar|200|专业|||
|dianhua|varchar|200|电话|||
|youxiang|varchar|200|邮箱|||
|shenfenzheng|varchar|200|身份证|||
|sushehao|varchar|200|宿舍号|||




表名：token

功能：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|




5. # 系统详细设计



## 5.1管理员功能模块
管理员登录，通过填写用户名、密码、角色等信息，输入完成后选择登录即可进入学生宿舍管理系统 ，如图5-1所示。

![](/md/blog.012.png)

图5-1管理员登录界面图

管理员登录进入学生宿舍管理系统可以查看首页、个人中心、宿舍信息管理、学生管理、宿舍报修管理、访客信息管理、水电费管理、管理员管理、交流论坛、系统管理等内容，如图5-2所示。	 

![](/md/blog.013.png)

图5-2管理员功能界面图

学生管理，在学生管理页面可以填写学号、密码、姓名、性别、年龄、学院、专业、电话、邮箱、身份证、宿舍号等信息，并可根据需要对学生管理进行详情，修改，删除操作，如图5-3所示。

![](/md/blog.014.png)

图5-3学生管理界面图

宿舍报修管理，在宿舍报修管理页面可以查看学号、姓名、宿舍号、报修物品、报修内容、图片、报修时间、审核回复、审核状态、审核等信息，并可根据需要对宿舍报修管理进行详情，修改、删除或查看详细内容等操作，如图5-4所示。

![](/md/blog.015.png)

图5-4宿舍报修管理界面图

访客信息管理，在访客信息管理页面可以查看访客姓名、电话、宿舍号、到访原因、来访时间、离开时间、备注等信息，并可根据需要对访客信息管理进行详情，修改、删除或查看详细内容操作，如图5-5所示。![](/md/blog.016.png) 

图5-5访客信息管理界面图

水电费管理，在水电费管理页面可以查看宿舍号、月份、收费类型、金额等内容，并可根据需要对水电费管理进行查看详情，修改，删除或查看详细内容等操作，如图5-6所示。![](/md/blog.017.png) 

图5-6水电费管理界面图

管理员管理，在管理员管理页面可以查看用户名、密码、角色等信息，并可根据需要对管理员管理进行详情，修改、删除或查看详细内容等操作，如图5-7所示。

![](/md/blog.018.png)

图5-7管理员管理界面图

交流论坛，在交流论坛页面可以查看帖子标题、用户名、状态等信息，并可根据需要对交流论坛进行详情，修改、删除或查看详细内容等操作，如图5-8所示。

![](/md/blog.019.png)

图5-8交流论坛界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图5-9所示。

![](/md/blog.020.png)

图5-9轮播图管理界面图

通知公告，在通知公告页面可以查看标题、简介、图片等信息，并可根据需要对通知公告进行详情，修改、删除或查看详细内容等操作，如图5-10所示。

![](/md/blog.021.png)

图5-10通知公告界面图




## 5.2学生功能模块 
学生登录，学生通过填写用户名、密码、角色等信息，输入完成后选择登录即可进入学生宿舍管理系统 ，如图5-11所示。

![](/md/blog.022.png)

图5-11学生登录界面图

学生登录进入学生宿舍管理系统可以查看首页、个人中心、宿舍报修管理、水电费管理等内容，如图5-12所示。

![](/md/blog.023.png)

图5-12学生功能界面图

宿舍报修管理，在宿舍报修管理页面可以查看学号、姓名、宿舍号、报修物品、报修内容、图片、报修时间、审核回复、审核状态、审核等详细信息进行详情、修改、删除，如图5-13所示。

![](/md/blog.024.png)

图5-13宿舍报修管理界面图

水电费管理，在水电费管理页面可以查看宿舍号、月份、收费类型、金额等信息，并可根据需要对水电费管理进行删除或查看详细内容等操作，如图5-14所示。

![](/md/blog.025.png)

图5-14水电费管理界面图

5.3前台首页功能模块

学生宿舍管理系统 ，在系统首页可以查看首页、交流论坛、通知公告、个人中心、后台管理、在线沟通等内容，如图5-15所示。

![](/md/blog.026.png)

图5-15系统功能界面图



`    `学生登录，在登录页面可以填写账号、密码等信息进行登录，如图5-16所示。

![](/md/blog.027.png)


图5-16学生登录界面图

交流论坛，在交流论坛页面通过填写标题、类型、内容等信息进行提交，如图5-17所示。在个人中心页面通过填写学号、密码、姓名、性别、年龄、学院、专业、电话、邮箱、身份证、宿舍号等信息进行更新信息、退出登录操作，如图5-18所示。

![](/md/blog.028.png)

图5-17交流论坛界面图

![](/md/blog.029.png)

图5-18个人中心界面图





# 










