#  SmartCity&Education

> Other languages: [中文版](README-zh.md)

## Introduction

This repository is mainly about a series of research work of the intelligent service research group led by Mrs. Sun Yanchun of Peking University during the past three years, whose research is mainly about smart city services and smart learning services based on big data analysis. 

Smart city services are mainly based on various public data such as Weibo, POI, public transportation data, etc., combined with a variety of machine learning models and data mining methods, from the functions of urban areas, transportation convenience, population density distribution, building functions, etc.,  comprehensively describe urban geographic semantic information from multiple perspectives; smart learning services are mainly based on public data from open source communities such as GitHub, StackOverflow, CSDN, and CNBlogs, and perform different types of data analysis and mining such as user-relationship, repository, API, and code, excavate and establish user learning and development demand models, and provide learning content automatic generation and recommendation services for learners' personalized learning needs based on deep learning, knowledge graph, NLP and other technologies.

This repository stores research on smart city services and smart education services, mainly including papers, patents, competitions, codes, open source systems, and data used in the analysis process. The authors of these projects include both graduate and ungraduate students, some unpublished works are excluded.



## Repository List

- https://github.com/delavet/SOworkspace

  - author: Hang Yin
  - title: An API learning Service designed for inexperienced developers. Powered by StackOverflow, Wikipedia, Javadoc, etc
  - conference: ICWS 2021
- https://github.com/zhouyuqi1492/GHTRec-Service

  - author: Yuqi Zhou
  - title: GHTRec：A Personalized Service to Recommend GitHub Trending Repositories for Developers
  - description: Repositories are implementations of the services in the paper for recommending topics that users might link to their repositories.

  - conference: ICWS 2021
- https://github.com/Vremold/LinkSO
  - author: Jiawei Wu
  - description: A weak supervised approach to link Stack Overflow posts to programming language textbooks. Mainly relies on matching in 3 extracted features: keywords, semantics and code elements
  - year: (2022~, unpublished yet)
- https://github.com/Vremold/DLS/

  - author: Jiawei Wu
  - title: An Open-source Repository Retrieval Service Using Functional Semantics for Software Developers
  - description: This work mainly mines structured and unstructured functional semantic information from existing front-end open source libraries, and provides retrieval services for user queries on this basis.
  - conference: ICSS 2022 (Best Paper)
  - competition: NCSC 2022
  - project front-end repo: https://github.com/quackson/Semantical-Library-Retrieval
- https://github.com/Git-JK/A-Retireval-System-Based-on-the-Functional-Semantics-of-Stack-Overflow-Posts
  - author: Ke Jin
  - description: Use verb phrases and phrase patterns to extract explicit functional semantics contained in Q&A post titles, and use a Bert-based bertlets model to extract implicit functional semantics contained in question descriptions and answers and answer posts, matching the explicit functional semantics of the question to be queried. Explicit and implicit function semantics, thus recommending StackOverflow Q&A posts.
  - year: 2022
- https://github.com/Harris-pku/graduation_design
  - author: Yuanhao Zheng
  - description: Chinese Question Answering Community Retrieval System
  - year: 2022
- https://github.com/quackson/cn_blogs-analysis
  - author: Zihan Xu
  - This repository is a research on the Chinese tech community cnblog. Graph methods are used for Modeling and Classification of Chinese blogs. 
  - year: 2021
- https://github.com/quackson/springbootApiUsageCase
  - author: Jiaqi Zhang
  - title: An API case recommendation service based on open source community analysis
  - description: This research is mainly a case search study for springboot beginners, and the data comes from GitHub open source data. The algorithms used are mainly graph kernels and spectral clustering. 
  - conference: NCSC 2021



## Paper List

