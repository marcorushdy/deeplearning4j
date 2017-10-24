---
title: 如何管控人工智能？
layout: cn-default
---

# “天网”问题：如何管控人工智能？

从本质上看，人工智能是很难监管的，因为它其实只是在一些芯片上运行的数学算法和程序代码，任何程序员都可以在自家车库里随意使用这些算法和代码工作，推动人工智能不断进步。

法规监管的对象一般需要是可见且可及的事件。但是谈到对算法和代码进行约束时，这一条件可能就无法满足了——我们怎样才能知道算法和代码何时会出现？如何分辨算法是善是恶？

人工智能研究正在向实现强人工智能逐步迈进，对其进行监控也许并非完全不可行，但所有相关方都将为此付出高昂的代价，研究者则有可能面临沉重的负担。

实际情况更为复杂，因为世界上许多国家都在进行人工智能研究，它们认为在人工智能领域取得优势可以带来各种短期效益。所以这些国家不可能接受其他国家或国际组织实施的规则。

即便它们从理论上接受应当对人工智能实行全球监管的观点，要说服众多互为竞争对手的国家就各种复杂的议题达成共识依然十分困难，气候变化监管以及石油输出国组织的定价会议已经证明了这一点。

因此，我们固然可以设想应当用哪些规则来约束人工智能，但不能天真地以为这些规则实施起来很容易。

<p align="center">
<a href="http://deeplearning4j.org/quickstart" class="btn btn-custom" onClick="ga('send', 'event', ‘quickstart', 'click');">Deeplearning4j快速入门指南</a>
</p>

我们或许可以对人工智能软件的开发者提出以下几点要求：

1）让我们听见“心跳”。“心跳”指的是一小段“打电话回家”的代码。换言之，这段代码会让开发者知道代码正在被人使用。对于任何被界定为人工智能的程序而言，这一约束机制可以让人工智能的开发者（或者某种经授权的中央机构）知道程序已经启用。

2）有了“心跳”，自然就可以设置独特的身份标识。让我们确保每个智能体都有一个独特的标识，以此来约束人工智能。

3）每个有着独特标识的智能体都应当有为其负责的人类开发者和/或所有者。这也就是说，每个人工智能程序都应当包括并披露其所有者和开发者的身份信息，以便在出现问题时联系代码的负责人，由负责人协助解决相关问题。

4）紧急切断开关。对于超人工智能最大的担忧是出现能力远超人类、可以自我改进且不关心人类处境的人工智能。监管者可以要求在所有的人工智能程序中建立后门，允许特定人士（政府监管人员，或者甚至是所有者？）由此访问人工智能并发出将其关闭的指令。

5）为递归和对抗训练规定软性或硬性上限。在证明其算法可以击败围棋特级大师的论文中，DeepMind描述了训练自主智能体相互对弈的过程（亦即人工智能通过彼此回应来学习，或者说人工智能使其自身变得更聪明）。以递归方式提升人工智能可能是通向超人工智能的最快途径了，所以应当关注递归训练。我并不是说这一定可行，但还是要指出监管者应当注意的领域。

6）对超强性能芯片及其集合的销售进行监控和管制。深度人工神经网络和其他算法需要消耗大量计算资源。它们需要用海量的硬件（或者很长的时间）来训练才能实现准确的预测。这类硬件主要是组成大型集群的特种芯片，可以用于运行优化的软件，在合理的时间内得到结果。所以我们可以追踪芯片。制造更快更好的芯片远比开发更好软件困难，而且对监管者而言，追踪和约束这类实体物件比追踪代码要来得容易。上述1～4项也可以烧录到芯片中。（我认为目前的芯片都还不足以产生威胁，不过这一现状可能会因为未来芯片集群规模的直线提升而改变。但是，如果量子计算机与人工智能相结合，我们将会看到自主人工智能体的能力和复杂度出现飞跃。）

7）追踪机器学习博士的职业发展，关注这类人才聚集的企业。

8）为配备人工智能的无人机和其他载具安装能够识别人类伤亡情形或求救信号的传感器（这其实相当可行）。世界各国的军队已经在制造用于杀伤人员的无人机。这已不是什么新鲜事物。军方很可能会不断造出杀伤方式越来越智能化的无人机。我建议采用自动化的方式来识别由人工智能控制的无人机如何伤害人类。我们可以将这一系统在获准动用致命武力的无人机上进行测试，从而研制出可以确保人工智能不会失控的系统，再安装到一切由人工智能控制的机器上。

思考人工智能管控（或者至少是管控某种特定智能水平的人工智能）的方法之一是将其与动物管制类比。饲养宠物的人必须已特定的方式管制和约束自己的宠物，比如不能让宠物在人行道上大便，应当让宠物接受绝育手术，应当教会宠物在大多数情况下不去伤害或攻击其他人。不过并不是每一位饲主都会管制和约束自己的宠物。有时这些宠物会野化，毫无约束地繁殖后代，有时又会破坏财产、伤害人类。但是从总体上而言，我们仍然受益于动物管制法律。

*－Chris Nicholson，2016年7月*

### <a name="beginner">其他Deeplearning4j教程</a>
* [Word2vec：基于Java语言的神经词向量](./word2vec)
* [神经网络简介](./neuralnet-overview)
* [受限玻尔兹曼机](./restrictedboltzmannmachine)
* [本征向量、协方差、PCA和熵](./cn/eigenvector)
* [LSTM和循环网络](./cn/lstm)
* [神经网络与回归分析](./linear-regression)
* [卷积网络](./convolutionalnets)