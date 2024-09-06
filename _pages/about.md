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

何巧芝，工学博士，助理研究员。本科毕业于<a href = "http://mse.hust.edu.cn/">华中科技大学机械科学与工程学院</a>，后推免直博于<a href = "https://www.seiee.sjtu.edu.cn/">上海交通大学电子信息与电气学院</a>，期间赴<a href = "https://www.psu.edu/">美国宾夕法尼亚州立大学</a>公派留学。2024年加入<a href = "https://saist.usst.edu.cn">上海理工大学智能科技学院</a>，从事波前整形、衍射神经网络等方面研究，并对计算光学、智能感知等方向有浓厚兴趣，迄今已在 Science Advances、Light: Science & Applications、Photonics Research、Light: Advanced Manufacturing等知名SCI期刊发表论文20余篇
 <a href='https://scholar.google.com/citations?user=Rm2lL78AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>，申请国家发明专利20余项。

研究方向：散射光场调控、衍射神经网络、精密光学检测

<span class='anchor' id='-xsdt'></span>

# 📣 学术动态
- *2024.09*: &nbsp; 加入上海理工大学智能科技学院
- *2024.08*: &nbsp;🎉🎉 获批国家自然科学基金青年科学基金项目
- *2024.02*: &nbsp;🎉🎉 散射介质传输矩阵测量相关研究被 Photonics Research 接收
- *2023.12*: &nbsp;🎉🎉 夏克-哈德曼波前传感相关研究被中国科技期刊卓越行动计划高起点新刊 Light: Advanced Manufacturing 接收
- *2023.10*: &nbsp;🎉🎉 相位偏折术相关研究被 Optics Express 接收
- *2023.09*: &nbsp;🎉🎉 超高清全息三维显示相关研究被 Science 子刊 Science Advances 接收
- *2023.08*: &nbsp;🎉🎉 夏克-哈特曼波前传感相关研究被 Applied Physics Letters 接收
<!-- - *2023.07*: &nbsp; 参加 2023 中国光学学会学术大会（口头报告） -->

<span class='anchor' id='-gzfw'></span>

# 💻 工作服务
- *2024.09 - 至今*, 上海理工大学 — 智能科技学院, 讲师, 上海
- *2022.01 - 2024.08*, 上海交通大学 — 海洋装备研究院, 助理研究员, 上海

<span class='anchor' id='-qxjl'></span>

# 🎓 求学经历

- *2014.09 - 2021.12*, 上海交通大学 — 电子信息与电气工程学院, 仪器科学与技术, 推免直博, 上海
- *2018.09 - 2019.09*, 宾夕法尼亚州立大学 — 工程学院，材料研究所，交流，美国
- *2010.09 - 2014.06*, 华中科技大学 — 机械科学与工程学院, 测控技术与仪器, 本科, 湖北武汉

<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2018.05* 获得 国家留学基金委（CSC）联合培养博士生奖学金
- *2014.06* 获得 华中科技大学优秀毕业生
- *2013.01* 获得 华中科技大学学习优秀奖学金
- *2012.10* 获得 华中科技大学本科特优生（`专业唯一`）
- *2012.11* 获得 国家奖学金（`年度专业唯一`）
- *2011.12* 获得 国家励志奖学金（`年度专业唯一`）
- *2011.12* 获得 华中科技大学学习优秀奖学金

<span class='anchor' id='-lwzl'></span>

# 📝 论文专利

