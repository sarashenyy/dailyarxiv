# Week 45
## Mon, 6 Nov

>今日陆老师名言 ： 我不在乎这个工作能不能发nature，我做得开心就行 🐶 

- [Filamentary structures as the origin of blazar jet radio variability](https://arxiv.org/abs/2311.01861) Antonio Fuentes, José L. Gómez, José M. Martí
	- **status** : Initial version of an article published in **Nature Astronomy**
	- **summary** : 观测文章，用了更高精度的数据，推翻了标准的 shock-in-jet model 中多普勒因子为常数的假设，发现喷流中的发射特征可能是由变化的 Doppler-boosting 带来的。
	- **key sentence** : high angular resolution and dynamic range image, suggests that **emission features traveling down the jet** may manifest as a result of **differential Doppler-boosting within the filaments**, **as opposed to the standard shock-in-jet model invoked to explain blazar jet radio variability**.
	- **Data** : **microarcsecond-scale angular resolution** images of the **blazar 3C 279** obtained at 22 GHz with the space **VLBI**(very long baseline interferometric) mission RadioAstron

 - [Core-collapse supernova inside the core of a young massive star cluster: 3D MHD simulations](https://arxiv.org/abs/2311.01789) D. V.  Badmaev, A. M. Bykov, M. E. Kalyashova
	- **subjects** : High Energy Astrophysical Phenomena (astro-ph.HE)
	-  **background** : 在星团形成的几百万年后，年轻大质量恒星可能以核坍缩超新星的形式结束演化，超新星的 blast wave 在星团内部区域以年轻亮星的多重恒星风形式传播。
	- **summary** : present the results of **3D magnetohydrodynamic simulations**(三维磁流体动力学模拟) of the **plasma flows by a supernova event** inside a cluster similar to **Westerlund 1**, followed its evolution over a few thousand years(a few shock crossing time), found the plasma tempreture, density and magnetic field are highly distributed by supernova event.

- [The metallicity variations along the chromosome maps: The Globular Cluster 47 Tucanae](https://arxiv.org/abs/2311.01871) A. F. Marino, A. P. Milone, E. Dondoglio
	- **background** : 
		- 球状星团多星族问题, the "chromosome maps" (ChMs) of globular clusters (GCs)。In Type II GCs, display larger variations, sometimes coupled with slow neutron caputure (s) 慢中子俘获 (s 过程) element enrich on the ChMs redder sequences, which has been interpreted as due to multiple generations of stars. 但大部分 GC 在第一代星族形成时 (first populations, 1P)， 就有较大的$\Delta_{F275W},\Delta_{F814W}$，表明形成恒星的原始分子云本身就不是混合均匀的。
		- Tucanae : 杜鹃座
	- **summary** : analyse the chemical composition the **GC 47 Tucanae**, shows **1P stars are not homogeneous** with metallicity variations ~0.1 dex, **no evidence** for a sigificant **enrichment in the s elements** with the anomalous stars distributed on a redder sequences of the ChM.

- [Nebular dominated galaxies in the early Universe with top-heavy stellar initial mass functions](https://arxiv.org/abs/2311.02051) Alex J. Cameron, Harley Katzm, Callum Witten
	- **status** :  submitted to **Nature**
	- **background** : 随着 JWST 的发射，人们开始研究早期宇宙的恒星形成问题。在早期宇宙的高气体压力和低金属丰度下，恒星初始质量函数(IMF)会是什么样的呢？IMF 影响了星系的几乎所有观测特性， 控制了恒星如何影响星系生长，所以 IMF 在星系形成领域也是至关重要的。
	- **summary** : report the detection of **two Lyman-$\alpha$-emitting galaxies** in the Epoch of Reionization with **exceptionally top-heavy IMFs**, analysis of **JWST/NIRSpec** data demonstrates that these galaxies exhibit spectra which are completely dominated by the nebular continuum, observe a steep turnover in the ultraviolet continuum. Instead of a contrived damped Lyman-$\alpha$-absorption model, we show this feature is **two-photon emission from neutral hydrogen** (which can only dominate if the ionizing emissivity is $\geq 10 \times$ that of a typical star-forming galaxy). 
	- **key** : Found such radiation fields can be produced in star clusters dominated by low-metallicity stars of $\geq 50 M_{\odot}$, where the IMF is $10 - 30 \times$ **more top-heavy** than typically assumed.

## Tue, 7 Nov
- [Parameter Estimation for Open Clusters using an Artificial Neural Network with a QuadTree-based Feature Extractor](https://arxiv.org/abs/2311.03009) L.Gavallo(2021-2024, PhD in Università degli Studi di Padova), G. Carraro, L. Magrini
	- **status** : accepted in AJ
	- **summary** : develop a ANN trained on synthetic clusters to estimate **age, metallicity, extinction and distance** of **Gaia** open clusters, extract features  using **QuadTree** tool and adopt a multi-band approach, obtain reliable parameters for [~5400 clusters](https://phisicslollo0.github.io/cavallo23.html).
	- **why ANN not CNN ?** ANN maintains the **full positinal information** and have better performance for this work.

## Wed, 8 Nov
- [Hierarchical Bayesian Inference of Globular Cluster Properties](https://arxiv.org/abs/2311.03704) Robin Y. Wen, Joshua S. Speagle, Jeremy J. Webb
	- **summary** :  Bansed on **lowered isothermal cluster models**, present a **hierarchical bsyesian model** to estimate the structural properties and the phase space center (相空间中心) of a globular cluster (GC). First build a lowered isothermal distribution function using interpolation to provide realiable gradient information for **Hamiltoian Monte Carlo methods** (HMC) to sample large bayesian models (hundreds of parameters).
	- **advantage** : avoids the common techinique of radial binning, try to explore hierarchical bayesian model to address issues including the unknown GC center, incomplete data and measurement errors.
	- **model** : ![](../figure/2023-11-8.png)

- [Why Galaxies are Indeed Simpler than Expected](https://arxiv.org/abs/2311.03632) Jun-Sung Moon, Jounghun Lee
	- 由于宇宙中星系的不同的合并历史、随机恒星形成以及纤维环境的多尺度影响 (multi-scale influences of filamentary environments)，我们很难想象早期宇宙存在**单一初始条件**能够单独解释星系的形成及演化。但观测研究发现，局部宇宙中观测到的星系的关键物理特征似乎收到单一因素调控，本工作将这一单一因素确定为初始潮汐场与原星系惯性动量张量之间的错位程度 (**degree of misalignments between the initial tidal field and protogalaxy inertia momentum tensors**)。通过 **IllustrisTNG** 验证了这一猜想，认为宇宙学初始条件对星系演化的影响比人们通常认为的要大得多。

- [Galaxy Spectra neural Network (GaSNet). II. Using Deep Learning for Spectral Classification and Redshift Predictions](https://arxiv.org/abs/2311.04146) Fucheng Zhong(中山), Nicola R. Napolitano, Caroline Heneka
	- **summary** : present Galaxy Spectra Network/GaSNet-II, a surpervised multi-network deep learning tool for **spectra classification** and **redshift prediction**. 可以自定义分类数量，优化每个类别中分类对象的红移预测，提供红移误差，使用network-of-networks的方法，能够在每个光谱上重现蒙特卡洛测试。
	- **data** : 
		- **SDSS DR16** (260k), 13 classes (including 140k galactic, 120k extragalactic)
		- **4MOST** mock spectra (200k)
		- **DESI** spectra (21k)
	- **capability** : process ~40k spectra in less than one minute (normal desktop GPU)

## Thu, 9 Nov
- [The Future of Astronomical Data Infrastructure: Meeting Report](https://arxiv.org/abs/2311.04272) Workshop report in February 2023 on the Future of Astronomical Data Infrastructure
	- 涨知识系列
	- 讨论为了面对天文数据在获取、分析、合并方面的困难，建议一个协调机构，其具体任务是加强天文数据和软件的互操作性、存档、分发和制作(interperability, archiving, distribution, production)。
	- Future of Astrophysical Data Infrastructure Workshop, 13-16 February 2023, at the Flatiron Institute in New York City, [Center for Computational Astrophysics (CCA) at the Flatiron Institute](https://www.simonsfoundation.org/flatiron/center-for-computational-astrophysics/)

## Fri, 10 Nov
- [Two Watts is All You Need: Enabling In-Detector Real-Time Machine Learning for Neutrino Telescopes Via Edge Computing](https://arxiv.org/abs/2311.04983) Miaochen Jin, Yushi Hu, Carlos A. Argüelles
	- 首次尝试在Google Edge TPU (Tensor Processing Units)上将实时机器学习方法部署到 water/ice neutrino telscopes (中微子探测器)，设计了一种recursive neural network with a residual convolutional embedding。与传统基于GPU的方法有类似的精度，与基于CPU的方案有相同的功耗，实现了高精度低功耗。

- [An evolutionary continuum from nucleated dwarf galaxies to star clusters](https://arxiv.org/abs/2311.05448) Kaixiang Wang(北大PhD), Eric W. Peng, Chengze Liu
	- [作者讲解](https://weibo.com/2014366965/4966613864157758?wm=3333_2001&from=10DB193010&sourcetype=weixin&s_trans=6643844464_4966613864157758&s_channel=4)
	- **status** : Published in **Nature.** Accepted on September 15
	- **background** : In the nearby Universe, there are **hundreds** of **ultra-compact dawrf galaxies** (UCDs), with half-light radii $r_{h}$ of approximatesly **10-100 parsecs** and **stellar masses** $\approx 10^6-10^8 M_{\odot}$ . The detection of extended stellar envelopes, complex star formation histories, elecates mass-to-light ratio and supermassive black holes suggests that some UCDs are **remnant nuclear star clusters** of **tidally stripped dawrf galaxies** or even ancient compact galaxies. However, only a **few** objects have been found in the transient stage of tidal stripping. 超致密矮星系可能是潮汐剥离矮星系的残余核星团，但观测中只看到了很少的正在进行潮汐剥离的矮星系，这种猜测的演化道路并没有被完全追踪。
	- **summary** : show **106 galaxies** in the Virgo cluster have **morphologies** that are intermediate between normal, nucleated dwarf galaxies and single-component UCDs, revealing a continuum that **fully maps this morphological transition** and **fills the ‘size gap’ between star clusters and galaxies.**

# Week 46
## Mon, 13 Nov
- [Imprints of Sagittarius accretion event: Young O-rich stars and discontinuous chemical evolution in Milky Way disc](https://arxiv.org/abs/2311.05815)
	- **status** : Under review at **Nature Communications**
	- **background** : 
		- 在银河系早期历史中，有剧烈的合并和卫星星系吸积。在这些事件中，卫星星系 **Gaia-Enceladus/Sausage** 的吸积被认为是最后一次重大合并事件，从根本上改变了银河系的演化并塑造了银河系的化学-动力学结构 (chemo-dynamical structure)。
		- 然而，最近的观测证据表明银河系在过去的 **4 Gyr** 中仍然经历了显著的恒星形成过程，这可能是**人马座矮星系**的扰动引起的 **perturbations** from **Sagittarius dwarf galaxy (Sgr)**。
	- **summary** : 
		- 测量**薄盘中的 [Fe/H] 和 [O/Fe]**， 首次报告了过去 4 Gyr，Sgr 吸积事件的化学特征。揭示了之前发现的 **年龄-[Fe/H] 关系的 V状结构 在银河系不同位置中会有变化**，并且包含了丰富的子结构。
		- 有趣的是，在 $z_{max} < 0.3$ kpc 处发现了一个**不连续的结构**，它被大约 4 Gyr - 2Gyr 之间的一次恒星形成爆发所打断。在这一过程中，发现了氧丰度的富集，导致了明显的 [O/Fe] 梯度，形成了很多年轻的**富氧星**。
		- 结合模拟的恒星形成历史和 Sgr的化学丰度，本文认为在银河系盘的这次不连续的化学演化过程中， Sgr 扮演了重要的角色。

## Tue, 14 Nov
- [Spectral Modeling of the Supersoft X-ray Source CAL87 based on Radiative Transfer Codes](https://arxiv.org/abs/2311.06492) Masahiro Tsujimoto, Misaki Mizumoto, Ken Ebisawa
	- **background** : 
		- **Super Soft X-ray Sources (SSS)** are white dwarf (WD) binaries that radiate almost entirely below ∼1~keV. X射线谱很软，燃烧非常稳定。
		- 它们的X射线光谱通常都很复杂，发射特征和吸收特征交织在一起很难区分。吸收特征主要来自白矮星的大气层，这部分的辐射转移模型**已经被构建**出来了；发射特征来自白矮星大气层周围的冕(corona)，将从白矮星表面发出的辐射进行了二次辐射转移(The emission features are from the corona surrounding the WD atmosphere, **in which incident emission from the WD surface is reprocessed**)
		- **冕的辐射传递模型**还**没有**被构建出来。
	- **summary** : 
		- 对 CAL87，LMC 中的 SSS 系统，它有来自冕的发射主导的光谱（如果假设白矮星大气发射全部被吸积盘阻挡）
		- 用两种辐射转移代码构建了冕的辐射传递模型：**xstar** for a one-dimensional two-stream solver, **MONACO** for a three-dimensional Monte Carlo solver
		- 通过 XMM-Newton Satellite 的光谱数据，分析了两种方法的差异和局限，对 CAL87 构建了一个较好的光谱模型。

- [Multi-wavelength photometric study of five contact binaries in the field of globular cluster M4](https://arxiv.org/abs/2311.07051) Shanti Priya Devarapallia, Rukmini Jagirdara, Ravi Raja Pothunenia
	- **background** : 双星是球状星团演化的关键
	- **summary** : 
		- 对距离最近的**球状星团M4**中的**5个双星**系统（5个变源）做了**多色测光**分析
		- 使用**Wilson-Devinney method (WD)** 分析了5个变源的**光变曲线**，得到了基本参数
		- 使用 **M-R diagram** 分析了它们的**演化阶段**
		- 结合 **Gaia DR3** 的数据，建立了**三维 Vector-Point Diagrams(VPD)**，分析变源是否为星团成员星，发现 V49 和 NV4 并不是星团的成员星
	- **data** : 
		- 4个变源(**V48, V49, V51, V55**) : CASE, M4 Core Project with HST
		- **NV4** : T40 and C18 Telescopes of Wise Observatory

## Wed, 15 Nov
- [Evaporation Ages: a New Dating Method for Young Star Clusters](https://arxiv.org/abs/2311.08363) V.-M. Pelkonen, N. Miret-Ring, P.Padoan
	- **background** : 
		- 年轻星团的年龄可以给主序前星和原行星盘的形成和演化提供基本的参考(fundamental clock)，但是对年轻星团的年龄测量不同方法的差别很大。
		- **evaporation age** 可以给低质量的主序前星演化，恒星形成和年轻星团的气体蒸发(gas-evaporation)历史提供重要的制约。对年轻星团来说，evaporation age可能比等龄线年龄**更精确**，因为等龄线模型对这些年轻星团本身的观测和建模就有很大的不确定性。
	- **smmary** : 
		- 本文提出了一种新方法，基于星团的 **evaporation age** 来推算它的动力学年龄 **kinematic age**。
		- 利用了数百个模拟星团(40 Myr, 250pc)对方法进行了检验。
		- 星团 evaporation age 的测量不确定性最小在10% （large evaporated stars & small observational errors），并且获得了10个观测星团的evaporation age，与等龄线年龄非常符合。

- [MCMC to address model misspecification in Deep Learning classification of Radio Galaxies](https://arxiv.org/abs/2311.08243) Devina Mohan, Anna Scaife
	- **background** : 
		- 贝叶斯神经网络(BNN)为深度学习模型预测中的不确定性建模提供了一种原则性的方法，能够从模型输出中提取误差估计。
		- 但是，大部分基于贝叶斯推断的技术（ex. 变分推断variational inference, 基于MCMC的技术）都会有 **"cold posterior effect(CPE)" 冷后验效应**，即为了得到更好的预测性能，必须要**降低后验的权重**。
		- CPE可能和数据扩大和数据管理 (data augmentation or dataset curation) 带来的先验和似然的误判有关。
	- **summary** : 本工作中使用MCMC采样，高斯参数族(**Gaussian parametric family**)对真实的后验来说是不好的变分近似(**poor variational approximation**)，并且**导致**了之前在使用基于变分推理的 **BNN** 进行射电星系形态分类时观测到的 **CPE**。

## Thu, 16 Nov
- [On the mass and wind luminosity of young Galactic open clusters in Gaia DR2](https://arxiv.org/abs/2311.09089) Silvia Celli, Andreas Specovius, Stefano Menchiari
	- **background** : 星团作用于星际介质的反馈机制，影响了星系的化学和动力学演化。另外，**年轻大质量星团**可能是高效的粒子加速器，可能有助于宇宙射线的产生。
	- **summary** : 
		- 基于恒星数量，星等和消光，提出了一种方法，评估被Gaia观测的银河系年轻疏散星团(< 30 Myr)的 **wind luminosity**，其对确定加速粒子的能量非常重要假设恒星质量分布函数为 kroupa 函数，考虑当前年龄和质量的星团下可能的最大恒星质量，保守地估计了**Gaia DR2**中的 **387 个星团的质量和 wind luminosity**。
		- 与之前工作相比，本文的样本比之前的**多了三倍**，尤其是在**几千个太阳质量以上**的，这对于预测加速粒子相互作用产生的伽马射线辐射具有极其重要的意义。得到的星团 wind luminosity distribution 可以达到**3 x 10^38 erg/s**，对于潜在的粒子加速情况来说是一个很有希望的特征。

- [The POKEMON Speckle Survey of Nearby M dwarfs. II. Observations of 1124 Targets](https://arxiv.org/abs/2311.08489) Catherine A. Clark, Gerared T. van Belle, Elliott P. Horch
	- **background** : 恒星多重性和许多性质相关，对**M矮星的多重性**测量很难，因为M矮星非常暗，并且直到最近才有完整的星表出现。
	- **POKEMON** : Pervasive Overview of "Kompanions" of Every M dwarf in Our Neighborhood (POKEMON) survey, 用了 Differential Speckle Survey Instrument on the 4.3-meter Lowell Discovery Telescope, the NN-EXPLORE Exoplanet Stellar Speckle Imager on the 3.5-meter WIYN telescope
	- **data** : M0V-M9V, out to 15 pc， 和一些额外的比较远但亮的源。总样本数 1124 颗M矮星。新发现的源在第一篇文章中描述。
	- **summary**： 列出了所有探测到的M矮星多星系统，发现大部分探测到的样本(58.9%)**在Gaia中都不可分辨**。发现模拟中大部分的多星都(73.2%)**可以被 speckle observations 探测到**。

## Fri, 17 Nov
- [Optical polarisation study of Galactic Open clusters](https://arxiv.org/abs/2311.09617) Namita Uppal, Shashikiran Ganesh, Santosh Joshi （印度人写的，摘要中特别指出用了两个 Indian national facilities 🐶）
	- **background** : 
		- 尘埃虽然只占 ISM (Interstellar Medium) 的 1%，但仍然是银河系的重要组成部分。它吸收了短波的星光并将之在长波再发射，从而影响我们对银河系的观测，在长波上研究银河系的尘埃分布可能会因为未知的银河系势能造成的**距离**模糊而产生偏差(may cause discrepancies due to distance ambiguity caused by unknown Galactic potential)。
		- 但是，如果将距离信息与尘埃对背景星光的偏振相结合，就可以给出视线方向遇到的尘埃云的数量的直接观测信息。
	- **summary** : 
		- 观测了**15个星团**，它们分别位于**3个视线方向**的**不同距离**上。
		- 测量得到的偏振信息用于检查尘埃分布情况和对选定平面上的磁场(The measured polarisation results used to scrutinize the dust distribution and orientation of the local plane of sky magnetic fields towards selected directions.)
		- 发现遥远的 King8 有2个前景层分别位于～500pc和～3500pc。对不同的星团也发现了多个尘埃层。

# Week 47
## Mon, 20 Nov
- [Ursa Major III/UNIONS 1: the darkest galaxy ever discovered?](IMF-sensitive line-strengths with velocity dispersion) Raphaël Errani, Julio F. Navarro, Simon E. T. Smith
	- Urea Major III/UNIONS 1 (UMa3/U1): 
		- 目前已知最暗的银河系卫星，质量为$16^{+6}_{-5}\, \rm M_\odot$, 半光半径为 $3\pm 1$ pc，它可能是当前发现的最暗的星系，也可能是最暗的围绕银河系旋转的自引力束缚的星团。
		- 它的视向速度弥散表明它可能有暗物质的存在，但是因为双星弥散的贡献不能确定所以并不能确定一定有暗物质。
	- **summary** : 
		- 使用N-体模拟的方法，发现如果这个系统是自引力束缚的，那么它在银河系的潮汐场中只能存在一个轨道周期 (~0.4 Gyr)。这个证据表明该系统稳定存在的原因可能是它有大量的暗物质。
		- 如果 UMa3/U1 是在一个以 ~$10^9\rm M_\odot$ 为中心的 cusp $\Lambda$CMD halo 中形成的话，它的速度弥散大约为 ～1 km/s，与现在观测的差不多（忽略双星，将$\sigma_{\rm los}$ 放在 1 - 4 km/s）。因为有这样的 dense cusp 的存在，这个暗晕应该就能从银河系的潮汐场中存活至今。
		- 推测 UMa3/U1 很可能是最暗最致密的银河系矮星系，能够对 $\Lambda$CMD 模型在星系形成上给出最小的 halo mass 阈值。

- [The discovery of the faintest known Milky Way satellite using UNIONS](https://arxiv.org/abs/2311.10147) Simon E.T. Smith, William Cerny, Christian R. Hayes
	- 发现了Urea Major III/UNIONS 1 (UMa3/U1)

- [Galaxy stellar and total mass estimation using machine learning](https://arxiv.org/abs/2311.10351) Jainism Chu, Hongming Tang(唐弘铭，清华), Dandan Xu
	- **background** : 传统的星系质量测量方法收到模型假设和简并 degeneracy 的影响，机器学习方法可以减少对假设的依赖，可以用于确定目前的观测结果能在多大程度上预测恒星和暗物质的分布
	- **summary** : 
		- 使用 **TNG100** 中的模拟数据，基于**多分支的卷积神经网络** multi-branch convolutional neural network (CNN)，预测中心质量和质光关系: the central (i.e., within $1-2$ effective radii) stellar and total masses, and the stellar mass-to-light ratio $M_*/L$
		- 模型输入为星系图片和空间可分辨的平均速度和速度弥散图：galaxy images and spatially-resolved mean velocity and velocity dispersion maps
		- 优势：基于CNN的模型能够去除重子物质 baryonic和暗物质之间的简并，可以对这两种成分的单独贡献作出可靠的预测
		- 发现星系光度对中心区域素有质量的预测都有主导作用，其次是速度弥散。
		- 特征重要性分析：investigate the main contributing features when predicting stellar and dark matter mass fractions ($f_*$, $f_{\rm DM}$) and the dark matter mass $M_{DM}$

## Tue, 21 Nov
- [Mass ratio estimates for overcontact binaries using the derivatives of light curves](https://arxiv.org/abs/2311.10949) Shinjirou Kouzuma
	- summary: 用高度相接的双星做质量比，认为这个方法在之后的巡天里会很有用

- [Detecting Cosmic 21 cm Global Signal Using an Improved Polynomial Fitting Algorithm](https://arxiv.org/abs/2311.10951) (上台) Tianyang Liu, Junhua GU, Quan Guo
	- summary: 改进了polynomi fitting的21cm线信号提取方法。

- [Apparent effect of dust extinction on the observed outflow velocity of ionized gas in galaxy mergers](https://arxiv.org/abs/2311.11245)
	- summary: 基于模拟，消光对星系并合时电离气体外流速度的影响。
	- 题外话：银河系和M31的并合会对单颗星上的生命有什么影响？由于星系中星和星的距离非常远，恒星的运行速度相对宇宙尺度来说很慢，基本上不会有什么影响（撞在一起） 😜

- [G213.0−0.6, a true supernova remnant or just an HII region?](https://arxiv.org/abs/2311.11277) (国台)
	- summary: 发现 G213.0−0.6 这个射电源可能不是超新星遗迹而是 HII 区。（这个源在历史上有人声称是超新星遗迹，因为有一个shell-like morphology, steep radio continuum spectrum, 和高 [S II]/H$\alpha$ 的特征）

-  [On the co-rotation of Milky Way satellites: LMC-mass satellites induce apparent motions in outer halo tracers](https://arxiv.org/pdf/2311.11359)
	- summary: 认为 LMC 会影响 MW 外晕的恒星的转动

- [Evidence of Dark Contents in the Center of NGC 6517](https://arxiv.org/abs/2311.11478)
	- summary: 利用毫秒脉冲星作为探针探测银河系球状星团中的中等质量黑洞(IMBHs)

- [Chasing the break: Tracing the full evolution of a black hole X-ray binary jet with multi-wavelength spectral modeling](https://arxiv.org/abs/2311.11523)
	- 发了很多篇 nature 的源 **MAXI J1820+070**，这个源很近很亮可以解释很多以前未知的东西

## Wed, 22 Nov
- [Intermediate-Mass Black Holes in Star Clusters and Dwarf Galaxies](https://arxiv.org/abs/2311.12118) Abbas Askar, Vivienne F. Baldassare, Mar Mezcuz
	- **comments** : To appear in Chapter 2 in the book 《Black Holes in the Era of Gravitational Wave Astronomy》 Chapter 2
	- **background** : 
		- **Intermediate-mass black holes** 质量范围在 100-100,000 $\rm M_{\odot}$，可能是恒星质量黑洞和超大质量黑洞之间的缺失环节。
		- 当恒星初始质量大于20 $\rm{M}_{\odot}$时，**恒星质量黑洞**是这种恒星演化的终点，恒星级黑洞的质量在 10-100 $\rm{M}_{\odot}$。
		- **超大质量黑洞**在星系中心形成，并且质量范围在 $10^{6}$-$10^{10} \ \rm{M}_{\odot}$。人们并不清楚超大质量黑洞是如何形成的，但有许多猜测认为它们经历了一个中等质量阶段。
		- 中等质量黑洞到底是一个独立的类型，还是只是最终的恒星质量黑洞和最轻的超大质量黑洞，目前并不清楚。原因是缺乏确凿的观测证据 (smoking gun，确凿的证据)。
	- **summary** :
		- 第一部分总结了中等质量黑洞可能的形成途径，重点讨论了它们在球状星团和核星团等致密恒星环境中的形成和成长过程。同时强调了中等质量黑洞通过与其他黑洞合并的增长过程，从引力波的角度来看它的重要性。
		- 第二部分重点关注对致密星团和矮星系核中的中等质量黑洞的多波段观测约束，以及未来的引力波探测器对揭示中等质量黑洞之谜带来的帮助。

- [Nebular dominated galaxies in the early Universe with top-heavy stellar initial mass functions](https://arxiv.org/abs/2311.02051) Alex J. Cameron, Harley Katz, Callum Witten
	- **background** : **恒星初始质量函数**影响了星系的几乎所有观测性质，控制了重元素的生成速率，决定着有多少能量可以用来调节星系生长。理论表明，由于高红移处更高的气体压强，更高的宇宙微波背景辐射和更低的金属丰度，**高红移处的IMF**与近邻宇宙相比可能会更加 **top-heavy** （更多恒星可能会倾向于拥有较大质量，而较少的恒星拥有较小的质量）。但是！没有直接观测证据。
	- **summary** : 
		- 报告了两个分别在**红移 5.9 和 7.9 处的 Layman-$\alpha$-emitting 星系**，显示出了非常明显的 top-heavy IMFs
		- 对 JWST/NIRSpec 数据的分析表明，这些星系的光谱完全由星云连续体主导 nebular continuum，除了明显的巴尔莫跳变外，还观测到了紫外连续谱的陡峭变化。
		- 本工作证明了这种特征是来自于中性氢的双光子发射而不是级厚的带有空洞的莱曼$\alpha$系统 :  Although this feature can be produced by an extremely thick damped Lyman-$\alpha$ system with holes, we show instead that this turnover is two-photon emission from neutral hydrogen.
		- 只有当电离发射率是典型恒星形成星系的10倍时，双光子发射才会占主导地位。虽然微弱的 He II 辐射不利于来自AGN或X射线双星的电离贡献，但这种辐射场可以在由低金属度恒星主导的星团中产生，这些恒星的金属度为$\gtrsim50{\rm M_{\odot}}$，其中的 IMF 比通常假设的top-heavy 10-30倍。

## Thu, 23 Nov
- [Variation of the stellar initial mass function in semi-analytical models III: testing the cosmic ray regulated integrated galaxy-wide initial mass function](https://arxiv.org/abs/2311.12932) Fabio Fontanot (INAF, 意大利 Trieste 天文台), Francesco La Barbera, Gabriella De Lucia
	- **summary** : 
		- 本工作中，研究了这种情况对本地早型星系 (local Early-Type galaxies, ETG) 的性质的影响，ETG 的性质通过动力学、测光和光谱研究得出。
		- 在星系演化与组装 (GAEA) 模型的框架下实现了一个 CR-IGIMF 形状库 : We implement a library of CR-IGIMF shapes in the framework of the Galaxy Evolution and Assembly (GAEA) model.
		- 对每个模型星系给出模版光谱能量分布，直接推倒出低质量恒星在平均 IMF 中的质量分数 (i.e. the dwarf-to-giant ratio - $f_{dg}$)，并比较了对光谱特征敏感的 IMF
	- **findings** ：
		- CR-IGIMF 能够正确再现在 z～0 处观测到的动力学质量 (mass-to-light ratios) 相对于光谱 (测光) 估计的过量 (assuming a universal, MW-like, IMF, and the observed increase of [α/Fe] ratios with stellar mass in spheroidal galaxies)
		- 能够重现 $f_{dg}$ 的递增趋势，以及 IMF-sensitive line-strengths with velocity dispersion， 虽然模型预测的关系明显低于观测
	![[11-November-2.png]]

## Fri, 24 Nov
>Happy Thanksgiving ! 🎃

# Week 48
## Mon, 27 Nov
- [Possibilities of Identifying Members from Milky Way Satellite Galaxies using Unsupervised Machine Learning Algorithms](https://arxiv.org/abs/2311.14102) Devika K Divakar, Pallavi Saraf, Sivarani Thirupathi
	- **background** : 对**银河系卫星星系中的星族调查**目前在观测上是一个挑战，由于它们很微弱，光谱确认的**成员星**很少。
	- **summary** : 
		- 使用**无监督学习**的方法，基于GaiaDR3的测光数据，the Dark Energy Survey (DES)，the DECam Local Volume Exploration Survey (DELVE) photometry，确认**9个银河系卫星星系的成员星**。
		- 前人的研究：已经有基于密度的聚类算法，DBSCAN和HDBSCAN，在四维天测参数空间识别了银河系卫星星系的成员星
		- 本工作的结果：能够恢复出80%已经使用光谱方法认证的成员星，也能够排除95-100%的非光谱成员。使用本工作的新方法新发现了许多成员星。与前人也使用光度和测光数据的工作进行了比较。

- [The origin of the metallicity distributions of the NE and W stellar shelves in the Andromeda Galaxy](https://arxiv.org/abs/2311.14252) Stanislav Milošević, Miroslav Mićić, Geraint F. Lewis
	- **background** :
		- **潮汐流**和**恒星壳**是在星系相互作用和合并中自然形成的：**Tidal streams** and **stellar shells** are naturally formed in galaxy interactions and mergers
		- **The Giant Stellar Stream (GSS)**, **the North-East (NE)**, and **Western (W) stellar shelves**：M31中的这些结构是M31在与一个卫星星系合并是形成的
	- **summary** : 
		- 研究了 NE 与 W 恒星壳的形成的它们与GSS的关系
		- 假设卫星星系是 GSS 与恒星壳的前身，对它的潮汐瓦解过程做了数值模拟
		- progenitor as a **dwarf spheroidal galaxy** with the stellar mass of $10^9\rm M_{\odot}$ and evolve its merger with M31 for 3 Gyrs to reproduce the chemodynamical properties of the NE and W shelves
		- find that an **initial metallicity** of the progenitor with a **negative radial gradient** of Δ FeH = -0.3 ± 0.2, successfully **reproduces observed metallicities** of the NE, W shelves, and the GSS, showing that all these structures can originate from the same merger event.

## Tue, 28 Nov
- [Status of Women in Astronomy: A need for advancing inclusivity and equal opportunities](https://arxiv.org/abs/2311.15364) Mamta Pandey-Pommier, Arianna Piccialli, Belinda J. Wilkes
	- A compregensive **four point plan** established by a new organizing committee established by the **IAU WiA working Group**, in **August 2021**:
		- (i) Awareness Sustainability: Achieved through surveys and data collection
		- (ii) Training and Skill Building: Focused on professional development
		- (iii) Fundraising: To support key initiatives
		- (iv) Communication: Dissemination of results through conferences, WG Magazines, newsletters, and more.

- [The Influence of the Bar on the Dynamics of Globular Clusters in the Central Region of the Milky Way. Frequency Analysis of Orbits According to Gaia EDR3 Data](https://arxiv.org/abs/2311.14789) A.T.Bajkova, A.A.Smirnov, V.V.Bobylev
	- **aim** : the influence of the bar on the orbital dynamics of globular clusters 星系棒对球状星团轨道动力学的影响
	- The orbits of **45 globular clusters** in the **central galactic region** with a **radius of 3.5 kpc** were analyzed using **spectral dynamics methods** in order to identify objects captured by the bar: 距离银心半径为3.5kpc的45个球状星团
	- **data** : Gaia DR3, 6D phase & new refined average distances to GCs
	- **results** : 
		- First get an analytical expression for the dependence of the dominant frequency $f_{x}$ on the angular velocity of rotation of the bar : 首次获得了主频 fX 与棒材旋转角速度关系的分析表达式
		- the probabilities of capturing globular clusters by the bar were determined when the bar parameters were varied in certain ranges of values according to a random distribution law : 根据随机分布定律，确定了当棒参数在一定数值范围内变化时，棒捕获球状星团的概率
		- given **14 GCs** with the most capture probabilities, with **five GCs** - NGC6266, NGC6569, Terzan 5, NGC6522, NGC6540 - showing the probability capture by bar $\geq$ 0.2

- [Measuring the Initial-Final Mass-Relation using wide double white dwarf binaries from Gaia DR3](https://arxiv.org/abs/2311.14801) Mark A. Hollands, Stuart P. Littlefair, Steven G. Parsons
	- **IFMR** (Initial-Final Mass-Relation)
		- **meaning** : maps the masses of main sequence stars to their white dwarf descendants 将主序星的质量映射到它们的白矮星后代上
		- **methods** : use white dwarfs in clusters(most common approach), wide double white dwarfs with Bayesian approach
	- **data** : 90 Gaia double white dwarfs usinf FORS2 on the VLT, Very Large Telescope (VLT) Focal Reducer and Low Dispersion Spectrograph (FORS2); 52 DA+DA, DA+DC, and DC+DC pairs
	- **method** : Bayesian mixture-model
	- **results** : 
		- **monotonic IFMR** well constrained for **initial masses of 1-5 Msun**, with the range 1-4 Msun mostly constrained to **a precision of 0.03 Msun** or better：在初始质量为1-5 Msun的情况下，单调IFMR受到了观测数据的良好约束，而在1-4 Msun的范围内，大部分的约束精度为0.03 Msun或更高
		- find a large but uncertain outlier fraction of 59±21 percent, with outlier systems requiring an additional $0.70^{+0.40}_{−0.22}$ Gyr uncertainty in their cooling age differences, find this fraction is dominated by a few systems with massive components near 0.9 Msun, where we are most sensitive to outliers, but are also able to establish four systems as merger candidates ：没明白

- [Great Balls of FIRE III: Modeling Black Hole Mergers from Massive Star Clusters in Simulations of Galaxies](https://arxiv.org/abs/2311.14855) Tristan Bruel, Carl L. Rodriguez, Astrid Lamberts
	- **previous works**: 
		- [Great Balls of FIRE I: The formation of star clusters across cosmic time in a Milky Way-mass galaxy](https://arxiv.org/abs/2203.05732) Michael Y. Grudić, Zachary Hafen, Carl L. Rodriguez
		- [Great Balls of FIRE II: The evolution and destruction of star clusters across cosmic time in a Milky Way-mass galaxy](https://arxiv.org/abs/2203.16547) Carl L. Rodriguez, Zachary Hafen, Michael Y. Grudić
	- **background** : the origin of **merging binary black holes (BBHs)** remains unclear, two main formation
		1. from **isolated field binaries** 孤立的双星
		2. via **dynamical assemble** in dense star clusters 致密星团的动力学
	- **method** : 
		- in **zoom-in cosmological simulation**, using a new framework to consistently model the **formation and evolution of massive star clusters**
		- combined with the star cluster evolution code **CMC**, produced **populations of dynamically formed merging BBHs** across cosmic time in **different environments**
	- **results** : 
		- as the most massive clusters preferentially form in dense massive gas clouds, despite their low metallicities favourable to the creation of black holes, low-mass galaxies contain few massive clusters and therefore have a limited conrtibution to the global production of dynamically formed merging BBHs 大质量星团由于其低金属丰度，是有利于产生黑洞的，但是大质量星团是在致密气体云中诞生的，而低质量星系中并没有很多大质量星团，所以来自其的BBH合并并没有那么多
		- find strong correlations between BBH mergers and the most extreme episodes of star formation 发现BBH合并与极端恒星形成事件有强相关性

## Wed, 29 Nov
- [Asteroseismology of the young open cluster NGC 2516 I: Photometric and spectroscopic observations](https://arxiv.org/abs/2311.16991) Gang Li, Conny Aerts, Timothy R. Bedding
	- **background** : the difficulty in determining stellar age make asteroseismic modelling hard for isolated stars, this challenge can be overcomed by observing stars in open clusters 由于难以精确测定恒星参数（特别是年龄），对单一恒星的星震学模型难以构建，这一困难可以通过使用星团数据解决
	- **data** ：
		- light curves from **TESS** FFI , 301 member stars in **NGC 2516**
		- high resoluation spectra from FEROS for the g-mode pulsators
	- **method** : fitting theoretical isochrones to the CMD, find age is $102\pm15 \rm$ Myr, extinction at 550nm is $0.53\pm0.04$ mag 

## Thu, 30 Nov
- [Globular Clusters Contribute to the Nuclear Star Cluster and Galaxy Center Gamma-Ray Excess, Moderated by Galaxy Assembly History](https://arxiv.org/abs/2311.17071) Yuan Gao, Hui Li (清华), Xiaojia Zhang
	- **background** : 
		- two unresolved questions at **galaxy centers**, namely the **formation of nuclear star cluster (NSC)** and the origin of the **gamma-ray excess** in the Milky Way (MW) and Andromeda (M31), are both related to the formation and evolution of **globular cluster**. 关于星系中心的两个谜题，核星团的形成，银心及M31中心的伽马超射，都与球状星团有关
		- globular cluster migrate towards galaxy center due to dymanical friction, and get tidally disruoted to release the stellar mass content including **millisecond pulsars (MSPs)**, which contribute to the NSC and gamma-ray excess 球状星团在动力学摩擦的作用下向星系中心迁移，收到潮汐扰动，贡献出恒星质量，包括毫秒脉冲星，从而导致核星团的形成和伽马超射
	- **method** : 
		- proposed  a **semi-analytical model** of GC formation and evolution using **Illustris** simulation 用 Illustris 模拟构建了一个 GC 形成和演化的半解析模型
		- utilize the catalog of Illustris halos to investigate the influence of galaxy assembly history 用 Illustris 的晕表研究星系组装历史
	- **results** : 
		- simulated GC properties at z=0 are consistent with obervations, naturally explains the formation of massive NSC in MW-like and M31-like galaxies 模拟结果与当前观测数据类似，自然解释了在类银河系星系中核星团的成因
		- find a remarkable similarity in gamma-ray excess signal between thsi simulation and the MW, fall short by approximately an order of magnitude in M31, indicating distinct origins for the two gamma-ray excesses 对伽马超射的预测，模拟模型与银河系类似，比M31少了一个量级，意味着银河系与M31的伽马超射成因可能不同
		- find that the earlier a galaxy is assembled, the heavier and spatially more concentrated it GC system behaves at z=0, which results in a larger NSC mass and brighter gamma-ray emission from deposited MSPs 当星系组装的时间越早，其中的 GC 在 z=0 时会表现得重、空间上越集中，意味着有大质量的核星团和来自 MSPs 的更亮的伽马超射

## Fri, 1 Dec
- [Nature vs. Nurture: Revisiting the environmental impact on star formation activities of galaxies](https://arxiv.org/abs/2311.18427) Ke Shi (西南大学), Nicola Malavasi, Jun Toshikawa, Xianzhon Zheng 
	- present a systematic study of **environmental impact on star formation activities of galaxies** using a mass-complete sample of **~170k galaxies** at **z < 4** from the latest **COSMOS2020 catalog**
	- **at z < 1** : 
		- find that **mean star formation rate (SFR) of all galaxies decreases with increasing density of the environment** 对整体星系样本来说，环境密度越大，恒星形成率越低
		- However, when consider only **star-forming galaxies**, the mean SFR becomes **independent** of the environment 当只考虑恒星形成星系时，平均恒星形成率与环境无关
	- **at z > 2** : 
		- observe a clear **positive correlation bewteen the SFR and density** of the environment for **all galaxies** 观察到所有星系的恒星形成率与环境密度成明显正相关
		- However, stellar mass of the galaxies increases significantly with the environments at all redshifts except for star-formaing galaxies at z < 1 除了 z < 1 时的恒星形成星系之外，所有红移下星系的恒星质量都会随着环境变化而显著增加
	- the fraction of **quiescent galaxies increases with incresing density** of environments **at z < 2**, the **"morphology-density" relation** is confirmes to **be present up to z ~ 1** 在红移小于2时，淬火星系的比例随着环境密度的增加而增加，“形态-密度”关系在红移为 1 时依旧存在
	- find that **environmental quenching is negligible at z ~ 1**, whereas **mass quenching** is the dominant quenching mechanism for massive galaxies at all redshifts 环境淬火在红移为 1 时可以忽略不计， 而质量淬火则是大质量星系在所有红移下的主要淬火机制
	- **conclusion** : 
		- based on the above results, authors argue that **stellar mass regulated physical process** might be the **major driving force** for star formation of galaxies 基于以上发现， 作者认为恒星质量调节的物理过程可能是星系恒星形成的主要驱动力
		- At low redshift (z < 1) massive galaxies are quenched primarily due to their high mass, resulting in a normal "SFR-density" relation. 在低红移时，大质量星系主要由于质量大而被淬火，从而形成正常的 "SFR-密度" 关系
		- At high redshift (z > 2) most of the galaxies are star-forming ones tightly following the star-forming main sequence, and the difference in their stellar mass at different environments naturally leads to a reversal of "SFR-density"relation. 在高红移时，大多数星系都是恒星形成星系，它们在不同环境下恒星质量的差异会自然地导致反转的 “SFR-密度” 关系