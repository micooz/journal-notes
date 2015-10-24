# NOTES

## 摘要

人口老龄化 -> **Neurodegenerative**(神经退化)疾病流行度和发病率上升。

BBB限制了药物到达中枢神经系统 -> 目前治疗手段功效差 -> 需要 **Novel Drug Delivery Systems(新型给药系统, NNDS)**。

提出了 **Polymeric nanoparticles(聚合纳米微粒)** 方案。

选择：poly-(lactic-co-glycolic acid) (**PLGA**, 聚乳酸-羟基乙酸共聚物)

原因：

* biocompatibility(生物适应性)
* biodegradability(生物可降解性)

目标结构：PLGA **loperamide**-loaded nanoparticle

制备方法：

1. 使用 **PIC** 方法制备 **nano-emulsion templating(纳米乳液模板)**。
2. 药物溶液 + 纳米乳液模板 --蒸掉溶剂--> 产物

优点：精确尺寸控制，条件温和。

实验方法：**hot-plate test(热板实验)**

结论：证明了目标结构的表面被活性靶向部位(铁蛋白受体的单克隆抗体)活化时，能高速透过BBB。

### 补充

**Neurodegenerative(神经退化)**:

> is the umbrella term for the progressive(逐步) loss of structure or function of neurons(神经元), including death of neurons.
> https://en.wikipedia.org/wiki/Neurodegeneration

**loperamide(洛哌丁胺)**:

> ![][1]
> 
> is a medication used to decrease the frequency of diarrhea(腹泻).
> 
> **Mechanism**: Loperamide is an opioid-receptor(阿片受体) agonist and acts on the μ-opioid receptors in the myenteric plexus of the large intestine(大肠肌间神经丛); by itself it does **not** affect the central nervous system.
> https://en.wikipedia.org/wiki/Loperamide

**haloperidol(氟哌啶醇)**:

> ![][2]
> 
> is a typical antipsychotic(抗精神病) medication. It is used in the treatment of schizophrenia(精神分裂症)...
> https://en.wikipedia.org/wiki/Haloperidol

**the Phase Inversion Composition(PIC)**:

> **Phase inversion** is a chemical phenomenon exploited(被利用在) in the fabrication(制造) of artificial(人工) membranes(膜). It is performed by removing the solvent from a liquid-polymer solution, leaving a porous(多孔), solid membrane.
> https://en.wikipedia.org/wiki/Phase_inversion_(chemistry)

**Hot Plate Test(热板实验)**:

> is a test of the pain response in animals, similar to the tail flick test. It is used in basic pain research and in testing the effectiveness of analgesics(止痛剂) by observing the reaction to pain caused by heat.
> https://en.wikipedia.org/wiki/Hot_plate_test

## 1. 简介

### Nanocarriers

可以保证生物适应性，具有较长的血液循环时间和 **targeting the brain capillary endothelial cells (BCEC, 脑毛细管上皮细胞靶向)**，可以产生药理作用和减少副作用。

### Polymeric Nanoparticle

的制备过程会直接影响其穿透BBB的效率，安全性，生物代谢以及后面生产 Nanocarriers 的可用性。

因此，选择了 **nano-emulsion templating** 来制备 **Polymeric Nanoparticle**。

### Nano-emulsions(纳米乳液)

直径在 20-200 nm 范围内的液滴形成的乳液。

制备方法：

PIC, 室温。

原理：

表面活性剂曲率的自发变化 -> 发生乳化作用 -> 形成乳滴。

1. 乳滴 -> 分散相中原位单体聚合
2. 乳滴 -> 使用**预制备的聚合物**(溶解于挥发性有机溶剂)作为分散相。。。

2优于1的原因：避免了副产物，提高了生物适应性，减少了纯化步骤。

**预制备的聚合物** 中选用了 PLGA，原因：

1. 生物适应性和生物可降解性，确保安全治疗

### 目前工作的目标

证明使用PIC方法制备的纳米乳液模板是合适的，简单的技术，且可以使纳米微粒透过BBB进入 **central nervous system(CNS, 中枢神经系统)**。

* 为何选择洛哌丁胺？

作为一个**没有阵痛效果(无法进入CNS)**的药物模型。用聚合纳米微粒搭载洛哌丁胺研究BBB透过性有很广泛的应用。

搭载有洛哌丁胺的纳米微粒对铁传递蛋白受体的单克隆抗体(8D3)有作用。

