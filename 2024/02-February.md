# Week 6
## Mon, 5 Feb
- [Where do they come from? Identification of globular cluster escaped stars](https://arxiv.org/abs/2402.01133) Cheng Xu, Baitian Tang, Chengyuan Li 中山大学
	- 球状星团演化，通过化学丰度（N-rich）和动力学寻找场星起源的球状星团
	- **background**：
		- Globular clusters (GCs), as old as our Galaxy, constantly lose their members to the field as they cross through the Milky Way (MW).
		- **GC escaped stars (or escapees)** are suggested to contribute significantly to the **MW halo**.
		- **chemical finger prints**, e.g., **N enrichment**, may reveal its origin
	- **results**:
		- found **29 potential GC progenitors** for **15 N-rich field stars** by establishing dynamical connections between N-rich field stars recently identified by LAMOST and the existing MW GCs
		- successfully identified **more than 1600 extra-tidal candidates** in the vicinity of six Gaia-Enceladus (GE)-related GCs (i.e., NGC 1851, NGC 1904, NGC 6205, NGC 6341, NGC 6779, NGC 7089)
		- Among 95 extra-tidal candidates with spectroscopic radial velocities and metallicity, **54 of them are confirmed** to be GC escaped stars, which can be the ideal spectrocsopic follow-up targets for investigating the GC dynamical evolution (e.g., mass loss, rotation)

## Tue, 6 Feb
- [The Gaia RVS benchmark stars II. A sample of stars selected for their Gaia high radial velocity](https://arxiv.org/abs/2402.02878)E. Caffau(GEPI), D. Katz (GEPI), A. Gómez(GEPI) 巴黎天文台
	- the **Radial Velocity Spectrometer (RVS)** on board Gaia has provided the radial velocity for **33 million stars**
	- to **verify the credibility** of measurements, some bright stars with the modulus of radial velocity in excess of 500 are observed with SOPHIE at OHP and UVES as VLT

- [Constraints on Triton atmospheric evolution from occultations: 1989-2022](https://arxiv.org/abs/2402.02476) B. Sicardy, A. Tej, A. R. Gomes-Junior
	- **background**：海卫一掩星，测量大气状况
		- a few occultations probed Triton's atmosphere in 1989, 1995, 1997, 2008 and 2017
		- a recent ground-based stellar occultation observed on 6 October 2022 provides a new measurement of Triton's atmospheric pressure which is presented here
	- Fits to the **occultation light curves** yield Triton's **atmospheric pressure** at the reference radius 1400 km, from which the surface pressure is induced. 掩星曲线的拟合，得出了海卫一在参考半径 1400 公里处的大气压力，并由此得出了表面压力。

## Wed, 7 Feb
- [The JWST Resolved Stellar Populations Early Release Science Program V. DOLPHOT Stellar Photometry for NIRCam and NIRISS](https://arxiv.org/abs/2402.03504) Daniel R. Weisz, Andrew E. Dolphin, Alessandro Savino
	- 开发了 NIRCAM 和 NIRISS 的 DALPHOT 模块，并用 M92（银河系球状星团）、Draco II（超暗矮星系）和 WLM（恒星形成星系）做了测试，提供了推荐的DALPHOT参数以及观测建议和在线文档
	- **present NIRCAM and NIRISS modules for DOLPHOT**, describe details of the modules iincluding pixel masking, astrometric alignment, star finding, photometry, catalog creation, and artificial star tests (ASTs).
	- **tested** these modules using NIRCam and NIRISS images of **M92** (a Milky Way globular cluster), **Draco II** (an ultra-faint dwarf galaxy), and **WLM** (a star-forming dwarf galaxy)
	- systematic uncertainties: primary from **mismatches** in the model and observed point spread functions (**PSFs**) and **aperture** corrections
	- Temporal variations in the **photometry are generally $\lesssim0.01$ mag**, although rare large misalignment events can introduce errors up to 0.08 mag.

- [The Stellar "Snake" -- II: The Mass Function](https://arxiv.org/abs/2402.04130) Xiang-Ming Yang, Sarah A. Bird, Jiadong Li
	- develop a simulated model color-magnitude diagram-based inference method to derive **the mass function, binary fraction, and mass-ratio distribution** of the clusters in the Stellar Snake
	- The ''head'' of the Snake conforms to a canonical initial mass function with a power-law slope of α∼−2.3. Extending towards the ''tail'' the MF becomes **more top-light**, indicating a deficiency of massive stars within these clusters, which provides evidence for the **delayed formation of massive stars** in the clusters. 
	- Such clues give **support** to the hypothesis that the **Stellar Snake constitutes as a hierarchically primordial structure.**

## Thu, 8 Feb
- [Euclid: Identifying the reddest high-redshift galaxies in the Euclid Deep Fields with gradient-boosted trees](https://arxiv.org/abs/2402.04800) [Euclid Collaboration](https://arxiv.org/search/astro-ph?searchtype=author&query=Euclid+Collaboration) T. Signor, G. Rodighiero, L. Bisigello (~100 authors)
	- **status**: accepted in A&A
	- **background**:
		- Dusty, distant, massive ($M_*\gtrsim 10^{11}\,\rm M_\odot$) galaxies are usually found to show a remarkable **star-formation** activity, contributing on the order of $25\%$ of the **cosmic star-formation rate density** at $z\approx3$-$5$, and up to $30\%$ at $z\sim7$ from ALMA observations 有很多尘埃的，遥远的巨大的星系贡献了宇宙中很大一部分恒星形成率
		- Since these objects have **low space densities**, **deep and wide surveys** are necessary to obtain statistically relevant results about them.
		- Euclid will be **potentially capable** of delivering the required information, **but**, given the lack of spectroscopic features at these distances within its bands, it is still **unclear** if it will be possible to identify and characterize these objects 不清楚Euclid对这些星系有怎样的探测能力
	- **aim**: assess the **capability of Euclid**, together with ancillary optical and near-infrared data, to identify these distant, dusty and massive galaxies, based on broadband photometry
	- **method**: used a **gradient-boosting algorithm** to predict both the **redshift** and **spectral type** of objects at high $z$
	- **results**:
		- method foound to be **accurate** in predicting both the redshift and spectral type of objects within the Euclid Deep Survey simulated catalog at $z>2$
		- found that the **dusty population at $3\lesssim z\lesssim 7$ is well identified**, with a redshift RMS and OLF of only $0.55$ and $8.5\%$ ($H_E\leq26$), respectively (through studying the analog of **HIEROs** (i.e. sources with $H-[4.5]>2.25$), combining Euclid and **Spitzer** data at the depth of the Deep Fields,)
		- with Euclid we will obtain meaningful insights into the role of massive and dusty galaxies in the cosmic star-formation rate over time

## Fri, 9 Feb
- 

# Week 7

# Week 8

# Week 9
## Mon, 26 Feb
- [Binary origin of blue straggler stars in Galactic star clusters](https://arxiv.org/abs/2402.14990) [M. J. Rain](https://arxiv.org/search/astro-ph?searchtype=author&query=Rain%2C+M+J) (ESO Chile), [M. S. Pera](https://arxiv.org/search/astro-ph?searchtype=author&query=Pera%2C+M+S) (La Plata), [G. Perren](https://arxiv.org/search/astro-ph?searchtype=author&query=Perren%2C+G) (Rosario)
	- 银河系星团中蓝离散星的双星起源，根据基于 Gaia 的河内星团蓝离散星星表，发现蓝离散星的数目和星团双星比有关，支持了蓝离散星起源于双星演化的假说，
	- Building on the recent release of a new **Gaia-based blue straggler star catalog** in Galactic open star clusters (OCs), we **explored the properties of these stars** in a cluster sample spanning a wide range in fundamental parameters.
	- use **ASteCA** to estimate the fundamental parameters of the selected clusters, in particular, the binary fraction
	- **results**:
		- For the first time, found a **correlation between the number of blue stragglers and the host cluster binary fraction and binaries**, supports the hypothesis that **binary evolution** is the most viable scenario of **straggler formation** in Galactic star clusters
		- The excellent comparison between the bulk **distribution of blue stragglers** and the **composite evolutionary sequences loci** further supports the binary origin of most stragglers in OCs

- [Is the universe older than commonly accepted?](https://arxiv.org/abs/2401.11549) Félix Llorente de Andrés
	- 受限于公认的宇宙年龄模型，球状星团的年龄不会超过 13.8 Gyr。但是近期根据蓝离散星的数量和弛豫时间之间的关系，得出 NGC104 的年龄介于19.04 Gyr 和 20.30 Gyr 之间。本研究对 NGC 5634 和 NGC 5024 这两个 GC 进行了研究，发现它们的年龄在 15.8 和 21.6 Gyr 之间，超过了公认的宇宙年龄。
	- 根据 Gupta 模型，以及JWST早起宇宙观测的结果，认为宇宙年龄约为 267 亿年。（支持证据：NGC104, NGC5634, NGC5024, IC 4499, NGC 6273, NGC 5824, NGC 4833）
	- A plausible explanation aligns with Gupta's model (Gupta 2023), suggesting a Universe age of around 26.7 billion years, consistent with early universe observations from the James Webb Space Telescope (JWST). Additionally, **four other GCs (IC 4499, NGC 6273, NGC 5824 and NGC 4833)** support Gupta's model.

## Tue, 27 Feb
- [Galaxy stellar and total mass estimation using machine learning](https://arxiv.org/abs/2311.10351) Jiani Chu, Hongming Tang, Dandan Xu (清华)
	- 传统星系质量测量方法会受到模型假设和简并的影响，机器学习方法可以减小这些影响。使用TNG100的星系样本探究CNN对中央恒星质量，总质量和质光关系的测量能力，将星系图像，空间分辨的平均速度和速度弥散作为输入
	- Conventional galaxy mass estimation methods suffer from model assumptions and degeneracies. Machine learning can reduce the reliance on such assumptions.
	- use sample of galaxies from the TNG100 simulation to investigate the ability of **multi-branch convolutional neural network (CNN)** to predict the **central (i.e., within $1-2$ effective radii) stellar and total masses**, and the **stellar mass-to-light ratio $M_*/L$**
	- Such CNN-based models can in general **break the degeneracy between baryonic and dark matter** in the sense that the model can make reliable predictions on the individual contributions of each component 打破重子和暗物质之间的简并性，因为它可以单独预测那个成分的贡献
	- **results**:
		- with $r$-band images and two galaxy kinematic maps as inputs, our model predicting $M_*/L$ has a prediction uncertainty of **0.04 dex**
		- use a **gradient boosting machine** to investigate which (global) features significantly contribute to the correct predictions of the properties
		- find that **galaxy luminosity dominates** the prediction of all masses in the central regions, with stellar velocity dispersion coming next
		- also investigate the **main contributing features** when predicting stellar and dark matter mass fractions ($f_*$, $f_{\rm DM}$) and the dark matter mass $M_{DM}$

## Wed, 28 Feb
- [Discovery of Globular Cluster Candidates in the Dwarf Irregular Galaxy IC 2574 Using HST/ACS Imaging](https://arxiv.org/abs/2402.16955) Noushin Karim, Michelle L. M. Collins, Duncan A. Forbes
	- 发现在距离 3.86 Mpc 处的矮星系 IC 2574（M81星系群） 附近有 23个GC候选体，
	- report the discovery of **23 globular cluster (GC) candidates** around the relatively isolated **dwarf galaxy IC 2574** within the Messier 81 (M81) group, at a distance of **3.86 Mpc**
	- **data**: HST Advanced Camera for Surveys (ACS)

## Thu, 29 Feb


## Fri, 1 Mar
- [[Ne v] emission from a faint epoch of reionization-era galaxy: evidence for a narrow-line intermediate mass black hole](https://arxiv.org/abs/2402.18643) J. Chisholm, D. A. Berg, R. Endsley
	- high spectral resolution JWST NIRSpec observations of **GN42437**, a low-mass (log(M∗/M⊙)=7.9), compact (re<500pc), extreme starburst galaxy at z=5.59 with 13 emission line detections
	- GN42437 has an extraordinary 7σ significant [Ne V] 3427 A˚ detection. The [Ne V] line has a rest-frame equivalent width of 11±2A˚, [Ne V]/Hα=0.04±0.007, [Ne V]/[Ne III] 3870A˚=0.26±0.04, and [Ne V]/He II 4687 A˚=1.2±0.5. Ionization from massive stars, shocks, or high-mass X-ray binaries **cannot simultaneously produce** these [Ne V] and low-ionization line ratios. Reproducing the complete nebular structure **requires both massive stars and accretion onto a black hole**.
	- Thus, the very-high-ionization emission lines powerfully diagnose faint **narrow-line black holes** at high-redshift. We approximate the black hole mass in a variety of ways as **log(MBH/M⊙)∼5−7**.
