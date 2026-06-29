---
layout: default
title: "Horizon Summary: 2026-06-29 (ZH)"
date: 2026-06-29
lang: zh
---

> 从 106 条内容中筛选出 14 条重要资讯。

---

1. [通过载流子屏蔽在 LiNbO3 中实现超快非热抑制铁电性](#item-1) ⭐️ 9.0/10
2. [BRAVE：风险感知贝叶斯优化高效发现高熵合金](#item-2) ⭐️ 9.0/10
3. [PtyRANNOSAUR：用于超快电子叠层成像的神经网络](#item-3) ⭐️ 9.0/10
4. [偶极玻璃设计实现创纪录的低温储能](#item-4) ⭐️ 9.0/10
5. [多光子吸收揭示交变磁自旋分裂指纹](#item-5) ⭐️ 9.0/10
6. [LitMOF：利用 LLM 多智能体修正 MOF 数据库错误](#item-6) ⭐️ 9.0/10
7. [非均匀流体的熵密度泛函理论](#item-7) ⭐️ 9.0/10
8. [非厄米斯格明子中拓扑电荷在例外点分裂](#item-8) ⭐️ 9.0/10
9. [利用热梯度消除超导电路中的磁通捕获](#item-9) ⭐️ 9.0/10
10. [面向混合量子计算的工业化自旋-光子接口](#item-10) ⭐️ 9.0/10
11. [用于 meV 轴子暗物质探测的量子半导体异质结构](#item-11) ⭐️ 9.0/10
12. [提出通用混合数字-模拟费米子量子模拟器](#item-12) ⭐️ 9.0/10
13. [Au(111)上二维π共轭聚合物生长揭示有机金属中间体](#item-13) ⭐️ 8.0/10
14. [铁电纳米畴阵列中的毫米波共振](#item-14) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [通过载流子屏蔽在 LiNbO3 中实现超快非热抑制铁电性](https://arxiv.org/abs/2606.27494) ⭐️ 9.0/10

研究人员展示了飞秒激光脉冲可以通过载流子屏蔽在 LiNbO3 中瞬态抑制铁电极化，而无需加热，这通过时间分辨二次谐波产生和受激拉曼散射测量得以证实。 这一发现提供了一种可逆的超快机制来控制铁电序，有望实现更快、更节能的电子器件和量子材料的新可能性。 即使极低浓度的光激发载流子也能快速且持久地抑制极化和拉曼响应。注量依赖和温度依赖分析确认该效应是非热的且保持对称性。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 铁电材料具有自发极化，可被电场翻转。载流子屏蔽是指自由电荷累积并部分抵消内建电场，通常会抑制铁电性。在平衡态下，屏蔽是有害的，但这项工作显示，瞬态光激发载流子可以在超快时间尺度上可逆地调制铁电性，而无需显著加热。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.researchgate.net/publication/346687451_Screening_of_hot_electrons_in_the_ferroelectric_semiconductor_I_n_2_S_e_3">Screening of hot electrons in the ferroelectric semiconductor I n 2 S e 3 | Request PDF</a></li>
<li><a href="https://pubmed.ncbi.nlm.nih.gov/29855531/">Thermooptical evidence of carrier-stabilized ferroelectricity in ultrathin electrodeless films - PubMed</a></li>
<li><a href="https://www.nature.com/articles/s41467-025-60851-w">Coherent manipulation of second-harmonic generation via ... - Nature</a></li>

</ul>
</details>

**标签**: `#ferroelectricity`, `#ultrafast optics`, `#carrier screening`, `#LiNbO3`, `#materials science`

---

<a id="item-2"></a>
## [BRAVE：风险感知贝叶斯优化高效发现高熵合金](https://arxiv.org/abs/2606.27522) ⭐️ 9.0/10

研究人员开发了 BRAVE（贝叶斯风险感知合金发现与探索）框架，该框架将学习到的可行性分类器集成到多目标贝叶斯优化中，在保留高性能边界成分的同时，对可能存在风险的候选物进行概率性惩罚。从约 27,000 个经 CALPHAD 筛选的候选物中，他们通过三个闭环迭代合成了 48 种合金，仅探索了 0.12%的可行空间。 这项工作解决了在相稳定边界附近探索高性能成分但失败风险高的关键挑战。风险感知方法能够高效发现具有优异性能的高熵合金，可能加速多目标优化问题中的材料设计。 该活动针对屈服强度和延展性等五个目标，识别出两种成分区域：富钒、富镍的高强度区域（屈服强度高达约 1480 MPa，延伸率 50%）和含锰的高延展性区域（屈服强度/屈服比高达 4.20）。钒显示出双重作用，同时驱动屈服强度（r=0.84）和 sigma 相形成（与不可行性 r=0.54），这与 KKT 预测的约束最优解位于活动约束边界上一致。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 高熵合金是多主元合金，可展现优异的力学性能，但其巨大的成分空间使得发现具有挑战性。贝叶斯优化是一种序贯设计策略，通过建模未知目标函数并选择最有希望的候选物进行下一步评估。CALPHAD（相图计算）方法利用热力学数据库预测相稳定性，常被用作筛选工具。一个关键见解是最优成分通常位于相稳定边界附近，而此处实验失败风险最高。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC4912057/">The CALPHAD method and its role in material and process...</a></li>
<li><a href="https://pdfs.semanticscholar.org/31f2/a6e1ab5aa27ebdb354e12c5c5bd73f25e454.pdf">The CALPHAD method and its role in material and</a></li>
<li><a href="https://botorch.org/docs/multi_objective">Multi - Objective Bayesian Optimization | BoTorch</a></li>

</ul>
</details>

**标签**: `#Bayesian optimization`, `#high-entropy alloys`, `#materials design`, `#computational materials science`, `#alloy discovery`

---

<a id="item-3"></a>
## [PtyRANNOSAUR：用于超快电子叠层成像的神经网络](https://arxiv.org/abs/2606.27587) ⭐️ 9.0/10

研究人员开发了基于卷积自编码器的神经网络 PtyRANNOSAUR，其重建原子分辨率电子叠层成像数据的速度比标准迭代方法快 10-100 倍，分辨率达到亚 0.5 埃。 这一突破实现了近乎实时的电子叠层成像重建，大幅缩短处理时间，使高分辨率成像在材料科学中更易普及。 PtyRANNOSAUR 能够处理空间部分相干、多次散射和扫描位置误差等实验缺陷，无需超参数调优。该网络在多种材料体系的模拟和实验数据上进行了测试，其重建结果与迭代方法相当。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 电子叠层成像是一种计算显微技术，通过记录聚焦电子束在样品上重叠扫描时的一系列相干衍射图案，重建样品的复振幅像（包括振幅和相位）。4D 扫描透射电子显微镜在每个扫描位置记录一个完整的衍射图案，产生大量需要计算密集的迭代相位恢复的数据集。PtyRANNOSAUR 采用卷积自编码器（一种专为图像处理设计的深度学习架构）学习从 4D STEM 数据到相位图像的直接映射，从而大幅缩短重建时间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Electron_ptychography">Electron ptychography</a></li>
<li><a href="https://en.wikipedia.org/wiki/4D_scanning_transmission_electron_microscopy">4D scanning transmission electron microscopy</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/auto-encoders/">Autoencoders in Machine Learning - GeeksforGeeks</a></li>

</ul>
</details>

**标签**: `#electron ptychography`, `#neural networks`, `#materials science`, `#scanning transmission electron microscopy`, `#deep learning`

---

<a id="item-4"></a>
## [偶极玻璃设计实现创纪录的低温储能](https://arxiv.org/abs/2606.27887) ⭐️ 9.0/10

研究人员通过在 Pb0.6Sr0.4ZrO3 薄膜中构建单元级无序的偶极玻璃态，实现了优异的低温储能，在 9 MV/cm 下能量密度高达 211 J/cm³，且在 4 K 时效率仍超过 88%。 这一突破解决了传统电池和介电电容器在低温下的根本限制，为深空探索和量子计算应用提供了可靠的储能方案。 偶极玻璃态是在反铁电-顺电相界附近实现的，引入了单元级复杂性，抑制了长程铁电序。该薄膜表现出超低滞后、微秒级充放电能力以及超过 10⁸次循环的稳定性。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 低温储能对于深空任务和量子计算机至关重要，但传统电池在约 230 K 以下因离子迁移冻结而失效。弛豫铁电电容器在室温下效率高，但低温下由于极性纳米畴的冻结而出现滞后增加。偶极玻璃是一种无序状态，其中电偶极子随机取向冻结，消除了长程有序，从而实现超低滞后。这项研究利用反铁电衍生的偶极玻璃在 4 K 下同时实现了高能量密度和高效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dipole_glass">Dipole glass</a></li>
<li><a href="https://www.nature.com/articles/s41467-024-51766-z">A highly polarizable concentrated dipole glass for ultrahigh energy ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Antiferroelectricity">Antiferroelectricity</a></li>

</ul>
</details>

**标签**: `#cryogenic energy storage`, `#dipole glass`, `#dielectric capacitors`, `#thin films`, `#materials science`

---

<a id="item-5"></a>
## [多光子吸收揭示交变磁自旋分裂指纹](https://arxiv.org/abs/2606.27548) ⭐️ 9.0/10

这项理论工作表明，通过偏振分辨的多光子吸收可以直接识别交变磁自旋分裂的角谐波。具体而言，双光子、四光子和六光子吸收分别对应 d 波、g 波和 i 波序，提供了超越线性响应的清晰层级。 这项工作为交变磁性——一种具有自旋电子学潜力的新发现量子物态——建立了直接的非线性光学探针。所提出的指纹能够实验区分不同的交变磁序，对于推进凝聚态物理和材料科学至关重要。 在锁定于交变磁织构对称谐波的特定偏振通道中，直接 n 光子对跃迁矩阵元的贡献缺失。这种缺失改变了吸收率的频率标度，提供了清晰的光学指纹。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 交变磁性是最近发现的一种磁相，具有零净磁化强度，但由于晶体对称性导致电子能带自旋分裂，区别于传统的反铁磁体。多光子吸收是一种非线性光学过程，其中两个或更多光子同时被吸收以激发材料。这项工作结合了这些概念，提出了一种用于交变磁性材料的偏振分辨光谱技术。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Altermagnetism">Altermagnetism</a></li>
<li><a href="https://physics.aps.org/articles/v17/4">Physics - Altermagnetism Then and Now</a></li>

</ul>
</details>

**标签**: `#altermagnetism`, `#nonlinear optics`, `#multiphoton absorption`, `#quantum materials`, `#spin splitting`

---

<a id="item-6"></a>
## [LitMOF：利用 LLM 多智能体修正 MOF 数据库错误](https://arxiv.org/abs/2512.01693) ⭐️ 9.0/10

LitMOF 采用多智能体 LLM 框架，验证并纠正金属有机框架（MOF）数据库中的结构错误，生成包含 189,567 个计算就绪结构的精选数据集，并修复了 9,227 个无效条目。 MOF 数据库中的结构错误严重扭曲了高通量筛选和机器学习预测，限制了数据驱动的发现。LitMOF 提供了一种可扩展、可泛化的科学数据库自我修正方法，显著提高了 MOF 研究的可靠性。 LitMOF 应用于 CSD MOF 子集，成功修复了当前 CoRE MOF DB 中 69.1%的未计算就绪 MOF，并发现了现有数据库中缺失的 8,771 个实验报道的 MOF。直接空气捕获筛选案例研究显示，未修正的错误会导致材料排名系统偏差、假阳性和遗漏高性能候选材料。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 金属有机框架（MOF）是一类多孔晶体材料，广泛应用于气体储存、分离和催化。大型 MOF 数据库如 CSD MOF 子集和 CoRE MOF DB 用于高通量筛选和机器学习，但近半数的条目因文献提取不一致而含有结构错误。传统上修正这些错误需要人工专家验证，耗时且无法规模化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sites.google.com/view/csdmofsubset/home">CSD MOF subset</a></li>
<li><a href="https://pubs.acs.org/doi/abs/10.1021/acs.chemmater.7b00441">Development of a Cambridge Structural Database Subset: A Collection of Metal–Organic Frameworks for Past, Present, and Future | Chemistry of Materials</a></li>
<li><a href="https://www.ccdc.cam.ac.uk/free-products/csd-mof-collection/">CSD MOF Collection | CCDC</a></li>

</ul>
</details>

**标签**: `#metal-organic frameworks`, `#databases`, `#machine learning`, `#large language models`, `#crystallography`

---

<a id="item-7"></a>
## [非均匀流体的熵密度泛函理论](https://arxiv.org/abs/2606.28240) ⭐️ 9.0/10

该论文提出了一种非均匀经典流体的精确变分方案，引入了一个关于单体密度和全局粒子间距离分布的元密度最小化原理，绕过了非均匀两体密度。 这是一项重要的理论进展，简化了非均匀流体的计算，与神经函数机器学习及软物质设计直接相关，有望实现结构关联的更精确预测。 该变分原理对单体密度和全局粒子间距离分布进行联合元密度最小化，保持了计算简单性。一个通用的过量熵泛函解释了任意成对相互作用系统中的所有多体关联。

rss · arXiv Soft Condensed Matter · 6月29日 04:00

**背景**: 经典密度泛函理论（DFT）是研究非均匀流体的标准方法，但通常需要对过量自由能泛函进行近似，并且经常涉及计算昂贵的非均匀两体密度。这项新工作基于元密度泛函理论和熵对泛函理论的最新发展，提出了一种使用元密度方法的精确变分方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2603.11973">Metadensity functional learning for classical fluids: Regularizing with pair correlations</a></li>
<li><a href="https://arxiv.org/html/2411.06972">Metadensity functional theory for classical fluids: Extracting the pair potential</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7923074/">Entropy Pair Functional Theory: Direct Entropy Evaluation Spanning Phase Transitions - PMC</a></li>

</ul>
</details>

**标签**: `#Statistical Mechanics`, `#Inhomogeneous Fluids`, `#Density Functional Theory`, `#Soft Matter`, `#Machine Learning`

---

<a id="item-8"></a>
## [非厄米斯格明子中拓扑电荷在例外点分裂](https://arxiv.org/abs/2606.27810) ⭐️ 9.0/10

一项新的理论研究揭示，在非厄米磁性斯格明子中，拓扑保护分裂为两个不同的电荷，并且双正交电荷在斯格明子赤道上的例外点环处失效。 这项工作从根本上改变了人们对非厄米系统中拓扑保护的理解，表明它不是一个单一的不变量，而是可以分裂的。它对拓扑物理、自旋电子学和非厄米光子学具有广泛影响。 该论文引入了两种拓扑电荷：一种来自右本征态的同伦保护电荷，另一种来自左右对的复值双正交电荷。双正交电荷失去量子化，并在例外点环处发散，这是因果响应函数中解析性破坏的实空间类似物。

rss · arXiv Mesoscale and Nanoscale Physics · 6月29日 04:00

**背景**: 磁性斯格明子是具有整数拓扑电荷的拓扑保护自旋纹理，可防止其解旋。非厄米物理学描述具有增益和损耗的开放系统，其中例外点是本征值和本征向量合并的奇点。本文通过研究 PT 对称非厄米磁体中的斯格明子，将这些概念联系起来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Exceptional_point">Exceptional point - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Magnetic_skyrmion">Magnetic skyrmion - Wikipedia</a></li>

</ul>
</details>

**标签**: `#non-Hermitian physics`, `#skyrmions`, `#topological charge`, `#exceptional points`, `#PT-symmetry`

---

<a id="item-9"></a>
## [利用热梯度消除超导电路中的磁通捕获](https://arxiv.org/abs/2606.27415) ⭐️ 9.0/10

这一突破克服了超导电子学和量子计算中长期存在的难题——磁通捕获会降低器件性能，为无需复杂磁屏蔽的可扩展高性能超导电路铺平了道路。 该方法通过磁成像和电读出验证，能够移除场冷却过程中捕获的磁通以及电路运行产生的磁通。配合基本的磁屏蔽，可抑制大规模电路中的所有磁通。

rss · arXiv Mesoscale and Nanoscale Physics · 6月29日 04:00

**背景**: 超导电路在环境磁场中冷却时会捕获磁涡旋，导致性能下降。沟槽（蚀刻孔）常用于隔离磁通，但涡旋仍可能钉扎在敏感区域。热梯度对涡旋施加力，使其向热区移动，从而实现可控操纵。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.researchgate.net/publication/299499829_How_Moats_Protect_Superconductor_Films_From_Flux_Trapping">(PDF) How Moats Protect Superconductor Films From Flux Trapping</a></li>
<li><a href="https://www.researchgate.net/publication/307169893_Optical_Manipulation_of_Single_Flux_Quanta">(PDF) Optical Manipulation of Single Flux Quanta</a></li>

</ul>
</details>

**标签**: `#superconducting circuits`, `#flux trapping`, `#quantum computing`, `#cryoelectronics`, `#magnetic vortices`

---

<a id="item-10"></a>
## [面向混合量子计算的工业化自旋-光子接口](https://arxiv.org/abs/2606.27787) ⭐️ 9.0/10

研究人员使用 III-V 族试生产线制造了数千个单片半导体量子点器件，实现了自旋-光子接口的受控源参数，具有最先进的效率和接近一致的光子不可区分性。 该演示直接解决了混合光子量子计算的可扩展性挑战，将核心自旋-光子接口从实验室规模推进到工业兼容的制造，是迈向容错量子计算的关键一步。 这些器件实现了创纪录的单光子维格纳函数负性、七部分自旋-多光子纠缠，以及可扩展至微秒时间尺度的自旋相干性，并且来自远距离源的光子与单个源发射的光子具有相同的不可区分性。

rss · arXiv Mesoscale and Nanoscale Physics · 6月29日 04:00

**背景**: 混合光子量子计算机结合了静止物质量子比特（如量子点）和飞行光子量子比特，利用自旋-光子接口实现高效单光子生成和纠缠。微腔中的半导体量子点是领先的平台，但扩展到纠错所需的数千个器件需要工业制造方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/spin-photon-interfaces">Spin - Photon Interfaces in Quantum Systems</a></li>
<li><a href="https://inspirehep.net/literature/3006146">Photonic Hybrid Quantum Computing - INSPIRE</a></li>
<li><a href="https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=927523">Advanced technologies for quantum photonic devices based</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#quantum dots`, `#spin-photon interface`, `#semiconductor fabrication`, `#photonic quantum computing`

---

<a id="item-11"></a>
## [用于 meV 轴子暗物质探测的量子半导体异质结构](https://arxiv.org/abs/2509.14320) ⭐️ 9.0/10

本文提出了 SQWAREs，一种基于量子半导体异质结构和磁等离子体腔的新型探测器，通过逆普里马科夫效应实现共振增强的轴子-光子转换，用于 meV 质量轴子暗物质的探测。 SQWAREs 针对轴子暗物质难以探测的 meV 质量范围，填补了直接搜索中的关键空白，并且支持原位调谐，无需复杂的机械调整，有望实现广泛扫描并探测备受关注的 QCD 轴子参数空间。 该探测器使用多层量子阱结构形成磁等离子体腔，内含高迁移率二维电子气，在太赫兹范围内实现可调的 epsilon 近零共振。轴子诱导的信号以辐射形式发射并由光电探测器接收，灵敏度投影表明其可覆盖 QCD 轴子参数空间。

rss · arXiv Mesoscale and Nanoscale Physics · 6月29日 04:00

**背景**: 轴子是假想粒子，是暗物质的主要候选者之一，但在 meV 质量范围内探测它们极具挑战性。逆普里马科夫效应允许轴子在强磁场存在下转换为光子。量子半导体异质结构可以承载具有 epsilon 近零共振的磁等离子体腔，从而在特定频率下增强转换效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.researchgate.net/profile/Sean-Molesky/publication/233282228_High_Temperature_Epsilon-Near-Zero_and_Epsilon-Near-Pole_Metamaterial_Emitters_for_Thermophotovoltaics/links/550a17d20cf20f127f90d4f6/High-Temperature-Epsilon-Near-Zero-and-Epsilon-Near-Pole-Metamaterial-Emitters-for-Thermophotovoltaics.pdf">High temperature epsilon - near - zero and epsilon - near -pole</a></li>
<li><a href="https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.125.131805">Inverse Primakoff Scattering as a Probe of Solar Axions at Liquid...</a></li>
<li><a href="https://www.sci-hub.ru/10.1002/adom.201200011">Sci-Hub: Magnetoplasmonics : Combining Magnetic and Plasmonic ...</a></li>

</ul>
</details>

**标签**: `#axion dark matter`, `#quantum semiconductors`, `#heterostructures`, `#terahertz`, `#magnetoplasmonics`

---

<a id="item-12"></a>
## [提出通用混合数字-模拟费米子量子模拟器](https://arxiv.org/abs/2606.05517) ⭐️ 9.0/10

提出了一种针对费米子超冷原子的通用混合数字-模拟量子模拟框架，证明在现有硬件上使用变分算法模拟多体基态性质，相对于经典精确对角化可实现指数级加速。 这项工作为量子模拟复杂费米子多体系统（如 Hubbard 和 Hofstadter-Hubbard 模型）提供了实用途径，超越了当前硬件的原生能力，有望革新材料科学和凝聚态物理。 该框架在理论和数值上针对三种模型：排斥 Hubbard 模型、带吸引性最近邻相互作用的 Hubbard 模型以及含规范场的 Hofstadter-Hubbard 模型。量子演化时间与逆误差呈多项式关系，T ~ O(poly(1/ε))，最多对数修正。

rss · arXiv Strongly Correlated Electrons · 6月29日 04:00

**背景**: 混合数字-模拟量子模拟结合了数字量子门的通用性和模拟演化的高效性，能够模拟超出原生哈密顿量的系统。费米子超冷原子是研究多体物理的前沿平台，但仅靠纯数字或纯模拟方法仍难以模拟任意费米子模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/digital-analog-simulation-protocol">Digital - Analog Simulation Protocol</a></li>
<li><a href="https://inspirehep.net/files/d2bad288521a0099687c5a2ef8101047">Experimental realization of phase-controlled dynamics with hybrid ...</a></li>
<li><a href="https://www.linkedin.com/posts/googleresearch_today-on-the-blog-we-describe-a-novel-hybrid-activity-7320131808044404738-vvCU">Quantum simulation breakthrough: emulating quantum ... | LinkedIn</a></li>

</ul>
</details>

**标签**: `#quantum simulation`, `#fermionic systems`, `#many-body physics`, `#variational algorithms`, `#ultracold atoms`

---

<a id="item-13"></a>
## [Au(111)上二维π共轭聚合物生长揭示有机金属中间体](https://arxiv.org/abs/2606.27512) ⭐️ 8.0/10

通过扫描探针显微镜和密度泛函理论，研究人员绘制了三溴三氧杂氮杂三角烯在 Au(111)上生长为有序共价膜的图谱，发现了此前未报道的含 Au 吸附原子的有机金属中间体以及溴稳定的边缘终止结构。 这项工作为具有 Kagome 晶格的二维π共轭聚合物的表面合成提供了机理见解，揭示了残留溴和 Au 吸附原子如何影响生长路径，有望实现对平带材料制备的更精确控制。 该研究以三溴三氧杂氮杂三角烯（TBTANG）为前驱体，在 Au(111)上发现大多数聚合物边缘在高达 250°C 时仍保持溴化，许多边缘通过与相邻溴原子配位的 Au 吸附原子键合。这些观察表明溴在稳定边缘和指导有序 Kagome 聚合物晶格生长中起关键作用。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 表面 Ullmann 偶联是一种在金属表面从卤化前驱体合成二维π共轭聚合物的常用方法。Kagome 晶格因其平坦电子带可产生奇异量子态而备受关注。像 TBTANG 这样的杂三角烯衍生物是构建此类晶格的有前途的结构单元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2606.27512">Mapping the Growth of Two-Dimensional 𝜋-Conjugated Polymers on...</a></li>
<li><a href="https://pubs.rsc.org/en/content/articlehtml/2022/mh/d1mh00935d">Engineering of flat bands and Dirac bands in two-dimensional covalent...</a></li>
<li><a href="https://arxiv.org/pdf/2307.03433">67305_0_art_file_506767_q098ny.pdf</a></li>

</ul>
</details>

**标签**: `#on-surface synthesis`, `#scanning probe microscopy`, `#2D polymers`, `#Kagome lattice`, `#organometallic intermediates`

---

<a id="item-14"></a>
## [铁电纳米畴阵列中的毫米波共振](https://arxiv.org/abs/2606.27616) ⭐️ 8.0/10

研究人员在 SrTiO3/PbTiO3 超晶格中的自组装铁电纳米畴阵列中，展示了高达数百 GHz 的涌现毫米波共振。这是通过相场模拟和实验毫米波表征相结合实现的。 这项工作为下一代通信和计算中的毫米波谐振器设计提供了新途径，满足了日益增长的对太赫兹频段组件的需求。自组装方法为集成电子器件提供了可扩展性和设计灵活性。 该研究使用典型的 SrTiO3/PbTiO3 介电-铁电超晶格来创建周期性铁电纳米畴。相场模拟预测了一种畴呼吸模式，毫米波测量确认了高达数百 GHz 的共振，归因于涌现的压电特性。

rss · arXiv Materials Science · 6月29日 04:00

**背景**: 铁电材料具有可在电场作用下切换的自发电极化。当组织成周期性纳米畴时，它们会表现出均匀材料所不具有的集体行为，例如畴呼吸模式。毫米波共振对高频电子器件至关重要，但传统材料在此频段缺乏内在共振。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.researchgate.net/publication/238929332_Breathing_domain_wall_mode_of_an_interface_pinned_Neel_wall">Breathing domain wall mode of an interface pinned Nèel wall</a></li>
<li><a href="https://www.linkedin.com/posts/moritz-flaschel-b353b8258_phase-field-simulations-produce-beautiful-activity-7448656107750748160-gr1h">Phase field simulations produce beautiful, evolving patterns.</a></li>

</ul>
</details>

**标签**: `#metamaterials`, `#ferroelectrics`, `#millimeter-wave`, `#nanodomains`, `#superlattices`

---