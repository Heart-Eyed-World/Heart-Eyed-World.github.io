---
layout: post
title: "谢君泽：论大数据证明"
date:   2020-04-07
tags: [大数据建模,司法证明,网络法学,智能社会]
comments: true
author: 山顶洞人
---

***（本文是博主发表的论文，原文刊发在《中国刑事法杂志》2020年第2期，脚注略）***



**【按语】大数据的直接运用模式是将其原始载体或等量复制数据直接作为证据使用；间接运用模式是将筛出的“小”数据或分析结论作为证据使用。二者都无法回避大数据建模这个技术方法问题。大数据证明的实践价值取决于实体法规范，方法本质是从相关关系“挖掘”出行为因果关系，技术关键是因果性数据的“辨别”。统计建模反映相关关系，可用于证据调查。行为建模反映行为因果关系，具有可解释性，可直接作为大数据证明的技术方法。应基于“保证证据信息原始性”的基本原则构建大数据取证规范体系，可赋予质证方无条件申请司法鉴定的权利以弥补质证权利的缺失，《司法鉴定程序通则》应恢复“自行制定有关技术规范”条款以使大数据建模得以进入司法鉴定领域。**



近年来，有关大数据的理论探讨和实践应用日渐升温，但与大多数信息学领域的问题一样，大数据的基本概念及特点，大数据要解决的核心问题，目前尚无统一认识。大数据的获取、存储、处理、分析等诸多方面也一直存在争议。对于新的事物，如果从认知上说清它往往很难一蹴而就，而从价值论上讨论它是有益的或是有害的又令人迷茫。从实用主义出发讨论大数据的运用思维乃至运用方法，可能更为实际，司法证明领域对大数据的讨论亦不例外。

从司法证明领域研究大数据，可以从价值论与方法论两个标准进行界定。从价值论标准判断，大数据之所以值得研究是因为大数据的运用可以产生某种实用意义上的增值价值。否则，仅是数据“大”只能体现数据的原始价值，这与普通的“电子数据”无异。从方法论的标准进行判断，大数据的运用必须基于某种有效的处理方法才能“挖掘”出增值价值。如果没有专门的大数据处理方法介入，而只是若干条信息的查询与使用，这并不是真正的大数据运用。比如，e租宝案件涉及的金融数据至少包括从4000多家银行、247家第三方支付平台、164家保险公司、114家券商汇总的1万多个账户的几十亿条资金交易流水信息。这些大数据的运用必须要经过专门方法的技术处理。本文从价值论（增值价值）与方法论（专门技术方法）的标准来界定大数据，并以此为逻辑起点围绕大数据证明展开分析和研究。

**一、大数据证明的基本问题**

大数据证明要解决何种证明困难，具体的证明路径和方法是什么，证明的关键又是什么。这些大数据证明的基本问题需要通过对大数据证明的运用模式、实践价值、方法本质、技术关键等展开分析讨论。

（一）大数据证明的运用模式

从逻辑上讲，大数据证据的运用主要有四种方法：第一种是把大数据所涉及的所有服务器（原始载体）作为证据使用；第二种是把服务器中的大数据（全样本）以等量复制的数据副本形式作为证据使用；第三种则是从大数据（全样本）筛出“小”数据作为证据使用；第四种是将大数据（全样本）经过计算模型处理后的分析结论（如数额）作为证据使用。前两种方法是把大数据（全样本）的原始载体或等量复制数据直接作为证据使用，可称为直接运用模式；后两种是把大数据分析筛出所得的“小”数据或分析结论[[2]]作为证据使用，可称为间接运用模式或转化运用模式。直接运用模式与间接运用模式的关键区别在于：前者将大数据技术处理的工作重心放在法庭举证、质证、认证阶段，而后者则放在取证阶段。