1. Jiawei Wu, Yanchun Sun (Corresponding Author), and Jiaqi Zhang. **An Open-source Repository Retrieval Service Using Functional Semantics for Software Developers.** CCF 15th International Conference on Service Science (ICSS 2022), May 13-15, 2022 (Best Paper Award).
2. Yanchun Sun, Hang Yin, Jiu Wen, Zhiyu Sun. **Urban Region Function Mining Service Based on Social Media Text Analysis[J].** International Journal of Software Engineering and Knowledge Engineering, 2021, 31(4): 563-586.
3. Hang Yin, Yuanhao Zheng, Yanchun Sun (Corresponding Author), Gang Huang. **An API Learning Service for Inexperienced Developers Based on API Knowledge Graph.** In Proceedings of IEEE International Conference on Web Services (ICWS 2021), online virtual congress, September 5-10, 2021.
4. Yuqi Zhou, Jiawei Wu, Yanchun Sun (Corresponding Author). GHTRec: A **Personalized Service to Recommend GitHub Trending Repositories for Developers.** In Proceedings of IEEE International Conference on Web Services (ICWS 2021), online virtual congress, September 5-10, 2021.
5. Hang Yin, Zhiyu Sun, Yanchun Sun (Corresponding Author), Gang Huang. **Automatic Learning Path Recommendation for Open Source Projects Using Deep Learning on Knowledge Graphs.** In Proceedings of 2021 IEEE 45th Annual Computers, Software, and Applications Conference (COMPSAC 2021), all-virtual, July 12-16, 2021.
6. [Chinese] Jiaqi Zhang，Yanchun Sun（corresponding author，Gang Huang. **API Case Recommendation Service Based On Open Source Community Analysis[J].** Computer Application, DOI: 10.11772/j.issn.1001-9081.2021122070.
7. Yanchun Sun, Hang Yin, Jiu Wen, Zhiyu Sun. **Urban Region Function Mining Service Based on Social Media Text Analysis.** Proceedings of the 13th International Conference on Service Science (ICSS 2020), Qinghai, China.
8. [Chinese] Jiawei Wu, Yanchun Sun (corresponding author). **Consultation recommendation system integrating knowledge graph and deep learning method[J].** Computer Science and Exploration, 2021, 15(8): 1432-1440.
9. Zhiyu Sun, Fang Peng, Junrui Guan, Yanchun Sun(Corresponding Author). **Learning path recommendation based on machine learning.** In Proceedings of ACM Internetware 2019, Fukuoka, Japan, October 28-29, 2019.
10. Hang Yin, Zhiyu Sun, Yanchun Sun(Corresponding Author), Wenpin Jiao. **A Question-Driven Source Code Recommendation Service Based on Stack Overflow.** In Proceedings of IEEE SERVICES 2019, Milan, Italy, July 8-13, 2019.
11. Zhiyu Sun, Chao Xin, Yanchun Sun(Corresponding Author). **An Automatic Semantic Code Repair Service Based on Deep Learning for Programs with Single Error.** In Proceedings of IEEE SERVICES 2019, Milan, Italy, July 8-13, 2019.
12. Jiao Wenpin, Sun Yanchun. **A values-driven self-organization mechanism for automating multiagent coordination[J].** Computational Intelligence, 2018, 34(2):635-678.
13. Jialun Shao, Yanchun Sun(Corresponding Author). **A Recommendation Service for Programming Study Based on Stack Overflow.** In Proceedings of IEEE SERVICES 2018, San Francisco, USA, July 2-7, 2018.
14. Jiu Wen, Yanchun Sun(Corresponding Author). **A Map-Matching Service Designed for Courier Trajectories.** In Proceedings of the 24th IEEE ICWS 2017, Hawaii, USA, June 25-30, 2017.
15. Yanchun Sun, Chao Xin. **Using Coursera Clickstream Data to Improve Online Education for Software Engineering.** In proceedings of ACM TUR-C '17, Shanghai, China, May 12-14, 2017.
16. Yanchun Sun, Kui Wei, ZijianQiao, Jiu Wen, Tianyuan Jiang. **A Personalized Service for Scheduling Express Delivery Using Courier Trajectories.** In Proceedings of the 23rd IEEE International Conference on Web Services（ICWS 2016）, San Francisco, USA, June 27 - July 2, 2016.
17. Yanchun Sun, ZijianQiao, Dejian Chen, Chao Xin, Wenpin Jiao. **An Approach to Using Existing Online Education Tools to Support Practical Education on MOOCs.** In Proceedings of the 40th IEEE Computer Society International Conference on Computers, Software & Applications（COMPSAC 2016）, Atlanta, Georgia, USA, June 10-14, 2016.
18. Wenpin Jiao, Yanchun Sun. **Self-adaptation of multi-agent systems in dynamic environments based on experience exchanges[J],** Journal of Systems and Software, Volume 122, December 2016, Pages 165–179.



