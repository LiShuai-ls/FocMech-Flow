# FocMech-Flow
An automatic workflow to obtain the Focal Mechanisms with P-wave first-motion polarities.

we use the DiTingMotion model(mzhao@cea-igp.ac.cn) based on massive data and deep learning training to determine P-wave first motion polarity, and combine with the grid search method (CHNYTX) to construct an automated process which named FocMech-Flow (Focal Mechanism Flow).

The inversion of the focal mechanisms is performed by the grid search method (CHNYTX), and the relevant code can be contacted to Ph.D. Yu Chunquan(yucq@sustech.edu.cn) of the Southern University of Science and Technology.


# References:
DiTingMotion:
Zhao, M., Xiao, Z., Zhang, M., Yang, Y., Tang, L., & Chen, S. (2023). DiTingMotion: A deep-learning first-motion-polarity classifier and its application to focal mechanism inversion. Frontiers in Earth Science, 11, 335.https://doi.org/10.3389/feart.2023.1103914

DiTing Dataset:
Zhao, M., Xiao, Z., Chen, S., & Fang, L. (2022). DiTing: a large-scale Chinese seismic benchmark dataset for artificial intelligence in seismology. Earthquake Science, 35, 1-11.

CHNYTX:
俞春泉, 陶开, 崔效锋, 等. 2009. 用格点尝试法求解P波初动震源机制解及解的质量评价. 地球物理学报, 52(5): 1402-1411.
