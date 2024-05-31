# Week 21
## Mon, 20 May


# Week 22
## Tue, 28 May
- [Forecasting the Population of Globular Cluster Streams in Milky Way-type Galaxies]()
	- 用矮星系/暗晕中剥离出来的银河系的球状星团，研究其分布；作为Rubin的预研究

- [He-enriched STAREVOL models for globular cluster multiple populations. Self-consistent isochrones from ZAMS to the TP-AGB phase]()
	- 用氦增丰的恒星模型做球状星团的多星族问题
	- isochrone的形态会被氦增丰影响
	- 新的模型可以在 $1\sigma$ 情况下与观测数据对上

## Thu, 30 May
- [Filamentary Hierarchies and Superbubbles: Galactic Multiscale MHD Simulations of GMC to Star Cluster Formation](https://arxiv.org/abs/2405.18474) Bo Zhao(McMaster University 加拿大), Ralph E. Pudritz, Rachel Pillsworth
	- 恒星形成是一个高度动态的过程，它将丝状层级结构和超新星反馈从星系级的kpc丝状体和超级气泡连接到100pc级的巨分子云（GMC）和星团（1pc）。本工作通过星系多尺度MHD模拟，追踪了类银河系中从星系到亚pc级结构的形成。

- [Probing Intracluster Dynamics and Evolution of Globular Clusters through Cataclysmic Variable Populations](https://arxiv.org/abs/2405.18479) Kwangmin Oh, Jongsuk Hong, C. Y. Hui
	- 球状星团中的动力学相互作用对双星源（激变变星）的形成和演化有重要影响，CV可以作为GC动力学历史的失踪剂。通过模拟和观测数据，研究了GC动力学与CV的X射线光度分布之间的关系，利用蒙特卡洛模拟工具 MOCCA，模拟了GC的三个演化阶段（I / II / III)，分析了Chandra观测的18个GC中的179个CV候选，发现在动力学演化更完全的星团中（II/ III），CV会发射更明亮的X射线。

- [Environmental Effects on the Stellar Mass Function in a z~3.3 Overdensity of Galaxies in the COSMOS Field](https://arxiv.org/abs/2405.18491) Ben Forrest, Brian C. Lemaux, Ekta A. Shah
	- 分析了COSMOS场($z \sim 3.3$)中星系数密度与恒星质量函数（SMF）的关系，对超密度环境中的 SMF 与同期场中的 SMF 进行了比较。发现在超密度环境中恒星质量的积累速度更快。虽然这与过密星系增强其成员星系的演化相一致，可能是通过增加合并率实现的，但这种增强是始于原星系团环境还是更早开始于星系群环境仍不清楚，需要更多具有良好特征的过密星系样本。

- [Elevated Rates of Tidal Disruption Events in Active Galactic Nuclei](https://arxiv.org/abs/2405.18500)
	- 研究了AGN里TDE的rate，严重依赖于恒星密度。这篇文章的特点是考虑盘的影响。TDE之所以重要是因为通过它能够研究吸积盘的形成。

- [Photometric Completeness Modelled With Neural Networks](Photometric Completeness Modelled With Neural Networks) William E. Harris, Joshua S. Speagle 
	- **background** : understanding the completeness of detection and recovery is an essential part of the work. The recovery fraction is, in general, a function of several variables including magnitude, color, background sky noise, and crowding. 
	- 探索用假星测试来建模完备性，同时将所有参数包含在神经网络中，该方法能够处理常见问题，包括不对称完整性函数和检测极限对颜色指数的双线性依赖性。
	- 使用两个样本 HST（哈勃太空望远镜）数据集测试：第一个涉及围绕巨型英仙座星系 NGC 1275 的星团群的光度测定，第二个涉及附近椭圆星系 NGC 3377 中的晕星群。基于 NN 的方法实现了 $> 94\%$ 的分类准确率，并产生与确定完整性的更传统技术完全一致的结果。该方法的其他优点是不存在因数据分箱而产生的任何问题，并且可以为实际光度测定中的每颗恒星分配恢复概率。
	- 数据&代码：[zenodo](https://doi.org/10.5281/zenodo.8306488)

- [A two-phase model of galaxy formation: III. The formation of globular clusters](https://arxiv.org/abs/2405.18735) Yangyao Chen, Houjun Mo, Huiyuan Wang
	- 在星系形成的宇宙学层次结构情景下，提出了一个球状星团形成模型，其中高红移的暗物质晕的快速吸积导致自引力湍流气体云的形成，随后分裂成动态热系统，其中密集的子云质量为 $\sim 10^6$-$10^7 M_\odot$。模型可以有效地应用于宇宙学 N 体模拟，以生成连贯的晕、星系和 GC 样本。