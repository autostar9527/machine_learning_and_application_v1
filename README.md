# 清华出版社《机器学习与应用》第一版代码
本项目代码为雷明老师18年12月在清华出版社出版的《机器学习与应用》第一版中的配套代码，欢迎登录www.sigai.cn试听雷老师《[机器学习](http://www.sigai.cn/course_13.html)》《[深度学习](http://www.sigai.cn/course_18.html)》视频

## 作者简介

雷明，毕业于清华大学计算机系，研究方向为机器学习、计算机视觉。有超过12年的学术研究与产品研发经验，曾发表论文数篇，具有深厚的理论功底与丰富的实践经验。其撰写的系列技术文章在半年内累计阅读量达数百万次，擅长用生动、形象的语言把复杂、抽象的理论和算法解释清楚。

## 适读人群

- 计算机，电子，自动化，人工智能等相关专业的本科生，研究生
- 从事人工智能学术研究与产品研发的人员
- 对人工智能、机器学习感兴趣的人

## 本书优势

### 1、内容全面、系统，紧跟时代步伐
完整的讲述了机器学习、深度学习主要算法以及在各个领域的典型应用，含括了学术界与工业界截止2017年初的新成果，紧跟时代步伐，弥补了市面上经典教材内容老化的缺憾。
### 2、推导论证清晰、深入、详细
绝大部分核心算法均有详细的推导、证明过程，从问题本源、思想层面对算法进行讲解，让读者不仅知其然还知其所以然，真正掌握算法的思想与精髓。在书的前部对机器学习所需的数学知识也做了系统的讲解
### 3、核心算法配有实现细节介绍，使用示例，知名开源库代码分析
对大部分核心算法的实现细节进行了介绍，并配有示例程序与知名开源库源代码分析，包括OpenCV，libsvm，liblinear，Caffe，这对需要使用、实现机器学习算法的读者至关重要
### 4、重要算法的实际应用均有讲解
核心算法的实际应用都有介绍，对深度学习技术在计算机视觉、语音识别、自然语言处理、计算机图形学等领域的应用情况有详细而深入的介绍。这些内容能帮助读者掌握算法的实际应用方法、建模的思路。

## 购买指南

[目前本书在京东上打折包邮预售](https://item.jd.com/12504554.html)


## 完整目录

全书由21章组成，共分为三大部分。第1～3章为第一部分，介绍机器学习的基本原理、所需的数学知识（包括微积分、线性代数、概率论和优化方法），以及机器学习中的核心概念。第4～20章为第二部分，是本书的主体，介绍各种常用的有监督学习算法、无监督学习算法、半监督学习算法和强化学习算法。对于每种算法，从原理与推导、工程实现和实际应用3个方面进行介绍，对于大多数算法，都配有实验程序。第21章为第三部分，介绍机器学习和深度学习算法实际应用时面临的问题，并给出典型的解决方案。此外，附录A给出各种机器学习算法的总结，附录B给出梯度下降法的演化关系，附录C给出EM算法的推导。

一部分 基本概念与数学知识

 

第1章机器学习简介3

1.1机器学习是什么3

1.1.1一个简单的例子3

1.1.2为什么需要机器学习5

1.2典型应用7

1.2.1语音识别7

1.2.2人脸检测8

1.2.3人机对弈9

1.2.4机器翻译10

1.2.5自动驾驶11

1.3发展历程11

1.3.1历史成就11

1.3.2当前进展12

1.4关于本书13

参考文献15

 

第2章数学知识17

2.1微积分和线性代数17

2.1.1导数17

2.1.2向量与矩阵19

2.1.3偏导数与梯度21

2.1.4雅克比矩阵22

2.1.5Hessian矩阵23

2.1.6泰勒展开24

2.1.7行列式24

2.1.8特征值与特征向量25

2.1.9奇异值分解26

2.1.10二次型26

2.1.11向量与矩阵求导26

2.2最优化方法27

2.2.1梯度下降法27

2.2.2牛顿法28

2.2.3坐标下降法29

2.2.4拉格朗日乘数法30

2.2.5凸优化30

2.2.6拉格朗日对偶34

2.2.7KKT条件36

2.2.8拟牛顿法37

2.2.9面临的问题38

2.3概率论39

2.3.1随机事件与概率39

2.3.2条件概率39

2.3.3随机变量40

2.3.4数学期望与方差41

2.3.5随机向量41

2.3.6最大似然估计42

参考文献43

 

第3章基本概念44

3.1算法分类44

3.1.1监督信号44

3.1.2分类问题与回归问题45

3.1.3判别模型与生成模型47

3.1.4强化学习47

3.2模型评价指标48

3.2.1精度与召回率48

3.2.2ROC曲线48

3.2.3混淆矩阵50

3.2.4交叉验证50

3.3模型选择50

3.3.1过拟合与欠拟合50

3.3.2偏差与方差分解51

3.3.3正则化52

参考文献54

 

第二部分主要的机器学习算法与理论

 

第4章贝叶斯分类器57

4.1贝叶斯决策57

4.2朴素贝叶斯分类器58

4.2.1离散型特征58

4.2.2连续型特征59

4.3正态贝叶斯分类器59

4.3.1训练算法59

4.3.2预测算法60

4.4实验程序61

4.5源代码分析64

4.5.1主要数据结构64

4.5.2训练函数65

4.5.3预测函数68

4.6应用70

参考文献71

 

第5章决策树72

5.1树形决策过程72

5.2分类与回归树73

5.3训练算法74

5.3.1递归分裂过程74

5.3.2寻找最佳分裂74

5.3.3叶子节点值的设定77

5.3.4属性缺失问题77

5.3.5剪枝算法78

5.4实验程序79

5.5源代码分析81

5.5.1主要数据结构81

5.5.2递归分裂84

5.5.3寻找最佳分裂90

5.5.4寻找替代分裂96

5.5.5变量的重要性99

5.5.6预测算法100

5.6应用103

参考文献103

 

第6章k近邻算法104

6.1基本概念104

6.2预测算法104

6.3距离定义105

6.3.1常用距离定义105

6.3.2距离度量学习106

6.4实验程序107

6.5应用109

参考文献110

 

第7章数据降维111

7.1主成分分析111

7.1.1数据降维问题111

7.1.2计算投影矩阵111

7.1.3向量降维114

7.1.4向量重构114

7.2源代码分析114

7.2.1主要数据结构114

7.2.2计算投影矩阵115

7.2.3向量降维117

7.2.4向量重构117

7.3流形学习118

7.3.1局部线性嵌入119

7.3.2拉普拉斯特征映射119

7.3.3局部保持投影122

7.3.4等距映射123

7.4应用124

参考文献124

 

第8章线性判别分析125

8.1用投影进行分类125

8.2投影矩阵125

8.2.1一维的情况125

8.2.2推广到高维127

8.3实验程序128

8.4源代码分析131

8.4.1主要数据结构131

8.4.2计算投影矩阵132

8.4.3向量投影135

8.4.4向量重构136

8.5应用136

参考文献137

 

第9章人工神经网络138

9.1多层前馈型神经网络138

9.1.1神经元138

9.1.2网络结构139

9.1.3正向传播算法140

9.2反向传播算法141

9.2.1一个简单的例子141

9.2.2完整的算法145

9.3实验程序149

9.4理论解释152

9.4.1数学性质152

9.4.2与神经系统的关系153

9.5面临的问题153

9.5.1梯度消失153

9.5.2退化154

9.5.3局部极小值154

9.5.4鞍点154

9.6实现细节问题154

9.6.1输入值与输出值154

9.6.2网络规模155

9.6.3激活函数155

9.6.4损失函数156

9.6.5权重初始化156

9.6.6正则化156

9.6.7学习率的设定156

9.6.8动量项156

9.7源代码分析157

9.7.1主要数据结构157

9.7.2激活函数160

9.7.3权重初始化163

9.7.4训练函数164

9.7.5预测函数177

9.8应用179

参考文献180

 

第10章支持向量机182

10.1线性分类器182

10.1.1线性分类器概述182

10.1.2分类间隔182

10.2线性可分的问题183

10.2.1原问题183

10.2.2对偶问题184

10.3线性不可分的问题187

10.3.1原问题187

10.3.2对偶问题187

10.4核映射与核函数190

10.5SMO算法193

10.5.1求解子问题193

10.5.2优化变量的选择196

10.6多分类问题197

10.7实验程序198

10.8源代码分析200

10.8.1求解算法201

10.8.2主要数据结构204

10.8.3求解器211

10.9应用222

参考文献223

 

第11章线性模型225

11.1logistic回归225

11.2正则化logistic回归228

11.2.1对数似然函数228

11.2.2L2正则化原问题229

11.2.3L2正则化对偶问题232

11.2.4L1正则化原问题233

11.2.5实验程序234

11.3线性支持向量机236

11.3.1L2正则化L1 loss SVC原问题236

11.3.2L2正则化L2 loss SVC原问题237

11.3.3L2正则化SVC对偶问题237

11.3.4L1正则化L2 loss SVC原问题238

11.3.5多类线性支持向量机238

11.3.6实验程序240

11.4源代码分析241

11.4.1求解的问题241

11.4.2主要数据结构241

11.4.3求解器249

11.5softmax回归262

11.6应用263

参考文献264

 

第12章随机森林266

12.1集成学习266

12.1.1随机抽样266

12.1.2Bagging算法267

12.2随机森林概述267

12.3训练算法267

12.4变量的重要性268

12.5实验程序269

12.6源代码分析271

12.6.1主要数据结构271

12.6.2训练算法273

12.6.3预测算法282

12.7应用282

参考文献283

 

第13章Boosting算法284

13.1AdaBoost算法简介284

13.2训练算法284

13.3训练误差分析286

13.4广义加法模型288

13.5各种AdaBoost算法290

13.5.1离散型AdaBoost290

13.5.2实数型AdaBoost292

13.5.3LogitBoost292

13.5.4Gentle型AdaBoost294

13.6实现细节问题294

13.6.1弱分类器的选择295

13.6.2弱分类器的数量295

13.6.3样本权重削减295

13.7实验程序295

13.8源代码分析297

13.8.1主要数据结构297

13.8.2弱分类器300

13.8.3强分类器306

13.9应用——目标检测318

13.9.1VJ框架的原理319

13.9.2模型训练321

参考文献322


第14章深度学习概论324

14.1机器学习面临的挑战324

14.1.1人工特征325

14.1.2机器学习算法326

14.2深度学习技术326

14.3进展与典型应用328

14.3.1计算机视觉329

14.3.2语音识别331

14.3.3自然语言处理331

14.3.4计算机图形学332

14.3.5推荐系统332

14.3.6深度强化学习333

14.4自动编码器333

14.4.1自动编码器简介333

14.4.2去噪自动编码器334

14.4.3稀疏自动编码器334

14.4.4收缩自动编码器335

14.4.5多层编码器335

14.5受限玻尔兹曼机335

14.5.1玻尔兹曼分布335

14.5.2受限玻尔兹曼机336

14.5.3训练算法338

14.5.4深度玻尔兹曼机339

14.5.5深度置信网339

参考文献339


第15章卷积神经网络347

15.1网络结构347

15.1.1卷积层348

15.1.2池化层351

15.1.3全连接层351

15.2训练算法352

15.2.1卷积层352

15.2.2池化层355

15.2.3随机梯度下降法356

15.2.4迁移学习357

15.3典型网络357

15.3.1LeNet 5网络357

15.3.2AlexNet网络358

15.3.3VGG网络359

15.3.4GoogLeNet网络360

15.4理论分析361

15.4.1反卷积运算361

15.4.2卷积层可视化362

15.4.3理论解释364

15.5挑战与改进措施365

15.5.1卷积层365

15.5.2池化层365

15.5.3激活函数366

15.5.4损失函数366

15.5.5网络结构366

15.5.6批量归一化370

15.6实际例子371

15.6.1LeNet 5网络371

15.6.2训练自己的模型373

15.7源代码分析374

15.7.1Caffe简介374

15.7.2数据层376

15.7.3卷积层376

15.7.4池化层378

15.7.5神经元层378

15.7.6内积层384

15.7.7损失层386

15.7.8网络的实现——Net类396

15.7.9求解器398

15.8应用——计算机视觉413

15.8.1人脸检测414

15.8.2通用目标检测416

15.8.3人脸关键点定位425

15.8.4人脸识别425

15.8.5图像分割428

15.8.6边缘检测429

15.8.7风格迁移432

15.8.8图像增强433

15.8.9三维视觉435

15.8.10目标跟踪436

15.9应用——计算机图形学437

15.9.1几何模型438

15.9.2物理模型439

15.9.3纹理合成440

15.9.4图像彩色化441

15.9.5HDR442

15.10应用——自然语言处理444

15.10.1文本分类444

15.10.2机器翻译444

参考文献444
 

第16章循环神经网络450

16.1网络结构450

16.1.1循环层450

16.1.2输出层451

16.1.3一个简单的例子452

16.1.4深层网络452

16.2网络的训练453

16.2.1一个简单的例子453

16.2.2完整的算法455

16.3挑战与改进措施457

16.3.1梯度消失457

16.3.2长短期记忆模型458

16.3.3门控循环单元459

16.3.4双向网络459

16.4序列预测问题460

16.4.1序列标注问题460

16.4.2连接主义时序分类461

16.4.3序列到序列学习465

16.5应用——语音识别467

16.5.1语音识别问题467

16.5.2隐马尔可夫模型468

16.5.3高斯混合模型474

16.5.4GMM-HMM框架475

16.5.5深度模型475

16.6应用——自然语言处理478

16.6.1中文分词479

16.6.2词性标注480

16.6.3命名实体识别480

16.6.4文本分类481

16.6.5自动摘要483

16.6.6机器翻译483

16.7应用——机器视觉485

16.7.1字符识别485

16.7.2目标跟踪486

16.7.3视频分析488

参考文献490


第17章生成对抗网络494

17.1随机数据生成494

17.2生成对抗网络简介495

17.2.1生成模型495

17.2.2判别模型496

17.3模型的训练496

17.3.1目标函数496

17.3.2训练算法497

17.3.3理论分析498

17.4应用与改进499

17.4.1改进方案500

17.4.2典型应用503

参考文献505


第18章聚类算法506

18.1问题定义506

18.2层次聚类507

18.3基于质心的算法507

18.4基于概率分布的算法508

18.5基于密度的算法512

18.5.1DBSCAN算法512

18.5.2OPTICS算法514

18.5.3Mean Shift算法516

18.6基于图的算法517

18.7算法评价指标518

18.7.1内部指标518

18.7.2外部指标518

18.8应用519

参考文献519


第19章半监督学习521

19.1问题假设521

19.1.1连续性假设521

19.1.2聚类假设521

19.1.3流形假设521

19.1.4低密度分割假设521

19.2启发式算法522

19.2.1自训练522

19.2.2协同训练522

19.3生成模型522

19.4低密度分割523

19.5基于图的算法523

19.6半监督深度学习524

参考文献525

 

第20章强化学习527

20.1强化学习简介527

20.1.1问题定义527

20.1.2马尔可夫决策过程528

20.2基于动态规划的算法532

20.2.1策略迭代算法532

20.2.2价值迭代算法534

20.3蒙特卡洛算法535

20.3.1算法简介535

20.3.2状态价值函数估计536

20.3.3动作价值函数估计537

20.3.4蒙特卡洛控制537

20.4时序差分学习538

20.4.1Sarsa算法538

20.4.2Q学习539

20.5深度强化学习540

20.5.1深度Q网络541

20.5.2策略梯度算法544

20.6应用547

参考文献547

 

第三部分工程实践问题

 

第21章工程实践问题概述551

21.1实现细节问题551

21.1.1训练样本551

21.1.2特征预处理552

21.1.3模型选择552

21.1.4过拟合问题552

21.2安全性问题553

21.2.1对抗样本553

21.2.2形成原因分析555

21.3实现成本问题556

21.3.1训练样本量556

21.3.2计算与存储成本556

21.4深度模型优化557

21.4.1剪枝与编码557

21.4.2二值化网络558

21.4.3卷积核分离562

参考文献563

附录A各种机器学习算法的总结565

附录B梯度下降法的演化关系（见第15章）569

附录C EM算法的推导（见第18章）570