从司法实践来看，直接运用模式在很多情况下难以实现证明效果。首先，从取证技术角度看，提取大数据的原始载体抑或等量数据副本存在客观上的困难。大数据往往“分布式”地存储于一个庞大的服务器集群（“云”端），司法人员根本无法判断哪个或哪些才是涉案大数据的原始载体，甚至可能找不到原始载体的所在位置，也有可能“整个”服务器集群都是原始载体。即使借助于技术人员的帮助确定了涉案大数据的原始载体范围，也往往会因为涉案服务器数量过多或等量数据复制数据量过大而无法提取。不论原始载体的提取还是等量数据的复制都存在时间成本、人力成本、存储空间等司法资源代价问题。其次，从权利保障来看，直接运用模式还存在着权利被过度侵犯的风险。大数据服务器的扣押会使相关单位的生产经营活动受到影响，提取等量数据也会涉及到数据信息内容的正当权利保护问题。最后，直接运用模式无助于实质质证。表面上看，将大数据提交法庭满足了证据举证形式的要求。然而，脱离了原始环境与技术条件的大数据往往是“举而不能质”。不论是对大数据原始载体进行实质质证，还是对大数据的等量复制数据进行实质质证，都势必要基于数据的读取与分析。但是，大数据原始载体的运行往往依赖于服务器集群所组成的整体技术环境，如网络拓扑结构、网络系统设置及相关应用组件等，而对等量复制数据的分析同样存在着数据格式、数据定义等技术细节要求，更不必说大数据分析的时间耗费问题。因而，直接运用模式从逻辑上看“简单”“易行”，但往往无法实现实质质证的效果。

从制度设计上讲，大数据证据的运用应当以间接模式为原则，直接运用模式为例外。间接运用模式在技术可行性与司法资源投入成本上的优势是显而易见的。间接运用模式所存在的关键问题仍然是如何保障实质质证的效果。这从一定程度上可以通过巧妙的法律规则设计，创设一些特殊的质证规则予以实现。本文将在后文的制度保障部分进行论述。

诚然，不论采取哪种运用模式，都难以回避大数据的技术处理方法问题。作为一种新兴科学证据，技术处理方法不仅关系到大数据证据的证据能力也关系到大数据证据的证明力。因而，有必要对大数据运用的技术方法原理进行研究。