### 发表论文 (`†`表示共同一作, `*`表示通信作者)
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sci. Adv.</div><img src='blob/png/SA_2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b>An ultrahigh fidelity 3D holographic display using scattering to homogenize the angular spectrum</b>. <a href="https://doi.org/10.1126/sciadv.adi9987">[Web]</a><br>
Jiamiao Yang†, Lei S. Li†, `Qiaozhi He†`, et al. <br>
**Science Advances**, 9(41): eadi9987 (2023). (中科院 1 区, Top, IF:14.956)<br><br>
<b>挑战</b>: 全息三维显示技术（3DHD）能够准确复现物体三维信息，使人们裸眼即可观看与现实物体一样逼真的三维图像，被认为是三维显示的终极形态。然而，当前3DHD的保真度非常低，限制了它的进一步应用。<br>
<b>方法</b>: 提出一种超高保真度的3DHD显示器，利用散射效应将光束空间频谱均匀化，然后记录在具有亿级调控模式数和半波长级像素尺寸的光致聚合物上，从而高效还原记录信息。此方法将聚焦光斑的峰背比和横向分辨率分别提高至6×10<sup>6</sup>和0.5 µm。此外，利用光致聚合物的空间复用性和散射介质的传输通道选择性，实现了1 mm × 1 mm × 26 mm空间内三维螺旋曲线的动态全息显示。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Light: Sci. Appl.</div><img src='blob/png/LSA_2021.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b>Anti-scattering light focusing by fast wavefront shaping based on multi-pixel encoded digital-micromirror device</b>. <a href="https://doi.org/10.1038/s41377-021-00591-w">[Web]</a><br>
Jiamiao Yang, `Qiaozhi He (学生一作)`, Linxian Liu, et al. <br>
**Light: Science & Applications**, 10(1): 149 (2021). (中科院 1 区, Top, IF:20.257)<br><br>
<b>挑战</b>: 精确测量散射介质传输矩阵对于抗散射光学成像、光治疗、光学神经网络等领域具有重要意义。当前基于数字微镜阵列的非干涉散射传输矩阵测量方法存在全局收敛性不足的问题，导致传输矩阵测量准确度受限。 <br>
<b>方法</b>: 提出一种基于区域相位掩模差分的强散射介质复传输矩阵测量方法，通过数值模拟证明了所提出方法对传输矩阵测量准确度相比常规方法提高了3个数量级。基于此，实验实现了透过diffuser的高对比度光束聚焦（峰背比提高3.6倍）和低误码率图像传输（误码率降低24倍）。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Photonics Res.</div><img src='blob/png/PR_2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b>Complex transmission matrix retrieval for highly scattering medium via regional phase differentiation</b>. <a href="https://doi.org/10.1364/PRJ.513519">[Web]</a><br>
`Qiaozhi He`, Rongjun Shao, Yuan Qu, et al. <br>
**Photonics Research**, 12(5): 876 (2024). (中科院 1 区, Top, IF:7.254)<br><br>
<b>挑战</b>: 数字微镜阵列（DMD）同时具备数百万的调控模式数和几十kHz的刷新频率，是当前最有潜力实现快速高对比度抗散射光聚焦的光场调控器件。然而，DMD的二值化振幅调控特性导致其在优化聚焦光斑的过程中速度过慢且难以准确收敛。 <br>
<b>方法</b>: 提出一种多像素编码方法来解决DMD调控离散度过大的问题，同时提出采用可分自然进化策略这一全局搜索算法从随机散射光中快速分离聚焦光斑。相比于传统二进制DMD光场调控技术，将聚焦光斑的优化速度提高了179倍，对比度提高了16倍。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Light: Adv. Manuf.</div><img src='blob/png/LAM_2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b>Large dynamic range Shack-Hartmann wavefront sensor based on spot adaptive matching</b>. <a href="https://doi.org/10.37188/lam.2024.007">[Web]</a><br>
Jiamiao Yang†, Jichong Zhou†, `Qiaozhi He*`, et al. <br>
**Light: Advanced Manufacturing**, 4:7 (2024). (中国科技期刊卓越行动计划高起点新刊)<br><br>
<b>挑战</b>: 夏克-哈特曼传感器（SHWS）是一种高速、精确、稳定的波前测量技术。然而，传统的SHWS存在一个限制，即每个微透镜的聚焦光斑被限制在单个微透镜内，导致动态范围受限，并且在存在缺失点的情况下无法完成检测。 <br>
<b>方法</b>: 提出一种基于自适应斑点匹配(ASM)的大动态范围SHWS，通过最近距离匹配策略寻找最匹配检测到的斑点分布的入射波前，从而实现全局光斑匹配，显著扩大了动态范围。实验表明，在12.5%光斑缺失情况下，ASM-SHWS可以测量到局部斜率为204.97 mrad的高曲率球面波前，比传统SHWS高出14.81倍。
</div>
</div>

