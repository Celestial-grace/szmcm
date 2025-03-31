# szmcm
2025深圳杯数学建模
## 编程环境
### Python
1. Jupyter Notebook下载/网页：https://jupyter.org/try-jupyter/notebooks/?path=notebooks/Intro.ipynb
2. VSCode：https://zhuanlan.zhihu.com/p/165379391
3. PyCharm专业版2024.3.4（社区版会禁用numpy等第三方库）：https://mp.weixin.qq.com/s?__biz=Mzg4OTk3MTI5Mg==&mid=2247526127&idx=8&sn=f5e4b800025cd8ee6df60dab79734ba0&chksm=cfe191dcf89618ca754d42bb8428d47b5ed078ac977fc85c60a2f607bf0a335d8f8aebadbad8&scene=178&cur_album_id=3450258744834146305#rd
4. 第三方库安装（在cmd运行）：pip install numpy pandas sympy matplotlib scipy cvxpy requests
### Matlab
（无需过于纠结版本）https://mp.weixin.qq.com/mp/appmsgalbum?__biz=Mzg4OTk3MTI5Mg==&action=getalbum&album_id=3448437508713889792#wechat_redirect
## 注意事项
1. 所有文件（夹）均交到src内，并在"Commit message"填写具体修改信息
2. 代码内不要用绝对路径，要用相对路径，'@/'：从src开始查找，'../'：返回上一级文件夹查找，'./'：从本文件夹查找，可叠加使用
## 文件说明
1. data：题目原始数据，搜集的资料，中间计算结果
2. result：数据最终图表
3. utils：自定义工具函数，类
4. quest1.py：问题1主代码
5. quest2.py：问题2主代码
6. quest3.py：问题3主代码
