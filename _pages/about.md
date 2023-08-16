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

何巧芝，工学博士，助理研究员。本科毕业于<a href = "http://mse.hust.edu.cn/">华中科技大学机械科学与工程学院</a>，后推免直博于<a href = "https://www.seiee.sjtu.edu.cn/">上海交通大学电子信息与电气学院</a>，期间赴<a href = "https://www.psu.edu/">美国宾夕法尼亚州立大学</a>公派留学。2022年入职<a href = "https://ime.sjtu.edu.cn/">上海交通大学海洋装备研究院</a>，加入<a href = "https://juopt.sjtu.edu.cn/">智能光电感知研究所</a>，从事光场调控、光学检测等方面研究，并对计算光学、智能感知等方向有浓厚兴趣，迄今已在 Light Sci. Appl.、Laser Photonics Rev.、Opt. Lett.、Appl. Phys. Lett. 等知名SCI期刊发表论文20余篇
 <a href='https://scholar.google.com/citations?user=Rm2lL78AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>，申请国家发明专利20余项（已授权5项）。

研究方向：
- 散射光场调控
- 精密光学检测
- 波前检测

<span class='anchor' id='-xsdt'></span>

# 📣 学术动态
- *2023.08*: &nbsp;🎉🎉 夏克-哈特曼波前传感相关研究被中科院Top期刊 Applied Physics Letters 接收
- *2023.07*: &nbsp; 参加 2023 中国光学学会学术大会（口头报告）
- *2023.07*: &nbsp;🎉🎉 散射全光场全息显示相关研究被中科院1区Top期刊 Lasers & Photonics Review 接收

<span class='anchor' id='-lwzl'></span>

# 📝 论文专利

### 发表论文 (`†`表示共同一作)
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Appl. Phys. Lett.</div><img src='blob/png/APL_2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


<b>Arbitrary wavefront uncertainty evaluation for the Shack-Hartmann wavefront sensor using physical optics propagation</b>. <a href="https://pubs.aip.org/aip/apl/article/123/7/071102/2906681/Arbitrary-wavefront-uncertainty-evaluation-for-the">[Web]</a> <a href="blob/pdf/APL_2023.pdf">[PDF]</a> <br>
Jichong Zhou†, `Qiaozhi He†`, Yuan Qu, et al. <br>
**Applied Physics Letters**, 123: 071101 (2023). (SCI:Q2, Top, IF:3.971)<br><br>
<b>挑战</b>: 夏克-哈特曼传感器（SHWS）作为一种常用波前探测手段，具有精度高、速度快、系统简单等优点，广泛应用于天文探测等领域。然而，目前SHWS的标称精度通常采用某一标准波前来评定，无法给出针对任意测量波前的误差评定结果。 <br>
<b>方法</b>: 提出基于物理光学传播的SHWS误差评定方法，通过物理光学模型分析12种误差源对波前测量精度的影响，并基于蒙特卡洛方法评估特定波前的测量不确定度。对三个实验测得波前（平面、球面、自由曲面）进行了测量不确定度评估，分别得到λ/65、λ/260和λ/40的评估结果。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Light Sci. Appl.</div><img src='blob/png/LSA_2021.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b>Anti-scattering light focusing by fast wavefront shaping based on multi-pixel encoded digital-micromirror device</b>. <a href="https://www.nature.com/articles/s41377-021-00591-w">[Web]</a> <a href="blob/pdf/LSA_2021.pdf">[PDF]</a> <br>
Jiamiao Yang, `Qiaozhi He (学生一作)`, Linxian Liu, et al. <br>
**Light: Science & Applications**, 10(1): 149 (2021). (SCI:Q1, Top, IF:20.257)<br><br>
<b>挑战</b>: 数字微镜阵列（DMD）同时具备数百万的调控模式数和几十kHz的刷新频率，是当前最有潜力实现快速高对比度抗散射光聚焦的光场调控器件。然而，DMD的二值化振幅调控特性导致其在优化聚焦光斑的过程中速度过慢且难以准确收敛。 <br>
<b>方法</b>: 提出一种多像素编码方法来解决DMD调控离散度过大的问题，同时提出采用可分自然进化策略这一全局搜索算法从随机散射光中快速分离聚焦光斑。相比于传统二进制DMD光场调控技术，将聚焦光斑的优化速度提高了179倍，对比度提高了16倍。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Opt. Lett.</div><img src='blob/png/OL_2021.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b>Gradient-assisted focusing light through scattering media</b>. <a href="https://opg.optica.org/ol/fulltext.cfm?uri=ol-46-7-1518&id=449250">[Web]</a> <a href="blob/pdf/OL_2021.pdf">[PDF]</a> <br>
Yanyu Zhao, `Qiaozhi He (学生一作)`, Shuna Li, et al. <br>
**Optics Letters**, 46(7): 1518-1521 (2021). (SCI:Q2, IF:3.56)<br><br>
<b>挑战</b>: 透过散射介质聚焦光束是生物医学光学领域的一项长期挑战，基于反馈的波前整形方法是一种强有力的解决方案。当前广泛使用遗传算法作为迭代优化算法，然而，这种算法非常耗时，且难以实现高对比度聚焦光斑。<br>
<b>方法</b>: 提出了一种基于梯度辅助波前整形策略的波前整形方法，该方法在Kullback-Leibler divergence散射来分析各像素相位的上升梯度，相比于遗传算法，此方法将光斑聚焦速度提高了 60 倍，其峰背比可达400。
 