补充：

8D3抗体是一种针对老鼠的，对抗铁传递蛋白受体(也称：转铁蛋白受体TfR)在BBB中的过度表达的单克隆抗体。它被用于动物体外实验。因此经过8D3抗体修饰过的纳米微粒会靶向作用于对应的受体上。

> 关于TfR：http://www.docin.com/p-41858747.html

## 2. 材料和方法

### 2.1 材料

* PLGA (Boehringer Ingelheim)  / 羟基乙酸 = 75/25
* 乙酸乙酯, 乙醇 (Merck) 用作挥发性有机溶剂
* 聚山梨醇（吐温）80 (Croda), 表面活性剂
* 盐酸洛哌丁胺 (Sigma-Aldrich)
* 鼠铁传递蛋白受体(8D3)的单克隆抗体(Bionova)
* N-(3-dimethylaminopropyl)-N-ethylcarbodiimide hydrochloride (EDC) (Fluka)
* N-hydroxisuccinimide sodium salt (NHS) (Sigma-Aldrich)
* NaCl, Na2HPO4·H2O, NaH2PO4·H2O (Merck)
* Water (微滤)
* CD1雄鼠，体重 30-35g，*原文有误* (Harlan) 

### 2.2 方法

#### 2.2.1 制备O/W型聚合纳米乳液

25°C，将 phosphate buffer saline(PBS, 磷酸缓冲盐溶液)，逐步加入到吐温80和(乙醇:乙酸乙酯 = 20/80)的混合物中，包含4%(质量百分数)的PLGA以及0.1%的LOP(洛哌丁胺)。

是否制备成功？

* 看：在水，表面活性剂，油相示意图中可以看到透明，半透明或轻微不透明的，显露出蓝色或红色的地方被认为是纳米乳液。
* 进一步确认：使用动态光散射描绘出粒子的尺寸。

#### 2.2.2 通过纳米乳液模板制备纳米微粒

使用 Buchi R-215V Rotavapor 设备在减压条件下，将溶剂蒸干得到纳米微粒分散态。

25°C，将4g纳米乳液的蒸干的条件是：45mbars的真空环境，150rpm的转速，45min。蒸发完成后，产物用微滤水调整为等渗溶液(300 mOsm/kg)。

在体内和体外的研究过程中，纳米微粒被浓缩以达到具有治疗作用的LOP浓度。浓缩过程使用 Centriprep® YM-3, 3 kDa 离心过滤器完成。

浓缩完成后，需要进行24h的透析来达到生理学的pH和等渗值(pH = 7.4 and osmolality = 300 mOsm/kg)。

约定：NP(0,8D3)表示未搭载药物的纳米微粒与8D3抗体的结合物。NE则表示纳米乳液。

#### 2.2.3 纳米乳液及纳米微粒的物化性质

液滴大小及其分布通过 dynamic light scattering(DLS, 动态光源散射) 确定。

仪器和条件：

* 分光计(LS Instruments, 3D 正交多重散射)
* 温度：25°C
* 632.8 nm He-Ne 光源
* 散射角为90°

ζ值由 Electrophoretic 的流动性测量设备和 Zetasizer NanoZS instrument (Malvern Co. Ltd., UK)，条件：

* 633nm He-Ne 光源

应用 Huckel-Onsager 方程计算得到：

![][3]

* εr 表示水的相对介电常数
* ε0 表示真空介电常数
* η 表示液体黏度

由于这个公式只适用于低流动性液体，因此样本用蒸馏水以1:20稀释。

所设计的纳米乳液和纳米微粒的稳定性，在25°C由肉眼观察到的宏观改变来评估。

#### 2.2.4 洛哌丁胺定量分析

HPLC：

* Breeze HPLC (Waters Corporation, Milford, MA, USA)
* UV检测器，220nm(LOP具有最大吸收)
* 流动相：1.824mM，磷酸:乙腈 = 1:1，pH = 3.5，30°C
* 流速：1 mL/min
* 进样：50μL
* 分析50min

LOP的保留时间大约是42min。

#### 2.2.5 诱导效率和载药分析

通过离心分离器(Amicon Ultra-15 Centrifugal Filter Unit with Ultracell-3 Membrane, Millipore, Billerica, Massachusetts, USA)，离心已载药的纳米微粒达到3000Da，然后用HPLC(同型号和条件)分析游离出来的药物。

