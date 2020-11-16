SNN_summaries

this repository record my  learning in spiking neural network, and [this](https://github.com/shenhaibo123/SNN_arxiv_daily) is my subscriptions of SNN daily in arxiv.

## Combined With Event Camera 



### Datasets

------



### [Papers]("each paper is tried to be organized as [year][trans/meeting][first author] name [paper_link with note from youdao][code(language)] [notes]")

#### `HMAX`

- [ ] [**2015**] [**IEEE Trans. Neural Netw. Learn. Syst.**] [**Zhao, B.**]  Feedforward categorization on aer motion events using cortex-like features in a spiking neural network. [**paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6933869 "本文介绍了一种事件驱动的前馈分类系统，该系统从时间对比地址事件表示(AER)传感器获取数据。该系统提取生物启发的类似皮质的特征，并使用AER基于tempotron分类器(一个泄漏的整合和激活脉冲神经元网络)来区分不同的模式。系统最吸引人的特性之一是其事件驱动的处理，输入和特性都采用地址事件(spikes)的形式。该系统在AER姿势数据集上进行了评估，并与两个最近开发的仿生模型进行了比较。实验结果表明，该算法在保持相同性能的前提下，大大减少了仿真时间。
  此外,混合国家标准与技术研究所的实验(MNIST)图像数据集已经证明该系统不仅可以工作在原始AER数据还在图片(一个预处理步骤将图像转化为爱尔兰事件),并能保持竞争力的准确性即使噪音是补充道。
  该系统在MNIST动态视觉传感器数据集(其中使用AER动态视觉传感器记录数据)上进行了进一步评估，测试精度为88.14%。")

- [ ] [**2020**] [**AAAI  oral**] [**Q. Liu**] Effective AER Object Classification Using Segmented Probability-Maximization Learning in Spiking Neural Networks. [**paper**](https://arxiv.org/abs/2002.06199   "摘要地址事件表示(AER)摄像机与传统的基于帧的摄像机相比，具有高时间分辨率和低功耗等优点，近年来受到越来越多的关注。
  由于AER摄像机将视觉输入记录为异步离散事件，它们天生适合与spiking神经网络(SNN)协调，这在神经形态硬件上是生物学上可信的和节能的。然而，使用SNN进行AER对象分类仍然具有挑战性，因为缺乏有效的学习算法来进行这种新的表示。
  为了解决这个问题，我们提出了一种新的分段概率最大化(SPA)学习算法的AER对象分类模型。在技术上，(1)SPA学习算法迭代地最大化样本所属类别的概率，以提高神经元响应的可靠性和学习的有效性;
  (2) SPA引入峰值检测(peak detection, PD)机制，逐段定位信息时间点，学习可以充分利用整个事件流中的信息。
  大量的实验结果表明，与现有的方法相比，我们的模型不仅更有效，而且需要更少的信息以达到一定的精度。"      ) 



#### Time-Surfaces

- [ ] [**2017**] [**TPAMI**] [**Lagorce, X.**] Hots: a hierarchy of event-based time-surfaces for pattern recognition. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7508476&tag=1"本文描述了一种新的基于事件的时空特征，称为时间表面，以及如何使用它们来创建一个基于事件的分层模式识别架构。与现有的模式识别层次结构不同，该模型依赖于面向时间的方法，从视觉场景异步获取的动态中提取时空特征。这些动态是通过生物启发的无框架异步事件驱动的视觉传感器获得的。与皮质结构类似，我们层次结构中的后续层次使用越来越大的时空窗口提取越来越抽象的特征。其核心概念是利用事件所提供的丰富的时间信息，以时间表面的形式创建上下文，以表示局部空间邻域内最近的时间活动。我们证明了这个概念可以稳健地用于基于事件的层次模型的所有阶段。第一层特征单元对像素组进行操作，随后的层特征单元对较低层次特征单元的输出进行操作。我们报告了之前发布的36类字符识别任务和4类规范动态卡pip任务的结果，每个任务都实现了接近100%的准确性。我们引入了一个新的七类运动人脸识别任务，达到了79%的准确率")