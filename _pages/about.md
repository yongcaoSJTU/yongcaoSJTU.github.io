---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Yong Cao is an Associate Professor at Shanghai Jiao Tong University, specializing in the application of Artificial Intelligence (AI) to fluid mechanics, computational fluid dynamics (CFD), and wind engineering & energy. My research focuses on the wind resistance of structures and cities during extreme climate events, such as typhoons, as well as wind energy prediction and utilization in both marine and terrain environments, all with the goal of contributing to a sustainable society.

I am also open to and actively seek international collaborations to further expand the impact of my research and to address global challenges in the fields of energy and climate resilience.

Please feel free to contact me: yongcao@sjtu.edu.cn

# 🔥 News
- *2025.11*: &nbsp;🎉🎉 The paper about advection scheme effects on WRF-LES has been accepted by _Wind and Structures_, entitled ["Advection scheme effects on large-eddy simulation of separated turbulent flows past a three-dimensional hill in the weather research and forecasting model"](in press). Congratulations!
- *2025.11*: &nbsp;🎉🎉 The paper by the PhD student Haokai Wu has been accepted by _Journal of Fluid Mechanics_, entitled ["Generalizable super-resolution turbulence reconstruction from minimal training data"](in press). Congratulations!
- *2024.11*: &nbsp;🎉🎉 Our work of generating small-scale turbulence is invited by Prof. George Karniadakis to give a speech at CRUNCH Seminar, Brown University.
 
