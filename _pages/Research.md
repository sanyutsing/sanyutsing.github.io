---
title: 'Research 研究'
layout: single
permalink: /Research/
author_profile: true
excerpt: 'Research interest/ publications & preprints/ academic activities '
mathjax: true
header:
  overlay_image: /images/Mathematics_Building_UBC_01.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
---

## Research Interest

My interest is on the mathematical analysis of PDEs and applied mathematics including interfacial change, free boundary and fluid models. This is my [research statement.](/file/research_statement.pdf)

## Research highlights

Three representative lines of work. The full publication and preprint list below is unchanged.

### Well-posedness

![The inviscid SQG equation on the torus](/images/research/sqg-equation.png)

*The inviscid surface quasi-geostrophic (SQG) equation on the torus.*

- **Non-uniqueness of weak solutions.** Stationary weak solutions of SQG are not unique at low regularity, which gives a route toward a stationary analogue of Onsager's conjecture ([Comm. Math. Phys. 2021](/file/paper/CKL-CMP21.pdf)).
- **Global strong solutions.** Global well-posedness for Klein–Gordon–wave systems, including global strong solutions in low-regularity spaces ([Calc. Var. PDE 2024](/file/paper/CX23.pdf); [Dynam. PDE 2022](/file/paper/CLLX22.pdf)).
- **Vanishing viscosity.** For dissipative SQG, the inviscid limit holds in borderline Besov spaces, with a quantitative rate, and the convergence takes place in the same topology as the initial data (to appear in Proc. Amer. Math. Soc.).
- Related analysis also includes equivalent formulations of Helmholtz equations and localization ([Comm. Contemp. Math.](/file/paper/CLY22.pdf); [J. Differ. Equ. 2024](/file/paper/CLY24.pdf)).

<p>
<img src="/images/research/wave-t20.jpg" alt="Klein-Gordon-wave field at t=20" style="width:48%; height:auto;">
<img src="/images/research/wave-t9.jpg" alt="Klein-Gordon-wave field at t=9" style="width:48%; height:auto;">
</p>

*Wave–Klein–Gordon fields at two times (t = 20 and t = 9).*

### Interface dynamics

![Phase-field coalescence: two interfaces merge into one](/images/research/interface-coalescence.png)
*Interface coalescence in a phase-field model.*

- **Modelling.** For the oxygen-consumption free-boundary problem we work with gradient-flow and variational-inequality formulations, and prove that the different models are equivalent ([SIAM J. Appl. Math. 2023](/file/paper/CFW23.pdf)).
- **Capturing the dynamics.** Stable schemes give a quantitative description of Allen–Cahn / Cahn–Hilliard interface evolution, including splitting, merging, and other topological changes ([J. Sci. Comput. 2021](/file/paper/CLPW21.pdf)).

<p>
<img src="/images/research/allen-cahn.png" alt="Allen-Cahn evolution at t=0.1, 1, 5, 10" style="width:48%; height:auto;">
<img src="/images/research/cahn-hilliard.png" alt="Cahn-Hilliard evolution at t=0.1, 5, 10, 20" style="width:48%; height:auto;">
</p>

*Allen–Cahn (left) and Cahn–Hilliard (right): small components disappear or merge as time evolves.*

### Low-regularity structure-preserving schemes

![Comparison of a low-regularity scheme at N=128 and N=1024](/images/research/low-regularity-resolution.png)

*Same initial data, two spatial resolutions (N = 128 vs N = 1024). The scheme remains stable while resolving the singular structure.*

- **Structure preservation.** Energy-stable semi-implicit schemes for phase-field models (Allen–Cahn, Cahn–Hilliard) that capture singularities and keep structural stability over long times ([IMA J. Numer. Anal. 2026](/file/paper/C25.pdf); [BIT Numer. Math. 2025](/file/paper/C25b.pdf)).
- **Low-regularity convergence.** Convergence can be proved in the same low-regularity space as the initial data, for SQG, Cahn–Hilliard, and related fluid models. The analysis and the schemes are designed to check each other ([J. Differ. Equ.](/file/paper/CLW26.pdf)).
- **SQG at endpoint regularity.** A low-regularity integrator for SQG admits optimal error estimates when the solution has only endpoint regularity (to appear in IMA J. Numer. Anal.). 


## Publications and preprints (by year)

#### published

