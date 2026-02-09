# 终末的计算器 / The End of All Field Calculators

![天有鸿璐](./honglu_in_the_sky.png)

*天有鸿璐，地生五金*

采用 MIP 建模求解，可扩展到任意线性生产配方，并能达到最精确数值。
代码部分以 GPL-3.0+ 发布，游戏相关资源数据为版权方（鹰角网络等）所有。

结论（2026-09-26）：假设武陵电量全部来自搬运电池，理想装备原件产量为每分钟 2.25，每天 3240，每周 22680。

## 如何运行

配方数据存在 `.ods` 表格里；默认储量和目标在 `.ipynb` 代码。

运行环境在 `./python-mip_py312.yml`，
可以 `mamba env create -f ./python-mip_py312.yml`
或者 `conda env create -f ./python-mip_py312.yml` 导入。