离心条件：

* 2300g
* 75min
* 25°C

药物诱导效率和载药率根据两个公式计算：

Entrapment efficiency (wt./wt.%)
= (initial drug amount − free drug) / initial drug amount * 100
= (起始药物质量分数 − 剩余药物质量分数) / 起始药物质量分数 * 100

Drug loading (g/g)
= amount of drug in nanoparticles / g of PLGA
= 在纳米微粒上的药物质量 / PLGA的质量

#### 2.2.6 体外释放实验

透析袋，通过 Thermojacketted glasses 保温在25°C。袋内装满受体溶液50mL。

Molecular Weight Cut off(MWCO, 截流分子量)在3.5-5 KDa的膜，2mL样品并用受体溶液润湿。

每间隔一定的时间就取出1mL受体溶液，用HPLC分析其中LOP的浓度。

#### 2.2.7 纳米微粒表面修饰

纳米微粒表面由于，8D3抗体上的**氨基**与PLGA聚合物上的**羧基**的**共价结合**，而被活化。

补充，碳亚二胺反应：

![][4]

https://en.wikipedia.org/wiki/Carbodiimide

实验操作：

1. 用HCl酸化4g纳米微粒分散体(pH = 4.5-6)，加入过量的EDC和NHS，在25 °C下搅拌2h。
2. 取150 μL已活化的纳米微粒分散体，用NaOH调整pH=8。
3. 再取150 μL 8D3抗体(浓度：1 mg/mL, 0.5 mg/mL 或 0.25 mg/mL根据样品而定)加入到上面的溶液中。
4. 25 °C下搅拌培养混合物18h。

鉴定抗体是否成功与纳米微粒表面共价结合？

通过 size exclusion chromatography(SEC, 分子排阻色谱)，HPLC测定。

补充：

**Size-exclusion chromatography**

> Size-exclusion chromatography (SEC) is a chromatographic method in which molecules in solution are separated by their size.
> https://en.wikipedia.org/wiki/Size-exclusion_chromatography

#### 2.2.8 体外细胞可行性分析

方法：MTT检验

> The MTT assay is a colorimetric(比色) assay for assessing cell metabolic activity(代谢活动). NAD(P)H-dependent cellular oxidoreductase enzymes may, under defined conditions, reflect the number of viable cells present.
> https://en.wikipedia.org/wiki/MTT_assay

操作：

* 将HeLa细胞接种到96个槽中，每个槽大约6x10^3个细胞和200 μL DMEM培养基。
* 在37 °C下培养24h。
* 将培养基替换为制备的合适浓度的样品。
* 在37 °C，5% CO2气氛下培养24h。
* 加入 0.5 mg/mL (25 μL) MTT试剂，和PBS磷酸缓冲液。
* 再37 °C培养2h。
* 加入DMSO 200 μL 溶解沉淀物。
* 室温下震荡15min。

用分光光度计(SpectraMax M5) 在 570nm 处测定吸收值。

补充：

**Hela**

> https://en.wikipedia.org/wiki/HeLa

#### 2.2.9 体内中枢阵痛作用研究

将老鼠分为4组，保持水和食物供应，适应环境1周。动物实验原则参考：

Animal Ethics Committee of the University of Barcelona，标准为86/609/EEC。

旨在最小化动物的痛苦和减少动物用量。

饲养条件：

* 22 ± 1 °C，12-h 昼夜循环
* 自由觅食(standard laboratory diet, PANLAB SL, Barcelona, Spain)，饮水。

实验使用成年雄鼠(22-30g)，于尾静脉血管注射 5ml/kg 计量的吗啡(Spanish National Health Service 提供)。

痛觉通过热板分析仪 LE 7406 (PANLAB, SL, Barcelona, Spain)测试，小鼠被放置于设备中，设备通过温度调节器控制水浴温度在 54 ± 0.5 °C。

潜伏期的定义：从放置小鼠于热板到小鼠作出疼痛反应(舔前腿，跳出热板)的时间间隔。

每只老鼠做两次试验，分别测试出**给药前**的潜伏期和**给药20min后**的潜伏期。

经过预选，给药前的潜伏期超过10s的小鼠(约10%)被排除。热板测试截止时间为25s，超过25s没做出反馈的小鼠按25s计算。

给药计量： 3mg/kg；给药方式：尾静脉注射。

