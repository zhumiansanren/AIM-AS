# AIM-AS

Agricultural Irrigation Model - Analytical Solution

农田土壤水量平衡统计学模型 (AIM-AS)


在 Rodriguez-Iturbe(1999), Laio(2001), Vervoort (2008), Vico(2011)等人的基础上耦合灌溉参数与潜水埋深，建立了稳定条件下土壤饱和度概率密度函数解析式以及农田水量计算公式.

作者: 黄仲冬

机构: 中国农业科学院农田灌溉研究所

邮箱: zdhuang@126.com


输入参数说明:

$\Alpha$    - 日降雨事件的平均雨量, mm

$\Lambda$    - 日降雨事件的发生频率, d^-1

Emax - 日潜在蒸发蒸腾量, mm/d

Zr   - 作物主要根系吸水层深度或计划湿润层深度, mm

n    - 土壤孔隙度

sr   - 残余饱和度或凋萎饱和度

sa   - 作物开始产生水分胁迫的土壤饱和度

sf   - 田持饱和度

Ks   - 土壤饱和导水率, mm/d

b    - 土壤水分特征曲线参数

hb   - 土壤进气值, mm

Zg   - 地下水埋深, mm

si   - 灌水下限

st   - 灌水上限

其余为中间变量.


函数说明:

RAPDF[s]  - 无灌溉农田土壤饱和度概率密度函数, 无潜水位

RAGPDF[s] - 无灌溉农田土壤饱和度概率密度函数, 有潜水位

DIPDF[s]  - 亏缺灌溉农田土壤饱和度概率密度函数, 无潜水位

DIGPDF[s] - 亏缺灌溉农田土壤饱和度概率密度函数, 有潜水位

SIPDF[s]  - 充分灌溉农田土壤饱和度概率密度函数, 无潜水位

SIGPDF[s] - 充分灌溉农田土壤饱和度概率密度函数, 有潜水位
