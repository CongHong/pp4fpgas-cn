# 译序
利用FPGA进行算法加速和实现已经被广泛认知，但对于很多没有FPGA和HDL设计经验的开发者而言，往往又觉得开发门槛较高，因此全球相关的科研和工程人员都在致力于如何将FPGA技术介绍给更多的开发者，使更多人从FPGA的并行性，高性能，低功耗，灵活配置中获益。其中，Vivado HLS（高层次综合）就是一个成功的代表。通过Vivado HLS 工具中，开发者可利用C/C++语言对FPGA进行编程，这项技术已经趋于成熟，在Xilinx客户的工程实践中也已广泛采用。

为此Xilinx研究院一直在考虑如何将HLS这项技术更好的介绍给学术圈，帮助原来熟悉FPGA开发的提高开发效率，帮助原来不了解FPGA开发的快速上手FPGA算法实现。此次Xilinx研究院的Steve首席工程师与UCSD的Ryan Kastner教授团队合作，推出了这本电子书，全书通过10个算法实现案例完整的介绍了通过HLS工具利用C/C++语言快速实现高性能FPGA实现的过程。看到这本电子书，我顿时觉得这就是我想要找的内容。这本书通过多年的工程、科研、教学经验的积累，深入浅出的将HLS实现方法，硬件设计的考虑以及系统优化都一一介绍。

因此，在此书刚刚推出后，我们在FPGA技术群里就发起了翻译志愿者的活动，当天就得到了本书的翻译者曹越，吴彦北，胡博，王芝斌，杨勇的支持，同时由Xilinx实习生胡成龙作为翻译项目经理，通过Github平台带领志愿者们开始协同翻译的工作，并将其电子版以博客的形式部署到GitHub Page和Gitbook上。Xilinx实习生李彦晔和陈雯也完成了部分翻译和审校工作，以及全部工程实现。大家都抱着一个心态，希望尽快将此书介绍给国内的读者。利用工作之余的时间，在短短两个月的时间内完成了本书的翻译，初次校对，以及全书工程实现的目标。本书的工程实现也有一定的特点，相关工程不仅仅实现了算法的并行编程，同时利用Pynq框架，在Pynq-Z2上通过Python实现了算法实现过程的可视化，这是相比于原始英文版加强之处。

相信通过阅读此书，可以让更多人了解、尝试并喜欢上FPGA开发，本书只是一个开始，我们也欢迎更多人的爱好者和我们一起来拓展HLS的应用场景，并将知识记录和传递下去。有任何疑问和建议，请与我联系 joshua.lu@xilinx.com 。

陆佳华

2018年8月

## 译者风采
本次翻译我们用了技术社区内最geek的范儿，向技术社区内征求志愿者，通过在GitHub上协作写作，共同完成了本稿书籍的翻译工作。下面我们将以负责翻译的章节顺序介绍各位译者的风采。

![胡成龙，复旦大学计算机科学技术学院在读研究生，Xilinx实习生](images/hcl.png)

![李彦晔，伊利诺伊大学香槟分校本科在读，Xilinx实习生](images/lyy.png)

![曹越，现就职于中国科学院电子学研究所，研究方向为实时信号处理。工作至今已完成多个合成孔径雷达实时信号处理项目，在雷达成像、动目标检测和识别领域有丰富的工程经验。](images/cy.png)

![陈雯，东南大学电气学院在读研究生，Xilinx实习生](images/cw.png)

![吴彦北，武汉邮电科学研究院硕士毕业，目前主要工作方式向是医疗图像处理FPGA平台相关的开发。](images/wyb.png)

![胡博，本硕毕业于哈尔滨工程大学。上学期间多次参加国家挑战杯（国家三等奖）、"博创杯"全国嵌入式设计大赛（国家一等奖）、Robosub全球水下机器人大赛（全球第五）、微软imageinecup等比赛。目前主要从事视频编解码、图像预处理、目标识别与跟踪等相关工作。近几年技术方向积累多围绕SOC相关开发来构建自己的知识体系，主要是逻辑设计（Verilog和HLS）、驱动开发（Linux及裸核）、Linux系统上应用程序设计等。目前正在研究深度学习在前端智能中的应用。](images/hb.png)

![王芝斌，江南大学计算机科学与技术硕士毕业，原OpenHEC FPGA 云初创公司联合创始人、技术合伙人，现任科大讯飞研究院高级软件工程师，从事异构计算、云计算方面的工作。基于HLS 的光流算法加速工作发表在FPGA、FPT、FSP 和ACM TACO 等国际会议或期刊上。](images/wzb.jpg)

![杨勇（网名：rowen800），2013年于华中师范大学获得无线电物理专业硕士学位，具有5年的FPGA设计和板级硬件开发经历，主要从事数字信号处理、无线通信以及FPGA应用技术的研究。活跃于各大电子技术论坛，分享了多篇博文，个人的技术博客深受广大网友的喜爱。](images/yy.png)
