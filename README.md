# 听报告收获

## 2026.7.17——2026.7.19

物理中的**对称性**能有希望 improve 方法的表现（数据的对称性和算法的保对称性）



Adam 收敛的必要条件：$\beta_2$ 足够大

![](figures\微信图片_20260719213553_28_63.jpg)



DNN 参数的 Hessian 往往是 block-wise dense

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213559_29_63.jpg)



Adam 可以看成是 Gaussian Newton 法在算 $gg^T$ 时用 $diag(gg^T)$（$g \circ g$）近似



参数初始化尺度越小，模型 reasoning能力越强（但也有一个临界点），反之更偏记忆

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213604_30_63.jpg)



由此在训练过程中，Normlization层中的 $\epsilon$ 大小就需要再调一些（$10^{-5} \to 10^{-12}$）

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213609_31_63.jpg)



有时候为了得到最佳结果，并不是 $D_{train}=D_{test}$，而是要有一定的 distribution shift（uniform $\leftrightarrow$ power law）

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213613_32_63.jpg)



控制参数的 spectrum（conditional number）能 improve 大模型表现

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213621_33_63.jpg)



Attention Sink

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213625_34_63.jpg)



用于验证因果发现算法的真实数据集：chambers

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213629_35_63.jpg)



通用因果推断大模型：LimiX

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213639_36_63.jpg)



表格型数据任务的 benchmark 和 datasets

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213646_37_63.jpg)



TabpFN [Accurate predictions on small data with a tabular foundation model | Nature](https://www.nature.com/articles/s41586-024-08328-6) 及其变体

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213652_38_63.jpg)

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213656_39_63.jpg)

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213702_40_63.jpg)



因果发现文献综述

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213707_41_63.jpg)

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213713_42_63.jpg)

![](C:\Users\Lenovo\Desktop\听报告收获\figures\微信图片_20260719213719_43_63.jpg)


