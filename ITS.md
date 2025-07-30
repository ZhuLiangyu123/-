ITS数据集对应论文：RESIDE: A Benchmark for Single Image Dehazing（IEEE Trans. Image Process 2018）

ITS数据集下载链接（官方提供的百度云链接）：  http://tinyurl.com/yaohd3yv Passward: g0s6

ITS（indoor training set）室内合成数据集由华中科技大学、中国科学院、中国科学技术大学、悉尼科技大学、微软研究院、德州农工大学等联合发布，是RESIDE数据集中的训练集。 ITS数据集由13,990个合成模糊图像组成，这些图像是使用来自NYU2和Middlebury立体数据库的1,399个清晰图像生成的。每个清晰图像合成了10个模糊图像，其中13,000个用于训练，990个用于验证。

实际下载的ITS数据集中，解压后的文件包括train和val两个子文件夹。其中，train文件夹下又包括ITS_clear、ITS_haze和ITS_trans三个子文件夹，ITS_clear中有10000张无雾图像，ITS_haze中有100000张合成的有雾图像，ITS_trans中同样也有100000张图像，ITS_clear中的每一张无雾图像对应ITS_haze中10张不同雾霾程度的有雾图像。val文件夹下也包括clear、haze和trans三个子文件夹，clear中有1000张无雾图像，hazy中有10000张合成的有雾图像，trans中同样也有10000张图像。

存疑：下载的ITS数据集中，实际图片数量与论文中描述的图片数量并不相等。此外，在ITS_haze文件夹中，某些图像合成的有雾图像很奇怪，与真实有雾图像相差甚远。

想了解更多关于ITS数据集的详细信息，请看原始论文！
