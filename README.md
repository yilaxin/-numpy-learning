[README.md](https://github.com/user-attachments/files/33383581/README.md)
# NumPy 中文学习笔记与练习 / NumPy learning notebooks

本仓库收录 NumPy 中文入门笔记、综合练习和含答案的 100 道练习题，供学习者在线浏览、下载和在本地运行。

Chinese NumPy tutorials and exercises. Browse the notebooks on GitHub, or download them and run locally with JupyterLab.

## 本地使用 / Getting started

安装 Python 后，在仓库目录运行：

```sh
python -m venv .venv
# Windows PowerShell:
.venv\Scripts\Activate.ps1
# macOS / Linux:
# source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyterlab
```

按 01–24 的顺序阅读课程，然后完成综合练习。依赖未固定版本；部分笔记使用较早的 NumPy API，运行结果可能随版本改变。笔记保留原有内容与执行输出，发布副本仅对输出中的本机用户路径做脱敏；本次发布进行了文件格式和内容检查，未声明全部单元可在最新版本下执行通过。

## 目录 / Contents

- [01_NumPy_ndarray.ipynb](01_NumPy_ndarray.ipynb)
- [02_NumPy_数据类型.ipynb](02_NumPy_数据类型.ipynb)
- [03_NumPy_数组属性.ipynb](03_NumPy_数组属性.ipynb)
- [04_NumPy_创建数组.ipynb](04_NumPy_创建数组.ipynb)
- [05_NumPy_从已有数据创建数组.ipynb](05_NumPy_从已有数据创建数组.ipynb)
- [06_NumPy_从数值范围创建数组.ipynb](06_NumPy_从数值范围创建数组.ipynb)
- [07_NumPy_切片和索引.ipynb](07_NumPy_切片和索引.ipynb)
- [08_NumPy_高级索引.ipynb](08_NumPy_高级索引.ipynb)
- [09_NumPy_广播.ipynb](09_NumPy_广播.ipynb)
- [100_Numpy_exercises_中文版_含答案.ipynb](100_Numpy_exercises_中文版_含答案.ipynb)
- [10_NumPy_迭代数组.ipynb](10_NumPy_迭代数组.ipynb)
- [11_NumPy_数组操作.ipynb](11_NumPy_数组操作.ipynb)
- [12_NumPy_位运算.ipynb](12_NumPy_位运算.ipynb)
- [13_NumPy_字符串函数.ipynb](13_NumPy_字符串函数.ipynb)
- [14_NumPy_数学函数.ipynb](14_NumPy_数学函数.ipynb)
- [15_NumPy_算术函数.ipynb](15_NumPy_算术函数.ipynb)
- [16_NumPy_统计函数.ipynb](16_NumPy_统计函数.ipynb)
- [17_NumPy_排序和条件筛选.ipynb](17_NumPy_排序和条件筛选.ipynb)
- [18_NumPy_字节交换.ipynb](18_NumPy_字节交换.ipynb)
- [19_NumPy_副本和视图.ipynb](19_NumPy_副本和视图.ipynb)
- [20_NumPy_矩阵库.ipynb](20_NumPy_矩阵库.ipynb)
- [21_NumPy_线性代数.ipynb](21_NumPy_线性代数.ipynb)
- [22_NumPy_IO.ipynb](22_NumPy_IO.ipynb)
- [23_NumPy_Matplotlib.ipynb](23_NumPy_Matplotlib.ipynb)
- [24_NumPy_综合测验.ipynb](24_NumPy_综合测验.ipynb)
- [综合练习.ipynb](综合练习.ipynb)

## 来源与许可 / Attribution and licensing

100 道练习的参考答案来自 [Nicolas P. Rougier 的 numpy-100](https://github.com/rougier/numpy-100)。仓库保留参考答案原文和上游 MIT 许可文件 `LICENSE_numpy-100.txt`，该许可适用于对应上游材料。

其余课程笔记与综合练习保留提供者的原始内容，未为整个仓库额外授予统一开源许可。公开浏览与下载不等于所有内容获得再分发或商业使用许可；再利用时请核对原作者许可。