# 📝 Publications 
[**2025**]
- [Generalizable super-resolution turbulence reconstruction from minimal training data](https://arxiv.org/pdf/2511.02604). Wu Haokai, **Cao Yong***, Chen Yaoran, Laima Shujin, Chen Wenli, Zhou Dai, Li Hui (2025). _Journal of Fluid Mechanics_. (in press)
- [Spanwise resolution effects on flow simulations around a square cylinder at the critical angle](). **Yong Cao***, **Tetsuro Tamura** (2025). _Physics of Fluids_, 37, 095146.
- [A pattern-constrained deep learning model for urban canopy turbulence reconstruction from sparse sensor data](https://doi.org/10.1016/j.buildenv.2025.113535). **Yong Cao**, Peixing Xie*, Guoshuo Huang, Wei Wang, Wenli Chen, Gang Hu, Shuyang Cao (2025). _Building and Environment_, 285(C), 113535.
- [Utility of high-order scheme for unsteady flow simulations: Comparison with second-order tool](https://doi.org/10.1016/j.joes.2025.01.002). Peng Jiang, Yichen Huang, **Yong Cao**, Shijun Liao, and Bin Xie*, _Journal of Ocean Engineering and Science_, 2025, 10(5), 774-787.
- [Multi-scale boundary-enhanced diffusion network for high-resolution sea surface height reconstruction](https://doi.org/10.1063/5.0250822). Xiaowei Li, Na Tao, Dan Zhang, Wenhu Liu, Yan Peng, **Yong Cao**, and Yaoran Chen*, _Physics of Fluids_, 2025, 37, 026610.
- [Aerodynamic characteristics of a surface mounted prism of small aspect ratio immersed in atmospheric boundary layer](https://doi.org/10.1063/5.0244832). Baiyang Song, **Yong Cao**, Redili Yushan, and Dai Zhou*, _Physics of Fluids_, 2025, 37, 015129. 
- [Aerodynamic forces and flows around a wall-mounted body in typhoon boundary layers](https://doi.org/10.1063/5.0244352). Guoshuo Huang, Baiyang Song, Haokai Wu, Viet Dung Duong, Dai Zhou, and **Yong Cao***, _Physics of Fluids_, 2025, 37, 015119.
  
[**2024**]
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JFM 2024</div><img src='images/small-scale_turbulence_generation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[High-flexibility reconstruction of small-scale motions in wall turbulence using a generalized zero-shot learning](https://doi.org/10.1017/jfm.2024.521), _Journal of Fluid Mechanics_, 2024, 990, R1.

Haokai Wu, Kai Zhang, Dai Zhou, Wenli Chen, Zhaolong Han, **Yong Cao***

[**Introduction**]
- This study proposes a novel super-resolution (or SR) framework for generating high-resolution turbulent boundary layer (TBL) flow from low-resolution inputs. The framework combines a super-resolution generative adversarial neural network (SRGAN) with down-sampling modules (DMs), integrating the residual of the continuity equation into the loss function. The framework iteratively applies the SRGAN and DM procedure to fully capture the energy cascade of multi-scale flow structures, collectively termed the SRGAN-based energy cascade reconstruction framework (EC-SRGAN). Despite being trained solely on turbulent channel flow data (via zero-shot transfer), EC-SRGAN exhibits remarkable generalization in predicting TBL small-scale velocity fields.
</div>
</div>

- [Free-surface effects on the flow around two circular cylinders in tandem](https://doi.org/10.1017/jfm.2024.1066). Feng Zhao, Rui Wang, Hongbo Zhu, **Yong Cao**, Yan Bao*, Dai Zhou, Bin Cheng and Zhaolong Han, _Journal of Fluid Mechanics_, 2024, 1001, A7.
- [Assessment of turbulence model effects on WRF-LES of separated turbulent flows past a 3D hill](https://doi.org/10.1016/j.jweia.2024.105910). Yujiang Shi, Tao Tao, Haokai Wu, Yaoran Chen, Zhaolong Han, Dai Zhou, Wenli Chen and **Yong Cao***, _Journal of Wind Engineering and Industrial Aerodynamics_, 2024, 254, 105910.
- [A Physics-informed deep learning model to reconstruct turbulent wake from random sparse data](https://doi.org/10.1063/5.0212298). Peixing Xie, Rui Li, Yaoran Chen, Baiyang Song, Wenli Chen, Dai Zhou and **Yong Cao***, _Physics of Fluids_, 2024, 36, 065145.
- [Deep learning reconstruction of high-Reynolds-number turbulent flow field around a square cylinder based on limited sensors](https://doi.org/10.1016/j.oceaneng.2024.117857), Rui Li, Baiyang Song, Yaoran Chen, Xiaowei Jin, Dai Zhou, Zhaolong Han, Wen-Li Chen and **Yong Cao***, _Ocean Engineering_, 2024, 304, 117857.
- [An optimization framework for wind farm layout design using CFD-based Kriging model](https://doi.org/10.1016/j.oceaneng.2023.116644), Zhenfan Wang, Yu Tu, Kai Zhang*, Zhaolong Han, **Yong Cao**, and Dai Zhou, _Ocean Engineering_, 2024, 293, 116644.
- [WindFix: Harnessing the power of self-supervised learning for versatile imputation of offshore wind speed time series](https://doi.org/10.1016/j.energy.2023.128995), Yaoran Chen, Candong Cai, Leilei Cao, Dan Zhang*, Limin Kuang, Yan Peng, Huayan Pu, Chuhan Wu, Dai Zhou, and **Yong Cao**, _Energy_, 2024, 287, 128995.
- [Wake suppression of a cylinder immersed in turbulence using rotating rods](https://doi.org/10.1063/5.0177306). Baiyang Song, Yan Bao, Kai Zhang, Dai Zhou and **Yong Cao***, _Physics of Fluids_, 36 (1), 015117.

[**2023**]
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Appl. Energy 2023</div><img src='images/wind-turbine.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Strategy for mitigating wake interference between offshore vertical-axis wind turbines: Evaluation of vertically staggered arrangement](https://doi.org/10.1016/j.apenergy.2023.121850),  _Applied Energy_, 2023, 351, 121850.

Limin Kuang, Hiroshi Katsuchi, Dai Zhou*, Yaoran Chen, Zhaolong Han, Kai Zhang, Jiaqi Wang, Yan Bao, **Yong Cao** and Yijie Liu

[**Introduction**]
- Wake interference between wind turbines potentially decreases the power output of offshore wind farms. This study utilized high-fidelity computational fluid dynamics simulations, and systematically evaluated the effectiveness of vertically staggered arrangement in mitigating wake interference between offshore VAWTs.
</div>
</div>
- [Significant wave height prediction through artificial intelligent mode decomposition for wave energy management](https://doi.org/10.1016/j.egyai.2023.100257), Yaoran Chen, Dan Zhang*, Xiaowei Li, Yan Peng, Chuhan Wu, Huayan Pu, Dai Zhou, **Yong Cao** and Jiujun Zhang, _Energy and AI_, 2023, 14, 100257.
- [Sparse-measurement-based peak wind pressure evaluation by super-resolution convolutional neural networks](https://doi.org/10.1016/j.jweia.2023.105574), Haokai Wu, Yaoran Chen, Peixing Xie, Dai Zhou, Tetsuro Tamura, Kai Zhang, Shuyang Cao and **Yong Cao***, _Journal of Wind Engineering and Industrial Aerodynamics_, 2023, 242, 105574.
- [Surrogate models for twin-VAWT performance based on Kriging and artificial neural networks](https://doi.org/10.1016/j.oceaneng.2023.113947), Yaoran Chen, Dan Zhang*, Xiaowei Li, Yan Peng, Xiangyu Zhang, Zhaolong Han, **Yong Cao** and Zhikun Dong, _Ocean Engineering_, 2023, 273, 113947.
- [Reynolds number effects on the bistable flows over a wavy circular cylinder](https://doi.org/10.1016/j.oceaneng.2023.113776), Kai Zhang, Hongbo Zhu, **Yong Cao**, and Dai Zhou*, _Ocean Engineering_, 2023, 271, 113776.
- [On the distributed blowing control of flow around a square cylinder at a low Reynolds number](https://doi.org/10.1016/j.oceaneng.2023.115240), Yize Ran, Wen-Li Chen, **Yong Cao**, Hui Li and Donglai Gao*, _Ocean Engineering_, 2023, 285, 115240.
- [Peak suction on a wall-mounted square cylinder by conditional POD: Effects of incident angles](https://doi.org/10.1016/j.jweia.2023.105460), **Yong Cao**, Weizhi Li, Tao Tao, Shiyu Wang and Dai Zhou*, _Journal of Wind Engineering and Industrial Aerodynamics_, 2023, 239, 105460.
- [Large-eddy simulation of separated turbulent flows over a three-dimensional hill using WRF and OpenFOAM](https://doi.org/10.1016/j.jweia.2023.105357), **Yong Cao***, Tao Tao, Yujiang Shi, Shuyang Cao, Dai Zhou and Wen-Li Chen, _Journal of Wind Engineering and Industrial Aerodynamics_, 2023, 236, 105357.
- [Systematic investigation of effect of rotor solidity on vertical-axis wind turbines: Power performance and aerodynamics analysis](https://doi.org/10.1016/j.jweia.2022.105284), Limin Kuang, Rui Zhang, Jie Su, Yixiao Shao, Kai Zhang, Yaoran Chen, Zhihao Zhang, Yu Tu, Dai Zhou*, Zhaolong Han, Yan Bao and **Yong Cao**, _Journal of Wind Engineering and Industrial Aerodynamics_, 2023, 233, 105284.

[**2022**]
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JFM 2022</div><img src='images/wall-mounted_square.png' alt="sym" width="110%"></div></div>
<div class='paper-box-text' markdown="1">

[Topological description of near-wall flows around a surface-mounted square cylinder at high Reynolds numbers](https://doi.org/10.1017/jfm.2021.1043), _Journal of Fluid Mechanics_, 2022, 933, A39.

**Yong Cao***, Tetsuro Tamura, Dai Zhou\*, Yan Bao and Zhaolong Han

[**Introduction**]
- This study topologically describes near-wall flows around a surface-mounted cylinder at a high Reynolds number and in a very thick boundary layer, which were partially measured or technically approximated from the literature. The high-resolution simulations and critical-point theory are applied for complete and rational flow construction.
</div>
</div>

- [Wake dynamics and hydrodynamic forces of a circular cylinder beneath a free surface](https://doi.org/10.1016/j.oceaneng.2022.112669), Feng Zhao, Rui Wang, Hongbo Zhu, **Yong Cao**, Yan Bao*, Dai Zhou and Zhaolong Han, _Ocean Engineering_, 2022, 265, 112669.
- [Vortex-induced vibrations of two rigidly coupled circular cylinders in tandem arrangement](https://doi.org/10.1016/j.oceaneng.2022.112316), Huan Ping, **Yong Cao**, Kai Zhang, Zhaolong Han, Dai Zhou\*, Hongbo Zhu* and Yan Bao, _Ocean Engineering_, 2022, 263, 112316.
- [Investigation of pitch angles on the aerodynamics of twin-VAWT under staggered arrangement](https://doi.org/10.1016/j.oceaneng.2022.111385), Yaoran Chen, Limin Kuang, Jie Su, Dai Zhou, **Yong Cao**, Hao Chen, Zhaolong Han*, Yongsheng Zhao and Shixiao Fu, _Ocean Engineering_, 2022, 254, 111385.
- [Investigation of local severe suction on the side walls of a high-rise building by standard, spectral and conditional POD](https://doi.org/10.1016/j.buildenv.2022.109047), **Yong Cao***, Xu Liu, Dai Zhou and Hehe Ren, _Building and Environment_, 2022, 217, 109047.
- [Wind peak pressures on a square-section cylinder: Flow mechanism and standard/conditional POD analyses](https://doi.org/10.1016/j.jweia.2022.104918), **Yong Cao***, Huan Ping, Tetsuro Tamura and Dai Zhou\*, _Journal of Wind Engineering and Industrial Aerodynamics_, 2022, 222, 104918.
- [The mean wake model and its novel characteristic parameter of H-rotor VAWTs based on random forest method](https://doi.org/10.1016/j.energy.2021.122456), Zhikun Dong, Yaoran Chen, Dai Zhou*, Jie Su, Zhaolong Han, **Yong Cao**, Yan Bao, Feng Zhao, Rui Wang, Yongsheng Zhao and Yuwang Xu, _Energy_, 2022, 239, 122456.
- [Direct numerical simulation of flow over a cylinder immersed in the grid-generated turbulence](https://doi.org/10.1063/5.0072730), Baiyang Song, Huan Ping, Hongbo Zhu, Dai Zhou*, Yan Bao, **Yong Cao** and Zhaolong Han, _Physics of Fluids_, 2022, 34(1), 015109.


[**2021 and before**]
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PoF 2020</div><img src='images/pof_cover.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Large-eddy simulation study of Reynolds number effects on the flow around a wall-mounted hemisphere in a boundary layer](https://doi.org/10.1063/1.5142371), _Physics of Fluids_, 2020, 32, 025109. (Cover Paper & Featured)

**Yong Cao***, Tetsuro Tamura

[**Introduction**]
- Large-eddy simulations were used to investigate unsteady flows around a wall-mounted hemisphere as the Reynolds number (Re, based on the diameter of the hemisphere D) increased from 7×10^4 to 7×10^5. Strong Re dependence was found to be present even for the flow around a wall-mounted obstacle after systematic examination of aerodynamic forces, local pressures, and flow structures. 
</div>
</div>

- [Large-eddy simulations of flow past a circular cylinder near a free surface](https://doi.org/10.1063/5.0068193), Feng Zhao, Rui Wang, Hongbo Zhu, Huang Ping, Yan Bao*, Dai Zhou, **Yong Cao** and Hongyu Cui, _Physics of Fluids_, 2021, 33 (11), 115108.
- [Comparison of hexahedral, tetrahedral and polyhedral cells for reproducing the wind field around an isolated building by LES](https://doi.org/10.1016/j.buildenv.2021.107717), Wei Wang*, **Yong Cao** and Tsubasa Okaze, _Building and Environment_, 2021, 195, 107717.
- [Low-frequency unsteadiness in the flow around a square cylinder with critical angle of 14° at the Reynolds number of 2.2×104](https://doi.org/10.1016/j.jfluidstructs.2020.103087), **Yong Cao***, Tetsuro Tamura, _Journal of Fluids and Structures_, 2020, 97, 103087.
- [Spanwise resolution requirements for the simulation of high-Reynolds-number flows past a square cylinder](https://doi.org/10.1016/j.compfluid.2019.104320), **Yong Cao***, Tetsuro Tamura and Hidenori Kawai, _Computers & Fluids_, 2020, 196, 104320.
- [Investigation of wall pressures and surface flow patterns on a wall-mounted square cylinder using very high-resolution Cartesian mesh](https://doi.org/10.1016/j.jweia.2019.02.013), **Yong Cao***, Tetsuro Tamura and Hidenori Kawai, _Journal of Wind Engineering and Industrial Aerodynamics_, 2019, 188, 1-18.
- [Aerodynamic characteristics of a rounded-corner square cylinder in shear flow at subcritical and supercritical Reynolds numbers](https://doi.org/10.1016/j.jfluidstructs.2018.07.012), **Yong Cao***, Tetsuro Tamura, _Journal of Fluids and Structures_, 2018, 82, 473-491.
- [Shear effects on flows past a square cylinder with rounded corners at Re= 2.2× 104](https://doi.org/10.1016/j.jweia.2017.12.025), **Yong Cao***, Tetsuro Tamura, _Journal of Wind Engineering and Industrial Aerodynamics_, 2018, 174, 119-132.
- [Supercritical flows past a square cylinder with rounded corners](https://doi.org/10.1063/1.4998739), **Yong Cao***, Tetsuro Tamura, _Physics of Fluids_, 2017, 29, 085110.
- [Large-eddy simulations of flow past a square cylinder using structured and unstructured grids](https://doi.org/10.1016/j.compfluid.2016.07.013), **Yong Cao***, Tetsuro Tamura, _Computers & Fluids_, 2016, 137, 36-54.
- [Numerical investigation of steady suction control of flow around a circular cylinder](https://doi.org/10.1016/j.jfluidstructs.2015.09.002), Wen-Li Chen*, **Yong Cao**, Hui Li, Hui Hu, _Journal of Fluids and Structures_, 2015, 59, 22-36.
- [Numerical investigations into effects of three-dimensional wake patterns on unsteady aerodynamic characteristics of a circular cylinder at Re= 1.3× 105](https://doi.org/10.1016/j.jfluidstructs.2015.10.001), **Yong Cao***, Tetsuro Tamura, _Journal of Fluids and Structures_, 2015, 59, 351-369.


# 🎖 Honors and Awards
- *2023* JAWE Award (Excellence in Research Paper), Japan Association for Wind Engineering
- *2023* Excellent Paper Award for Young Scientist, The 2nd Chinese Conference of Aerodynamics
- *2022* Spotlight in Advances in Engineering
- *2021* Oversea High-level Talent of Shanghai
- *2021* Sailing Program of Shanghai
- *2020* Cover Paper of Physics of Fluids, First-authored Paper
- *2019* Best CFD Picture, The Japan Society of Fluid Mechanics
- *2018* Outstanding Reviewer, Journal of Fluids and Structures, Elsevier


# 📖 Educations
- *2013.10 - 2016.12*, Ph.D., Tokyo Institute of Technology (Japan), Environmental Science and Technology (minor: Wind-resistance of Structures)
Thesis: LES study of aerodynamics of two-dimensional bluff bodies in crossflow at very high Reynolds numbers (advisor: Tetsuro Tamura)

- *2011.09 - 2013.07*, M.S., Harbin Institute of Technology (China), Structural Engineering
Thesis: Numerical study on flow control of flow around a circular cylinder using steady suction method (advisor: Hui Li, Wen-Li Chen)

# 💬 Invited Talks
- Yong Cao, "基于移动边界条件的柔性板流固耦合机器学习时空预测模型," 能源工程中的流固耦合前沿问题研讨会, November 2, 2025. (invited talk)
- Yong Cao, "结构风荷载预测的气象-工程多尺度耦合模型," 第九届长三角地区结构工程青年学者学术沙龙, December 14, 2024. (大会报告)
- Haokai Wu, Yong Cao, "Generation of small-scale turbulence," CRUNCH Seminar, Brown University, November 22, 2024. (invited talk)
- Yong Cao, "Intelligent generation method of wall turbulence in meso-micro scale model," The 13rd National Conference of Structural Design and Reliability, October 25-27, 2024. (invited speech)
- Yong Cao, "High-flexibility reconstruction of small-scale motions in wall turbulence using a generalized zero-shot learning," The 3rd International Symposium on Recent Advances in Vortex-induced Vibrations, September 20-23, 2024. (plenary speech)
- Yong Cao, Dai Zhou, Zhaolong Han and Kai Zhang, "High-fidelity and intelligent simulation of wind fields and pressures on buildings," The 2023 International Workshop on The Numerical Simulation of Typhoons, Hanzhou, October 18, 2023. (invited speech)
- Yong Cao, Tetsuro Tamura and Dai Zhou, "Analyses of local severe wind suction on a square-section cylinder by high-resolution simulation and conditional POD method," The 15th World Congress on Computational Mechanics (WCCM-XV) & 8th Asian Pacific Congress on Computational Mechanics (APCOM-VIII). Virtual, July 31-August 5, 2022.  (keynote in minisymposia)
- Yong Cao, Zhaolong Han and Dai Zhou, "Key points and recent advances of offshore vertical-axis wind turbine," The 2021 Workshop on Offshore Renewable Energy, Dalian, July 11, 2021. (invited speech)

# 💻 Professional Services
**Journal Editor**
- *2024.11 - now*, Managing Guest Editor of **Building and Environment**, with Dayi Lai, Hideki Kikumoto and Hao Zheng, Special Issue on "Advancements of AI Technology in the Built Environment"
- *2024.05 - now*, Topical Advisory Panel for **Mathematics**
- *2022.05 - 2023.12*, Guest Editor of **Atmosphere**, with Y. C. He and Y. H. He, Special Issue on "Wind Gusts: Observations, Processes, and Predictions"
- *2021.11 - 2023.08*, Guest Editor of **Mathematics**, with S. J. Laima, X. W. Jin and H. H. Ren, Special issue on "Advanced Mathematical Modeling and Numerical Solutions in Applied Mechanics and Engineering"
  
**Conference services**:
- *2024.08.27*, Session Moderator for Oral Presentation Session **Vortex dynamics**, the 26th International Conference of the Theoretical and Applied Mechanics (ICTAM 2024), with Melissa Green (University of Minnesota)
- *2024.08.27*, Session Moderator for Short Oral Presentation Session **Vortex dynamics**, the 26th International Conference of the Theoretical and Applied Mechanics (ICTAM 2024), with Melissa Green (University of Minnesota)
- *2023.08.29*, Chairperson for Oral Presentation Session **Bluff body aerodynamics**, 16th International Conference on Wind Engineering (ICWE)

**Referee (Papers)**:

- _Applied Energy,
Atmosphere,
Building and Environment,
Canadian Journal of Civil Engineering,
Computers and Fluids,
Energy,
Engineering Applications of Computational Fluid Mechanics,
Flow, Turbulence and Combustion,
International Journal of Heat and Fluid Flow,
International Journal of Heat and Mass Transfer,
Journal of Aerospace,
Journal of Applied Fluid Mechanics,
Journal of Fluid Mechanics,
Journal of Fluids and Structures,
Journal of Marine Science and Engineering,
Journal of Mechanical Science and Technology,
Journal of Wind Engineering and Industrial Aerodynamics,
Ocean Engineering,
Physics of Fluids,
PLOS ONE,
PNAS Nexus,
Wind and Structures_

# 📖 Teaching
- Autumn 2023, Engineering Management, Systems Engineering (G)
- Spring 2023, Civil Engineering, Wind-resistant Safety of Engineering Structures (G)
- Spring 2023, Architecture, Simulation Technology on Built Environment (G)
- Spring 2023, Civil Engineering, Uncover Secret of Super Engineering Secret (U)
- Spring 2022, Civil Engineering, Wind-resistant Safety of Engineering Structures (G)
- Spring 2021, Civil Engineering, Wind-resistant Safety of Engineering Structures (G)
  <br>
Note: U/G = undergraduate/graduate courses
