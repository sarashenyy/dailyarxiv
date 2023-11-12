# Week 46
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
	- **model** : ![[2023-11-8.png]]

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

- [An evolutionary continuum from nucleated dwarf galaxies to star clusters](https://arxiv.org/abs/2311.05448) Kaixiang Wang, Eric W. Peng, Chengze Liu
	- **status** : Published in **Nature.** Accepted on September 15
	- **background** : In the nearby Universe, there are **hundreds** of **ultra-compact dawrf galaxies** (UCDs), with half-light radii $r_{h}$ of approximatesly **10-100 parsecs** and **stellar masses** $\approx 10^6-10^8 M_{\odot}$ . The detection of extended stellar envelopes, complex star formation histories, elecates mass-to-light ratio and supermassive black holes suggests that some UCDs are **remnant nuclear star clusters** of **tidally stripped dawrf galaxies** or even ancient compact galaxies. However, only a **few** objects have been found in the transient stage of tidal stripping. 超致密矮星系可能是潮汐剥离矮星系的残余核星团，但观测中只看到了很少的正在进行潮汐剥离的矮星系，这种猜测的演化道路并没有被完全追踪。
	- **summary** : show **106 galaxies** in the Virgo cluster have **morphologies** that are intermediate between normal, nucleated dwarf galaxies and single-component UCDs, revealing a continuum that **fully maps this morphological transition** and **fills the ‘size gap’ between star clusters and galaxies.**