## Patent List

1. A Construction Method of Urban Geographic Semantic Knowledge Graph

   - patent no.：ZL201910725275.4
   - person to complete：Yanchun Sun、Gang Huang、Zixuan LinLiu，Zhiyu Sun。
   - date of authorization：2022.3.25

2. A Comprehensive Urban Geographic Semantic Mining Method based on Multivariate Big Data

   - patent no.：ZL201910701692.5

   - person to complete：Yanchun Sun、Gang Huang、Yu Liu、Jiu Wen

   - date of authorization：2022.1.28

3. An Optimization Method and System for Open Source Project Knowledge Graph

   - patent no.：ZL202010643010.2

   - person to complete：Yanchun Sun、Gang Huang、Zhiyu Sun

   - date of authorization：2021.6.25

4. A Recommendation Method and System for Supporting Fragmented Learning in Open Source Projects

   - patent no.：ZL202010643009.X

   - person to complete：Yanchun Sun、Gang Huang、Zhiyu Sun

   - date of authorization：2021.5.28

5. A Mining Method of Disease Influencing Factors based on Gene Chip Data

   - patent no.：201710595987X

   - person to complete：Yanchun Sun，Zijian Qiao

   - date of authorization：2020.3.20

6. A Diet Control method and Control System for Mobile Health and Medical Care

   - patent no.：ZL 201610681391.7

   - person to complete：Yanchun Sun、Lingyun Zu、Zhiyu Sun、Jialun Shao

   - date of authorization：2018.12.04

7. A Method for Recommending Optimal Contact Information to Mobile Users based on Context Awareness

   - patent no.：ZL 201410709710.1

   - person to complete：Yanchun Sun、Xiwei Zhuang、Kui Wei、Gang Huang

   - date of authorization：2018.02.09

8. An Online Vector Modeling Process Description and Reproduction Method

   - patent no.：201410662733.1

   - person to complete：Yanchun Sun, Dejian Chen, Gang Huang

   - date of authorization：2017.11.06



### Contest Award List

1. Jiawei Wu, Yanchun Sun, and Jiaqi Zhang. An Open-source Repository Retrieval Service Using Functional Semantics for Software Developers. CCF 15th International Conference on Service Science (ICSS 2022), May 13-15, 2022 (**Best Paper Award**).
2. Jiawei Wu, Jiaqi Zhang, "An Open-source Repository Retrieval Service Using Functional Semantics", won the first prize of the 2022 China Digital Service Conference Software Service Innovation Competition. (Instructor: Yanchun Sun)
3. Yuqi Zhou, Jiawei Wu, "A Personalized Service to Recommend GitHub Trending Repositories for Developers", won the first prize of the 2021 China Digital Service Conference Software Service Innovation Competition. (Instructor: Yanchun Sun)
4. Hang Yin, "A Question-driven Java Code Retrieval Service based on Stack Overflow", Won the second prize of the 2018 China Computer Federation Service Computing Academic Conference Software Service Innovation Competition. (Instructor: Yanchun Sun)
5. Lecong Zhang, Jiu Wen, "Location Semantics-Oriented Smart Map Service", Won the third prize of the 2018 China Computer Federation Service Computing Academic Conference Software Service Innovation Competition. (Instructor: Yanchun Sun)

