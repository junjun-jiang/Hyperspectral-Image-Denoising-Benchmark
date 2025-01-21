# Hyperspectral-Image-Denoising-Benchmark

A list of hyperspectral image denoising resources collected by [Yongsen Zhao]( https://github.com/seniusen) and [Junjun Jiang](http://homepage.hit.edu.cn/jiangjunjun).

#### Band-wise denoising methods
- **[BM3D]** Image Denoising by Sparse 3-D Transform-Domain Collaborative Filtering, TIP2007, K. Dabov et al.
- **[WNNM]** Weighted nuclear norm minimization with application to image denoising, CVPR2014, S. Gu et al.
- **[EPLL]** From learning models of natural image patches to whole image restoration, ICCV2011, D. Zoran et al.

#### Multi-band based methods

###### **[---Transform domain method---]**
- Wavelet-based hyperspectral image estimation, IGARSS2003, I. Atkinson et al.
- Hyperspectral image denoising using 3D wavelets, IGARSS2013, B. Rasti et al.
- A nonlocal transform-domain filter for volumetric data denoising and reconstruction, TIP2012, M. Maggioni et al.
- Hyperspectral Image Denoising Using First Order Spectral Roughness Penalty in Wavelet Domain, JStars2014, B. Rasti et al.

###### **[---Spatial domain methods---]**
By adopting reasonable assumptions or priors, such as Global Correlation along Spetrum, Non-local Self Similarity (NSS) across space, Total Variation (TV), Non-local (Non-Local), Sparse Representation (SR), Low Rank (LR) models, Tensor models, etc., spatial domain based methods can well preserve the spatial and spectral characteristics.

- **[GCS and NSS]** Adaptive Spatial-Spectral Dictionary Learning for Hyperspectral Image Denoising, ICCV2015, Ying Fu et al.
- **[GCS and NSS and Tensor]** Decomposable nonlocal tensor dictionary learning for multispectral image denoising, CVPR2014, P. Yi et al. [[Code]](http://gr.xjtu.edu.cn/c/document_library/get_file?folderId=1766524&name=DLFE-38410.zip)
- **[GCS and NSS]** Multispectral images denoising by intrinsic tensor sparsity regularization, CVPR2016, Q. Xie et al. [[Code]](http://gr.xjtu.edu.cn/c/document_library/get_file?folderId=2343711&name=DLFE-86323.zip)
- **[GCS]** Denoising of hyperspectral images using the parafac model and statistical performance analysis, TGRS2012, X. F. Liu, et al.
- **[TV]** Hyperspectral image denoising with cubic total variation model, ISPRS2012, H. Zhang et al.
- **[TV]** Hyperspectral image denoising with a combined spatial and spectral hyperspectral total variation model, CJRS2014, G. Chen et al.
- **[SR]** Spectral–Spatial Adaptive Sparse Representation for Hyperspectral Image Denoising, TGRS2016, T. Lu et al.
- **[SR]** Noise removal from hyperspectral image with joint spectral-spatial distributed sparse representation, TGRS2016, J. Li et al.
- **[LR]** Denoising and dimensionality reduction using multilinear tools for hyperspectral images, GRSL2008, N. Renard et al.
- **[LR]** Hyperspectral image restoration using low-rank matrix recovery, TGRS2014, H. Zhang et al. [[PDF]](http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/papers/Hyperspectral%20Image%20Restoration%20Using%20Low-Rank%20Matrix%20Recovery.pdf)[[Code]](http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/resource/LRMR_HSI%20restoration.zip)
- **[LR]** Hyperspectral Image Denoising via Noise-Adjusted Iterative Low-Rank Matrix Approximation, JStars2015, H. Zhang et al. [[PDF]](http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/papers/Hyperspectral%20Image%20Denoising%20via%20Noise-Adjusted%20Iterative%20Low-Rank%20Matrix%20Approximation.pdf)[[Code]](http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/resource/NAILRMA_HSI%20denoising.zip)
- **[LR]** Hyperspectral image denoising via sparse representation and low-rank constraint, TGRS2015, Y. Zhao et al. [[Code]](http://pan.baidu.com/s/1sjNTijj)
- **[LR and GCS]** Hyperspectral Image Denoising Using Local Low-Rank Matrix Recovery and Global Spatial-Spectral Total Variation, JStars2015, H. Zhang et al. [[PDF]](http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/papers/Hyperspectral%20Image%20Denoising%20Using%20Local%20Low-Rank%20Matrix%20Recovery%20and%20Global%20Spatial-Spectral%20Total%20Variation.pdf)[[Code]](http://www.lmars.whu.edu.cn/prof_web/zhanghongyan/resource/LLRGTV.rar)
- **[[LR  and Tensor]]** Hyper-Laplacian Regularized Unidirectional Low-rank Tensor Recovery for Multispectral Image Denoising, CVPR2017, Y. Chang et al. [[Code]](http://www.escience.cn/system/file?fileId=91483)
- **[LR]** Hyperspectral image restoration via iteratively regularized weighted Schatten p-norm minimization, TGRS2016, Y. Xie et al.
- **[LR  and Tensor]** Hyperspectral image restoration using low-rank tensor recovery, J-STARS2017, H. Fan et al.
- **[LR]** Hyperspectral Image Restoration Using Low-Rank Representation on Spectral Difference Image, J-STARS2017, L. Sun et al. [[Code]](http://www.escience.cn/system/file?fileId=90518)
- **[LR]** Hyperspectral Image Denoising with Superpixel Segmentation and Low-Rank Representation, INS2017, F. Fan et al. [[Code]](http://www.escience.cn/system/file?fileId=19)
- **[LR]** Fast hyperspectral image denoising and inpainting based on low-rank and sparse representations, J-STARS2018, L. Zhuang et al. [[PDF]](http://www.lx.it.pt/~bioucas/files/submitted_ieee_jstars_2017.pdf)[[Code]](www.lx.it.pt/∼bioucas/code/Demo_FastHyDe_FastHyIn.rar)
- **[LR and TV]** A Novel Anisotropic Total Variation Regularized Low Rank Method for Hyperspectral Image Mixed Denoising, ISPRS International Journal of Geo-Information, 2018, L. Sun et al. [[Code]](http://www.escience.cn/system/file?fileId=102178)
- **[LR]** Fast Superpixel based Subspace Low Rank Learning Method for Hyperspectral Denoising. IEEE Access,2018, L. Sun et al. [[Code]](http://www.escience.cn/system/file?fileId=97575)
- **[LR and TV  and Tensor]** Spatial-Spectral Total Variation Regularized Low-Rank Tensor Decomposition forv Hyperspectral Image Denoising, TGRS2018, H. Fan et al.
- **[LR]** Hyperspectral Image Denoising via Minimizing the Partial Sum of Singular Values and Superpixel Segmentation, Neurocomputing2018, Y. Liu et al. [[PDF]](https://ac.els-cdn.com/S0925231218313705/1-s2.0-S0925231218313705-main.pdf?_tid=b9341448-ec31-43ee-9984-5b4653353341&acdnat=1543139827_163d7541ba7ab463ee3cc9dcfdcb09f4)
- **[LR]** Non-local Meets Global: An Integrated Paradigm for Hyperspectral Denoising, arXiv2018, W. He et al. [[Web]](https://sites.google.com/site/rshewei/home)[[Pdf]](https://arxiv.org/pdf/1809.03298.pdf)
- **[Tensor]** Color Image and Multispectral Image Denoising Using Block Diagonal Representation, arXiv2019, Zhaoming Kong et al. [[PDF]](https://arxiv.org/pdf/1902.03954.pdf)[[Code]](http://openremotesensing.net/wp-content/uploads/2018/03/MatlabCodes.zip)
- Nonlocal Tensor-Ring Decomposition for Hyperspectral Image Denoising, IEEE TGRS 2019, Y. Chen et al.
- Intracluster Structured Low-Rank Matrix Analysis Method for Hyperspectral Denoising, IEEE TGRS, Xiangtao Zheng et al.[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8527652)
- Hyperspectral Image Denoising by Fusing the Selected Related Bands, IEEE TGRS, Xiangtao Zheng et al.[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8527652)
- Nonlocal Low-Rank Regularized Tensor Decomposition for Hyperspectral Image Denoising, IEEE TGRS, Jize Xue et al.[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8657368)
- A Novel Rank Approximation Method for Mixture Noise Removal of Hyperspectral Images, IEEE TGRS, Hailiang Ye et al.[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8632962)
- A Low-Rank Tensor Dictionary Learning Method for Hyperspectral Image Denoising, IEEE TSP 2020, X. Gao et al.
- Double Low-Rank Matrix Decomposition for Hyperspectral Image Denoising and Destriping, IEEE TGRS 2021, H. Zhang et al.
- Hyperspectral Image Denoising Based on Global and Nonlocal Low-Rank Factorizations, IEEE TGRS 2021, L. Zhuang et al.
- Deep spatio-spectral Bayesian posterior for hyperspectral image non-i.i.d. noise removal, ISPRS P&RS 2020, Q. Zhang et al.

#### Deep learning methods
- Hyperspectral imagery denoising by deep learning with trainable nonlinearity function, GRSL2017, W. Xie et al.
- Hyperspectral Image Denoising Employing a Spatial-Spectral Deep Residual Convolutional Neural Network, TGRS2018, Q. Yuan et al. [[Code]](https://github.com/WHUQZhang/HSID-CNN)
- HSI-DeNet: Hyperspectral Image Restoration via Convolutional Neural Network, TGRS2019, Yi Chang et al. [[Web]](http://www.escience.cn/people/changyi/index.html) [[Pdf]](http://www.escience.cn/system/download/100951)
- Deep Hyperspectral Prior: Denoising, Inpainting, Super-Resolution, arxiv2019, Oleksii Sidorov et al. [[Code]](https://github.com/acecreamu/deep-hs-prior) [[Pdf]](https://arxiv.org/pdf/1902.00301)
- Hybrid Noise Removal in Hyperspectral Imagery With a Spatial-Spectral Gradient Network, IEEE TGRS 2019, Qiang Zhang et al. [[Code]](https://github.com/WHUQZhang/SSGN) [[Pdf]](https://arxiv.org/pdf/1810.00495)
- Deep Spatial-spectral Representation Learning for Hyperspectral Image Denoising, IEEE TCI 2019, Weisheng Dong et al. [[Pdf]](https://ieeexplore.ieee.org/document/8734833)[[Code]](http://see.xidian.edu.cn/faculty/wsdong/Code_release/DENOISE_NG_ST.tar.gz)
- Hyperspectral image denoising via matrix factorization and deep prior regularization, IEEE TIP 2019, B. Li. [[Pdf]](https://ieeexplore.ieee.org/abstract/document/8767025)
- A 3-D Atrous Convolution Neural Network for Hyperspectral Image Denoising, IEEE TGRS 2019， Wei Liu et al.
- Hyperspectral Image Denoising Using SURE-Based Unsupervised Convolutional Neural Networks, IEEE TGRS 2020, Han V. Nguyen et al.
- A Single Model CNN for Hyperspectral Image Denoising, IEEE TGRS 2020, Alessandro Maffei et al.
- Hyperspectral image restoration via CNN denoiser prior regularized low-rank tensor recovery, CVIU 2020, H. Zeng et al.
- Hyperspectral Image Denoising via Clustering-Based Latent Variable in Variational Bayesian Framework, IEEE TGRS 2021, Peyman Azimpour et al.
- Uncertainty Quantification of Hyperspectral Image Denoising Frameworks Based on Sliding-Window Low-Rank Matrix Approximation, IEEE TGRS 2021, J. Song et al.
- Deep Spatial-Spectral Global Reasoning Network for Hyperspectral Image Denoising, IEEE TGRS 2021, X. Cao et al. [[Code]](https://github.com/xiangyongcao/GRN)
- Hyperspectral Image Denoising Using a 3-D Attention Denoising Network, IEEE TGRS 2021, Q. Shi et al.
- 3-D Quasi-Recurrent Neural Network for Hyperspectral Image Denoising, IEEE TNNLS 2021, K. Wei et al.
- SSUMamba: Spatial–Spectral Selective State Space Model for Hyperspectral Image Denoising, IEEE TGRS 2024, Guanyiman Fu et al. [[Code]](https://github.com/lronkitty/SSUMamba)
- Unmixing Diffusion for Self-Supervised Hyperspectral Image Denoising, CVPR 2024, Haijin Zeng et al.
- Flex-DLD: Deep Low-Rank Decomposition Model With Flexible Priors for Hyperspectral Image Denoising and Restoration, TIP 2024, Yurong Chen et al.
- Hyperspectral Image Denoising via Spatial–Spectral Recurrent Transformer, IEEE TGRS 2024, Guanyiman Fu et al. [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10463066)[[Code]](https://github.com/lronkitty/SSRT)
- HIR-Diff: Unsupervised Hyperspectral Image Restoration Via Improved Diffusion Models, CVPR 2024, Li Pang et al. [[PDF]](https://openaccess.thecvf.com/content/CVPR2024/papers/Pang_HIR-Diff_Unsupervised_Hyperspectral_Image_Restoration_Via_Improved_Diffusion_Models_CVPR_2024_paper.pdf)[[Code]](https://github.com/LiPang/HIRDiff)
- Latent Diffusion Enhanced Rectangle Transformer for Hyperspectral Image Restoration, IEEE TPAMI 2025, Miaoyu Li et al. [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10713101)

#### Other methods for Non-i.i.d. Noise
- Noise reduction of hyperspectral imagery using hybrid spatial-spectral derivative-domain wavelet shrinkage, TGRS2006, H. Othman et al.
- Hyperspectral image denoising employing a spectral–spatial adaptive total variation model, TGRS2012, Q. Yuan et al.
- 3-D nonlocal means filter with noise estimation for hyperspectral imagery denoising, IGRSS2013, Y. Qian et al.
- Hyperspectral imagery restoration using nonlocal spectral-spatial structured sparse representation with noise estimation, JStars2013, Y. Qian et al.
- Spectral–spatial kernel regularized for hyperspectral image denoising, IEE TGRS2015, Y. Yuan et al.
- Denoising Hyperspectral Image with Non-i.i.d. Noise Structure, IEEE TCYB2017, Y. Chen et al. [[PDF]](http://arxiv.org/pdf/1702.00098v1.pdf)[[Code]](http://gr.xjtu.edu.cn/c/document_library/get_file?folderId=2406028&name=DLFE-88042.zip)
- Hyperspectral Image Denoising by Fusing the Selected Related Bandsx, IEEE TGRS2018, X. Zheng et al.
- A Novel Rank Approximation Method for Mixture Noise Removal of Hyperspectral Images, IEEE TGRS2018, X. Zheng et al.

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

![visitors](https://visitor-badge.glitch.me/badge?page_id=junjun-jiang/Hyperspectral-Image-Denoising-Benchmark) Since 2022/5/7 
