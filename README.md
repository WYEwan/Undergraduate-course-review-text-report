# Undergraduate-course-review-text-report
# 本科课程复习文本报告

This project provides non-programming content from my undergraduate studies, such as course reports and course notes.
本项目提供了我在本科学习期间的一些非编程内容，例如课程报告和课程笔记。

# Back to the top of the page
# 返回页面顶部

# Table of Contents
# 目录

### English Table of Contents
- [Back to the top of the page](#back-to-the-top-of-the-page)
- [1. "AGB Time Series Analysis Paper Interpretation.pdf"](#1-agb-time-series-analysis-paper-interpretationpdf)
- [2. "AIoT—The Internet of Things in the Age of AI.pdf"](#2-aiotthe-internet-of-things-in-the-age-of-aipdf)
- [3. "GPS Positioning Experiment.pdf"](#3-gps-positioning-experimentpdf)
- [4. "QGIS Source Code Analysis.pdf"](#4-qgis-source-code-analysispdf)
- [5. "WiFi and Bluetooth Positioning Experiment.pdf"](#5-wifi-and-bluetooth-positioning-experimentpdf)
- [6. “A Small Case Study of Spatial Analysis.pdf”](#6-a-small-case-study-of-spatial-analysispdf)
- [7. "A Small Spatial Analysis Case: Spatial Autocorrelation.pdf"](#7-a-small-spatial-analysis-case-spatial-autocorrelationpdf)
- [8. "Different Interchange Structures.pdf"](#8-different-interchange-structurespdf)
- [9. “Research on the Resilience of China's Urban Economies.pdf”](#9-research-on-the-resilience-of-chinas-urban-economiespdf)
- [10. “Shared Bike Data Analysis.pdf”](#10-shared-bike-data-analysispdf)
- [11. “Cartography Review.pdf”](#11-cartography-reviewpdf)
- [12. "Urban Traffic System Traffic Flow Observation Report.pdf"](#12-urban-traffic-system-traffic-flow-observation-reportpdf)
- [13. "Resident Travel OD Calculation.pdf"](#13-resident-travel-od-calculationpdf)
- [14. "Filter Operator Implementation and Comparison.pdf"](#14-"filter-operator-implementation-and-comparisonpdf")

### 中文目录
- [返回页面顶部](#返回页面顶部)
- [1. "AGB时序分析论文解读.pdf"](#1-agb时序分析论文解读pdf)
- [2. "AIoT——AI 时代下的物联网.pdf"](#2-aiotai-时代下的物联网pdf)
- [3. "GPS定位实验.pdf"](#3-gps定位实验pdf)
- [4. "QGIS源代码解读.pdf"](#4-qgis源代码解读pdf)
- [5. "WIFI和蓝牙定位实验.pdf"](#5-wifi和蓝牙定位实验pdf)
- [6. “一个小的空间分析案例.pdf”](#6-一个小的空间分析案例pdf)
- [7. “一个小的空间分析案例：空间自相关.pdf”](#7-一个小的空间分析案例空间自相关pdf)
- [8. "不同的立交结构.pdf"](#8-不同的立交结构pdf)
- [9. “中国城市经济韧性研究.pdf”](#9-中国城市经济韧性研究pdf)
- [10. “共享单车数据分析.pdf”](#10-共享单车数据分析pdf)
- [11. “地图学综述.pdf”](#11-地图学综述pdf)
- [12. “城市交通系统交通流观察报告.pdf”](#12-城市交通系统交通流观察报告pdf)
- [13. “居民出行OD计算.pdf”](#13-居民出行OD计算pdf)
- [14. “滤波算子的实现和对比.pdf”](#14-滤波算子的实现和对比pdf)

# 1. "AGB Time Series Analysis Paper Interpretation.pdf"
# 1. "AGB时序分析论文解读.pdf"
This paper takes the English article titled "Inter- and intra-year forest change detection and monitoring of aboveground biomass dynamics using Sentinel-2 and Landsat" as its research subject, focusing on analyzing temporal forest changes and aboveground biomass dynamics.
本文以英文论文《Inter- and intra-year forest change detection and monitoring of aboveground biomass dynamics using Sentinel-2 and Landsat》为研究对象，围绕森林时间变化及地上生物量动态展开分析。

The authors include Flavy Pelletier, Jeffrey A. Cardille, etc., affiliated with the Department of Natural Resource Sciences at McGill University and the Canadian Forest Service of Natural Resources Canada (Pacific Forestry Centre). The core of the paper is the development of the "Tracking Intra- and Inter-annual Changes (TIIC)" algorithm, which utilizes Landsat and Sentinel-2 satellite data to achieve near real-time monitoring of forest changes across Canadian forest ecozones. It can detect forest cover changes and attribute them to disturbance types such as wildfires or mechanical harvesting. Additionally, by integrating forest biomass maps, it quantifies the aboveground biomass (AGB) dynamics in 2019. The results show that despite disturbances, Canadian forests achieved an annual AGB increase of 2.54%.
论文作者包括弗拉维・佩莱蒂埃、杰弗里・A・卡迪尔等，分别来自麦吉尔大学自然资源科学系和加拿大自然资源部加拿大森林服务局（太平洋林业中心）。其核心是开发了 “跟踪年内和年际变化（TIIC）” 算法，利用 Landsat 和 Sentinel-2 卫星数据，实现对加拿大森林生态区森林变化的近实时监测，能检测森林覆盖变化并归因于野火或机械采伐等干扰类型，还结合森林生物量地图量化了 2019 年地上生物量（AGB）动态变化，结果显示尽管存在干扰，加拿大森林 AGB 仍实现 2.54% 的年增长。

In terms of data and methodology, the study covers twelve forest-dominated ecozones in Canada, using surface reflectance data from Landsat-8 and Sentinel-2A/B, as well as aboveground biomass data, land cover data, etc. The analysis is conducted through steps such as assembling image collections, change detection, and change type classification using the TIIC algorithm, followed by accuracy assessment. The research results present the forest changes in Canada in 2019 and the dynamics of AGB, discussing aspects such as data fusion and near real-time monitoring capabilities. Finally, conclusions and limitations of the TIIC algorithm in forest change monitoring are drawn.Furthermore, the paper also compiles similar studies, offering understanding, critique, and outlook on the topic. It highlights the research significance, core ideas, and techniques, analyzes issues such as the simplification of growth increment estimation, and provides prospects for future research directions.
在数据与方法上，研究覆盖加拿大十二个森林主导生态区，使用了 Landsat-8、Sentinel-2A/B 的表层反射率数据，以及地上生物量数据、地表覆盖数据等，通过 TIIC 算法的组装图像集合、变化检测、变化类型划分等步骤进行分析，并开展了精度评估。研究结果呈现了 2019 年加拿大森林变化情况、AGB 动态变化等内容，讨论了数据融合与近实时监测能力等方面，最后得出 TIIC 算法在森林变化监测等方面的结论及局限性。此外，文章还整理了相似研究，提出了对该选题的理解、批判与展望，指出研究意义、核心思路与技术，分析了研究存在的生长增量估计简化等问题，并对未来研究方向进行了展望。

Through conducting this study, I have gained a comprehensive and in-depth understanding of the fields of forest change monitoring and aboveground biomass dynamics. In terms of professional knowledge, I became familiar with the application of satellite data such as Landsat and Sentinel-2 in forest monitoring, mastered the principles and processes of change detection algorithms like TIIC, and learned about related methods and techniques for estimating aboveground biomass.
通过开展这项研究，我对森林变化监测及地上生物量动态领域有了全面且深入的认识。在专业知识方面，熟悉了 Landsat 和 Sentinel-2 等卫星数据在森林监测中的应用，掌握了 TIIC 等变化检测算法的原理与流程，了解了地上生物量估算的相关方法和技术。

In terms of research capability, I improved my ability to analyze and summarize literature, learning how to sort out key content such as research background, data methods, and result conclusions. At the same time, through understanding, critiquing, and looking ahead to the topic, I developed critical thinking and innovative awareness, enabling me to examine the strengths and weaknesses of the research from different perspectives and consider future research directions.
在研究能力上，提升了对文献的分析和总结能力，学会了如何梳理研究背景、数据方法、结果结论等关键内容。同时，通过对选题进行理解、批判与展望，培养了批判性思维和创新意识，能够从不同角度审视研究的优缺点，并思考未来的研究方向。

Moreover, this study also made me realize the importance of technologies such as multi-source data fusion and near real-time monitoring in ecological and environmental research, laying a solid foundation for future research or work in related fields.
此外，这项研究也让我认识到多源数据融合、近实时监测等技术在生态环境研究中的重要性，为今后从事相关领域的研究或工作奠定了坚实的基础。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 2. “AIoT—The Internet of Things in the Age of AI.pdf”
# 2. “AIoT——AI 时代下的物联网.pdf”

This article focuses on the concept of AIoT (Artificial Intelligence of Things), exploring the development and transformation of the Internet of Things (IoT) in the era of artificial intelligence.
本文聚焦于 AIoT（人工智能物联网）这一概念，探讨了在 AI 时代下物联网的发展与变革。

The article first introduces the rise of AI, the development history of IoT, and the concept of AIoT. AI originated in 1956, and after several ups and downs, it has flourished in the era of large models, profoundly changing people's lives. The concept of IoT was proposed in 1999. Although it has developed steadily, it faces challenges such as security, cost efficiency, and others. AIoT is the product of the integration of AI and IoT, with IoT as the network foundation and AI as the technical support, and it does not have a specific time or event of proposal.
文章首先介绍了 AI 的兴盛、物联网的发展历程以及 AIoT 的概念。AI 起源于 1956 年，历经多次起伏后，在大模型时代迎来蓬勃发展，深刻改变人们生活；物联网概念于 1999 年提出，虽发展稳定但面临安全性、成本效率等挑战；而 AIoT 是 AI 与物联网融合的产物，以 IoT 为网络基础，以 AI 为技术支持，并无明确的提出时间和事件。

Next, the article analyzes the upgrade of the AIoT architecture from the perspectives of edge, fog, and cloud. Intelligent edge, based on the perception layer, achieves data compactification and autonomous operations through lightweight AI algorithms. Intelligent fog corresponds to the upgrade of the network layer, using AI to cope with complex architectures and dual pressures, assisting in decision-making and security maintenance. Intelligent cloud further decentralizes on the basis of the traditional application layer, retaining advantages such as elastic scheduling, and also requires AI assistance to complete resource allocation and anomaly handling. In the future, the three will move towards integrated development, promoting the transformation of IoT architecture from original data transmission and centralized control to AI-processed streamlined data and distributed intelligent control.
接着，文章从边缘、雾和云的角度解析了 AIoT 架构的升级。智能边缘在感知层基础上，通过轻量级 AI 算法实现数据紧凑化处理和自主化操作；智能雾对应网络层升级，借助 AI 应对复杂架构和双重压力，辅助决策与安全维护；智能云在传统应用层基础上进一步去中心化，保留弹性调度等优势，还需 AI 辅助完成资源调配和异常处理。未来，三者将走向融合发展，推动物联网架构从原始数据传输、中心化控制向 AI 处理精简数据、分布式智能控制转变。

Then, the article discusses the applications of traditional AI and the new XAI in IoT. Traditional AI covers various methods such as fully supervised learning and unsupervised learning, and is widely used in IoT but has problems like the "black box issue" and hyperparameter tuning. XAI (Explainable Artificial Intelligence) can solve these limitations, help quantify model correctness, and has begun to be applied in multiple IoT fields.
然后，文章探讨了传统 AI 和新型 XAI 在物联网中的应用。传统 AI 涵盖全监督学习、无监督学习等多种方法，在物联网中应用广泛但存在 “黑匣子问题” 和超参数调节问题；XAI（可解释人工智能）能解决这些局限，有助于量化模型正确性等，已开始在多个物联网领域应用。

In addition, the article also introduces important research examples of AIoT, such as using machine learning for IoT anomaly attack detection, utilizing autonomous computing for automatic updates of IoT systems, and employing federated learning for distributed AI updates in IoT systems.
此外，文章还介绍了 AIoT 的重要研究实例，如使用机器学习进行物联网异常攻击检测、利用自主计算实现物联网系统自动更新、利用联邦学习实现物联网系统分布式 AI 更新等。

Finally, the article analyzes the future of AIoT, pointing out its transformation in IoT architecture innovation and AI technology advancement, while also facing challenges such as imperfect XAI models, insufficient hardware performance, and data security and privacy. However, it also brings opportunities for digital transformation in multiple industries.
最后，文章分析了 AIoT 的未来，指出其在物联网架构创新和 AI 技术进步上的变革，同时面临 XAI 模型不完善、硬件性能不足、数据安全隐私等挑战，但也为多个行业带来数字化转型机遇。

Through the study of this article, I have gained a comprehensive and in-depth understanding of AIoT. At the knowledge level, I systematically learned about the development history of AI and IoT, clarified the concept and architecture upgrade of AIoT, as well as the applications of related AI technologies in IoT, and mastered the characteristics and development trends of key technologies such as edge computing, fog computing, and cloud computing.
通过对这篇文章的研究，我对 AIoT 有了全面且深入的认识。在知识层面，系统了解了 AI 和物联网的发展历程，明晰了 AIoT 的概念、架构升级以及相关 AI 技术在物联网中的应用，掌握了边缘计算、雾计算、云计算等关键技术的特点和发展趋势。

In terms of capability improvement, I have developed the ability to sort out and analyze complex technical concepts, and learned to examine the current status and future direction of technology development from multiple perspectives. At the same time, by studying the challenges and opportunities faced by AIoT, I have enhanced my forward-looking thinking on technology development, and realized the importance of interdisciplinary collaboration and industry cooperation in promoting technological progress.
在能力提升方面，培养了对复杂技术概念的梳理和分析能力，学会了从多个角度审视技术的发展现状与未来方向。同时，通过研究 AIoT 面临的挑战与机遇，增强了对技术发展的前瞻性思考，认识到跨学科合作和行业协作在推动技术进步中的重要性。

This study has also made me deeply appreciate the great potential of the integration of AI and IoT, laying a solid foundation for future learning and practice in related fields, and inspiring my interest in exploring the application and innovation of AIoT technology.
此次研究也让我深刻体会到 AI 与物联网融合的巨大潜力，为今后在相关领域的学习和实践奠定了坚实基础，激发了对 AIoT 技术应用和创新的探索兴趣。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 3. "GPS Positioning Experiment.pdf"
# 3. "GPS定位实验.pdf"

This article is a report on the GPS positioning experiment, completed by a group consisting of Wang Yi, Luo Huiming, and Zhang Heng. It mainly focuses on GPS data collection, analysis, and error exploration.
本文是关于 GPS 定位实验的报告，由王逸、罗慧铭、张恒组成的小组完成，主要围绕 GPS 数据采集、分析及误差探究展开。

The objectives and requirements of the experiment are clearly defined. It requires using an Android app to collect GPS data and perform analysis. The report is to be completed in groups, with the requirement of collecting data from more than 4 different routes (covering two or more modes of transportation). After exporting the data, the GPS trajectory should be displayed in relevant software and screenshots should be taken. The positioning accuracy, error conditions, and their causes should be analyzed in conjunction with maps. Additionally, the average speed should be calculated in units of every 10 seconds, and a speed variation curve should be plotted.
实验目的与要求明确，需使用 Android app 采集 GPS 数据并进行分析，分组完成报告，要求采集 4 条以上不同路线（覆盖两种及以上交通方式），导出数据后在相关软件中显示 GPS 轨迹并截图，结合地图分析定位精度、误差情况及原因，且按每 10 秒为单位计算平均速度并绘制速度变化曲线。

In terms of experimental methods, the hardware used includes the Oppo Find X5 Pro, iPhone 13 Pro, and Honor 70 smartphones. The software includes Phyphox, MATLAB, ArcGIS 10.8.1, etc. References include "Principles of Surveying," course materials on navigation and positioning technology, and some online resources. The process methodology adopts the "Review-Practice-Compare-Learn-Analyze" model. The analysis method starts from two aspects: errors related to satellite signal propagation and errors related to satellite signal receivers, combined with satellite quantity distribution maps, trajectory multi-ring buffer analysis maps, and speed variation curve maps for analysis.
实验方法方面，硬件采用 oppo findx5pro、iphone13pro、荣耀 70 手机，软件包括 phyphox、matlab、ArcGIS10.8.1 等；参考了《测量学原理》、导航与定位技术课程资料及部分网络资料；过程方法采用 “审 - 践 - 比 - 学 - 析” 模式；分析方法从与卫星信号传播、卫星信号接收机有关的误差两方面入手，结合卫星数量分布图、轨迹多环形缓冲区分析图及速度变化曲线图进行分析。

In the experimental process and analysis section, the possible causes of errors are summarized, mainly divided into three categories: errors related to satellites, errors related to satellite signal propagation, and errors related to satellite signal receivers. It introduces the transportation modes (bicycle, walking, taxi) of the six routes and their corresponding speed variation curve maps. Based on the causes of errors, a detailed analysis is conducted on the impact of clouds, trees, buildings, etc., on signal propagation in each route, as well as the errors brought about by device status, performance and accuracy, and measurement software compatibility.
实验过程与分析部分，概括了误差产生的可能原因，主要分为与卫星有关、与卫星信号传播有关、与卫星信号接收机有关三类误差；介绍了 6 条路线的交通方式（自行车、步行、出租车）及对应的速度变化曲线图；并基于误差产生原因，详细分析了各路线中云层、树木、建筑物等对信号传播的影响，以及设备状态、性能与精度、测量软件匹配度等带来的误差。

The experimental summary points out the shortcomings of this experiment, such as the failure to obtain satellite quantity data for some routes and the insufficient quantification of error analysis. It also outlines the completion of the experiment, mentioning the overcoming of difficulties in transitioning from theory to practice, and the understanding of the practical applications of navigation and positioning technology, as well as the limitations of methods and technologies.
实验总结指出了本次实验存在的不足，如部分路线未获取卫星数量数据、误差分析量化程度不够等，同时概述了实验完成情况，提及克服了理论转实践的困难，体会到导航与定位技术的实际应用及方法和技术局限。

The appendix includes the source code used for data processing and plotting, as well as original and processed images.
附录包含了用于数据处理和绘图的源代码，以及原始图片和处理图片。

By participating in this GPS positioning experiment, I have grown in several aspects. At the knowledge level, I have gained a deeper understanding of the basic principles of GPS positioning, clarified the impact of factors such as satellites, signal propagation, and receivers on positioning accuracy, mastered the basic methods of GPS data collection, processing, and analysis, and became familiar with the use of related software such as Phyphox, MATLAB, and ArcGIS.
通过参与本次 GPS 定位实验，我在多个方面获得了成长。在知识层面，深入了解了 GPS 定位的基本原理，明确了卫星、信号传播、接收机等因素对定位精度的影响，掌握了 GPS 数据采集、处理及分析的基本方法，熟悉了 phyphox、matlab、ArcGIS 等相关软件的使用。

In terms of practical ability, I have improved my ability to apply theoretical knowledge to practical operations, learned to design experimental routes, collect effective data, and use various tools to analyze and visualize the data. In terms of problem-solving, facing issues such as data loss and difficulties in error analysis during the experiment, I have developed the ability to troubleshoot problems and find solutions.
在实践能力上，提升了将理论知识应用于实际操作的能力，学会了设计实验路线、采集有效数据，并运用多种工具对数据进行分析和可视化。在问题解决方面，面对实验中出现的数据缺失、误差分析困难等问题，培养了排查问题和寻找解决方案的能力。

At the same time, through group collaboration in completing the experiment, I have enhanced my teamwork awareness and communication skills. I have deeply realized the importance of rigor and attention to detail in the experimental process, and also recognized my own shortcomings in professional knowledge and technical means, which points out the direction for improvement in future learning and practice.
同时，通过小组合作完成实验，增强了团队协作意识和沟通能力，深刻认识到实验过程中严谨性和细节把控的重要性，也意识到自身在专业知识和技术手段上的不足，为今后的学习和实践指明了改进方向。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 4. "QGIS Source Code Analysis.pdf"
# 4. "QGIS源代码解读.pdf"

This article conducts an in-depth analysis of the QGIS underlying code, aiming to explore the implementation mechanisms of its core functionalities.
本文围绕 QGIS 底层代码展开深入分析，旨在探究其核心功能的实现机制。

The article first clarifies the assignment content, outline, and standards, including installing and deploying the open-source GIS platform QGIS, setting up a C++ environment to compile and run the platform, and understanding the QGIS source code. According to the experimental report outline, key core codes for various functionalities need to be located and filled into corresponding sections. The experimental report must cover seven items, including the Windows program Main function and message handling functions, the encapsulation of GDI drawing functions, and view and window transformation codes, with a requirement of no less than 15 pages and covering all outlined contents.
文章首先明确了作业内容、提纲及标准，包括安装部署开源 GIS 平台 QGIS，搭建 C++ 环境以实现平台的编译和运行，同时需要了解 QGIS 源代码，根据实验报告提纲寻找各项功能的关键核心代码并填入对应章节。实验报告需涵盖 Windows 程序 Main 函数及消息过程函数、GDI 绘图功能的封装、视图与窗口变换代码等七项内容，且有不少于 15 页、涵盖所有提纲内容等要求。

In the QGIS installation and deployment section, detailed steps are provided, including downloading OSGeo4W, installing the program, creating a new VS empty project, configuring the environment (adding header file directories, library directories, configuring the linker, adding debugging environment, defining preprocessors), and running debugging, ultimately successfully setting up the compilation environment.
在安装部署 QGIS 部分，详细介绍了下载 OSGeo4W、安装该程序、新建 vs 空项目、配置环境（添加头文件目录、库目录、配置连接器，添加调试环境、定义预处理器）以及运行调试等步骤，最终成功搭建编译环境。

For each core functionality code, the article analyzes them one by one: the Windows program Main function and message handling functions involve files such as main.cpp, qgisapp.cpp, and mainwin.cpp, including classes like QgsApplication and QgisApp, and related functions responsible for application initialization and main window implementation; GDI drawing functions are based on the QPainter class of the QT framework, implemented in files like qgsmaprenderercustompainterjob.cpp for map rendering operations; view and window transformation codes are located in files such as qgsprojectviewsettings.cpp and qgsmapcanvasutils.cpp, implementing various view transformations and window zooming, panning, and other functions; point, line, and polygon geometry classes are concentrated in the src/core/geometry folder, with related classes and functions defined in files like qgspoint.cpp, qgslinesegment.cpp, and qgspolygon.cpp; feature, symbol, layer, and map classes have corresponding files, implementing feature operations, symbol rendering, layer management, and map configuration functions; in spatial analysis functions, point and polygon relationship judgment functions are implemented in qgsgeometry.cpp, and polygon buffer algorithms are implemented in files like qgsalgorithmbuffer.cpp; the storage and retrieval of map data (GeoJSON format) are mainly handled through qgsjsonutils.cpp and qgsjsonutils.h files, with conversion processing using the external GDAL library.
对于各项核心功能代码，文章逐一分析：Windows 程序 Main 函数及消息过程函数涉及 main.cpp、qgisapp.cpp、mainwin.cpp 等文件，包含 QgsApplication 类、QgisApp 类等多个类和相关函数，负责应用程序初始化、主窗口实现等；GDI 绘图功能基于 QT 框架的 QPainter 类，在 qgsmaprenderercustompainterjob.cpp 等文件中实现地图渲染等操作；视图与窗口变换代码位于 qgsprojectviewsettings.cpp、qgsmapcanvasutils.cpp 等文件，实现视图的各种变换及窗口缩放、平移等功能；点、线、面几何类集中在 src/core/geometry 文件夹，分别通过 qgspoint.cpp、qgslinesegment.cpp、qgspolygon.cpp 等文件定义相关类和函数；要素、符号、图层、地图类各有对应文件，实现要素操作、符号渲染、图层管理、地图配置等功能；空间分析功能中，点与面关系判断函数在 qgsgeometry.cpp 中实现，面缓冲区算法在 qgsalgorithmbuffer.cpp 等文件中实现；地图数据（geojson 格式）的存取主要通过 qgsjsonutils.cpp 和 qgsjsonutils.h 文件，借助 gdal 外界库进行转换处理。

Through the analysis of the QGIS underlying code, my professional knowledge has significantly improved. I have gained a deep understanding of the architecture and core functionality implementation principles of QGIS, familiarized myself with the roles and locations of multiple key classes and functions, and mastered its development model based on the QT framework.
通过对 QGIS 底层代码的分析，我在专业知识上有了显著提升。深入理解了 QGIS 的架构和核心功能实现原理，熟悉了多个关键类和函数的作用及所在文件，掌握了其基于 QT 框架的开发模式。

In terms of practical skills, I have learned how to locate and analyze the source code of large open-source projects, enhancing my ability to interpret C++ code and understand the underlying mechanisms of GIS software. At the same time, completing various analysis tasks according to experimental requirements has cultivated rigorous logical thinking and systematic problem-solving abilities, laying a solid foundation for future software development and research in related fields.
在实践能力方面，学会了如何查找和分析大型开源项目的源代码，提升了对 C++ 代码的解读能力和对 GIS 软件底层机制的认知。同时，按照实验要求完成各项分析任务，培养了严谨的逻辑思维和系统分析问题的能力，为今后从事相关软件开发和研究奠定了坚实基础。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 5. "WiFi and Bluetooth Positioning Experiment.pdf"
# 5. "WIFI和蓝牙定位实验.pdf"

This article is a WiFi and Bluetooth positioning experiment report jointly completed by Wang Yi, Luo Huiming, and Zhang Heng, focusing on the research of WiFi and Bluetooth signal attenuation models and positioning performance.
本文是由王逸、罗慧铭、张恒共同完成的 WiFi 和蓝牙定位实验报告，围绕 WiFi 和蓝牙信号的衰减模型及定位性能展开研究。

The experimental objectives are clear: use an Android app to collect WiFi and Bluetooth iBeacon data, collect sampling points at certain intervals, design an indoor signal propagation model formula and calculate parameters, evaluate positioning errors, and compare the positioning parameters and performance of the two.
实验目的明确，需使用 Android app 采集 WiFi 和蓝牙 ibeacon 数据，间隔一定间距采集采样点，设计信号室内传播模型公式并计算参数，评估定位误差，对比两者的定位参数和性能。

The theoretical review section introduces Location-Based Services (LBS), points out various indoor positioning technologies and the advantages of WiFi positioning, explains positioning principles such as RSSI, TOA, and TDOA, and focuses on comparing WiFi and Bluetooth in terms of signal attenuation, navigation and positioning application characteristics, RSSI indicators, signal characteristics, positioning errors, and applicable scopes. It also mentions that the combined use of the two can improve positioning effectiveness.
理论综述部分介绍了基于位置的服务（LBS），指出室内定位技术的多种方式及 WiFi 定位的优势，阐述了 RSSI、TOA、TDOA 等定位原理，重点对比了 WiFi 和蓝牙在信号衰减、导航定位应用特点、RSSI 指标、信号特性、定位误差及适用范围等方面的差异，并提到两者融合使用可提升定位效果。

The experimental environment selected two locations: an indoor area (a unilaterally enclosed corridor) and an outdoor area (basically unobstructed on all sides) at Shenzhen University. It analyzed factors affecting signal strength in different environments and proposed multiple variables such as vertical height and horizontal distance. During data collection, nodes were set at different positions for cases with and without obstacles, and multiple mobile phones were used to receive signals. It also pointed out the difficulties in data collection (such as mobile phone compatibility and software refresh) and limitations (such as unknown transmission power and few data points).
实验环境选取了深圳大学室内（单侧封闭走廊）和室外（四周基本无遮挡）两处地点，分析了不同环境下影响信号强度的因素，拟定了垂直高度、水平距离等多个变量。数据采集过程中，对有无障碍的情况分别按不同位置设置节点，使用多部手机接收信号，同时指出了数据采集存在的难点（如手机兼容性、软件刷新等）和局限性（如发射功率未知、数据点少等）。

The loss model comparison and analysis included various models such as the free space dissipation model and the log-distance path dissipation model, ultimately selecting an improved log-distance path dissipation model. Data preprocessing involved analyzing reflection effects, multipath effects, and noise impacts, and using special methods for data filtering. Subsequently, initial data fitting and model construction verification were carried out, and the feasibility of the model was verified through classification processing and visual analysis.
损耗模型比对分析了自由耗散模型、对数距离路径耗散模型等多种模型，最终选用改进后的对数距离路径耗散模型。数据预处理通过分析反射效应、多径效应和噪声影响，采用特殊方法进行数据筛选。之后进行了数据初拟合和模型构建验证，通过分类处理和可视化分析验证了模型的可行性。

The model distribution construction and factor calculation section, based on the selected model formula, explained the parameter meanings, practical uses, and error and weighted calculation methods, and detailed the calculation process and final error analysis. The model fusion and system analysis constructed four target fusion model functions according to different scenarios, obtained corresponding n values through weighted fusion algorithms, and plotted fusion model curves.
模型的分布构建与因子计算部分，基于所选模型公式，解释了参数含义、实际用途及误差和加权计算方法，详细展示了计算过程和最终误差分析。模型融合和系统分析则按不同场景构建了四个目标融合模型函数，通过加权融合算法得出对应 n 值并绘制融合模型曲线。

The experimental summary pointed out the research results, while also mentioning the limitations of the experiment, such as the inability to obtain transmission and reception frequency data and insufficiently dense data points, and proposed directions for improvement.
实验总结指出了研究的成果，同时提及实验存在的局限性，如无法获取发射和接收频率数据、数据点不够密集等，并提出了改进方向。

Through participating in this WiFi and Bluetooth positioning experiment, I have significantly improved both in professional knowledge and practical ability. At the knowledge level, I gained a deep understanding of the basic principles of WiFi and Bluetooth positioning, became familiar with the application of RSSI indicators in positioning, mastered the characteristics and applicable scenarios of various signal attenuation models, especially the principles and calculation methods of the log-distance path dissipation model.
通过参与本次 WiFi 和蓝牙定位实验，我在专业知识和实践能力上均有显著提升。在知识层面，深入理解了 WiFi 和蓝牙定位的基本原理，熟悉了 RSSI 指标在定位中的应用，掌握了多种信号衰减模型的特点及适用场景，尤其是对数距离路径耗散模型的原理和计算方法。

In terms of practical ability, I learned to design experimental plans, including selecting experimental environments, determining variables, and collecting data, improved my ability to process and analyze experimental data, mastered methods such as data filtering, model fitting, and error analysis, and became proficient in using data visualization tools to assist analysis.
在实践能力方面，学会了设计实验方案，包括选取实验环境、确定变量、采集数据等环节，提升了对实验数据的处理和分析能力，掌握了数据筛选、模型拟合、误差分析等方法，同时熟练运用了数据可视化手段辅助分析。

In team collaboration, I enhanced communication and cooperation skills, and jointly solved various problems encountered in the experiment, such as device compatibility and data anomalies. Through this experiment, I also deeply realized the importance of rigorous experimental design and data quality, understood the limitations of existing experiments, provided ideas for future improvements and refinements in related research, and sparked further interest in exploring wireless positioning technologies.
团队协作中，增强了沟通与合作能力，共同解决了实验中遇到的各种问题，如设备兼容性、数据异常等。通过本次实验，也深刻认识到实验设计的严谨性和数据质量的重要性，了解了现有实验的局限性，为今后相关研究的改进和完善提供了思路，激发了对无线定位技术进一步探索的兴趣。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 6. “A Small Case Study of Spatial Analysis.pdf”
# 6. “一个小的空间分析案例.pdf”

This paper is an assignment on the spatial statistics and analysis of POIs (Points of Interest) in Shenzhen, exploring the distribution characteristics of POIs in Shenzhen through various spatial analysis methods.
本文是一篇关于深圳市 POI（兴趣点）的空间统计与分析作业，通过多种空间分析方法对深圳市 POI 的分布特征进行了探究。

Firstly, the article presents descriptive distribution maps of POIs, including the distribution map of POIs in Shenzhen's traffic zones, POI kernel density map, three-dimensional POI distribution map, and spatial trend map of POI distribution. These maps were created using tools such as ArcMap and ArcScene. The distribution and kernel density maps show the distribution of POI quantities in different traffic zones, the three-dimensional map intuitively displays the spatial differences in POI distribution, and the spatial trend map reflects the overall trend of POI distribution. The analysis found that the global distribution of POIs in Shenzhen is uneven, with concentrated areas corresponding to traffic zone concentrations. The southwest is a high-value area, the southeast is a low-value area, the north-south difference is smaller than the east-west difference, and the western region is densely distributed while the eastern region is sparse.
首先，文章展示了 POI 描述性分布图，包括深圳市交通小区 POI 分布图、POI 核密度图、POI 分布立体图和 POI 分布空间趋势图。这些图通过 ArcMap 和 ArcScene 等工具制作，其中分布图和核密度图呈现了不同交通小区 POI 数量的分布情况，立体图直观展示了 POI 分布的空间高低差异，空间趋势图则反映了 POI 分布的整体趋势。分析发现，深圳市 POI 全局分布不均衡，集中区与交通小区集中区对应，西南部为高峰区，东南部为低值区，南北差异小于东西差异，西部地区分布密集而东部稀疏。

Secondly, hotspot analysis and comprehensive analysis were conducted, generating a hotspot distribution map of POIs in Shenzhen's traffic zones and the results of a combined analysis of POI quantities. The hotspot analysis further verified the distribution characteristics of POIs, showing small clusters in the northwest and northeast, a medium cluster in the southwest, and a large cluster running north-south in the central-western area. The combined analysis utilized functions such as directional distribution, cluster and outlier analysis, and mean center, finding that the average center of POI density is relatively west of the geographical center. The standard deviation ellipse indicates that the main coverage area is in the west, and the cluster and outlier analysis reveals the distribution of high-value areas, low-value areas, and transition zones.
其次，进行了热点分析和综合分析，生成了深圳市交通小区 POI 热点分布图和 POI 数量组合式分析结果。热点分析进一步验证了 POI 分布特征，显示出西北、东北有小聚集区，西南有中等聚集区，中部偏西有连贯南北的大聚集区；组合式分析运用了方向分布、聚类和异常值分析、平均中心等功能，发现 POI 密度平均中心相对地理中心偏西，标准差椭圆表明主要覆盖区为西部，聚类和异常值分析则揭示了高值区、低值区及变化区的分布.

Then, different attributes of POIs were comprehensively analyzed, including statistical charts of POI attributes in various administrative regions, semivariogram cloud maps, covariance cloud maps, and normal QQ plots. The statistical charts show differences in the quantity and types of POIs across administrative regions, with Bao'an District and Longgang District having a larger number, and transportation facilities and other types dominating. The semivariogram and covariance cloud maps indicate significant spatial correlation in different traffic zones at short to medium scales, with correlation decreasing as distance increases. The normal QQ plot shows that the data as a whole differs significantly from the standard normal distribution and does not exhibit significant randomness.
然后，综合分析了 POI 的不同属性，包括各行政区 POI 点属性统计图、半变异函数云图、协方差云图和正态 QQ 图。统计图显示不同行政区 POI 数量和种类存在差异，宝安区和龙岗区数量较多，交通设施等类型占主导；半变异和协方差云图表明不同交通区在中短尺度上空间相关性显著，随距离增大相关性降低；正态 QQ 图显示数据整体与标准正态分布有较大区别，不具显著随机性。

Finally, the article also mentions other statistical results, such as the average nearest neighbor p-value indicating that the spatial randomness hypothesis can be rejected, the Pearson correlation test showing a high correlation between POI types and point coordinates, and statistical measures such as variance and standard deviation of locationx and locationy.
最后，文章还提及了其他统计量结果，如平均最邻近 p 值表明可拒绝空间随机性假设，Pearson 关系验证显示 POI 种类和点坐标相关度较高，以及 locationx 和 locationy 的方差、标准差等统计量。

By completing this spatial analysis case study, I have significantly improved my skills in spatial analysis methods and tool applications. At the knowledge level, I have mastered various spatial analysis methods such as descriptive analysis of POI distribution, hotspot analysis, cluster and outlier analysis, and understood concepts such as kernel density, standard deviation ellipse, and semivariogram and their roles in spatial analysis. I have clarified how these methods can be used to reveal the spatial distribution characteristics and patterns of geographical elements.
通过完成这个空间分析案例，我在空间分析方法和工具应用方面有了显著提升。在知识层面，掌握了 POI 分布的描述性分析、热点分析、聚类和异常值分析等多种空间分析方法，了解了核密度、标准差椭圆、半变异函数等概念及其在空间分析中的作用，明确了如何通过这些方法揭示地理要素的空间分布特征和规律。

In terms of tool usage, I have become proficient in using software such as ArcMap, ArcScene, and MATLAB for data processing, map creation, and statistical analysis. I have improved my operational ability with spatial analysis tools and learned how to select appropriate tools and methods based on research needs to process and analyze data.
在工具使用上，熟练运用了 ArcMap、ArcScene 和 matlab 等软件进行数据处理、地图制作和统计分析，提升了对空间分析工具的操作能力，学会了根据研究需求选择合适的工具和方法来处理和分析数据。

At the same time, through the analysis of POI distribution in Shenzhen, I have developed a spatial thinking perspective, improved my ability to interpret geographical data, and learned to extract effective information from charts and conduct reasonable analysis. This practice has also made me realize the importance of spatial analysis in fields such as urban planning and resource distribution research, laying a solid foundation for future related research and applications.
同时，通过对深圳市 POI 分布的分析，培养了从空间角度思考问题的思维，提高了对地理数据的解读能力，能够从图表中提取有效信息并进行合理分析。此次实践也让我认识到空间分析在城市规划、资源分布研究等领域的重要性，为今后开展相关研究和应用奠定了坚实基础。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 7. "A Small Spatial Analysis Case: Spatial Autocorrelation.pdf"
# 7. "一个小的空间分析案例：空间自相关.pdf"

This paper is an experiment and analysis assignment on spatial autocorrelation, taking the average income attribute values of traffic zones in Shenzhen as the research object, and delves into related issues in spatial autocorrelation analysis.
本文是一篇关于空间自相关的实验与分析作业，以深圳市交通小区的平均收入属性值为研究对象，深入探讨了空间自相关分析中的相关问题。

First, the role of the spatial weight matrix in spatial autocorrelation analysis was studied. From an overall macro perspective, the spatial weight matrix defines the adjacency relationships of spatial units and is an indispensable part of spatial autocorrelation analysis. It is used in various autocorrelation analyses for intermediate calculations to obtain autocorrelation coefficients and is also commonly used to construct spatial lag terms. From the formulas of Moran’s I and Getis-Ord G indicators, it can be seen that the values of the elements in the spatial matrix directly affect the absolute values of these indicators. In terms of empirical validation, experiments were designed to explore the impact of parameters and types of spatial weight matrices on spatial autocorrelation analysis. It was found that changes in the k value significantly affect Moran’s I and Geary’s C indicators. After k is greater than 15, the indicators tend to stabilize, and when the k value is small, the degree of spatial autocorrelation is high, while when the k value is large, it is low. Different types of spatial weight matrices (k-nearest neighbor weight adjacency matrix and distance adjacency matrix) also have a significant impact on the indicators, with the indicators changing more smoothly under the distance adjacency matrix.
首先，研究了空间权重矩阵在空间自相关分析中的作用。从总体宏观作用来看，空间权重矩阵定义了空间单位的相邻关系，是空间自相关分析必不可少的部分，在多种自相关分析中用于中间计算以得到自相关系数，还常用于构建空间滞后项等。通过 Moran’s I 指标和 Getis-Ord G 指标的公式可以看出，空间矩阵元素的值直接影响这些指标的绝对数值。实例验证方面，设计实验探究空间权重矩阵的参数和种类对空间自相关分析的作用，发现 k 值变化显著影响 Moran’s I 和 Geary’s C 指标，k 大于 15 后指标趋于稳定，且 k 值较小时空间自相关程度较高，k 值较大时则较低；不同种类的空间权重矩阵（k 近邻权重邻接矩阵和距离邻接矩阵）对指标影响也很大，距离邻接矩阵下的指标变化更平滑。

Second, the relationship between spatial distance and spatial autocorrelation coefficients was analyzed. In the case of a distance adjacency matrix, spatial autocorrelation indicators show a decreasing trend (Moran’s I) and an increasing trend (Geary’s C) as the distance threshold increases. This is because an increase in the distance threshold leads to more spatial randomness factors and a decrease in spatial autocorrelation. Pearson, Spearman, and Kendall coefficients were used to verify that this trend conforms to linear and rank trends. At the same time, extreme cases when the distance threshold is small were studied. It was found that Moran’s I has extreme values that are drastic and show no obvious pattern in this interval, while Geary’s C has relatively regular extreme values, and the reasons were speculated.
其次，分析了空间距离与空间自相关系数的关系。在距离邻接矩阵情形下，空间自相关指标随距离阈值增大呈现减少（Moran’s I）和增加（Geary’s C）的趋势，这是由于距离阈值增大使空间随机性因素增多，空间自相关性降低。通过 Pearson、Spearman 和 Kendall 系数验证，表明这种趋势符合线性和等级趋势。同时，研究了距离阈值较小时的极端情况，发现 Moran’s I 在该区间极端值剧烈且无明显规律，Geary’s C 的极端值相对有规律，并推测了原因.

Finally, an analysis of ordinary spatial clustering was conducted. Using ArcGIS spatial clustering research indicators to analyze the distribution of average income in Shenzhen traffic zones, it was found that for the Anselin Local Moran I indicator, there is little difference overall between using an ordinary distance matrix and a square inverse distance matrix, with the latter reducing the determined range of high-value and low-value areas. For the Getis-Ord Gi * indicator, the neighbor matrix is more suitable, as the ordinary distance matrix reduces its effective analysis range. High-value areas and high-value edge areas are concentrated in the south, while low-value areas and low-value edge areas are concentrated in the north and southeast.
最后，进行了普通空间聚集情况分析。使用 ArcGIS 的空间聚集研究指标对深圳交通小区平均收入分布进行分析，发现对于 Anselin Local Moran I 指标，采用普通距离矩阵和平方递减距离矩阵总体差别不大，后者使高值区和低值区确定范围减少；对于 Getis-Ord Gi * 指标，近邻矩阵更合适，普通距离矩阵会使其有效分析范围减小，且高值区和高值边缘区集中在南部，低值区和低值边缘区集中在北部和东南部。

Through this spatial autocorrelation experiment and analysis, I have gained a lot in both spatial analysis theory and practice. In terms of theoretical knowledge, I have deepened my understanding of the concept and role of the spatial weight matrix and its key position in spatial autocorrelation analysis. I have clarified the impact mechanisms of different types and parameters of spatial weight matrices on autocorrelation indicators and mastered the relationship between spatial distance and spatial autocorrelation coefficients.
通过本次空间自相关实验与分析，我在空间分析理论和实践方面都有不少收获。在理论知识上，深入理解了空间权重矩阵的概念、作用及其在空间自相关分析中的关键地位，明确了不同类型和参数的空间权重矩阵对自相关指标的影响机制，同时掌握了空间距离与空间自相关系数之间的关系规律。

In terms of practical skills, I have learned to use tools such as ArcGIS for spatial autocorrelation analysis, including selecting appropriate spatial weight matrices, calculating and interpreting indicators such as Moran’s I, Geary’s C, Anselin Local Moran I, and Getis-Ord Gi *, thereby enhancing my ability to process and analyze spatial data. By designing experiments to verify related hypotheses, I have cultivated experimental design and logical reasoning skills, enabling me to make reasonable speculations and explanations for analysis results.
在实践能力上，学会了运用 ArcGIS 等工具进行空间自相关分析，包括选择合适的空间权重矩阵、计算和解读 Moran’s I、Geary’s C、Anselin Local Moran I 和 Getis-Ord Gi * 等指标，提升了对空间数据的处理和分析能力。通过设计实验验证相关假设，培养了实验设计和逻辑推理能力，能够针对分析结果进行合理推测和解释。

This study has also made me realize the importance of spatial autocorrelation analysis in revealing the spatial distribution characteristics and patterns of geographical phenomena. It has provided a solid foundation for future applications of spatial analysis in urban planning, resource allocation, and other fields, and has also sparked my interest in exploring more complex spatial analysis methods.
此次研究也让我认识到空间自相关分析在揭示地理现象空间分布特征和规律中的重要性，为今后在城市规划、资源分配等领域的空间分析应用提供了坚实的基础，同时也激发了对更复杂空间分析方法的探索兴趣。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 8. "Different Interchange Structures.pdf"
# 8. "不同的立交结构.pdf"

This article focuses on different types of interchange structures, using several typical interchanges in Shenzhen as examples to provide a detailed introduction to their general situations and structural conditions.
本文聚焦于不同类型的立交结构，以深圳市多个典型立交为例，详细介绍了其概况与结构情况。

Trumpet + Oblique Cloverleaf Interchange (Honghu Interchange): Composed of Nigang East Road and Buxin Road (east-west urban expressways) and Honghu West Road and Wenjin North Road (north-south urban arterial roads). Due to the presence of Honghu Park, dense buildings, and other factors in the surrounding area, space needs to be compressed. Additionally, the road alignment is not orthogonal, and traffic volume is high. Therefore, an oblique cloverleaf interchange model is adopted. A trumpet interchange is also constructed in the southwest for connection. Independent ramps are set on both sides of the road to facilitate vehicles merging in and out without affecting through traffic.
喇叭型 + 斜向苜蓿叶式立交（洪湖立交）：由泥岗东路、布心路（东西向城市快速路）和洪湖西路、文锦北路（南北向城市主干路）组成。因周边有洪湖公园、密集建筑等，需压缩空间，且道路走向非正交、交通流量大，故采用斜向苜蓿叶立交模式，西南部还建设喇叭型立交衔接，道路两侧设有独立匝道方便车辆汇入驶出而不影响直行。

Partial Cloverleaf Interchange (Tangtou Interchange): Involves the Nanguang Expressway (northwest-southeast direction) and the Shenhai Expressway (east-west direction), both of which are expressways. The Nanguang Expressway carries a large volume of traffic, and its alignment is offset to bypass the Tiegang Reservoir. Farmland on the northeast and southwest sides limits space. Therefore, a partial cloverleaf interchange is adopted, with cloverleaves arranged in the northwest and southeast, and non-directional designs on the other two sides. Toll stations are located on the interchange, and their placement alleviates potential congestion.
半苜蓿叶式立交（塘头立交）：涉及南光高速（西北 - 东南方向）和沈海高速（东西方向），均为高速公路。南光高速承接大量车流且走向因绕开铁岗水库发生偏移，东北和西南侧有农田限制空间，因此采用半苜蓿叶式立交，西北和东南处布设苜蓿叶，另外两侧非定向设计，立交上设有收费站且位置缓和了潜在拥堵。

Fully Directional Interchange (Pingdi Interchange): Composed of the Changshen Expressway (north-south direction) and the Shenzhen Outer Ring Expressway (east-west direction), both of which are expressways. Located in a valley opening between two hills, the terrain is restricted. The surrounding roads are complex, buildings are dense, and traffic volume is high. A fully directional model is adopted. By increasing the number of vertical layers and using a quasi-circular pattern, land occupation is reduced, and traffic efficiency is improved. All sections are elevated to facilitate passage on the roads below.
全定向式立交（坪地立交）：由长深高速（南北方向）和深圳外环高速（东西方向）构成，均为高速公路。位于两丘陵间谷地开口，地形受限，周边道路复杂、建筑密集，交通量较大，采用全定向模式，通过增加垂直层数和类环形模式减少占地、提高通行效率，且全部设置高架方便下方路段通行。

Cross Intersection: Ruyi Road (northwest-southeast direction) and Longxiang Avenue (southwest-northeast direction) are both arterial roads located in a bustling area of Longgang District. Surrounding residential and office buildings are dense, making it impossible to adopt an interchange form. Therefore, it is a planar cross intersection with dedicated right-turn lanes. There are conflict points where left-turn routes intersect with other routes.
十字交叉口：如意路（西北 - 东南方向）和龙翔大道（西南 - 东北方向）均为主干路，位于龙岗区繁华地带，周边居民楼、办公楼密集，无法采用立交形式，故为平面十字交叉口，设置专用右转道，存在左转路线与其他路线的交叉冲突点。

Roundabout + Separated Interchange: Yingbin Avenue (east-west direction, including elevated and ground roads) and Yeting Avenue (north-south direction) are both arterial roads. A roundabout is set in the middle, with an overpass above for the east-west road to split and pass, reducing land occupation and allowing east-west through traffic to avoid intersection interference. North-south vehicles can pass directly but cannot handle large traffic volumes.
环岛 + 分离立交：迎宾大道（东西方向，含高架和地面道路）和叶挺大道（南北方向）均为主干路。中间设环岛，上方有高架桥供东西向道路分叉通行，减少占地，使东西向直行车辆不受路口干扰，南北向车辆可直接通行但无法承载大交通流量。

Through the study of different interchange structures, I have gained a comprehensive understanding of urban road interchange design. At the knowledge level, I have learned about the characteristics, applicable scenarios, and design considerations of various interchange structures, such as the impact of traffic volume, terrain, and surrounding environment on choosing the type of interchange. I have also clarified the advantages and limitations of different interchanges in solving traffic intersection problems.
通过对不同立交结构的研究，我对城市道路立交设计有了全面认识。在知识层面，了解了多种立交结构的特点、适用场景及设计考量因素，如交通流量、地形地貌、周边环境等对 choosing 立交类型的影响，明晰了不同立交在解决交通交汇问题上的优势与局限。

In terms of analytical ability, I have learned to interpret the rationality of interchange structure design in conjunction with specific geographical environments and traffic demands, enhancing my understanding of the relationship between spatial layout and traffic organization. At the same time, by comparing different interchange forms, I have developed a multi-angle problem-solving mindset, recognizing that engineering design must balance functionality, economy, and environmental adaptability.
在分析能力上，学会了结合具体地理环境和交通需求去解读立交结构设计的合理性，提升了对空间布局和交通组织关系的理解。同时，通过对比不同立交形式，培养了从多角度分析问题的思维，认识到工程设计需兼顾功能性、经济性和环境适应性。

This study has also made me deeply appreciate the close connection between urban transportation facility design and urban development. It has accumulated practical knowledge for future attention to urban planning and traffic engineering fields and sparked my interest in exploring the optimization of urban transportation systems.
此次研究也让我深刻体会到城市交通设施设计与城市发展的紧密联系，为今后关注城市规划和交通工程领域积累了实践认知，激发了对优化城市交通系统的探索兴趣。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 9. “Research on the Resilience of China's Urban Economies.pdf”
# 9. “中国城市经济韧性研究.pdf”

This paper focuses on the economic resilience of Chinese cities, integrating macroeconomic indicators and economic shock theory to explore the correlation of influencing factors and their geographical distribution patterns.
本文聚焦中国城市经济韧性，结合宏观经济指标和经济冲击理论，探究其因素相关性与地理分布规律。

Research Background and Theoretical Foundation: The article traces the origin of the concept of "resilience," introduces the five-dimensional framework of urban resilience, and defines urban economic resilience as the capacity of an urban economic system to resist and recover from crises. Against the backdrop of China's transition from high-speed growth to high-quality development, it underscores the forward-looking significance of studying urban economic resilience. It reviews relevant domestic and international research, summarizing how different literatures understand urban economic resilience, along with their analytical algorithms and indicator variables.
研究背景与理论基础：文章从 “韧性” 概念起源入手，介绍了城市韧性的五维维度及城市经济韧性的定义 —— 城市经济系统面对危机的抵御与恢复能力。结合中国经济从高速增长转向高质量发展的背景，强调研究城市经济韧性的前瞻意义，并梳理了国内外相关研究，总结了不同文献对城市经济韧性的理解、分析算法及指标变量。

Calculation of the Urban Economic Resilience Index and Spatial Analysis: An improved method is used to calculate the index, based on per capita GDP, independently measuring shock resistance (relative difference in per capita GDP before and after a shock) and recovery capacity (relative difference in per capita GDP before and after recovery), avoiding distortions from population or city size effects and subjective influences. Data visualization reveals that urban per capita GDP generally fluctuates, with most cities declining in 2020 before rebounding. Shock resistance follows a power-law distribution (mostly medium-low values), while recovery capacity follows a linear distribution (a few cities recover slowly). Geographically, high shock resistance clusters in Hunan-Jiangxi and Northeast China, while recovery capacity clusters in the Pearl River Delta and Yangtze River Delta, with most central and western regions showing low values.
城市经济韧性指数求解与空间分析：采用改进的方法求解指数，以人均 GDP 为基础，分别独立计算抗冲击能力（冲击前后人均 GDP 相对差异）和恢复能力（恢复前后人均 GDP 相对差异），避免人口和城市规模效应及主观因素影响。通过数据可视化发现，城市人均 GDP 普遍有波动，2020 年多数城市下降后回升；抗冲击能力呈幂律分布（中低值城市居多），恢复能力呈线性分布（少数城市恢复缓慢）；地理分布上，抗冲击能力在湘赣和东北地区有高值集聚区，恢复能力在珠三角、长三角等地区集聚，中西部多为低值区。

Factor Correlation and Spatial Analysis: Using Pearson, Spearman, and Kendall correlation coefficients, the analysis finds that economic indicators exhibit internal patterns (primary and secondary industry shares correlate weakly and negatively with others, tertiary industry share correlates positively, and most indicators correlate positively within themselves). Regarding correlations between economic indicators and resilience indices, recovery capacity shows stronger correlations with indicators than shock resistance. Shock resistance is mostly negatively correlated with indicators except tertiary industry share, while recovery capacity is mostly positively correlated except for primary and secondary industry shares.因素相关性与空间分析：运用 Pearson、Spearman、Kendall 三种相关系数，分析发现经济指标内部存在规律（第一、二产业占比与其他指标相关性小且负相关，第三产业占比正相关，多数指标内部正相关）；经济指标与韧性指数相关性中，恢复能力与指标相关性更强，抗冲击能力除第三产业占比外多呈负相关，恢复能力除第一、二产业占比外多呈正相关。

Analysis Based on the Economic Shock Process: Economic shocks are categorized as internal (e.g., natural disasters) or external (e.g., changes in international conditions), with differing impact processes on urban economies. The urban economic recovery process is also analyzed, distinguishing external recovery (shock weakening) from internal recovery (structural adjustment). Combining these analyses, the paper links urban economic conditions (economic scale, industrial structure, etc.) with resilience indicators, explaining possible reasons for geographical distribution differences (e.g., coastal cities' strong recovery capacity stems from rapid industrial transformation).基于经济冲击流程的分析：将经济冲击分为内部（自然灾害等）和外部（国际形势变化等），阐述其对城市经济的不同影响流程；同时分析了城市经济恢复流程，指出外部恢复（冲击减弱）与内部恢复（结构调整）的区别。结合分析总结了城市经济情况（经济规模、产业结构等）与韧性指标的联系，解释了地理分布差异的可能原因（如沿海城市恢复能力强源于产业转型快等）。

Through this research, I gained a systematic understanding of urban economic resilience. Theoretically, I deepened my grasp of the concept, measurement methods, and the mechanisms by which economic shocks affect urban economies, while mastering the application scenarios and differences of various correlation coefficients in data analysis.
通过本次研究，我对城市经济韧性有了系统认知。在理论层面，深入理解了城市经济韧性的内涵、衡量方法及经济冲击对城市经济的影响机制，掌握了不同相关系数在数据分析中的应用场景与差异。

Methodologically, I learned how to refine existing indicator calculations for greater rationality—such as using per capita GDP and independently calculating shock resistance and recovery capacity to reduce interference. I also acquired skills in data visualization and spatial analysis, enabling intuitive presentation of distribution patterns and correlations through charts, enhancing my ability to process and interpret macroeconomic data.
在研究方法上，学会了如何改进现有指标计算方法以提升合理性，如通过人均 GDP 和独立计算抗冲击与恢复能力减少干扰；掌握了数据可视化和空间分析手段，能通过图表直观呈现分布规律与相关性，增强了对宏观经济数据的处理与解读能力。

Additionally, I recognized the close ties between urban economic resilience and factors like industrial structure and fiscal conditions, as well as their guiding significance for urban planning and high-quality economic development. This provides a framework and approach for future multidimensional urban economic analysis.
同时，认识到城市经济韧性与产业结构、财政状况等因素的密切联系，及其对城市规划和经济高质量发展的指导意义，为今后从多维度分析城市经济问题提供了思路与框架。


- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 10. “Shared Bike Data Analysis.pdf”
# 10. “共享单车数据分析.pdf”

This paper is the final practical report for the course Introduction to Data Science and Data Mining, jointly completed by seven students including Wang Yi and Yu Xintong. Based on one-day shared-bike order data in Shanghai, and integrating POI data and road-network data, it explores the travel patterns and carbon-reduction benefits of shared bikes in Shanghai.
本文是数据科学与数据挖掘导论课程的期末实践报告，由王逸、余欣潼等七人合作完成，以上海市某一天的共享单车订单数据为基础，结合 POI 数据和路网数据，探究了上海市共享单车的出行模式及碳减排效益。

Research Background and Framework: As a mature public-transport facility, shared bikes can solve the “last-mile” problem, and also alleviate urban issues such as traffic congestion and air pollution. Existing studies mostly focus on travel patterns and environmental benefits; on this basis, this paper uses two frameworks—“basic analysis based on order data” and “trajectory-flow patterns and carbon-reduction-benefit analysis”—and employs data-mining methods such as DBSCAN, K-means, and PCA.
研究背景与框架：共享单车作为成熟的公共交通设施，能解决 “最后一公里” 问题，还可缓解交通拥堵、空气污染等城市问题。现有研究多聚焦出行模式和环境效益，本文在此基础上，通过 “基于订单数据的基本分析”“轨迹流模式和碳减排效益分析” 两大框架，结合 DBSCAN、K-means、PCA 等数据挖掘方法展开研究。

Basic Analysis Based on Order Data: Both order duration and travel distance are dominated by short trips; orders of 5–10 min and 500–1000 m are the most numerous. Departure times cluster in morning peak (7–9 a.m.) and evening peak (4–8 p.m.), with sharper variation in the morning. During peak hours, parking points concentrate in the city center, decreasing in a ring-shaped diffusion; small-scale clusters appear in the south and southwest. Using DBSCAN to identify parking clusters, we find more parking points in Puxi with a large core area, while Pudong has fewer; an OD map shows that cycling flows are mainly confined to the Puxi core.
基于订单数据的基本分析：订单持续时间和行驶距离均以短程为主，5-10 分钟、500-1000 米的订单数量最多；出发时刻集中在早高峰（7-9 点）和晚高峰（16-20 点），早高峰变化更剧烈。高峰期停车点主要集中在市中心，呈环形扩散递减趋势，南部和西南部有小规模集中分布。使用 DBSCAN 算法识别停车聚集区域，发现浦西停车点多且核心区域范围大，浦东较少；OD 图显示骑行流动主要局限在浦西核心区。

Trajectory-Flow Patterns and Carbon-Reduction-Benefit Analysis: Based on distance and geographic scope, clustering reveals that long-distance rides mostly occur in suburban and peripheral areas, medium- and short-distance rides are concentrated in the city, and relatively closed trajectory areas exist in the urban core; cross-river routes are few and small in scope, while popular routes concentrate on main urban arterials and cross-river roads. On the spatiotemporal scale, cycling activity peaks during morning and evening rush hours; trajectory centroids shift with time slots, and morning peak sees more unlock points in the city center, reflecting commuting demand. Combined with POI data, POI types near parking points during morning and evening peaks are mainly company/enterprise and residential/accommodation, indicating that shared bikes are mainly used for commuting. For carbon reduction, four calculation models are referenced; by selecting the middle result and computing the arithmetic mean, it is found that the southern suburbs show significant carbon reduction due to medium- and long-distance routes.
轨迹流模式和碳减排效益分析：基于距离和地理范围，通过聚类划分发现长距离骑行多在郊区及市区边缘，中短距离在市区且更集中，市区存在相对闭合的轨迹区域，跨江路线少且范围小，流行路线集中在市区主干道和跨江道路。时空尺度上，骑行活跃度早晚高峰最高，轨迹重心随时段变化，早高峰市中心开锁点增多，反映通勤需求。结合 POI 数据，早高峰和晚高峰停车点附近主要 POI 类型为公司企业和住宅住宿，说明共享单车主要用于上下班通勤。碳减排方面，参考四种计算模式，选取居中结果计算算术平均，发现南部郊区因中长途路线多，碳减排显著。

Through participation in this study, I grew in multiple aspects. At the knowledge level, I gained deep insight into shared-bike travel characteristics and their correlation with urban space and residents’ activities, mastered the application of data-mining algorithms such as DBSCAN and K-means in spatial-data analysis, and clarified relevant methods and reference standards for calculating carbon-reduction benefits.
通过参与本次研究，我在多方面获得成长。知识层面，深入了解了共享单车的出行特征及其与城市空间、居民活动的关联，掌握了 DBSCAN、K-means 等数据挖掘算法在空间数据分析中的应用，明晰了碳减排效益计算的相关方法和参考标准。

In practical skills, I enhanced data-processing and visualization abilities, learned to integrate and analyze order data, POI data, etc. with various tools, and can present research results intuitively through charts. In teamwork, I strengthened communication and division-of-labor skills, jointly completing tasks from data collection and analysis to report writing, and deeply experienced the importance of teamwork for efficient research completion.
实践能力上，提升了数据处理和可视化技能，学会了运用多种工具对订单数据、POI 数据等进行整合分析，能通过图表直观呈现研究结果。在团队协作中，增强了沟通与分工协作能力，共同完成数据收集、分析、报告撰写等任务，深刻体会到团队合作对高效完成研究的重要性。

This study also made me realize the great value of big-data analysis in urban transportation planning and environmental protection, providing ideas and methods for using data analysis to solve practical urban problems in the future, and sparking my interest in exploring the social applications of data science.
此次研究也让我认识到大数据分析在城市交通规划和环保领域的重要价值，为今后利用数据分析解决实际城市问题提供了思路和方法，激发了对数据科学在社会应用中的探索兴趣。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)


# 11. "Cartography Review.pdf"
# 11. "地图学综述.pdf"

Centering on cartographic principles and the future development of maps, this paper systematically discusses the map-making workflow, exploratory maps, the role of maps in emerging fields, the pan-map concept and practical cases, aiming to clarify the essence, framework and connection with new technologies of cartography.
本文围绕地图学原理及地图未来发展展开，系统探讨了地图制作流程、探索型地图、地图在新兴领域的作用、泛地图概念及实践案例，旨在梳理地图学的本质、框架及与新技术的关联性。

Analysis of the Map-Making Workflow: Based on cartographic principles, the article sorts out the complete map-making workflow: determine map type (need to clarify mapping method, category, etc., such as by regional scope, scale); determine data source and input methods (including ground-survey data, multi-source remote-sensing data, etc.); determine mathematical projection method and process data (including selection of geographic coordinates, projection mode, scale); conduct cartographic generalization (divided into manual and automatic generalization, involving classification, selection, simplification, etc.); design map symbols and determine the geographic-information symbol model; use digital technology to compile the map; carry out analysis and evaluation (from scientific, artistic angles); perform reproduction and compilation management (including traditional printing, electronic publishing, etc.). Each step explains its significance, reflecting the rigor and systematicness of map-making .
地图制作流程解析：文章基于地图学原理，梳理出完整的地图制作流程：确定地图类型（需明确成图方法、类别等，如按区域范围、比例尺划分）；确定数据源及输入方法（包括地面测量数据、多源遥感数据等）；确定数学投影方法并处理数据（含地理坐标、投影方式、比例尺的选择）；进行地图概括（分手工和自动概括，涉及分类、选取、简化等）；设计地图符号并确定地理信息符号模型；利用数字化技术汇总地图；开展分析评价（从科学性、艺术性等角度）；进行复制与编制管理（含传统印刷、电子出版等）。每个步骤均阐述了其意义，体现了地图制作的严谨性与系统性。

Analysis of Exploratory Maps: Introduces the concept of exploratory maps, pointing out that its core is the shift in map domination (from author-led to user-led), divided into two trends: data-stable tendency (users explore inherent relationships of data) and data-open tendency (everyone-as-mapper mode). Technically, it needs to combine database and Internet technologies, visualization technologies, and AI technologies for construction; in terms of development trends, exploratory maps are a transitional product of domination relationships, and will evolve toward network maps (highly open modeling methods) and mobile network maps (multi-dimensional, ubiquitous) in the future.
探索型地图分析：引入探索型地图概念，指出其核心是地图支配关系的转变（从作者主导转向用户主导），分为数据稳定趋向（用户探索数据内在关系）和数据开放趋向（人人制图模式）两类。技术应用上，需结合数据库与互联网技术、可视化技术、人工智能技术搭建；发展趋势上，探索型地图是支配关系过渡产物，未来将向网络地图（建模方法高度开放）、移动网络地图（多维度、泛在化）演进。

The Role of Maps in Emerging Fields: 1) Smart City: A smart city is the intelligent transformation of the tri-space (physical, social, information space); maps serve as a visualization carrier and open-data carrier, providing support for city management and public cognition, and the underlying cartographic theories (e.g., spatial cognition, symbol theory) also inspire smart-city construction. 2) Digital Twin: Digital twin is the technology of simulating entity behavior through digital models; maps can be its application-verification tool (using map causality to correct model distortion) and visualization medium (assisting in displaying modeling processes and results). 3) Metaverse: The metaverse is a virtual-reality system independent of reality; maps within it act as spatial-cognition tools, and their theories also provide references for the visualization framework of the metaverse and the use of geographic information (e.g., “procedural mapping”). 4) Pan-Map Concept and Expansion: Pan-map is the extension and expansion of traditional maps, proposed due to ICT-era technological development, limitations of classical theories, and needs of the public and professionals. It realizes the generalization of geographic information (content and form), domination relationships (increased user participation), and perceptual cognition (diverse visual-artistic expressions). Its framework covers standard maps and map-like graphics; in the future it will construct object-space theory, expression-dimension spectra, and optimize tri-space expression.
地图在新兴领域的作用：1）智慧城市：智慧城市是三元空间（物理、社会、信息空间）的智慧化转型，地图作为可视化载体和开放数据载体，为城市管理、大众认知提供支撑，其背后的地图学理论（如空间认知、符号理论）也为智慧城市构建提供启发。2）数字孪生：数字孪生是通过数字化模型模拟实体行为的技术，地图可作为其应用检验工具（利用地图因果关系纠正模型失真）和可视化媒介（辅助展示建模过程与结果）。3）元宇宙：元宇宙是独立于现实的虚拟现实系统，地图在其中既作为空间认知工具，其理论也为元宇宙的可视化框架、地理信息运用（如 “程序测绘”）提供参考。4）泛地图概念及拓展：泛地图是传统地图的延伸与拓展，因 ICT 时代技术发展、经典理论局限、大众与专业需求而提出，实现了地理信息（内容、形式泛化）、支配关系（用户参与度提升）、感性认识（多元视觉艺术表现）的泛化。其框架涵盖标准地图和类地图，未来将构建对象空间理论、表达维度谱系，优化三元空间表达。

Practical Case Studies: Five cases—high-speed-rail noise maps, submarine topographic maps, power-grid corrosion maps, etc.—are selected to analyze their production methods and characteristics, indicating expandable directions (e.g., adding exploratory functions, integrating digital-twin technology, enhancing dynamics), demonstrating the potential of new-type maps in technology integration and application scenarios.
实践案例分析：选取高速铁路噪声地图、海底地形图、电网腐蚀地图等五个案例，分析其制作方法与特点，指出可拓展方向（如加入探索型功能、结合数字孪生技术、提升动态性等），体现了新型地图在技术融合与应用场景上的潜力。

Through this study I gained a systematic understanding of cartography. At the knowledge level, I deeply grasped the complete workflow of map-making and the interconnections of each step, mastered the connotations of emerging concepts such as exploratory maps and pan-maps, and clarified the application logic of maps in smart cities, the metaverse and other fields.
通过本文研究，我对地图学有了系统性认知。在知识层面，深入理解了地图制作的完整流程及各环节的关联性，掌握了探索型地图、泛地图等新兴概念的内涵，明晰了地图在智慧城市、元宇宙等领域的应用逻辑。

At the capability level, I improved literature sorting and analysis skills, learned to dissect cartographic issues from multiple dimensions (technology, theory, application); through case studies I strengthened the ability to integrate theory and practice, and can propose targeted map optimization directions. Meanwhile, I realized that cartography is not a static discipline but continuously generalizes with technological development, which cultivated my sensitivity and forward-looking thinking toward the frontiers of the discipline.
在能力层面，提升了文献梳理与分析能力，学会从多维度（技术、理论、应用）剖析地图学问题；通过案例研究，增强了将理论与实践结合的能力，能针对性提出地图优化方向。同时，认识到地图学并非静态学科，其随技术发展不断泛化，这培养了我对学科前沿的敏感性与前瞻性思维。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 12. "Urban Traffic System Traffic Flow Observation Report.pdf"
# 12. "城市交通系统交通流观察报告.pdf"

This report is an observation report on the traffic organization and traffic flow of the west-gate road intersection of Shenzhen University (the junction of Nanhai Avenue and Taoyuan Road). Through detailed analysis of the intersection, it presents its traffic conditions and provides reference for planning improvements.
本文是关于深圳大学西门道路交叉口（南海大道与桃园路交接处）交通组织与交通流的观测报告，旨在通过对该交叉口的详细分析，呈现其交通状况并为规划改进提供参考。

Intersection Structure Analysis: The report meticulously draws the intersection plan, cross-sections in each direction (north-south, east-west, and east-side semi-circular road), longitudinal section and ramp cross-section, illustrating lane distribution, width, isolation facilities and surrounding green belts. For example, the north-south road includes motor lanes, non-motor lanes, sidewalks and green belts, with the dimensions and layout of each part specified; satellite images and street-view images are integrated to present the actual spatial form of the intersection. Nanhai Avenue here has a depressed tunnel section, with the upper level being a bridge deck, constituting a complex three-dimensional traffic structure.
交叉口结构分析：报告详细绘制了交叉口的平面图、各方向（南北向、东西向、东侧半环形道）的断面图、纵断面图及匝道断面图，展示了道路的车道分布、宽度、隔离设施及周边绿化带等情况。例如，南北向道路包含机动车道、非机动车道、人行道及绿化带等，明确了各部分的尺寸和布局；同时结合卫星图像和街景图像，直观呈现了交叉口的实际空间形态，南海大道在此处有一段下沉式隧道，上层为桥面，构成了复杂的立体交通结构。

Traffic Flow Analysis: The morning and evening peak traffic flow conditions are analyzed, including total flow analysis charts (marked with significant hot and cold flow directions), bar charts of vehicle-type flow distribution (covering small passenger cars, large passenger cars, small trucks, large trucks, non-motor vehicles and pedestrians). Flow curve variation graphs show the changing patterns of traffic volume for different vehicle types and pedestrians at different times and in different directions (south side, north side); peak hour factors (PHF) and other indicators are calculated to reflect the fluctuation characteristics of traffic flow during peak hours. Results indicate that the morning and evening peak flows differ, some directions are significant hot spots, and among motor vehicles small passenger cars dominate the volume.
交通流量分析：重点分析了早高峰和晚高峰的交通流量情况，包括总流量分析图（标注显著热点和冷点流向）、分车型流量分布柱状图（涵盖小客车、大客车、小货车、大货车、非机动车及行人）。通过流量曲线变化图展示了不同时段、不同方向（南侧、北侧）各类车辆及行人的流量变化规律，并计算了高峰小时系数（PHF）等指标，反映了高峰时段交通流量的波动特征。结果显示，早晚高峰流量存在差异，部分流向为显著热点，机动车中以小客车流量为主。

Basic Information and Improvement Suggestions: Basic information of the intersection is investigated, including its location, surrounding metro stations (Line 1 Taoyuan Station), bus routes and stops, important facilities (Shenzhen University, Nanshan District People’s Hospital, etc.) and vehicle origin (associated major roads). Based on the observations, attribution analysis is conducted and traffic planning improvement suggestions are proposed, providing directions for optimizing the traffic organization of the intersection.
基础信息与改进建议：调研了交叉口的基本信息，包括位置、周边地铁站（1 号线桃园站）、公交线路及站点、重要设施（深圳大学、南山区人民医院等）和车辆来源情况（关联的主要道路）。基于观测结果，进行了归因分析并提出了交通规划改进建议，为优化该交叉口的交通组织提供了方向。

By participating in this traffic flow observation study, I gained an intuitive and in-depth understanding of urban road intersection traffic organization and flow characteristics. On the knowledge level, I learned about the structural components of an intersection, traffic flow analysis methods and related indicators (such as peak hour factor), mastered how to present traffic data clearly through charts, and understood the relationship between traffic facility layout and traffic flow.
通过参与本次交通流观测研究，我对城市道路交叉口的交通组织和流量特征有了直观且深入的认识。在知识层面，了解了交叉口的结构组成、交通流量的分析方法及相关指标（如高峰小时系数），掌握了如何通过图表清晰呈现交通数据，理解了交通设施布局与交通流之间的关联。

In practical ability, I enhanced skills in data collection, organization and visualization, learned to analyze traffic conditions by combining maps and on-site images, and cultivated the ability to summarize patterns from complex traffic phenomena. At the same time, through team division of labor (such as drawing charts, writing text, and investigating information), I strengthened team collaboration awareness and communication skills, and recognized the importance of multi-party collaboration for completing comprehensive research.
在实践能力上，提升了数据收集、整理和可视化的技能，学会了结合地图和实地图像分析交通状况，培养了从复杂交通现象中总结规律的能力。同时，通过团队分工协作（如绘制图表、撰写文字、调研信息），增强了团队合作意识和沟通能力，认识到多方协作对于完成综合性研究的重要性。

This study also made me realize the complexity and importance of traffic planning. A reasonable traffic organization scheme can effectively improve traffic efficiency, and it has accumulated practical experience for paying attention to urban traffic issues and proposing optimization suggestions in the future.
此次研究也让我意识到交通规划的复杂性和重要性，一个合理的交通组织方案能有效提升通行效率，为今后关注城市交通问题、提出优化建议积累了实践经验。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 13. "Resident Travel OD Calculation.pdf"
# 13. "居民出行OD计算.pdf"

This document is a homework report on the OD (origin–destination) calculation for resident trips in Shenzhen; it focuses on the computation of resident travel OD demand, the display of OD distribution maps, and a preliminary analysis of traffic demand distribution.
本文是关于深圳市居民出行 OD（起讫点）计算的作业报告，主要围绕居民出行 OD 需求计算、OD 分布图展示及交通需求分布初步分析展开。

Homework Requirements & Data: first, compute the resident travel OD demand; second, present the OD distribution map and carry out a preliminary analysis of traffic demand distribution. A gravity model is to be employed for the calculation; relevant parameters may be set autonomously and a brief comparative analysis conducted. The data used include population and job statistics (GIS format) for Shenzhen’s ten administrative districts, road networks from Gaode/Baidu online maps, and information on the locations of each district’s government seat; additionally, one must independently construct the administrative center points (government locations) of each district and the straight-line (desire) lines between point pairs, and compute the shortest road distance between each point pair.
作业要求与数据: 作业明确了两项任务，一是计算居民出行 OD 需求，二是展示 OD 分布图并开展交通需求分布的初步分析，采用重力模型进行计算，相关参数可自行设定并进行简要对比分析。所使用的数据包括深圳市 10 个行政区的人口和就业岗位统计数据（GIS 格式）、高德 / 百度在线地图的道路网和各区政府所在地信息等，同时需要自行构建各区行政中心点（政府所在地）及点对之间的直线（期望线），并计算点对间的最短道路距离。

Data Pre-processing: Data pre-processing comprises several steps. First, the data are clipped and pre-processed: OpenStreetMap road-network data are taken, and, via the Shapely library and Geopandas tools, a spatial intersection with Shenzhen’s boundary is performed to restrict the data to Shenzhen’s administrative boundary. Next, district-government coordinates are obtained and a nearest-neighbor search is executed: after the geographic locations of each district government are organized into a latitude–longitude table, a nearest-neighbor algorithm maps them onto the linear structure of the road network; the minimum distance from each district-government coordinate to every road-network edge is calculated, and projection yields new coordinates. Finally, shortest paths are computed and a distance matrix constructed: the Dijkstra algorithm is adopted, combined with the Haversine formula for spherical distance, to obtain a shortest-path distance matrix between district governments; these steps are implemented in Python using libraries such as Geopandas, Shapely, and NetworkX.
数据预处理: 数据预处理包括多个步骤，首先对数据进行裁剪与预处理，使用 OpenStreetMap 提供的路网数据，通过 Shapely 库与 Geopandas 工具，将路网数据与深圳市边界进行空间相交操作，把数据限定在深圳市行政边界内。然后获取区政府坐标并进行最近邻查找，将各区政府的地理位置整理成经纬度表后，使用最近邻查找算法映射到路网的线性结构上，计算每个区政府坐标到所有路网边的最小距离并投影形成新坐标。最后计算最短路径并构建距离矩阵，采用 Dijkstra 算法，结合 Haversine 公式计算球面距离，得到区政府之间的最短路径距离矩阵，这些步骤通过 Python 中的 Geopandas、Shapely、NetworkX 等库实现。

Gravity Model & Improved Application: The gravity model is a predictive model based on inter-regional interaction strength; in OD calculation it is used to estimate travel flows between two regions. Its basic assumption is that the interaction strength between two regions is directly proportional to their attribute scale and inversely proportional to their distance. By adjusting parameters such as the distance-decay coefficient and observing changes in attraction values, it is found that attraction values exhibit a significant power-law distribution; the distance-decay coefficient has a large influence on attraction. Because the traditional gravity model ignores the matching relationship between regional population and jobs and thus suffers from model bias, an improved gravity model is adopted; this model better accounts for the matching relationship between regional population and jobs. Compared with the traditional model, the significance of the power-law distribution decreases, and the differentiation of attraction values among different administrative districts improves, aligning better with Shenzhen’s actual conditions. Examples include higher attraction between Futian and Bao’an districts, and between Bao’an and Nanshan districts, whereas Pingshan New District, Yantian District, and Dapeng New District show lower attraction.
重力模型及改进型应用：重力模型是一种基于区域间相互作用强度的预测模型，在 OD 计算中用于估计两个区域间的出行流量，其基本假设是两个区域间的相互作用强度与其属性规模成正比，与其距离成反比。通过调整距离衰减系数等参数观察吸引力数值变化，发现吸引力数值呈现显著的幂律分布规律，距离衰减系数对吸引力影响较大。由于传统重力模型忽略了区域人口与岗位的匹配关系，存在模型偏差，因此采用了改进型重力模型，该模型能更好地考虑区域人口与岗位的匹配关系，对比传统模型，其幂律分布的显著性下降，不同行政区之间的吸引力数值区分度更好，更符合深圳的实际情况，比如福田区与宝安区、宝安区与南山区等行政区对吸引力较高，而坪山新区、盐田区、大鹏新区等被吸引程度较低。

Through this assignment I gained in several areas. At the knowledge level, I deepened my understanding of the basic principles and application scenarios of the gravity model, grasped its role in traffic demand analysis, recognized the limitations of the traditional model and the advantages of the improved model, and clarified the importance of the matching relationship between regional population and jobs in model construction.
通过本次作业，我在多个方面有所收获。在知识层面，深入了解了重力模型的基本原理和应用场景，掌握了其在交通需求分析中的作用，同时认识到传统模型的局限性以及改进型模型的优势，明确了区域人口与岗位匹配关系在模型构建中的重要性。

In practical ability, I enhanced my capacity to process and analyze spatial data, learned to use relevant Python libraries for data clipping, shortest-path calculation, and distance-matrix construction, and mastered the basic workflow and methods of OD calculation. By adjusting parameters and comparing results, I cultivated analytical skills regarding the impact of model parameters and can better interpret traffic demand distribution patterns.
在实践能力上，提升了对空间数据的处理和分析能力，学会了使用相关 Python 库进行数据裁剪、最短路径计算、距离矩阵构建等操作，掌握了 OD 计算的基本流程和方法。通过调整参数并对比结果，培养了对模型参数影响的分析能力，能够更好地解读交通需求分布规律。

Moreover, through this assignment, I deeply sensed the close link between theoretical models and practical application, recognized the importance of traffic models in urban planning, accumulated experience for future study and work in related fields, and further stimulated my interest in exploring traffic data analysis.
此外，通过本次作业，我深刻体会到理论模型与实际应用的紧密联系，认识到交通模型在城市规划中的重要性，为今后从事相关领域的学习和工作积累了经验，也激发了对交通数据分析的进一步探索兴趣。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)

# 14. "Filter Operator Implementation and Comparison.pdf"
# 14. "滤波算子的实现和对比.pdf"

This paper centers on image filtering algorithms, detailing in depth the implementation principles, effects, and comparative analyses of various common filters, aiming to explore the applicability of different algorithms in remote-sensing image processing.
本文围绕图像滤波算法展开，详细介绍了多种常见滤波算法的实现原理、效果及对比分析，旨在探讨不同算法在遥感图像处理中的适用性。

Filtering Algorithms Overview：Image filtering is a key technique in remote-sensing image processing that can improve image quality, remove noise, enhance details, or highlight features, directly influencing the accuracy of subsequent processing. Common algorithms include mean filtering, median filtering, Roberts cross-gradient operator filtering, Sobel operator filtering, Laplacian operator filtering, and Gaussian filtering. Based on different mathematical principles, they achieve denoising, edge detection, and other functions by adjusting the kernel and parameters.
滤波算法概述：图像滤波是遥感图像处理的重要技术，可改善图像质量、去除噪声、增强细节或突出特征，直接影响后续处理的精度。常见算法包括均值滤波、中值滤波、Roberts 交叉梯度算子滤波、Sobel 算子滤波、拉普拉斯算子滤波和高斯滤波，它们基于不同数学原理，通过调整滤波核和参数实现去噪、边缘检测等功能。

Detailed Explanations of Each Filtering Algorithm：1）Mean Filtering: Replaces a pixel with the average of its neighborhood; smooths the image and reduces high-frequency noise, with high computational efficiency, but blurs edges and details and performs poorly against impulse noise. The larger the window, the more blurred the image and the longer the runtime. 2）Median Filtering: Replaces the current pixel with the median of its neighborhood; effectively removes impulse noise such as salt-and-pepper noise while better preserving edges, but is less effective against Gaussian noise and has higher computational complexity. As the window size increases, denoising improves but so does the time cost. 3） Roberts Cross-Gradient Operator Filtering: Uses first-order derivatives, computing horizontal and vertical gradients through two convolution kernels to highlight edges; efficient at detecting fine edges but sensitive to noise, and excessive sharpening may amplify noise. 4） Sobel Operator Filtering: Uses weighted convolution kernels to compute gradients, offering better noise immunity than the Roberts operator and suitable for detecting edges over larger areas; applicable to images with moderate noise, though edges may be less sharp. 5） Laplacian Operator Filtering: Detects edges based on second-order derivatives, sensitive to edges and suitable for sharpening blurred images, but highly susceptible to noise and prone to producing false edges; denoising is usually required beforehand. 6） Gaussian Filtering: Uses Gaussian-function-weighted averaging of neighborhood pixels, effective at smoothing Gaussian noise, better preserving details than mean filtering, but still blurs edges and performs poorly against impulse noise. The larger the kernel or the larger the standard deviation, the wider the blurring range.
各滤波算法详解：1）均值滤波：通过取像素邻域平均值替换该像素，平滑图像、减少高频噪声，计算效率高，但会模糊边缘和细节，对脉冲噪声效果差。窗口越大，图像越模糊，运行时间越长。2）中值滤波：用邻域像素中值代替当前像素，能有效去除椒盐噪声等脉冲噪声，较好保留边缘，但对高斯噪声效果一般，计算复杂度较高，窗口增大时去噪效果提升但耗时增加。3）Roberts 交叉梯度算子滤波：基于一阶导数，通过两个卷积核计算水平和垂直梯度以突出边缘，检测细小边缘效率高，但对噪声敏感，锐化强度过高易增强噪声。4）Sobel 算子滤波：使用加权卷积核计算梯度，抗噪声能力优于 Roberts 算子，适合检测较大范围边缘，对中等噪声图像适用，但边缘可能不够锐利。5）拉普拉斯算子滤波：基于二阶导数检测边缘，对边缘敏感，适合锐化模糊图像，但极易受噪声影响，可能产生伪边缘，通常需先去噪。6）高斯滤波：基于高斯函数加权平均邻域像素，平滑高斯噪声效果好，比均值滤波更能保留细节，但会模糊边缘，对脉冲噪声效果差，核越大或标准差越大，模糊范围越广。

Algorithm Comparison and Summary：Comparative analysis shows that mean and Gaussian filtering are suitable for denoising: the former is faster, whereas the latter better preserves details. Median filtering excels at handling impulse or salt-and-pepper noise. Roberts and Sobel operators are apt for edge detection, with the latter offering stronger noise immunity. The Laplacian operator is suitable for enhancing edge details but is sensitive to noise. For remote-sensing images with Gaussian noise, Gaussian filtering is optimal; when impulse or salt-and-pepper noise is present, median filtering is best; for edge extraction, choose the Roberts or Sobel operator according to noise conditions.
算法对比与总结：对比分析显示，均值滤波和高斯滤波适用于去噪，前者计算快，后者保留细节更好；中值滤波擅长处理脉冲或椒盐噪声；Roberts 和 Sobel 算子适合边缘检测，后者抗噪声能力更强；拉普拉斯算子适合增强边缘细节但对噪声敏感。对于含高斯噪声的遥感图像，高斯滤波为优选；含脉冲或椒盐噪声时，中值滤波最佳；边缘提取可根据噪声情况选择 Roberts 或 Sobel 算子。

Through studying these filtering algorithms, I improved both theoretically and practically. Theoretically, I gained deep understanding of the principles, applicable scenarios, advantages, and disadvantages of different filters, clarifying how parameter adjustments affect results—such as how window size and sharpening intensity alter denoising and edge-detection outcomes.
通过研究这些滤波算法，我在理论和实践层面均有提升。理论上，深入理解了不同滤波算法的原理、适用场景及优缺点，明确了参数调整对效果的影响，如窗口大小、锐化强度等如何改变图像去噪和边缘检测效果。

Practically, I mastered the implementation logic of each algorithm. By comparing the results of different filters, I learned to select the appropriate method according to specific needs—for example, prioritizing median filtering for salt-and-pepper noise and considering the Sobel operator for edge detection. Meanwhile, analyzing algorithmic computational complexity made me realize the importance of balancing efficiency and effectiveness in real applications.
实践中，掌握了各算法的实现逻辑，通过对比不同算法处理结果，学会了根据具体需求选择合适滤波方法，例如处理椒盐噪声优先选中值滤波，边缘检测可考虑 Sobel 算子。同时，对算法计算复杂度的分析让我认识到效率与效果的平衡在实际应用中的重要性。

This study also let me appreciate the critical role of filtering technology in remote-sensing image processing, accumulating knowledge and experience for future handling of actual image data and optimization of image-processing workflows, and sparking my interest in exploring more complex filtering algorithms.
此次研究也让我体会到滤波技术在遥感图像处理中的关键作用，为今后处理实际图像数据、优化图像处理流程积累了知识和经验，激发了对更复杂滤波算法的探索兴趣。

- [Back to the top of the page](#back-to-the-top-of-the-page)
- [返回页面顶部](#返回页面顶部)
