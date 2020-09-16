# Image-Quality-Assessment-Benchmark
A list of state-of-the-art image quality assessment algorithms and databases collected by [Wei Zhou](http://home.ustc.edu.cn/~weichou). If you find that important resources are not included, please feel free to contact me.

According to the availability of the whole or partial original undistorted image (often called reference image), image quality assessment (IQA) algorithms are typically divided into three categories as follows: 1) full-reference IQA (FR-IQA), 2) reduced-reference IQA (RR-IQA), and 3) no-reference IQA (NR-IQA).

**Traditional FR-IQA**
* Image Quality Assessment: from Error Visibility to Structural Similarity (SSIM), IEEE TIP, 2004, Wang Z et al. [[PDF]](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf) [[Code]](https://ece.uwaterloo.ca/~z70wang/research/ssim/)

* Multi-scale Structural Similarity for Image Quality Assessment (MS-SSIM), IEEE Asilomar Conference on Signals, Systems and Computers, 2003,  Wang Z et al. [[PDF]](https://ece.uwaterloo.ca/~z70wang/publications/msssim.pdf) [[Code]](https://ece.uwaterloo.ca/~z70wang/research/ssim/)

* FSIM: A Feature Similarity Index for Image Quality Assessment (FSIM), IEEE TIP, 2011,  Zhang L et al. [[PDF]](http://sse.tongji.edu.cn/linzhang/IQA/FSIM/Files/Fsim%20a%20feature%20similarity%20index%20for%20image%20quality%20assessment.pdf) [[Code]](http://sse.tongji.edu.cn/linzhang/IQA/FSIM/FSIM.htm)

* Information Content Weighting for Perceptual Image Quality Assessment (IW-SSIM), IEEE TIP, 2010,  Wang Z et al. [[PDF]](https://ece.uwaterloo.ca/~z70wang/publications/IWSSIM.pdf) [[Code]](https://ece.uwaterloo.ca/~z70wang/research/iwssim/)

* An Information Fidelity Criterion for Image Quality Assessment Using Natural Scene Statistics (IFC), IEEE TIP, 2005, Sheikh H R et al. [[PDF]](https://live.ece.utexas.edu/publications/2004/hrs_ieeetip_2004_infofidel.pdf) [[Code]](http://live.ece.utexas.edu/research/quality/ifcvec_release.zip)

* Image Quality Assessment Based on A Degradation Model (NQM), IEEE TIP, 2000, Damera-Venkata N et al. [[PDF]](https://live.ece.utexas.edu/publications.php) [[Code]](http://users.ece.utexas.edu/~bevans/papers/2000/imageQuality/index.html)

* VSNR: A Wavelet-Based Visual Signal-to-Noise Ratio for Natural Images (VSNR), IEEE TIP, 2007, Chandler D M et al. [[PDF]](https://www.researchgate.net/profile/Damon_Chandler/publication/3328654_VSNR_A_wavelet-based_Visual_Signal-to-Noise_Ratio_for_natural_images/links/56ea36d408aec8bc078178f9.pdf) [[Code]](https://github.com/sattarab/image-quality-tools/tree/master/metrix_mux/metrix/vsnr)

**Traditional RR-IQA**
* Reduced-reference Image Quality Assessment in Free-energy Principle and Sparse Representation (FSI), IEEE TMM, 2017, Liu Y et al. [[PDF]](https://kegu.netlify.com/PDF/Reduced-reference%20image%20quality%20assessment%20in%20free-energy%20principle%20and%20sparse%20representation.pdf) [[Code]](http://multimedia.sjtu.edu.cn/Assets/userfiles/sys_ea59f56d-4d4a-4775-8e55-a72700ff96de/files/FSI_pub.rar)

**Traditional NR-IQA**

* No-reference Image Quality Assessment in the Spatial Domain (BRISQUE), IEEE TIP, 2012, Mittal A et al. [[PDF]](https://live.ece.utexas.edu/publications/2012/TIP%20BRISQUE.pdf) [[Code]](https://live.ece.utexas.edu/research/Quality/index_algorithms.htm)

* A Feature-Enriched Completely Blind Image Quality Evaluator (IL-NIQE), IEEE TIP, 2015, Zhang L et al. [[PDF]](http://www4.comp.polyu.edu.hk/~cslzhang/paper/IL-NIQE.pdf) [[Code]](https://live.ece.utexas.edu/research/Quality/index_algorithms.htm)

* Perceptual Quality Prediction on Authentically Distorted Images Using A Bag of Features Approach (FRIQUEE), Journal of Vision, 2017, Ghadiyaram D et al. [[PDF]](https://live.ece.utexas.edu/publications/2016/friquee_jov.pdf) [[Code]](https://live.ece.utexas.edu/research/Quality/index_algorithms.htm)

* A Novel Blind Image Quality Assessment Method Based on Refined Natural Scene Statistics (NBIQA), IEEE ICIP, 2019, Ou F Z et al. [[PDF]](https://ieeexplore.ieee.org/document/8803047) [[Code]](https://github.com/GZHU-Image-Lab/NBIQA)

* Blind Quality Assessment of Compressed Images via Pseudo Structural Similarity (PSS), IEEE ICME, 2016, Min X et al. [[PDF]](https://kegu.netlify.com/PDF/Blind%20quality%20assessment%20of%20compressed%20images%20via%20pseudo%20structural%20similarity.pdf) [[Code]](https://drive.google.com/file/d/0BzIV-pviJ97tUnVoVFlpS1VRWFk/view)

* Blind Image Quality Estimation via Distortion Aggravation (BMPRI), IEEE TBC, 2018, Min X et al. [[PDF]](https://kegu.netlify.com/PDF/Blind%20image%20quality%20estimation%20via%20distortion%20aggravation.pdf) [[Code]](https://drive.google.com/file/d/1C_NxTLvnBOJDGhqqtixCkra0LIMP6loF/view)

**Deep Learning Based Approaches**

**(1) FR-IQA**
*  Deep Neural Networks for No-Reference and Full-Reference Image Quality Assessment, IEEE TIP, 2017, Bosse S et al. [[PDF]](https://arxiv.org/abs/1612.01697) [[Code]](https://github.com/Bobholamovic/CNN-FRIQA)

* Deep Learning of Human Visual Sensitivity in Image Quality Assessment Framework (DeepQA), IEEE CVPR, 2017, Kim J et al. [[PDF]](https://zpascal.net/cvpr2017/Kim_Deep_Learning_of_CVPR_2017_paper.pdf) [[Code]](https://github.com/jongyookim/IQA_DeepQA_FR_release)

* PieAPP: Perceptual Image-Error Assessment through Pairwise Preference (PieAPP), IEEE CVPR, 2018, Prashnani E et al. [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Prashnani_PieAPP_Perceptual_Image-Error_CVPR_2018_paper.pdf) [[Code]](https://github.com/prashnani/PerceptualImageError) [[Project]](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/)

**(2) NR-IQA**
* Convolutional Neural Networks for No-Reference Image Quality Assessment (CNNIQA), IEEE CVPR, 2014, Kang L et al. [[PDF]](https://www.zpascal.net/cvpr2014/Kang_Convolutional_Neural_Networks_2014_CVPR_paper.pdf) [[Code]](https://github.com/lidq92/CNNIQA)

* Visual Importance and Distortion Guided Deep Image Quality Assessment Framework (VIDGIQA), IEEE TMM, 2017, Guan J et al. [[PDF]](https://ieeexplore.ieee.org/document/7924311) [[Code]](https://github.com/GUAN3737/VIDGIQA)

* A Deep Neural Network for Image Quality Assessment (gbIQA), IEEE ICIP, 2016, Bosse S et al. [[PDF]](http://iphome.hhi.de/samek/pdf/BosICIP16.pdf) [[Code]](https://github.com/441711335/gbIQA)

* SGDNet: An End-to-End Saliency-Guided Deep Neural Network for No-Reference Image Quality Assessment (SGDNet), ACM MM, 2019, Yang S et al. [[PDF]](https://drive.google.com/file/d/1HWv1rqphZ4Cu7OzVI2s93xTe4u_a-lXU/view) [[Code]](https://github.com/ysyscool/SGDNet)

* Fully Deep Blind Image Quality Predictor (BIECON), IEEE JSTSP, 2016, Kim J et al. [[PDF]](https://ieeexplore.ieee.org/document/7782419) [[Code]](https://github.com/jongyookim/IQA_BIECON_release)

* Saliency-Based Deep Convolutional Neural Network for No-Reference Image Quality Assessment (Saliency-CNN), Multimedia Tools and Applications, 2018, Jia S et al. [[PDF]](https://link.springer.com/article/10.1007/s11042-017-5070-6) [[Code]](https://github.com/SenJia/Saliency-CNN-Image-Quality-Assessment)

* Hallucinated-IQA: No-Reference Image Quality Assessment via Adversarial Learning (HIQA), IEEE CVPR, 2018, Lin K Y et al. [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lin_Hallucinated-IQA_No-Reference_Image_CVPR_2018_paper.pdf) [[Code]](https://github.com/kwanyeelin/HIQA)

* Simultaneous Estimation of Image Quality and Distortion via Multi-Task Convolutional Neural Networks, IEEE ICIP, 2015, Kang L et al. [[PDF]](https://ieeexplore.ieee.org/document/7351311) [[Code]](https://github.com/lidq92/CNNIQAplusplus)

* Blind Image Quality Assessment Using A Deep Bilinear Convolutional Neural Network (DBCNN), IEEE TCSVT, 2018, Zhang W et al. [[PDF]](https://ieeexplore.ieee.org/document/8576582) [[Code]](https://github.com/zwx8981/BIQA_Project)

* End-to-End Blind Image Quality Assessment Using Deep Neural Networks (MEON), IEEE TIP, 2017, Ma K et al. [[PDF]](https://ece.uwaterloo.ca/~zduanmu/tip2018biqa/) [[Code]](https://ece.uwaterloo.ca/~zduanmu/tip2018biqa/)

* dipIQ: Blind Image Quality Assessment by Learning-to-Rank Discriminable Image Pairs (dipIQ), IEEE TIP, 2017, Ma K et al. [[PDF]](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_dipIQ.pdf) [[Code]](https://ece.uwaterloo.ca/~k29ma/codes/dipIQ.rar)

**Databases**

Synthetic distortion
* [[LIVE Database]](https://live.ece.utexas.edu/research/Quality/subjective.htm)
* [[CSIQ Database]](http://vision.eng.shizuoka.ac.jp/mod/page/view.php?id=23)
* [[TID2008 Database]](http://www.ponomarenko.info/tid2008.htm)
* [[TID2013 Database]](http://www.ponomarenko.info/tid2013.htm)

Authentic distortion
* [[LIVE Challenge Database]](https://live.ece.utexas.edu/research/ChallengeDB/index.html)
* [[KonIQ-10k Image Database]](http://database.mmsp-kn.de/koniq-10k-database.html)