- `Qiaozhi He`, Qian Zhang, Wenwu Cao, et al. Detecting trace of mercury ions in water using photoacoustic method enhanced by gold nanospheres. **Microchemical Journal**, 150: 104058 (2019). (中科院 2 区, Top, IF:5.304) [[Web]](https://doi.org/10.1016/j.microc.2019.104058)

- `Qiaozhi He`, Qian Wang, Pengfei Lv, et al. Liquid photoacoustic sensing with high sensitivity by temperature compensated differential detection method. **Applied Physics Express**, 13(11): 117001 (2020). (IF:2.819) [[Web]](https://doi.org/10.35848/1882-0786/abbd26) 

- Siyuan Jiang, `Qiaozhi He†`, Yifan Xing, et al. Multi-field stitching phase measuring deflectometry for freeform specular surface measurement. **Optics Express**, 31(22): 36557-36567 (2023). (中科院 2 区, Top, IF:3.833) [[Web]](https://doi.org/10.1364/OE.504254)

- Jichong Zhou, `Qiaozhi He†`, Yuan Qu, et al. Arbitrary wavefront uncertainty evaluation for the Shack-Hartmann wavefront sensor using physical optics propagation. **Applied Physics Letters**, 123: 071102 (2023). (中科院 2 区, IF:3.971) [[Web]](https://doi.org/10.1063/5.0163112)

- Yanyu Zhao, `Qiaozhi He (学生一作)`, Shuna Li, et al. Gradient-assisted focusing light through scattering media. **Optics Letters**, 46(7): 1518-1521 (2021). (中科院 2 区, Top, IF:3.56) [[Web]](https://doi.org/10.1364/OL.417606)

- Rongjun Shao†, Chunxu Ding, Yuan Qu, Linxian Liu, `Qiaozhi He`, et al. Full-polarization angular spectrum modeling of scattered light modulation. **Photonics Research**, 12(3): 485 (2024). (中科院 1 区, Top, IF:7.254) [[Web]](https://doi.org/10.1364/PRJ.506787)

- Linxian Liu, Yingxuan Zhang, Jiayin Chen, `Qiaozhi He`, et al. Energy-efficient dispersion compensation for digital micromirror device. **Optics Express**, 32(8): 13946-13954 (2024). (中科院 2 区, Top, IF:3.833) [[Web]](https://doi.org/10.1364/OE.521743)

- Rongjun Shao, Chunxu Ding, Linxian Liu, `Qiaozhi He`, et al. High-fidelity multi-channel optical information transmission through scattering media. **Optics Express**, 32(2), 2846-2855 (2024). (中科院 2 区, Top, IF:3.833) [[Web]](https://doi.org/10.1364/OE.514668)

- Linxian Liu, Jiahao Liu, Chunxu Ding, Jiamiao Yang, Jia Gao, Yuan Qu, `Qiaozhi He`, et al. Multi-focus manipulation system based on SNES aberration self-calibration. **Applied Physics Express**, 17: 032001 (2024). (IF:2.819) [[Web]](https://doi.org/10.35848/1882-0786/ad2afe)

- Chunxu Ding†, Rongjun Shao†, Yuan Qu, `Qiaozhi He`, et al. Spatial Full Degree‐Of‐Freedom Scattered Optical Field Modulation. **Laser & Photonics Reviews**, 17(9): 2300104 (2023). (中科院 1 区, Top, IF:10.947) [[Web]](https://doi.org/10.1002/lpor.202300104) 

- Chunxu Ding, Rongjun Shao, `Qiaozhi He`, et al. Wavefront shaping improves the transparency of the scattering media: a review. **Journal of Biomedical Optics**, 29(S1): S11507 (2023). (IF:3.758) [[Web]](https://doi.org/10.1117/1.JBO.29.S1.S11507)

- Linxian Liu, Wenjie Liang, Yuan Qu, `Qiaozhi He`, et al. Anti-scattering light focusing with full-polarization digital optical phase conjugation based on digital micromirror devices. **Optics Express**, 30(18): 31614-31622 (2022). (中科院 2 区, Top, IF:3.833) [[Web]](https://doi.org/10.1364/OE.467444)

- Rongjun Shao, Yuan Qu, Chunxu Ding, Kui Ma, Gaoyu Zou, `Qiaozhi He`, et al. Volumetric random-access multi-focus scanning based on fast light modulation. **Optics and Lasers in Engineering**, 158: 107128 (2022). (中科院 2 区, IF:5.666) [[Web]](https://doi.org/10.1016/j.optlaseng.2022.107128)

- Linxian Liu, Chunxu Ding, Yuan Qu, `Qiaozhi He`, et al. Anti-scattering light focusing by full-polarization wavefront shaping based on digital micromirror devices. **Applied Physics Express**, 15(9): 092001 (2022). (IF:2.819) [[Web]](https://doi.org/10.35848/1882-0786/ac851e)

- Gaoyu Zou, Rongjun Shao, Linxian Liu, `Qiaozhi He`, et al. Random-access multi-focus manipulation through superpixel-encoding wavefront engineering. **Applied Physics Express**, 15(11): 112004 (2022). (IF:2.819) [[Web]](https://doi.org/10.35848/1882-0786/ac99b7)

- Linxian Liu, Kui Ma, Yuan Qu, `Qiaozhi He`, et al. High-contrast light focusing through scattering media with multi-pixel encoding. **Applied Physics Express**, 14(9): 092009 (2021). (IF:2.819) [[Web]](https://doi.org/10.35848/1882-0786/ac200e)

- Xiaoqia Yin, Wei Tao, Chao Zheng, Hongwei Yang, `Qiaozhi He`, et al. Analysis and simplification of lens distortion model for the Scheimpflug imaging system calibration. **Optics Communications**, 430: 380-384 (2019). (IF:2.335) [[Web]](https://doi.org/10.1016/j.optcom.2018.05.086)

- Xiaoqia Yin, Wei Tao, Yu Feng, Hongwei Yang, `Qiaozhi He`, et al. A robust and accurate breakpoint detection method for line-structured laser scanner. **Optics & Laser Technology**, 118: 52-61 (2019). (中科院 2 区, Top, IF:4.939) [[Web]](https://doi.org/10.1016/j.optlastec.2019.03.037)

- Wei Tao, Zhiqian Lu, `Qiaozhi He`, et al. Research on the temperature characteristics of the photoacoustic sensor of glucose solution. **Sensors**, 18(12): 4323 (2018). (IF:3.847) [[Web]](https://doi.org/10.3390/s18124323)

- Siwei Zhao, Wei Tao, `Qiaozhi He`, et al. A non-invasive photoacoustic and ultrasonic method for the measurement of glucose solution concentration. **AIP Advances**, 7(3): 035313 (2017). (IF:1.697) [[Web]](https://doi.org/10.1063/1.4979110)

- Xiaoqia Yin, Wei Tao, Yiyang Feng, Qiang Gao, `Qiaozhi He`, et al. Laser stripe extraction method in industrial environments utilizing self-adaptive convolution technique. **Applied Optics**, 56(10): 2653-2660 (2017). (IF:1.905) [[Web]](https://doi.org/10.1364/AO.56.002653)

- Siwei Zhao, Wei Tao, `Qiaozhi He`, et al Glucose solution determination based on liquid photoacoustic resonance. **Applied optics**, 56(2): 193-199 (2017). (IF:1.905) [[Web]](https://doi.org/10.1364/AO.56.000193)

- Ting Yin, Haigang Wu, Qian Zhang, Guo Gao, Joseph G. Shapter, Yulan Shen, `Qiaozhi He`, et al. In vivo targeted therapy of gastric tumors via the mechanical rotation of a flower-like Fe3O4@ Au nanoprobe under an alternating magnetic field. **NPG Asia Materials**, 9(7): e408 (2017). (中科院 2 区, IF:10.761) [[Web]](https://doi.org/10.1038/am.2017.117)

- Ting Yin, Qian Zhang, Haigang Wu, Guo Gao, Joseph G Shapter, Yulan Shen, `Qiaozhi He`, et al. In vivo high-efficiency targeted photodynamic therapy of ultra-small Fe3O4@ polymer-NPO/PEG-Glc@ Ce6 nanoprobes based on small size effect. **NPG Asia Materials**, 9(5): e383 (2017). (中科院 2 区, IF:10.761) [[Web]](https://doi.org/10.1038/am.2017.68)

### 发明专利
---
- 赵辉, 陶卫, 吕娜, `何巧芝`等, 一种便携式重金属含量快速检测装置, 中国, ZL202010422811.6, 2021.05.07. (已授权, 学生第一发明人) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9IEF4DBA9FEC5EBA9FEB3BCA9FGG5DAA9DGC9CAB9IHH2BAA)

- 陶卫, 赵辉, 王侃, 赵思维, `何巧芝`等, 一种可在线连续进行液体光声检测的光声池及测量方法, 中国, ZL201710710472.X, 2023.06.20. (已授权)[[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=6AEA9DGA9HBACFHA3BBA9EFA9HBG7AGA9DHB5BAA9BIH4CAA)

- 陶卫, 赵辉, 胡艳丽, `何巧芝`等, 基于纳米金颗粒增强的液体痕量浓度检测方法及装置, 中国, ZL201810211449.0, 2020.03.10. (已授权, 学生第一发明人) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HDD9GFC9GGE9ADC6DCA9HGE9IGH9EEA8AHA9AHC9FFFBEFA)

- 赵辉, 陶卫, 吕娜, 吕鹏飞, 陆志谦, `何巧芝`等, 具备温度补偿的差动光声测量系统和方法, 中国,  ZL201910190004.3, 2021.04.27. (已授权) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9CHC9CIB9IBBABHA9EIE9EHC9FFCAIAA9DHB8AIA1BAA9IBE)

- 陶卫, 赵辉, 高强, 张正琦, 杨红伟, 邓凯鹏, 赵思维, 肖素枝, 尹小恰, `何巧芝`等, 基于激光与视觉的机器人零位标定系统与方法, 中国, ZL201610281886.0, 2018.08.03. (已授权) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9ICD4BDA9HGF9BHF9FIF7FCA9GBA9AGF6AFA9HBHDEIA9CIH)

- 杨佳苗, 周纪冲, `何巧芝`, 一种基于全局光斑匹配的夏克哈德曼波前检测方法, 中国, CN202311694390.2, 2023.12.12.

- 杨佳苗，蒋思源，`何巧芝`, 基于宽场多孔径合成相位偏折术的高反射自由曲面方法, 中国, CN202311320417.1, 2023.10.12. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9EDA9HEC9GFE8CDA7FBA9DFABIHA7AFA9CHA8EAA9GDB9AFD)

- 杨佳苗, `何巧芝`, 周纪冲等, 一种夏克哈特曼波前传感器误差评估方法, 中国, CN202310892349.X, 2023.07.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9BHB8CGA7CDAAHHA9EFB2BBAFHHA9FCH8BFACIIA9CHEGHHA)

- 杨佳苗, `何巧芝`, 李秋苑等, 基于相位掩模增强的散射介质传输矩阵测量方法和装置, 中国, CN202310851440.7, 2023.07.12. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=5BCA8CGA8ECA8CDA9IDD8EEACIDA9DDC9BIBAFIA9BEA9FFB)

- 杨佳苗, `何巧芝`, 李静伟等, 一种光计算拓扑结构、系统以及系统的调控方法, 中国, CN202210510603.0, 2022.05.11. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=7FAA9CIB9GBA9HCC9BHA1ABA9EEE8AHA9EFA9DGG8FDA3AAA)

- 杨佳苗, `何巧芝`, 刘林仙等, 基于全光场调控的散射介质光场聚焦方法与装置, 中国, CN202011312066.6, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=7AFA9IDC9ICD9ICB8HAA9GIGBHIA9IGG5BCA9IBA9HDH9IAF)

- 杨佳苗, `何巧芝`, 刘林仙等, 基于复振幅光场调控的散射介质光场聚焦方法与装置, 中国, CN202011315091.X, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=7FAA9IHG9HGG9HCA6BEA4CBA9HEF3BBABFIA9GHE9CAC9GDB)

- 杨佳苗, 刘林仙, `何巧芝`等, 光场实时探测调控方法与装置, 中国, CN202010492593.3, 2020.06.11. (学生第一发明人) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9IBC9FFB7CDA8EEA8CFA9HHF9CEC9EGD9BIH9IEG9HCH9IBC)

- 杨佳苗, 沈阳, 邵荣君, 王冬梅, `何巧芝`等, 一种补偿色散DMD投影方法, 中国, CN202310435279.5, 2023.04.21. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9IEF9IFE8GAA9FHG9IGG9FFB9HFH7BDA8ADA9EHE9DGH9DAD)

- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`等, 基于立体视觉引导的目标位置三维形貌高精度快速测量方法和装置, 中国, CN202011335835.4, 2020.11.25. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=3BAA9EID9EFC2CAA3CAA5AEA5CAA9CEA9FCD9IAH9HAB9BDA)

- 杨佳苗, 刘林仙, 邹高宇, 龚雷, `何巧芝`等, 基于复振幅光场调控技术的三维光束扫描方法与装置, 中国, CN202011315092.4, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HFF9HIG5ADA9GEB9CIC8DEA9GEE9HFE9EDD3CBAABHA9EDA)

- 杨佳苗, 邹高宇, 武文彬, 刘林仙, 龚雷, `何巧芝`等, 基于复振幅光场调控技术的光束扫描方法与装置, 中国, CN202011315093.9, 2020.11.20. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HEE1BAA9IEF0AAA6EBA9GFD9IBD6CDAAHFA9FIE9AHH4ABA)

- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 具有荧光污染物检测功能的智能手机及检测方法, 中国, CN202010492593.3, 2020.06.03. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9CFA4EAA9IGH9IFE8AHA7HAA9AFAACGA4CAA9BEB9EDHAIGA)

- 刘林仙, 沈阳, 杨佳苗, 童强, `何巧芝`, 智能手机荧光污染物检测方法与装置, 中国, CN202010492594.8, 2020.06.03. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=8BFA6BFA9IDE9EFA9BHA6CEA9EFEHHIA9EFC9BGD9BEF9EDC)

- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 智能设备荧光污染物检测方法与装置, 中国, CN202010492596.7, 2020.06.03. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9GFE7GBA9FEC8BHA7AGA9FEACIHADDIA9IAB9EHHACGA9FBD)

- 姜虹, 赵辉, 孙宇, 胡蓉, 吕娜, 严佳, 王佳怡, 郑超, `何巧芝`, 一种基于呼气末二氧化碳浓度分布的插管装置, 中国, CN201910511744.2, 2019.06.13. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9DIE7AHA6AFA9ACC9FDA8IAA9GEG3ACA4ADA9DBC9GEF9BEA)

- 陶卫, 赵辉, 赵思维, `何巧芝`等, 可抵抗环境干扰和振动的差动式无创血糖监测仪及方法, 中国, CN201710621448.9, 2017.07.27. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=4ACA9IGF9GDB9GDH9CIC6DDA8CAA3ABA5DBA9EIH9HBDEGHA)

### 实用新型专利
---
- 杨佳苗, 刘林仙, `何巧芝`等, 光场实时探测调控装置, ZL202021064109.9, 2020.12.29. [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9CFA9HHF7FAA7AHA9DHD7ECA8BHAAGFA8DBA6CDA9HCAIIIA)

- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 智能设备荧光污染物检测装置, 中国, ZL202020987643.0, 2021.03.23. (已授权) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9GHG5FAA8DDA8DFA9BGA5EBAGGIA9AIH9CGGAEHA9HDF9CGC)

- 杨佳苗, 沈阳, 刘林仙, 童强, `何巧芝`, 具有荧光污染物检测功能的智能手机, 中国, ZL202020987996.0, 2021.02.19. (已授权) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9HEE8BHA9BGA7BGA9FHF9BIA9BBCDIEA9BCB9AFFFGHABFHA)

- 姜虹, 赵辉, 孙宇, 胡蓉, 吕娜, 严佳, 王佳怡, 郑超, `何巧芝`, 一种基于呼气末二氧化碳浓度分布的插管装置, 中国, ZL201920891851.8, 2020.08.07. (已授权) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=4CAA8GCA9FGDCEGA9IFG8BHACIDAEGGA9GHF9AED5AAA7DDA)

- 陶卫, 赵辉, 王侃, 赵思维, `何巧芝`等, 一种可在线连续进行液体光声检测的光声池, 中国, ZL201721036422.X, 2018.03.06. (已授权) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=9EDA7HAA9EEA9CEE9EEB9IDD9HHF9BFA9FBD9EHG4BBA9BHB)

- 杨佳苗, 沈阳, 邵荣君, 王冬梅, `何巧芝`等, 一种补偿色散DMD投影装置, 中国, ZL202320915077.6, 2023.4.21. (已授权) [[Web]](https://cprs.patentstar.com.cn/Search/Detail?ANE=5ADA9CHA9HCC9EFD9GFE6CEA9CCE9DFA9DED8IAA9IBH9DEF)


<span class='anchor' id='-kyxm'></span>

# 🏛️ 科研项目

- *2025.01-2027.12*, 高分辨率快速抗散射非视域成像方法研究，国家自然科学基金青年科学基金项目, `项目负责人`
- *2019.01-2022.12*, 纳米金颗粒增强的痕量汞光声检测机理与方法研究, 国家自然科学基金面上项目,  `项目主要完成人`
- *2021.01-2022.12*, 超景深三维数字显微仪器研制, 上海季丰电子股份有限公司合作项目, `项目参与人`
- *2023.01-2025.12*, 近浅海微底形高分辨近底原位光学观测系统研制与应用, 上海交通大学“深蓝计划”基金重点项目, `项目核心成员`
- *2022.09-2023.02*, 高精度光学大型薄壁结构焊后变形测量技术研究, 上海交通大学集成攻关培育项目,  `项目核心成员`
- *2022.10-2023.12*, 微底形高分辨近底原位光学观测系统研制与应用, 东海实验室开放基金项目, `项目核心成员`
