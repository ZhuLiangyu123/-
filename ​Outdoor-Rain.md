​Outdoor-Rain数据集对应论文：Heavy rain image restoration: Integrating physics model and conditional adversarial learning（CVPR 2019）

Outdoor-Rain数据集下载链接：https://github.com/liruoteng/HeavyRainRemoval

Outdoor-Rain数据集是由新加坡国立大学和耶鲁-新加坡国立大学学院联合发布，是一个雨雾共存的数据集。官方提供的数据集中没有Test文件，在HeavyRainRemoval网页中的Issues中看到了Test1文件的下载链接：https://github.com/jeya-maria-jose/TransWeather/tree/33e677e0ecb15245b661b3c00b23dcabeafbd3f9

在Test1文件夹中，包含input和gt两个子文件夹，均由750张图像组成，图像名称从im_0301_***.png到im_0350_***.png。也就是说，在官方给出的train文件夹中，子文件夹gt中只有550张图像可以用作训练集；子文件夹in中有8250张图像可以用作训练集（两个子文件夹中图像名称从im_0301到im_0350的图像被分割出来用作测试集了）。

本博客讲解的Outdoor-Rain数据集中训练集和测试集与原始论文中给出的训练集和测试集大小并不一致，原始论文中指出：Outdoor-Rain数据集包含9000个训练样本和1500个验证样本（官方提供的数据集中并没有验证样本）。

想了解更多关于Outdoor-Rain数据集的详细信息，请看原始论文！
