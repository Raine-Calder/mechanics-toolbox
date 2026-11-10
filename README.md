# mechanics-toolbox

材料力学计算工具箱 —— 用 Python(SymPy / NumPy / Matplotlib)实现材料力学核心计算。

## 模块

| 文件 | 内容 |
| --- | --- |
| 01-axial-tension.ipynb | 轴向拉压:σ = F/A、σ = Eε、ΔL = FL/EA |
| 02-torsion.ipynb | 扭转:τ = 16T/πd³、扭转角 φ = TL/GJ |
| 03-bending.ipynb | 弯曲正应力:σ = My/I、矩形/圆截面惯性矩 |
| 04-shear-moment.ipynb | 剪力/弯矩图(简支梁 + 集中力) |
| 05-mohr-circle.ipynb | Mohr 圆:主应力、最大剪应力 |
| 06-deflection.ipynb | 梁挠度:积分法,w = PL³/48EI |

## 环境

- Python 3
- SymPy、NumPy、Matplotlib

## 说明

每个 notebook 对应一个材料力学知识点:用 SymPy 做符号推导、NumPy 做数值计算、Matplotlib 做可视化。