1. On the Spectral Gap of a Square Distance Matrix, joint with D. Li, D. Shirokoff and B. Wetton, J. Stat. Phys., 2017, 166(3-4), 1029--1035. [pdf](/file/paper/CLSW18.pdf)
2. Asymptotic Behaviour of Time Stepping Methods for Phase Field Models, joint with D. Li, K. Promislow and B. Wetton, J. Sci. Comput., 2021, 86(3), 1--34. [pdf](/file/paper/CLPW21.pdf)
3. On a parabolic Sine-Gordon model, joint with D. Li, C. Quan and W. Yang, Numerical Mathematics: Theory, Methods and Applications., 2021, 14(4), 1068--1084. [pdf](/file/paper/CLQY-2021.pdf)
4. Non-uniqueness of stationary weak solutions to the surface quasi-geostrophic equations, joint with H. Kwon and D. Li, Comm. Math. Phys., 2021, 388 (3), 1281-1295. [pdf](/file/paper/CKL-CMP21.pdf)
5. Global wellposedness for 2D quasilinear wave without Lorentz, joint with D. Li, J. Xu and D. Zha, Dynam. Part. Differ. Eq., 2022, 19(2), 123-140. [pdf](/file/paper/CLLX22.pdf)
6. On the equivalence of classical Helmholtz equation and fractional Helmholtz equation with arbitrary order, joint with D. Li and W. Yang, to appear in Comm. Contemp. Math. [pdf](/file/paper/CLY22.pdf)
7. Equivalent formulations of the oxygen diffusion problem and other implicit free boundary value problems and implications for numerical approximation, joint with Z. Fu and B. Wetton, SIAM J. Appl. Math., 2023, 83(1), 52-78. [pdf](/file/paper/CFW23.pdf)
8. On the global well-posedness and scattering of the 3D Klein-Gordon-Zakharov system, joint with J. Xu, Calc. Var. Part. Differ. Eqn., 63(17), 2024. [pdf](/file/paper/CX23.pdf)
9. Localization for general Helmholtz, joint with D. Li and W. Yang, J. Diff. Eqn., 393: 139-154, 2024. [pdf](/file/paper/CLY24.pdf)
10. Energy stable semi-implicit schemes for the 2D Allen-Cahn and fractional Cahn-Hilliard equations, IMA. J. Numer. Anal, 46(2):758--794, 2026. [pdf](/file/paper/C25.pdf)
11. Second order energy stable semi-implicit schemes for the 2D Allen-Cahn equation, BIT Numer. Math., 65(26): 26, 2025. [pdf](/file/paper/C25b.pdf)
12. Stability and convergence of an iterative low-regularity method for the Cahn-Hilliard equation, joint with Z. Luo and S. Wang, to appear in J. Diff. Eq. [pdf](/file/paper/CLW26.pdf)
13. Optimal error estimates of a low-regularity integrator for the SQG equations under endpoint regularity, joint with Z. Luo and S. Wang, to appear in IMA. J. Numer. Anal.
14. The vanishing viscosity limit of the surface quasi-geostrophic equations in borderline Besov spaces: Rates and same topology convergence, joint with Z. Luo and S. Wang, to appear in Proc. Amer. Math. Soc.


#### preprints