![谢君泽：论大数据证明](https://p3-tt.byteimg.com/origin/pgc-image/74569c8d7575470291aee5b109d608ee?from=pc)

​                                                             大数据运用的技术方法原理

上图从系统论角度描述了大数据运用在技术处理上的方法原理，即：在输入大数据后，系统根据大数据模型的算法处理，输出具有某种使用价值的分析结论。大数据的分析结论一般是一个具有增值价值的“小”结论。如果大数据的输出结论在“量”上依然是“较大”的，那么大数据并没有真正发挥它应有的价值。从司法证明角度而言，理想状态的大数据分析结论应当与案件事实密切相关，而不应是数量繁多、关系不清、指向不明、模棱两可，这往往无益于司法证明任务的达成。显然，大数据运用能否输出有效的证明结论取决于（主要以“算法”形式表达的）计算模型的有效构建，简称“大数据建模”。“大数据建模”关系到大数据能否实现司法证明的应有价值。

（二）大数据证明的实践价值

事实证明是为了实体法规范的适用，实体法规范的适用必须基于事实证明。从这个意义上讲，司法证明的应有价值必然取决于实体法规范的需求。在当下，我国实体法规范对大数据证明的价值需求集中体现在网络信息行为的后果或情节证明上。从理论上讲，大数据证明不限于行为后果或情节的证明，“人—机器—数据—行为”任两者之间都存在大数据证明问题。当下对行为后果或情节证明的特别关注从根本上讲是实体法规范使然。

我国现行刑法对待网络信息犯罪主要采取结果犯或情节犯的规制思维。比如，《刑法》第285条规定的非法侵入计算机信息系统罪，非法获取计算机信息系统数据，非法控制计算机信息系统罪，提供侵入、非法控制计算机信息系统程序、工具罪，第286条规定的破坏计算机信息系统罪以及第253条之一规定的侵犯公民个人信息罪等专业型网络信息犯罪都要求以某种“后果”或“情节”作为入罪门槛。这集中体现在《关于办理危害计算机信息系统安全刑事案件应用法律若干问题的解释》《关于办理侵犯公民个人信息刑事案件适用法律若干问题的解释》等相关司法解释文件之中。即使是像电信网络诈骗、网络造谣传谣等涉网型网络信息犯罪，同样有各式各样的“后果”或“情节”要求。这体现在《关于办理电信网络诈骗等刑事案件适用法律若干问题的意见》《关于办理利用信息网络实施诽谤等刑事案件适用法律若干问题的解释》等文件之中。上述犯罪对“后果”或“情节”的要求主要表现为对涉案资金金额、涉案对象数量、涉案行为次数等“数额”的要求，因此导致了每案必有“数额”计算或证明问题。

在数据时代背景下，如前述的e租宝案件，用于计算、证明犯罪“数额”的数据不仅体量庞大而且总是或多或少地与案件无关或相关的“数据”混杂在一起。这使得越来越多的“后果”或“情节”证明必须要借助于大数据分析才能解决。换言之，如何在个案中把涉及行为后果或行为情节的“数据”从大数据之中“准确”地“挖掘”出来，这是司法证明所面临的现实问题。不仅刑事法领域如此，民商事领域也同样存在相关行为的“损害结果”证明问题。

（二）大数据证明的方法本质

大数据证明主要依赖于技术处理方法，而计算处理方法主要体现为大数据的计算模型。因而，以算法为主要内容的计算模型，反映了大数据在技术处理上所采取的“测量”策略。

信息在记录与计量上的科学进步是影响人类社会发展的重要因素。《大数据时代:生活、工作与思维的大变革》对“数据”作如此描述：“计量和记录一起促成了数据的诞生，它们是数据化最早的根基。”大数据证据的产生不过是信息“记录”技术的科技成果，而大数据证明则是信息“记录”技术所带来的信息“计量”技术的方法挑战。

所谓计量，一般是指按照某种统一标准实现准确可靠的量值测量。换言之，要从技术上讨论大数据证明的“计量”问题，需从计量的技术标准与计量的技术方法两方面而展开。司法证明中，大数据计量的技术标准，也即大数据在技术处理上的计算依据，涉及到相关关系与因果关系之辨析。

司法证明活动中，大数据技术处理所采用的计算依据取决于实体法规范的要求。大数据证据的证明对象是以（实体法所调整的）“行为”为主要内容的待证事实，包括行为后果事实、行为情节事实等，而实体法对“行为”待证事实中“行为与后果”“行为与情节”之间的“联系”要求是十分明确的，即要求存在行为上引起与被引起的因果关系。

刑法学领域认为，“一个人只能对自己的危害行为及其造成的危害结果承担责任。因此，当危害结果发生时，要确定某人应否对该结果负责任，就必须查明他所实施的危害行为与该结果之间是否具有因果关系。危害行为与危害结果之间的因果关系，是指犯罪构成客观方面要件中的危害行为同危害结果之间存在的引起与被引起的关系。”在民事领域，因果关系是侵权行为民事责任的构成要件。“因果关系，是指侵权人实施的违法行为和损害后果之间存在因果上的联系。”“民法因果关系和刑法因果关系同属法律因果关系, 有其共同性。特别是民事侵权行为和刑事犯罪行为的关系尤为密切。”[[9]]不论是刑事实体法还是民事实体法（尤其是民事侵权行为），他们对行为与其相应后果、情节等结果事实之间的“联系”要求是一种“行为因果关系”，而非哲学意义上的“相关关系”。

因而，在司法证明领域，大数据在技术处理上的计算依据，或说大数据计量的技术标准是十分明确的，即实体法规范所提出的行为因果关系。事实证明是为了实体法规范的适用，司法证明的应有价值必然取决于实体法规范的需求。这意味着，实体法规范的价值目标决定了司法证明的方法要求。

基于此，大数据证明的方法本质可以归纳为：从相关关系的大数据中“挖掘”出具有行为因果关系的数据。至于如何“挖掘”则涉及到计量方法问题，也即大数据计算模型的构建问题。后文将从统计建模与行为建模这两种最为重要的建模方法展开论述。

（三）大数据证明的技术关键

大数据证明的方法本质是从相关关系的大数据中“挖掘”出具有行为因果关系的数据，这决定了大数据证明计量方法的要求。换言之，以大数据建模为核心的计量方法应当能够将具有因果关系的数据从相关关系的大数据中“挖掘”出来，其技术关键是因果性数据的“辨别”。

关于如何从技术上“辨别”数据，物证技术学领域的同一认定理论对思考有所裨益。在物证技术领域中同一认定就是通过对先后出现的客体留下的特征反映体进行检验，解决先后出现的客体是否同一的一种辨别方法。同一认定理论表明了作为中介的“特征反映体”是辨别此客体与彼客体的关键。这意味着数据的“辨别”势必也要基于某种类似“特征反映体”的实体。在网络信息环境下，这种“特征反映体”显然不再是一种物质性的反映形象或分离体，而应是某种具有类似“特征反映体”功能的信息。这种信息可以在相对概率上反映该客体与其他客体（个体或类型）有所不同，或者该客体与另一客体之间具有相互指向关系，它们可统称为“特征信息”。

在自然科学领域，人工智能识别技术对特征信息的运用，对数据“辨别”的技术研究也有重要的启发意义。“我们想要构建一个简单的人工智能系统，它能够像人类一样区分变色鸢尾和山鸢尾。像这样完成分类任务的人工智能系统，被称为分类器（classifier）。下图展示了整体系统的流程。当看到一朵鸢尾花时，首先提取它的特征，然后将这些特征输入到训练好的分类器中，分类器就能够根据这些特征做出预测，输出鸢尾花的品种。”这种特征的提取在人工智能识别的初级阶段主要依赖于经验。

![谢君泽：论大数据证明](https://p6-tt.byteimg.com/origin/pgc-image/ec5c4aeda1194305b086715e9af1122d?from=pc)

​                                                               特征提取与分类器

随着人工智能技术的发展，深度神经网络极大地提高了特征提取与分类器的工作效率。“深度神经网络之所以有这么强大的能力，就是因为它可以自动从图像中学习有效的特征……深度神经网络学习的特征也逐渐替代了手工设计的特征，人工智能也变得更加‘智能’……如下图所示，在传统的模式分类系统中，特征提取与分类是两个独立的步骤，而深度神经网络将二者集成在了一起。”

![谢君泽：论大数据证明](https://p1-tt.byteimg.com/origin/pgc-image/553397a9a4c043d98ae4790003ed1eba?from=pc)

​                                      基于深度神经网络的特征提取与分类器

人工智能识别技术发展到今天，已经全面运用于各个领域，如人脸识别、视频监控、识文断字、听声辨曲甚至是阿尔法狗的围棋程序。这一切的逻辑基础都是基于特征提取的分类方法。

特征信息是此事物区别于彼事物的认知“锚”点。不论是社会科学领域的同一认定理论还是自然科学领域的人工智能识别技术，都已经确定无疑地证明了这一结论。那么，大数据证明所要解决的数据“辨别”问题也不能例外。大数据证明的数据“辨别”与同一认定理论、人工智能识别的区别在于前者的对象是“数据”，依据是“行为因果关系”。即，大数据证明的技术关键是利用行为特征信息将具有行为因果关系的数据从大量数据中“测量”出来。



**二、大数据证明的建模方法**

大数据证明的实践价值是解决网络信息行为的后果情节证明问题，其方法本质是从相关关系“挖掘”出行为因果关系，其技术关键是因果性数据的“辨别”。这决定了司法证明领域的大数据建模应当主要基于反映行为因果关系的特征信息。基于行为特征信息的大数据建模，可以简称为“行为建模”。目前大数据行业普遍采用的、以统计方法为基础的建模方法，则可以简称为“统计建模”。“统计建模”在建模方法和证明功能上与“行为建模”大不相同。

（一）大数据的统计建模

顾名思义，统计建模是基于统计学的计算模型构建。从大数据实践来看，统计建模主要有基于关联因子的统计建模、基于趋势指标的统计建模和基于聚类特征的统计建模三类主流方法。

基于关联因子的统计建模，是指根据具有相关关系的因子形成参数体系进行统计分析的方法。比如，在大数据侦查领域，有人通过分析与业务风险相关的因子，如合规性指数、收益率偏离指数、投诉举报指数、传播力指数、特征词命中指数等构建统计参数体系，进而判断P2P（peer to peer）网贷平台是否存在“爆雷”风险。

基于趋势指标的统计建模，是指根据投产比、转化率、偏离率等指标的偏离异常进行统计分析的方法。比如，诸多互联网企业会通过分析注册成功转化率等指标来判断市场渠道质量及是否存在作弊行为。受益于趋势统计建模的思维，诸多单位已经建立了针对每一位员工的业绩大数据监管平台。

基于聚类特征的统计建模，是指根据行业、商品、人群等类型特征进行统计分析的方法。这种统计建模，最常见的是电子商务平台的广告推送，即根据用户购买的商品类型及消费习惯进行聚类分析并以此形成算法智能推送广告。

统计建模主要是基于业务行为的结果数据所进行的分析。因而，从结果数据的统计分析自然可以反向发现业务行为所存在的问题，包括违法犯罪行为。从证据意义上讲，统计建模能够用于发现违法犯罪行为后确定证据调查方向，划定证据存在范围。

然而，统计建模只注重“相关关系”，不注重“因果关系”。如果把统计建模作为大数据证明的主要技术方法，一般会面临合理性与科学性的质疑，作为间接证据或辅助性证据则另当别论。正如法理学领域学者所说：“证明过程需要依照理性的标准，发现案件事实真相……统计数据或数量上的可能性只是针对某类事物的一般描述，不能成为个人的具体事实。如果审判者仅仅根据统计数据，宣布某人的罪行成立，就违背了罪责自负的原则，因为没有充分理由足以让人相信，这是一个真实的案件事实。与统计数据相对，个别的、具体的证据是证明案件事实成立、保障罪责自由的理由。因此，在证明过程中，统计数据不能单独成为确定案情真实的依据，必须与个别的、具体的案件证据相一致，相配合。”按此理解，统计建模所体现的“相关关系”只是“某类事物”在统计数据或数量上的可能性，而不具备个别的、具体的“因果关系”指向性。从这个意义上讲，统计建模不符合司法证明的理性标准。

（二）大数据的行为建模

行为建模是一种能够反映行为因果关系的建模方法，具备司法证明的理性属性。行为建模的依据是个案中具体违法犯罪行为所遗留的特征信息，这种特征信息由人的具体行为所引起、产生、遗留。换言之，基于这种特征信息的大数据计算结果就能够从一定程度上反映具体行为与相应数据（行为后果、行为情节）之间的因果性。

鉴于个案的特殊性，行为特征信息的提取往往与个案行为方式及其所涉及的网络信息系统直接相关。因而，大数据的行为建模是一种具有个案针对性的具体技术方法。

比如，在一起虚假流量诈骗案件中，某广告商通过伪造虚假用户流量骗取互联网企业网络直播业务推广的广告费。该互联网企业通过投资回报率的统计分析发现，前述广告商的推广渠道之中，IP段尾数大于20的注册用户计算出的投资回报率明显低于IP段尾数小于等于20的注册用户；通过不同广告商的渠道比较分析发现，该广告商的推广渠道之中，使用同一支付账户充值的用户数量比例明显高于其他广告商（使用同一支付账户充值的用户数量）的比例；同时，在该广告商的子渠道中，存在大量使用同一支付账户充值超过100个注册账户的情形。以上是本案的统计建模分析。基于此，侦查人员发现该广告商存在伪造虚假广告流量的较大可能性，进而确定了侦查方向及涉案大数据证据存在的可能范围。

在统计建模确定大数据证据的存在范围后，需要通过行为建模来查明诈骗行为的具体实施过程，进而确定准确的诈骗数额。从伪造虚假广告流量的行为特征来看，使用同一支付账户给5个以上注册用户进行充值一般可认为是反常行为。根据这种反常行为的特征构建计算模型，可以发现：前述范围的大数据中，有113个支付账户符合上述反常行为的特征，这些支付账户的充值对象涉及12276个注册账户；在113个支付账户中，有4个支付账户给大量注册用户充值，分别涉及4827、2174、1513、739个注册用户；进一步对4个支付账户中的2个主要支付账户进行消费数据的行为分析，发现这2个支付账户的直播消费房间数量分别为6个和4个（即前者之中4个）；分析上述6个房间（主播）账户的提现行为，发现相关资金又被提现到最初充值的这2个主要支付账户。

以上行为建模分析，还原了该广告商通过注册、充值、消费、提现实施诈骗行为的整个“闭环”过程。显然，符合账户循环充值提现行为特征的涉案数据可以确定性地判断为诈骗金额。鉴于上述行为建模能够反映诈骗行为与诈骗数额之间的行为因果关系，因而其结论数据可以作为本案的定罪依据。然而，本案还存在漏算数额的可能，如使用2个主要支付账户以外的其他账户进行充值提现，以及使用2个主要支付账户充值后并非提现到初始账户等情形。基于上述考虑，可以把统计建模的分析结论作为量刑参考。

再如，在某刷单骗保案中，嫌疑人通过虚假购物并退货的方式骗取运费险赔付费。该案的实施过程是：第一步，嫌疑人首先购买一千多个某电商平台的账号（俗称“小号”），将自己控制的前端店铺全部开通运费险。第二步，嫌疑人使用小号在前端店铺购买一元商品并批量申请退货，同时在前端店铺批量确认退货。第三步，退货后电商平台自动支付运费险赔付费给小号。第四步，嫌疑人使用小号所收到的赔付费虚假购买、发货、收货，将钱款转移到正常经营的后端店铺后提现。

该案的核心问题是如何从交易大数据中“挖掘”出具有行为因果关系的骗保数额。在订单数据中，“收货地址”往往能够反映行为主体的特征信息；“小额支付”往往能够反映行为方式的特征信息，“IP地址”则一定程度上能够反映行为空间的特征信息。“收货地址”“小额支付”“IP地址”这三种数据都是由刷单骗保行为所引起，具有行为上的因果关系。以“收货地址”“小额支付”“IP地址”这三个特征信息进行建模，本案最终共“挖掘”出骗保金额1150余万元。

综上可见，行为建模能够反映行为与其相应后果、情节的因果性，因而是大数据证明的主要技术方法。因为行为建模是基于行为特征信息的提取，所以行为建模在行为因果关系上的强弱与行为特征信息的特征反映度密切相关。

（三）行为建模的可解释性

诚如法理学领域所提示，理性证明应当是“有充分理由足以让人相信”。这与证据法学领域的“说服责任”不谋而合。如果大数据证明不能进行充分地解释，那么势必无法说服别人、让人信服。因而，大数据证明的可解释性是理性证明的必然要求。

行为建模的可解释性体现在两个方面：一方面，行为建模具有行为因果关系上的可解释性。如在上述虚假流量诈骗案件中，通过行为建模分析，可以还原广告商骗取广告费行为的整个过程，而各个行为环节在引起与被引起的行为因果关系上也是明确可知的。另一方面，行为建模在行为因果关系上的强弱程度也是可解释的。比如，在上述刷单骗保案中，虽然行为建模使用了“收货地址”“小额支付”“IP地址”这三个行为特征进行分析，然而这三个特征在行为因果关系上的反映性有强有弱。作为特征信息，“收货地址”一般具有很强的特征反映性，以此为基础的行为建模及其所得数据的特征反映性也必然很强。相对而言，“小额支付”“IP地址”对违法犯罪行为的特征反映性并不够高，更适宜用作辅助印证。

虽说行为建模对行为因果关系的“挖掘”与证明具有重要意义，但是统计建模在确定证据调查方向与指明证据存在范围上的作用也不容忽视。从司法实务意义上讲，一般先通过统计建模确定行为因果关系数据是否存在或其范围，而后通过行为建模完成行为因果关系的证明。从“相关关系”到“因果关系”实际上是从宏观到微观、从抽象到具体、从整体到部分的过程。



**三、大数据证明的制度保障**

从理论上讲，证明方法的实践突破会影响诉讼程序的证据规范设计。“诉讼程序的法律规定和实践的许多差异, 在很大程度上是证明方法的规范模式和实践形态的不同知识特征所产生的程序效应。”下文将基于大数据的运用原理及技术方法，提出大数据证据证明的规范设计与制度保障。

（一）大数据的原始证据规则

如上文所述，大数据证明的运用在原则上应当采取间接运用模式。那么，大数据证明面临的首要挑战是一条具有悠久历史的证据法则，即原始证据规则。原始证据规则最早起源于文书的最佳证据规则。我国《民事诉讼法》第70条规定“书证应当提交原件”“物证应当提交原物”，《关于适用〈中华人民共和国刑事诉讼法〉的解释》第70、71条规定“据以定案的物证应当是原物”“据以定案的书证应当是原件”。《关于办理刑事案件收集提取和审查判断电子数据若干问题的规定》（以下简称《电子数据规定》）第8条也确立了“收集、提取电子数据，能够扣押电子数据原始存储介质的，应当扣押、封存原始存储介质”的基本原则。

然而，以“提交原始证据”为基本原则的制度规范设计并不能适用于大数据，因为大数据以“不提交原始证据”为常态。在大数据的司法运用中，显然不能再局限于原始证据规则的形式要求，而应追问原始证据规则的目的本质。从文书最佳证据规则的起源来看，正如威格默所说“对文书的**原始性**要求是少数几个能够追溯到1700年以前的规则之一”，它的目的在于保持文书的“原始性”。从证据的价值与功能来看，保持证据的“原始性”显然更有利于发现事实真相。经过复制、复印、传抄、转述等中间环节形成的传来证据，则容易造成证据信息的“失真”。不论从最佳证据规则的起源描述（即“原始性”）还是对原始证据规则的价值功能探讨，都可以发现其核心精神是：“保持证据信息的原始性”，以免“失真”。这意味着，对于大数据证据的间接运用而言，如果有合适的方法手段或制度规范能够保障大数据的证据信息不会产生“失真”，那么就可以不必苛求于最佳证据规则的形式遵守。

如何保障大数据的证据信息不会“失真”，可以借鉴有关电子数据最佳证据规则的例外条款。《电子数据规定》第9条规定“无法扣押原始存储介质的，可以提取电子数据，但应当在笔录中注明不能扣押原始存储介质的原因、原始存储介质的存放地点或者电子数据的来源等情况，并计算电子数据的完整性校验值”；第22条规定“对电子数据是否真实，应当着重审查以下内容：（一）是否移送原始存储介质；在原始存储介质无法封存、不便移动时，有无说明原因，并注明收集、提取过程及原始存储介质的存放地点或者电子数据的来源等情况；（二）电子数据是否具有数字签名、数字证书等特殊标识；（三）电子数据的收集、提取过程是否可以重现；（四）电子数据如有增加、删除、修改等情形的，是否附有说明；（五）电子数据的完整性是否可以保证。”值得注意的是，最佳证据规则的例外规定往往都存在“保持证据信息的原始性”的规范或技术保障。如，前述副本的“一致性”是电子数据原始证据规则例外规定在制度规范上的要求，前述“提取过程”“来源”“完整性”等要求则是其技术手段上的保障。从某种意义上讲，这其实是通过取证程序的规范性来保障证据本身的可靠性。

换言之，解决大数据的原始证据规则问题的关键在于：如何借鉴电子数据原始证据例外规则在制度规范和技术手段所提出的要求，基于大数据的特殊性，制定一套科学合理的规范体系。

构建大数据的取证规范体系，首先应当确立“保证证据信息原始性”的基本原则。在此基础上，可以从证据来源审查、取证过程记录、取证结果固定及取证主体资格等方面具体展开：首先，对大数据的来源做充分审查与固定。既包括对证据持有人、证据管理人等数据主体的审查，也包括对网络环境、系统架构、数据格式、数据定义等技术细节的固定。由于网络信息环境的特性，后者往往还有助于前者的确定。证据来源的有效固定往往关系到大数据证据的证明力。其次，对大数据的现场取证过程做充分记录与固定。如前文所述，大数据的计算模型及其构建方法往往直接决定了结果数据及分析结论的可靠性。因而，现场取证过程的关键是对大数据分析所使用的计算模型及其构建方法做详实记录并予说明。这直接影响到大数据证据的可信度，关系到大数据证明的成败。再次，对大数据分析的结果数据及分析结论做必要记录与固定，也可以附必要的解读说明。此为大数据取证的程序性要求，有利于与后续举证、质证、认证环节的衔接。此外，可以对大数据取证主体的资质或能力做必要审查。就大数据取证主体而言，司法鉴定人与专家辅助人通常是我国当下司法制度下最为重要的角色选择。在制度设计上可以将资质或能力作为取证主体的可选条件之一，平衡能力与资质的关系，以免出现“能者不会”“会者不能”的怪现象。

（二）大数据的质证权利保障

在间接运用模式下，大数据证据既可以表现为司法鉴定人的鉴定报告或专家辅助人的专业意见，也可以表现为司法人员的勘验检查笔录、当事人的书证或陈述意见乃至证人证言。在此情形下，质证对象往往是大数据分析的结果数据或分析结论，以及包含或随附的证据来源信息、取证方法过程、取证结果固定情况等等。

从形式质证上看，对于间接运用的大数据，可以借鉴勘验检查笔录或司法鉴定报告等的质证方法而展开。如，大数据分析的结果数据或分析结论是否由相应资质或能力的技术专家所作出，是否对大数据的证据来源作了充分审查与固定，是否由取证人员签字确认，等等。同时，鉴于大数据在技术方法上毕竟存在专门领域的特殊性，以建模为核心的技术方法应当始终是大数据质证的焦点问题，认证也不例外。

从实质质证角度而言，大数据的间接运用应当重点考虑质证权利规则的构建。显然，在大数据并非直接举证的情况下，质证方无法对大数据进行直接分析与质证，这实际上已经在一定程度上削弱乃至剥夺了质证权利。为了保障质证权利，从表面上看，允许质证方申请到大数据取证现场进行“重新”检验似乎是最为妥当的做法。然而，假如采取这种规则设计，势必面临另一种权利受到侵犯的风险。大数据往往涉及到大量的个人信息与商业秘密，质证方的“重新”检验会使数据信息内容“一览无余”，这极易导致对举证方或相关人的权利侵犯。

在此情形下，有必要引入一个中立性组织来缓和质证方与举证方及相关人之间的权利冲突。从目前来看，既具有法定保密义务又具有专业技术能力的司法鉴定机构可能是较为合理的中介选择。换言之，在举证方或相关人反对质证方“重新”检验的情况下，可以通过赋予质证方无条件申请司法鉴定机构到大数据现场进行“重新”检验的权利，以弥补质证权利的缺失。

（三）大数据的技术方法标准

如前文所述，作为一种新兴科学证据，技术处理方法不仅关系到大数据证据的证据能力也关系到大数据证据的证明力。在美国，技术方法的科学性审查是法官的“看守职责”，这直接涉及到科学证据能否进入陪审团的“视野”。在我国，法官一般不会对技术方法的合规性进行直接审查，而是将其交由司法鉴定管理制度去控制。法官往往是对司法鉴定报告进行形式审查，如是否由具备鉴定资质的司法鉴定机构作出、是否盖印司法鉴定专用章等。

司法鉴定管理制度对技术方法的控制标准决定了大数据能否顺利通过司法鉴定的途径进行司法领域。目前，我国司法鉴定管理制度对司法鉴定的技术方法标准是采取严格“法定”的态度。详言之，虽然司法部2007年《司法鉴定程序通则》第22条规定允许采用“司法鉴定机构自行制定的有关技术规范”开展鉴定，然而司法部在2016年修订《司法鉴定程序通则》时却取消了该条款。“司法鉴定机构自行制定的有关技术规范”一般被理解为技术方法标准的保留，在国家标准、行业标准不能及时更新的情况下，可以作为新兴技术方法的例外允许。新修订《司法鉴定程序通则》不再允许“司法鉴定机构自行制定的有关技术规范”，这已经关闭了新兴技术方法的“自制”空间。

关闭了新兴技术方法的“自制”空间，显然是不妥当的。从技术发展来看，科学技术显然永远是“开放”的。国家标准、行业标准需要一个“成熟”的过程，不可能跟得上技术发展的变化，即使是专业领域的同行专家，也很难就某一个新的技术问题迅速达成共识。因此，在制度设计上，应当允许少数司法鉴定机构与技术专家先行“发明”并运用某些新兴技术方法的例外情形。否则，包括大数据建模在内的新兴技术方法将会受制于现行司法鉴定管理制度的约束而无法在司法领域运用。

从法律运用来看，美国对科学证据的技术方法审查也是采用相对“开放”的标准。在1993年，美国最高法院在多伯特诉梅里尔·道药品公司一案中针对科学证据做出了一项里程碑式的裁决。此案判决在阐释《联邦证据规则》第702条以及703条规则的基础上,提出著名的四项新标准，即著名的“多伯特规则”：“1.科学技术的正确性是否已经或可以被检验;2.这个理论或技术已经由同行复核和公开发表;3.应该考虑已知的或潜在的错误发生率;4.法院应该考虑该技术在科学团体内的接受程度。”[[21]]其中，第1项的“可检验”标准和第3项的“错误率”标准可以认为是技术方法审查的自然科学标准，它是以自然科学的技术验证来判断；而第2项的“同行认可”和第4项的“团体接受”则可以认为是社会科学标准，它是通过专业领域的同行认可来判断。这四项科学证据标准显然都不是通过“国家标准”“行业标准”等形式进行“法定”控制的。

在科学证据的技术方法已经相对成熟的情况下，通过“国家标准”“行业标准”等形式进行“法定”控制是有益的，这能够保持技术方法的稳定性进而确保科学证据的可靠性。然而，过于严格地限制技术方法的准入标准则会对新兴科学证据的技术方法运用形成掣肘，在制度设计上应当做好技术方法的例外保留。

综上所述，《司法鉴定程序通则》应当恢复“司法鉴定机构自行制定的有关技术规范”的条款设计，以使大数据建模等新兴技术方法得以合规合法地进入司法鉴定领域并发挥其应有的价值。