吗啡和洛哌丁胺对阿片μ受体的作用非常相似，pKi (morphine) = 9.28; pKi (loperamide) = 9.00

剂型：

1. 0.16 M PBS 溶液
2. 0.7 mg/ml (3 mg/kg) 吗啡水溶液
3. NP(0)
4. NP(0,8D3)
5. NP(0.1)
6. NP(0.1,8D3)
7. 0.7 mg/ml (3 mg/kg)洛哌丁胺水溶液(含15%吐温80)
8. 15%吐温80水溶液

使用SPSS Statistics 17.0软件进行结果的统计分析。

用**T检验**比较每组给药前和给药后的潜伏期的均值。

maximal possible effect (MPE) 由下式计算：

![%MPE][5]

**Paired-Sample T Test**

> Paired samples t-tests typically consist of a sample of matched pairs of similar units, or one group of units that has been tested twice.
> https://en.wikipedia.org/wiki/Student%27s_t-test

## 3. 结果

#### 3.1 纳米乳液和纳米微粒的制备和表征

模型系统：

![][6]

![][7]

#### 3.2 洛哌丁胺包装效率和体外释放

**包装效率**

![][8]

由分离/离心法评价的洛哌丁胺的包装效率(EE)高于99%。

相当于载药浓度9 mg/g，25 mg/g PLGA的纳米微粒分散体系。

使用低浓度的洛哌丁胺可达到体外治疗作用。

先前准备的纳米微粒可通过**连续离心**的方法**浓缩**来达到洛哌丁胺的治疗剂量(1.5-7 mg/kg)。

经过10次浓缩过程可讲洛哌丁胺浓缩到0.7 mg/mL(相当于给药300 μL, 剂量是7 mg/kg)。

分散体系的pH值由于PBS的缓冲效应，在浓缩时不会被改变，但注意等渗值会变大。因此浓缩后有必要进行8h的透析过程来调整等渗值，使其达到生理值(300 mOsm/kg)。

上述过程完成之后，ζ 电势和纳米微粒的大小和先前准备的纳米微粒参数很相似。

**体外释放**

下面将对比：洛哌丁胺从 **纳米微粒分散体**，**胶束溶液**以及**水溶液**中的释放作用。

其中胶束溶液是15%吐温80水溶液。选择这种高浓度的表面活性剂的原因是为了：

* 能溶解治疗量浓度的LOP
* 进行体内试验的需要

![][9]

上图显示，LOP在水溶液中5天完全释放。而胶束中的LOP释放了75%，纳米粒中的LOP只释放了15%。

#### 3.3 纳米微粒表面抗体的官能团化

NP(0.1)被8D3单克隆抗体修饰来拮抗铁传递蛋白受体在BBB中过度表达，利用聚合物上的羧基和利用碳亚二胺反应在抗体上形成的氨基。

![][10]

上表显示：经过抗体修饰过的纳米微粒和没修饰过的纳米微粒的物化性质变化不大。

为确认8D3抗体是否和纳米微粒共价结合，采用SEC分析下面四种样品：

1. 8D3抗体
2. NP(0)
3. NP(0,8D3)
4. NP(0) + 8D3 (简单混合)

![][11]

#### 3.4 体外细胞毒性分析

在HeLa细胞培养基上利用MTT法检验纳米微粒的细胞毒性。

3 mg/mL，30 mg/mL的：

1. NP(0.1)
2. NP(0,8D3)
3. NP(0.1,8D3) N/P = 12.5/1

![][12]

三大组的细胞生存能力均高于80%。30 mg/mL的高浓度组是用来确认无细胞毒性。

关于NP(0.1), NP(0,8D3) 的溶血试验以及血浆蛋白结合反应，已在之前研究中证实无溶血作用和很低的血浆蛋白结合作用。

#### 3.5 体内BBB透性



## 4. 讨论

## 5. 结论

#### 鸣谢

  [1]: https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Loperamide.svg/500px-Loperamide.svg.png
  [2]: https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Haloperidol2DACS2.svg/500px-Haloperidol2DACS2.svg.png
  [3]: images/Huckel–Onsager.png
  [4]: images/Carbodiimide_Amide_Coupling_Scheme.png
  [5]: images/MPE.png
  [6]: images/model_system.png
  [7]: images/Fig2.png
  [8]: images/Table2.png
  [9]: images/Fig3.png
  [10]: images/Table3.png
  [11]: images/Fig4.png
  [12]: images/Fig5.png