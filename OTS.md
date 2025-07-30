OTS数据集对应论文：RESIDE: A Benchmark for Single Image Dehazing（IEEE Trans. Image Process 2018）

OTS数据集下载链接（官方提供的百度云链接）：https://pan.baidu.com/s/1YMYUp5P6FpX_5b7emjgrvA Passward: w54h

OTS（outdoor training set）室外合成数据集由华中科技大学、中国科学院、中国科学技术大学、悉尼科技大学、微软研究院、德州农工大学等联合发布，是RESIDE数据集中的训练集。OTS包含313,950张从真实户外场景中收集到的合成的图像，但不包含深度信息。文中使用论文中的方法估算每幅图像的深度图，然后利用该深度图来合成户外雾霾图像。

实际下载的OTS数据集中，包括clear、depth、haze和vis_depth_map四个子文件夹。其中，clear文件夹中包含2061张室外无雾图像；depth文件夹中包含2061个与clear文件夹中无雾图像相对应的.mat文件；haze文件夹中包含part1、part2、part3、part4四个子文件夹，part1文件夹中包含18200张合成的有雾图像，part2文件夹中也包含18200张合成的有雾图像，part3文件夹中同样包含18200张合成的有雾图像，part4文件夹中包含17535张合成的有雾图像；vis_depth_map文件夹中包含2061张深度映射图。haze文件夹下四个子文件夹中总的有雾图像的数量为：18200 + 18200 + 18200 + 17535 = 72135。

想了解更多关于​OTS数据集的详细信息，请看原始论文！
