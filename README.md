# Hyperspectral-Image-Denoising-Benchmark

Hyperspectral image denoising techniques can be classified into two categories based on whether spatial and spectral information of hyperspectral images are jointly used. The first class is to apply the traditional 2-D image denoising method directly to each band of the hyperspectral image, called band-wise denoising. The second class is the joint use of spatial and spectral information for denoising, called multi-band denoising methods. The second class of method can be further divided into the following three categories: transform domain based methods, spatial domain based methods, and deep learning methods.

A list of face hyperspectral image denoising resources collected by [Yongsen Zhao]( https://github.com/seniusen) and [Junjun Jiang](http://homepage.hit.edu.cn/jiangjunjun).

#### Band-wise denoising methods
- **[BM3D]** Image Denoising by Sparse 3-D Transform-Domain Collaborative Filtering, TIP2007, K. Dabov et al.
- **[WNNM]** Weighted nuclear norm minimization with application to image denoising, CVPR2014, S. Gu et al.
- **[EPLL]** From learning models of natural image patches to whole image restoration, ICCV2011, D. Zoran et al.

#### Multi-band based methods

###### Transform domain method
- Wavelet-based hyperspectral image estimation, IGARSS2003, I. Atkinson et al.
- Noise reduction of hyperspectral imagery using hybrid spatial-spectral derivative-domain wavelet shrinkage, TGRS2006, H. Othman et al.

###### Spatial domain methods
By adopting reasonable assumptions or priors, such as Global Correlation along Spetrum, Non-local Self Similarity across space, Total Variation, Non-local (Non-Local), Sparse Representation, Low Rank models, etc., spatial domain based methods can well preserve the spatial and spectral characteristics.

- **[GCS and NSS]** Adaptive Spatial-Spectral Dictionary Learning for Hyperspectral Image Denoising, ICCV2015, Ying Fu et al.

- **[GCS and NSS]** Decomposable nonlocal tensor dictionary learning for multispectral image denoising, CVPR2014, P. Yi et al.
- **[GCS and NSS]** Multispectral images denoising by intrinsic tensor sparsity regularization, CVPR2016, Q. Xie et al.
- **[GCS]** Denoising of hyperspectral images using the parafac model and statistical performance analysis, TGRS2012, X. F. Liu, et al.
- **[TV]** Hyperspectral image denoising employing a spectral–spatial adaptive total variation model, TGRS2012, Q. Yuan et al.
- **[TV]** Hyperspectral image denoising with a combined spatial and spectral hyperspectral total variation model, CJRS2014, G. Chen et al.
- **[NL]** A nonlocal transform-domain filter for volumetric data denoising and reconstruction, TIP2012, M. Maggioni et al.
- **[SR]** Spectral–Spatial Adaptive Sparse Representation for Hyperspectral Image Denoising, TGRS2016, T. Lu et al.
- **[SR]** Noise removal from hyperspectral image with joint spectral-spatial distributed sparse representation, TGRS2016, J. Li et al.
- **[LR]** Denoising and dimensionality reduction using multilinear tools for hyperspectral images, GRSL2008, N. Renard et al.
- **[LR]** Hyperspectral image restoration using low-rank matrix recovery, TGRS2014, H. Zhang et al. [[PDF]]( http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/papers/Hyperspectral%20Image%20Restoration%20Using%20Low-Rank%20Matrix%20Recovery.pdf)[[Code]]( http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/resource/LRMR_HSI%20restoration.zip)
- **[LR]** Hyperspectral Image Denoising via Noise-Adjusted Iterative Low-Rank Matrix Approximation, JStars2015, H. Zhang et al. [[PDF]]( http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/papers/Hyperspectral%20Image%20Denoising%20via%20Noise-Adjusted%20Iterative%20Low-Rank%20Matrix%20Approximation.pdf)[[Code]]( http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/resource/NAILRMA_HSI%20denoising.zip)
- **[LR]** Hyperspectral image denoising via sparse representation and low-rank constraint, TGRS2015, Y. Zhao et al.
- **[LR and GCS]** Hyperspectral Image Denoising Using Local Low-Rank Matrix Recovery and Global Spatial-Spectral Total Variation, JStars2015, H. Zhang et al. [[PDF]]( http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/papers/Hyperspectral%20Image%20Denoising%20Using%20Local%20Low-Rank%20Matrix%20Recovery%20and%20Global%20Spatial-Spectral%20Total%20Variation.pdf)[[Code]]( http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/resource/LLRGTV.rar)
- **[LR]** Hyperspectral image restoration via iteratively regularized weighted Schatten p-norm minimization, TGRS2016, Y. Xie et al.
- **[LR]** Hyperspectral image restoration using low-rank tensor recovery, J-STARS2017, H. Fan et al.
- **[LR]** Hyperspectral Image Denoising with Superpixel Segmentation and Low-Rank Representation, INS2017, F. Fan et al. [[Code]](http://www.escience.cn/system/file?fileId=19)
- **[LR]** Fast hyperspectral image denoising and inpainting based on low-rank and sparse representations, J-STARS2018, L. Zhuang et al. [[PDF]]( http://www.lx.it.pt/~bioucas/files/submitted_ieee_jstars_2017.pdf)[[Code]]( www.lx.it.pt/∼bioucas/code/ Demo_FastHyDe_FastHyIn.rar)
- **[LR and TV]** Spatial-Spectral Total Variation Regularized Low-Rank Tensor Decomposition forv Hyperspectral Image Denoising, TGRS2018, H. Fan et al.
- Noise Reduction in Hyperspectral Imagery: Overview and Application, RS2018, B. Rasti et al. [[PDF]]( https://www.mdpi.com/2072-4292/10/3/482/pdf)[[Code]]( http://openremotesensing.net/wp-content/uploads/2018/03/MatlabCodes.zip)

###### Deep learning methods
- Hyperspectral imagery denoising by deep learning with trainable nonlinearity function, GRSL2017, W. Xie et al.
- Hyperspectral Image Denoising Employing a Spatial-Spectral Deep Residual Convolutional Neural Network, TGRS2018, Q. Yuan et al. [[Code]]( https://github.com/WHUQZhang/HSID-CNN)

#### Databases 
- [CAVE dataset](http://www.cs.columbia.edu/CAVE/databases/multispectral/)
- [AVIRIS](http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)
- [ROSIS](http://lesun.weebly.com/hyperspectral-data-set.html)
- [HYDICE](https://www.erdc.usace.army.mil/Media/Fact-Sheets/Fact-Sheet-Article-View/Article/610433/hypercube/)
- [EO-1 Hyperion Data](https://lta.cr.usgs.gov/ALI)
- [Harvard dataset](http://vision.seas.harvard.edu/hyperspec/explore.html)
- [iCVL dataset](http://icvl.cs.bgu.ac.il/hyperspectral/)
- [NUS datase](https://sites.google.com/site/hyperspectralcolorimaging/dataset/general-scenes)
- [NTIRE18 dataset](http://www.vision.ee.ethz.ch/ntire18/)

#### Image Quality Measurement 
- Peak Signal to Noise Ratio (PSNR)
- Structural SIMilarity index (SSIM)
- Feature SIMilarity index (FSIM)
- Erreur Relative Globale Adimensionnelle de Synthèse (ERGAS)
- Spectral Angle Mapper (SAM)