1. On a Sinc-type MBE model, joint with D. Li, C. Quan and W. Yang, submitted, [arXiv:2106.16193.](https://arxiv.org/abs/2106.16193)
2. Uniform Boundedness of Highest Norm for 2D Quasilinear Wave, joint with D. Li and J. Xu, submitted, [arXiv:2104.10019.](https://arxiv.org/abs/2104.10019)
3. Energy stability and convergence of Strang splitting method for Cahn-Hilliard equation, joint with D. Li, preprint.
4. Global well-posedness for 2D quasilinear wave equations with non-compactly supported initial data, joint with D. Li and J. Xu, preprint.
5. Global well-posedness of a two dimensional wave-Klein-Gordon system with small non-compactly supported data, [arXiv:2312.00821](https://arxiv.org/abs/2312.00821).
6. On semi-implicit schemes for the incompressible Euler equations via the vanishing viscosity limit, joint with Z. Luo and S. Wang, preprint [arXiv:2406.12320](https://arxiv.org/abs/2406.12320).
7. Global well-posedness and uniform-in-time vanishing damping limit for the inviscid Oldroyd-B model, joint with Z. Luo, Z. Yang and C. Yuan, preprint [arXiv:2410.09340](https://arxiv.org/abs/2410.09340).
8. A Besov-based integration-by-parts method for the incompressible Navier-Stokes equations, joint with Z. Luo and S. Wang, preprint [arXiv:2509.23192](https://arxiv.org/abs/2509.23192).

 




## Academic activities
#### conferences and talks 

+ SNSA 2026 （分组召集人） @ Guilin, Guangxi, China                                                      2026/07

+ AIMS 2026 （分组报告人，分组召集人）@ Athens, Greece                                                      2026/07

+ 2026年兰州大学计算数学前沿论坛 (报告）@ Lanzhou, Gansu, China                                              2026/04

+ 2026年中山大学理学院五周年院庆暨偏微分方程、动力系统与计算数学学术会议 （分组报告）@ Shenzhen, Guangdong, China    2026/03

+ 2025 HKU Workshop on PDEs and Analysis （报告）@ Hong Kong, China                                      2025/11
  
+ 中国工业与应用数学学会第二十三届年会（CSIAM 2025） (分组报告）@ Changsha, Hunan, China                         2025/10

+ 第30届差分方程和应用国际会议(ICDEA 2025) （分组报告） @ Guangzhou, Guangdong, China                          2025/07
  
+ 第二届“面向未来的复杂系统科学--交叉与融合”学者讲习班 （组织）@ IICS, Fudan University                        2025/07

+ 2025微分方程与动力系统研讨会 （报告） @ SUSTech University                                               2025/06                  
+ 现代偏微分方程分析与计算学术研讨会 （报告）@ Chongqing Normal University                                   2025/05

+ 第一届微分方程与非线性分析青年学术研讨会 （组织） @ Fudan University                                         2024/12                                   
+ 第四届国际生物数学建模、分析与应用研讨会 （报告） @ Harbin Engineering University                            2024/06

+ 非线性分析青年学术研讨会（报告）  @ Wuhan University of Technology                                         2024/06

+ 三亚波国际前沿论坛@清华三亚国际数学论坛                                                                     2024/01

+ 第一届“面向未来的复杂系统科学--交叉与融合”学者讲习班 （组织，报告）@ IICS, Fudan University                      2023/11

+ Seminar talk （报告）@ Institute of Mathematical Sciences, ShangTech University                         2023/11

+ Seminar talk（报告） @ School of Mathematics, South China University of Technology                       2023/07

+ CSIAM 2022 （报告）@ Guangzhou, Guangdong, China                                                        2022/09

+ Workshop on Analysis and PDE @ Tianjin Center for Applied Mathematics (TCAM)                           2019/08

+ SIAM Conference on Applications of Dynamical Systems （报告） @ Snowbird, UT, US                        2019/05



#### visiting

* South China University of Technology, Guangzhou, China
  2023/06-2023/07

* SUSTech, Shenzhen, China                                                                                         2021/10-2022/01

* SUSTech, Shenzhen, China                                                                                         2021/02-2021/04

* Tianjin University, Tianjin, China                                                                                2019/06-2019/07

* SUSTech, Shenzhen, China                                                                                                         2018/07

* Michigan State University, East Lansing, US                                                                            2018/04


## Academic Service
I have refereed articles for publications in
#### Numerical Analysis and Scientific Computing
+ Mathematics of Computation, IMA Journal of Numerical Analysis, Advances in Computational Mathematics, Applied Mathematics Letters, BIT Numerical Mathematics

#### PDE and Analysis
+ Acta Mathematica Scientia, Zeitschrift für Angewandte Mathematik und Mechanik, Communications in Analysis and Mechanics, Fractional Calculus and Applied Analysis, Dynamics of Partial Differential Equations, Applied Mathematics-A Journal of Chinese Universities

#### Mathematical Physics
+ Classical and Quantum Gravity, Physica Scripta.

## Academic advising 
#### Current
+ Haoran Wu (Phd student, since Fall 2024)
+ Weiran Xiong (Phd student, since Fall 2026)
+ Xuewen Lai (Phd student, since Fall 2026)

## Academic seminars
#### [Past and current](/seminar/) 

## Opportunities for graduate students and postdoc fellows
I am looking to recruit graduate students for three projects
+ numerical analysis of methods for capturing phase change
+ analysis and computation of fluid models
+ some aspects of machine learning using PINNs, neural ODEs, deepBSDE and others.