</div>
</div>

- `Qiaozhi He`, Qian Wang, Pengfei Lv, et al. Liquid photoacoustic sensing with high sensitivity by temperature compensated differential detection method. **Applied Physics Express**, 13(11): 117001 (2020). (IF:2.819) [[Web]](https://iopscience.iop.org/article/10.35848/1882-0786/abbd26/meta) [[PDF]](blob/pdf/APEX_2020.pdf)

- `Qiaozhi He`, Qian Zhang, Wenwu Cao, et al. Detecting trace of mercury ions in water using photoacoustic method enhanced by gold nanospheres. **Microchemical Journal**, 150: 104058 (2019). (SCI:Q2, IF:5.304) [[Web]](https://www.sciencedirect.com/science/article/pii/S0026265X19304205) [[PDF]](blob/pdf/MJ_2019.pdf)

- Chunxu Ding, Rongjun Shao, Yuan Qu, `Qiaozhi He`, et al. Spatial Full Degree‐Of‐Freedom Scattered Optical Field Modulation. **Laser & Photonics Reviews**, Early Access (2023). (SCI:Q1, Top, IF:10.947) [[Web]](https://onlinelibrary.wiley.com/doi/full/10.1002/lpor.202300104) 

- Xiaoqia Yin, Wei Tao, Yiyang Feng, Qiang Gao, `Qiaozhi He`, et al. Laser stripe extraction method in industrial environments utilizing self-adaptive convolution technique. **Applied Optics**, 56(10): 2653-2660 (2017). (IF:1.905) [[Web]](https://opg.optica.org/ao/fulltext.cfm?uri=ao-56-10-2653&id=361844)

- Rongjun Shao, Yuan Qu, Chunxu Ding, Kui Ma, Gaoyu Zou, `Qiaozhi He`, et al. Volumetric random-access multi-focus scanning based on fast light modulation. **Optics and Lasers in Engineering**, 158: 107128 (2022). (SCI:Q2, IF:5.666) [[Web]](https://www.sciencedirect.com/science/article/pii/S0143816622001804)

- Linxian Liu, Wenjie Liang, Yuan Qu, `Qiaozhi He`, et al. Anti-scattering light focusing with full-polarization digital optical phase conjugation based on digital micromirror devices. **Optics Express**, 30(18): 31614-31622 (2022). (SCI:Q2, IF:3.833) [[Web]](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-18-31614&id=492009)

- Linxian Liu, Chunxu Ding, Yuan Qu, `Qiaozhi He`, et al. Anti-scattering light focusing by full-polarization wavefront shaping based on digital micromirror devices. **Applied Physics Express**, 15(9): 092001 (2022). (IF:2.819) [[Web]](https://iopscience.iop.org/article/10.35848/1882-0786/ac851e/meta)

- Gaoyu Zou, Rongjun Shao, Linxian Liu, `Qiaozhi He`, et al. Random-access multi-focus manipulation through superpixel-encoding wavefront engineering. **Applied Physics Express**, 15(11): 112004 (2022). (IF:2.819) [[Web]](https://iopscience.iop.org/article/10.35848/1882-0786/ac99b7/meta)

- Linxian Liu, Kui Ma, Yuan Qu, `Qiaozhi He`, et al. High-contrast light focusing through scattering media with multi-pixel encoding. **Applied Physics Express**, 14(9): 092009 (2021). (IF:2.819) [[Web]](https://iopscience.iop.org/article/10.35848/1882-0786/ac200e/meta)

- Xiaoqia Yin, Wei Tao, Chao Zheng, Hongwei Yang, `Qiaozhi He`, et al. Analysis and simplification of lens distortion model for the Scheimpflug imaging system calibration. **Optics Communications**, 430: 380-384 (2019). (IF:2.335) [[Web]](https://www.sciencedirect.com/science/article/abs/pii/S003040181830484X)

- Xiaoqia Yin, Wei Tao, Yu Feng, Hongwei Yang, `Qiaozhi He`, et al. A robust and accurate breakpoint detection method for line-structured laser scanner. **Optics & Laser Technology**, 118: 52-61 (2019). (SCI:Q2, IF:4.939) [[Web]](https://www.sciencedirect.com/science/article/abs/pii/S0030399217317474)

- Wei Tao, Zhiqian Lu, `Qiaozhi He`, et al. Research on the temperature characteristics of the photoacoustic sensor of glucose solution. **Sensors**, 18(12): 4323 (2018). (IF:3.847) [[Web]](https://www.mdpi.com/1424-8220/18/12/4323)

- Ting Yin, Qian Zhang, Haigang Wu, Guo Gao, Joseph G Shapter, Yulan Shen, `Qiaozhi He`, et al. In vivo high-efficiency targeted photodynamic therapy of ultra-small Fe3O4@ polymer-NPO/PEG-Glc@ Ce6 nanoprobes based on small size effect. **NPG Asia Materials**, 9(5): e383 (2017). (SCI:Q2, IF:10.761) [[Web]](https://www.nature.com/articles/am201768)

- Ting Yin, Haigang Wu, Qian Zhang, Guo Gao, Joseph G. Shapter, Yulan Shen, `Qiaozhi He`, et al. In vivo targeted therapy of gastric tumors via the mechanical rotation of a flower-like Fe3O4@ Au nanoprobe under an alternating magnetic field. **NPG Asia Materials**, 9(7): e408 (2017). (SCI:Q2, IF:10.761) [[Web]](https://www.nature.com/articles/am2017117)

- Siwei Zhao, Wei Tao, `Qiaozhi He`, et al. A non-invasive photoacoustic and ultrasonic method for the measurement of glucose solution concentration. **AIP Advances**, 7(3): 035313 (2017). (IF:1.697) [[Web]](https://pubs.aip.org/aip/adv/article/7/3/035313/1023711)

- Siwei Zhao, Wei Tao, `Qiaozhi He`, et al Glucose solution determination based on liquid photoacoustic resonance. **Applied optics**, 56(2): 193-199 (2017). (IF:1.905) [[Web]](https://opg.optica.org/ao/abstract.cfm?uri=ao-56-2-193)


### 投稿论文 (`*`表示通信作者, `†`表示共同一作)
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submit to Sci. Adv.</div><img src='blob/png/SA_2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b>An ultrahigh fidelity 3D holographic display using scattering to homogenize the angular spectrum</b>. <br>
Jiamiao Yang†, Lei S. Li†, `Qiaozhi He†`, et al. <br>
**Science Advances** (SCI:Q1, Top, IF:14.956)<br><br>
<b>挑战</b>: 全息三维显示技术（3DHD）能够准确复现物体三维信息，使人们裸眼即可观看与现实物体一样逼真的三维图像，被认为是三维显示的终极形态。然而，当前3DHD的保真度非常低，限制了它的进一步应用。<br>
<b>方法</b>: 提出一种超高保真度的3DHD显示器，利用散射效应将光束空间频谱均匀化，然后记录在具有亿级调控模式数和半波长级像素尺寸的光致聚合物上，从而高效还原记录信息。此方法将聚焦光斑的峰背比和横向分辨率分别提高至6×10<sup>6</sup>和0.5 µm。此外，利用光致聚合物的空间复用性和散射介质的传输通道选择性，实现了1 mm × 1 mm × 26 mm空间内三维螺旋曲线的动态全息显示。

</div>
</div>

-	`Qiaozhi He`, Rongjun Shao, Yuan Qu, et al. Complex transmission matrix retrieval for highly scattering medium via regional phase differentiation. **PhotoniX**, Submitted. (SCI:Q1, Top, IF:19.818)

- Jiamiao Yang, Jichong Zhou, Yuan Qu, Rongjun Shao, `Qiaozhi He*`. Large dynamic range Shack-Hartmann wavefront sensor based on spot adaptive matching, **Optics Express**, Submitted. (SCI:Q2, IF:3.833) 

- Chunxu Ding, Rongjun Shao, Yuan Qu, Linxian Liu, `Qiaozhi He`, et al. Spatial full degree-of-freedom angular spectrum modeling of scattered light modulation, **Photonics Research**, Submitted. (SCI:Q1, Top, IF:7.254) 


### 发明专利
---
- 陶卫, 赵辉, 王侃, 赵思维, `何巧芝`等, 一种可在线连续进行液体光声检测的光声池及测量方法, ZL201710710472.X, 2023.06.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=6AEA9DGA9HBACFHA3BBA9EFA9HBG7AGA9DHB5BAA9BIH4CAA)
- 赵辉, 陶卫, 吕娜, `何巧芝`等, 一种便携式重金属含量快速检测装置, ZL202010422811.6, 2021.05.07. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9IEF4DBA9FEC5EBA9FEB3BCA9FGG5DAA9DGC9CAB9IHH2BAA)
- 赵辉, 陶卫, 吕娜, 吕鹏飞, 陆志谦, `何巧芝`等, 具备温度补偿的差动光声测量系统和方法, ZL201910190004.3, 2021.04.27. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9CHC9CIB9IBBABHA9EIE9EHC9FFCAIAA9DHB8AIA1BAA9IBE)
- 陶卫, 赵辉, 胡艳丽, `何巧芝`等, 基于纳米金颗粒增强的液体痕量浓度检测方法及装置, ZL201810211449.0, 2020.03.10. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HDD9GFC9GGE9ADC6DCA9HGE9IGH9EEA8AHA9AHC9FFFBEFA)
- 陶卫, 赵辉, 高强, 张正琦, 杨红伟, 邓凯鹏, 赵思维, 肖素枝, 尹小恰, `何巧芝`等, 基于激光与视觉的机器人零位标定系统与方法, ZL201610281886.0, 2018.08.03. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9ICD4BDA9HGF9BHF9FIF7FCA9GBA9AGF6AFA9HBHDEIA9CIH)
- 杨佳苗, `何巧芝`, 周纪冲等, 一种夏克哈特曼波前传感器误差评估方法, CN202310892349.X, 2023.07.20.
- 杨佳苗, `何巧芝`, 李秋苑等, 基于相位掩模增强的散射介质传输矩阵测量方法和装置, CN202310851440.7, 2023.07.12.
- 杨佳苗, 沈阳, 邵荣君, 王冬梅, `何巧芝`等, 一种补偿色散DMD投影方法, CN202310435279.5, 2023.04.21.
- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`等, 基于立体视觉引导的目标位置三维形貌高精度快速测量方法和装置, CN202011335835.4, 2020.11.25. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=3BAA9EID9EFC2CAA3CAA5AEA5CAA9CEA9FCD9IAH9HAB9BDA)
- 杨佳苗, `何巧芝`, 刘林仙等, 基于全光场调控的散射介质光场聚焦方法与装置, CN202011312066.6, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=7AFA9IDC9ICD9ICB8HAA9GIGBHIA9IGG5BCA9IBA9HDH9IAF)
- 杨佳苗, `何巧芝`, 刘林仙等, 基于复振幅光场调控的散射介质光场聚焦方法与装置, CN202011315091.X, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=7FAA9IHG9HGG9HCA6BEA4CBA9HEF3BBABFIA9GHE9CAC9GDB)
- 杨佳苗, 刘林仙, 邹高宇, 龚雷, `何巧芝`等, 基于复振幅光场调控技术的三维光束扫描方法与装置, CN202011315092.4, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HFF9HIG5ADA9GEB9CIC8DEA9GEE9HFE9EDD3CBAABHA9EDA)
- 杨佳苗, 邹高宇, 武文彬, 刘林仙, 龚雷, `何巧芝`等, 基于复振幅光场调控技术的光束扫描方法与装置, CN202011315093.9, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HEE1BAA9IEF0AAA6EBA9GFD9IBD6CDAAHFA9FIE9AHH4ABA)
- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 具有荧光污染物检测功能的智能手机及检测方法, CN202010492593.3, 2020.06.03. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9CFA4EAA9IGH9IFE8AHA7HAA9AFAACGA4CAA9BEB9EDHAIGA)
- 刘林仙, 沈阳, 杨佳苗, 童强, `何巧芝`, 智能手机荧光污染物检测方法与装置, CN202010492594.8, 2020.06.03. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=8BFA6BFA9IDE9EFA9BHA6CEA9EFEHHIA9EFC9BGD9BEF9EDC)
- 杨佳苗, 刘林仙, `何巧芝`等, 光场实时探测调控方法与装置, CN202010492593.3, 2020.06.11. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9IBC9FFB7CDA8EEA8CFA9HHF9CEC9EGD9BIH9IEG9HCH9IBC)
- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 智能设备荧光污染物检测方法与装置, CN202010492596.7, 2020.06.03. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9GFE7GBA9FEC8BHA7AGA9FEACIHADDIA9IAB9EHHACGA9FBD)
- 姜虹, 赵辉, 孙宇, 胡蓉, 吕娜, 严佳, 王佳怡, 郑超, `何巧芝`, 一种基于呼气末二氧化碳浓度分布的插管装置, CN201910511744.2, 2019.06.13. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9DIE7AHA6AFA9ACC9FDA8IAA9GEG3ACA4ADA9DBC9GEF9BEA)
- 陶卫, 赵辉, 赵思维, `何巧芝`等, 可抵抗环境干扰和振动的差动式无创血糖监测仪及方法, CN201710621448.9, 2017.07.27. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=4ACA9IGF9GDB9GDH9CIC6DDA8CAA3ABA5DBA9EIH9HBDEGHA)

### 实用新型专利
---
- 杨佳苗, 刘林仙, `何巧芝`等, 光场实时探测调控装置, ZL202021064109.9, 2020.12.29. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9CFA9HHF7FAA7AHA9DHD7ECA8BHAAGFA8DBA6CDA9HCAIIIA)
- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 智能设备荧光污染物检测装置, ZL202020987643.0, 2021.03.23. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9GHG5FAA8DDA8DFA9BGA5EBAGGIA9AIH9CGGAEHA9HDF9CGC)
- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 具有荧光污染物检测功能的智能手机, ZL202020987996.0, 2021.02.19. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HEE8BHA9BGA7BGA9FHF9BIA9BBCDIEA9BCB9AFFFGHABFHA)
- 姜虹, 赵辉, 孙宇, 胡蓉, 吕娜, 严佳, 王佳怡, 郑超, `何巧芝`, 一种基于呼气末二氧化碳浓度分布的插管装置, ZL201920891851.8, 2020.08.07. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=4CAA8GCA9FGDCEGA9IFG8BHACIDAEGGA9GHF9AED5AAA7DDA)
- 陶卫, 赵辉, 王侃, 赵思维, `何巧芝`等, 一种可在线连续进行液体光声检测的光声池, ZL201721036422.X, 2018.03.06. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9EDA7HAA9EEA9CEE9EEB9IDD9HHF9BFA9FBD9EHG4BBA9BHB)
- 杨佳苗, 沈阳, 邵荣君, 王冬梅, `何巧芝`等, 一种补偿色散DMD投影装置, CN202320915077.6, 2023.4.21.


<span class='anchor' id='-kyxm'></span>

# 🏛️ 科研项目

- *2019.01-2022.12*, 纳米金颗粒增强的痕量汞光声检测机理与方法研究, 国家自然科学基金面上项目, 63万, `项目主要完成人`
- *2021.1-2022.12*, 超景深三维数字显微仪器研制, 上海季丰电子股份有限公司合作项目, 647万, `项目参与人`
- *2023.01-2025.12*, 近浅海微底形高分辨近底原位光学观测系统研制与应用, 上海交通大学“深蓝计划”基金重点项目, 100万, `项目核心成员`
- *2022.09-2023.02*, 高精度光学大型薄壁结构焊后变形测量技术研究, 上海交通大学集成攻关培育项目, 50万, `项目核心成员`
- *2022.10-2023.12*, 微底形高分辨近底原位光学观测系统研制与应用, 东海实验室开放基金项目, 30万, `项目核心成员`

<span class='anchor' id='-gzfw'></span>

# 💻 工作服务
- *2021.01 - 至今*, 上海交通大学—海洋装备研究院, 助理研究员, 上海

<span class='anchor' id='-qxjl'></span>

# 🎓 求学经历

- *2014.09 - 2021.12*, 上海交通大学—电子信息与电气工程学院, 仪器科学与技术, 推免直博, 上海
- *2010.09 - 2014.06*, 华中科技大学—机械科学与工程学院, 测控技术与仪器, 本科, 湖北武汉

<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2018.05* 获得 国家留学基金委（CSC）奖学金
- *2014.06* 获得 华中科技大学优秀毕业生
- *2013.01* 获得 华中科技大学学习优秀奖学金
- *2012.10* 获得 华中科技大学本科特优生（`专业唯一`）
- *2012.11* 获得 国家奖学金（`年度专业唯一`）
- *2011.12* 获得 国家励志奖学金（`年度专业唯一`）
- *2011.12* 获得 华中科技大学学习优秀奖学金