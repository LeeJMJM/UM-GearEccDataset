# UM-GearEccDataset
__________
# 齿轮偏心数据集用户指南 User Guide for UM-GearEccDataset

## 1.	数据集总览 Dataset overview

### 1.1.	声明 Statement

该齿轮偏心数据集UM-GearEccDataset由澳门大学科技学院SMART Group提供。该数据集可用于：1）数据驱动的故障诊断模型案例分析。2) 齿轮偏心动力学模型研究的实验验证。

This gear eccentricity dataset, UM-GearEccDataset, is provided by the SMART Group from Faculty of Science and Technology, University of Macau. It can be used for: 1) Case study of data-driven mothods. 2) Experimental verification for dynamical modeling of gear eccentricity.

使用该数据集请引用：

To use this dataset, please cite:

J. Li, H. Chen, X.-B. Wang, and Z.-X. Yang, “A comprehensive gear eccentricity dataset with multiple fault severity levels: Description, characteristics analysis, and fault diagnosis applications,” _Mechanical Systems and Signal Processing_, vol. 224, p. 112068, 2025.

Available at: https://doi.org/10.1016/j.ymssp.2024.112068

### 1.2.	下载地址 Download address

#### 1)	Baidu Netdisk （Suggested for mainland China users）

Link: https://pan.baidu.com/s/1FW9gfMm2esTg0EV_2XoATg?pwd=bk5a

Password: bk5a

#### 2) NAS system of our group （Suggested for overseas users）

Link: http://QuickConnect.to/Smart5001

Account: GearEccDataset

Password: Smart2024

File Station -> GearEccDataset -> download

#### 3) Mendely, a data library of Elsevier （Only two data files uploaded due to its limited space）

Link: https://data.mendeley.com/datasets/ym6pk4889r/1

# 2.	数据集描述 Dataset description

## 2.1.	实验装置和实验方案 Test rig setup and experimental plan

请参考引用论文的章节2。

Please refer to Section 2 of the cited paper.

## 2.2.	数据文件描述 Data file description

该数据集共有4×4×11×2=352个v7.3版本的.mat数据文件。文件按照层级保存在不同文件夹里，如Fig. 1所示。

There are 4×4×11×2=352 data files (Version 7.3 MAT-files) in the dataset. They are saved hierarchically in different folders, as shown in Fig. 1.

![image](https://github.com/LeeJMJM/GearEccDataset/assets/93640564/94920096-f871-418e-bb37-afb7746194ee "Fig. 1 文件保存层级. Hierarchy of the data files.")Fig. 1 文件保存层级. Hierarchy of the data files.

以N139_G1_E16_T3_S1200.mat为例说明数据文件根据实验变量的命名规则：N139说明文件序号为139；G1说明偏心齿轮无破齿；E16说明偏心程度为0.16 mm；T3说明传动系结构为T3；S1200说明驱动电机转速为1200 rpm。

Take the file named N139_G1_E16_T3_S1200.mat as an example to demonstrate the experimental variables: N139 means the Serial No. is 139; G1 means the gear is without the chipped tooth; E16 means the fault severity level is 0.16 mm; T3 means the drivetrain structure is T3; S1200 means the rotating speed of the drive motor is 1200 rpm.

每个数据文件内包含了11个传感器记录的信号，如Fig. 2所示。

Each data file contains 11 signals from different sensors, as shown in Fig. 2.

![image](https://github.com/LeeJMJM/GearEccDataset/assets/93640564/1dcd5f65-cd02-490a-8ba3-33aef43de172 "Fig. 2 一个数据文件内的多传感器信号. Multi-source signals within a data file.")Fig. 2 一个数据文件内的多传感器信号. Multi-source signals within a data file.

# 3.	其他共享的信息 Other Info. shared here

偏心齿轮机构的加工图纸，以及齿顶圆跳动的原始测量数据。请参考相关文件夹内的描述。

The drawings of the eccentricity-simulating structure, and the raw the measurement data of the gear tip circle.
Please refer to the discription in the corresponding folder.




