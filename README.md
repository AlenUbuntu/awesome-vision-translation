# Awesome-Vision-Translation 
A collection of awesome vision translation resources

## Contributing

If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/AlenUbuntu/awesome-vision-translation/pulls)

Feedback and contributions are welcome!

## Table of Contents
- [Surveys and Tutorials](#Surveys-and-Tutorials)
- [Style Transfer](#Style-Transfer)
- [Image2Image Translation](#Image2Image-Translation)

## Surveys and Tutorials

[Unpaired Image-to-Image Translation.](http://efrosgans.eecs.berkeley.edu/CVPR18_slides/CycleGAN.pptx) CVPR Tutorial on GANs (2018)

[On Image-to-Image Translation.](https://people.csail.mit.edu/junyanz/talks/image_translation.pptx) Stanford, MIT, Facebook, CUHK, SNU (2017)

[Neural Style Transfer: A Review](https://arxiv.org/abs/1705.04058)  Yongcheng Jing, Yezhou Yang, Zunlei Feng, Jingwen Ye, Yizhou Yu, and Mingli Song

## Style Transfer
### Visual Texture Modeling
---
#### Parametric Texture Modeling with Summary Statistics
---
**Demystifying neural style transfer**<br>
*Y. Li*, *N. Wang*, *J. Liu*, *X. Hou*<br>
IJCAI, 2017, [[pdf](https://arxiv.org/abs/1701.01036)]

**Incorporating long-range consistency in cnn-based texture generation**<br>
*G. Berger*, *R. Memisevic*<br>
ICLR 2017, [[pdf](https://arxiv.org/abs/1606.01286)]

**Texture synthesis using convolutional neural networks**<br>
*L. A. Gatys*, *A. S. Ecker*, *M. Bethge*<br>
NIPS 2015, [[pdf](https://arxiv.org/abs/1505.07376)]

**A parametric texture model based on joint statistics of complex wavelet coefficients**<br>
*J. Portilla*, *E. P. Simoncelli*<br>
International journal of computer vision, 2000 [[pdf](https://www.cns.nyu.edu/pub/eero/portilla99-reprint.pdf)]

**Pyramid-based texture analysis/synthesis** <br>
*D. J. Heeger*,  *J. R. Bergen*<br>
the 22nd annual conference on Computer graphics and interactive techniques, 1995 [[pdf](https://www.cns.nyu.edu/heegerlab/content/publications/Heeger-siggraph95.pdf)]

**Visual pattern discrimination** <br>
*B. Julesz* <br>
IRE transactions on Information Theory, 1962 [[pdf](https://ieeexplore.ieee.org/document/1057698)]

---
#### Non-Parametric Texture Modeling with MRFs.
---
**Fast texture synthesis using treestructured vector quantization**<br>
*L.-Y. Wei*, *M. Levoy*<br>
the 27th annual conference on Computer graphics and interactive techniques, 2000 [[pdf](https://graphics.stanford.edu/papers/texture-synthesis-sig00/texture.pdf)]

**Texture synthesis by nonparametric sampling**<br>
*A. A. Efros*, *T. K. Leung*<br>
ICCV, 1999, [[pdf](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/papers/efros-iccv99.pdf)]
<br>
<br>

### Image Reconstruction
---
#### Image-Optimisation-Based Online Image Reconstruction (IOB-IR)
---
**Visualizing deep convolutional neural networks using natural pre-images**<br>
IJCV, 2016 [[pdf](https://arxiv.org/pdf/1512.02017.pdf)]

**Understanding deep image representations by inverting them**<br>
*A. Mahendran*, *A. Vedaldi*<br>
CVPR, 2015, [[pdf](https://arxiv.org/abs/1412.0035)]

---
#### Model-Optimisation-Based Offline Image Reconstruction (MOB-IR)
---
**Inverting visual representations with convolutional networks**<br>
*A. Dosovitskiy*, *T. Brox*<br>
CVPR, 2016, [[pdf](https://arxiv.org/pdf/1506.02753.pdf)]

**Generating images with perceptual similarity metrics based on deep networks**<br>
*Alexey Dosovitskiy*, *Thomas Brox*<br>
NIPS, 2016, [[pdf](https://arxiv.org/pdf/1602.02644.pdf)]
<br>
<br>

### A TAXONOMY OF NEURAL STYLE TRANSFER ALGORITHMS
---
#### Image-Optimization-Based Online Neural Methods
---

**Laplacian-steered neural style transfer**<br>
*S. Li*, *X. Xu*, *L. Nie*, *T.-S. Chua*<br>
ACM MM, 2017, [[pdf](https://arxiv.org/abs/1707.01253)]

**Stable and controllable neural texture synthesis and style transfer using histogram losses**<br>
*E. Risser*, *P. Wilmot*, *C. Barnes*<br>
Arxiv, 2017, [[pdf](https://arxiv.org/abs/1701.08893)]

**Demystifying neural style transfer**<br>
*Y. Li*, *N. Wang*, *J. Liu*, *X. Hou*<br>
IJCAI, 2017, [[pdf](https://arxiv.org/abs/1701.01036)]

**Image style transfer using convolutional neural networks**<br>
*L. A. Gatys*, *A. S. Ecker*, *M. Bethge*<br>
CVPR, 2016, [[pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)]

**Combining markov random fields and convolutional neural networks for image synthesis**<br>
*C. Li*, *M. Wand*<br>
CVPR, 2016, [[pdf](https://arxiv.org/abs/1601.04589)]

**A neural algorithm of artistic style**<br>
*L. A. Gatys*, *A. S. Ecker*, *M. Bethge*<br>
Arxiv, 2015, [[pdf](https://arxiv.org/pdf/1508.06576.pdf)]
<br>
<br>

---
#### Per-Style-Per-Model Offline Neural Methods
---
**Improved texture networks: Maximizing quality and diversity in feed-forward stylization and texture synthesis**<br>
*D. Ulyanov*, *A. Vedaldi*, *A. Vedaldi*<br>
CVPR, 2017, [[pdf](https://arxiv.org/abs/1701.02096)]

**Perceptual losses for realtime style transfer and super-resolution**<br>
*J. Johnson*, *A. Alahi*, *L. Fei-Fei*<br>
ECCV, 2016, [[pdf](https://arxiv.org/abs/1603.08155)]

**Texture networks: Feed-forward synthesis of textures and stylized images**<br>
*D. Ulyanov*, *V. Lebedev*, *A. Vedaldi*, *V. Lempitsky*<br>
ICML, 2016, [[pdf](https://arxiv.org/abs/1603.03417)]

**Instance Normalization: The Missing Ingredient for Fast Stylization**<br>
*Dmitry Ulyanov*, *Andrea Vedaldi*, *Victor Lempitsky*<br>
Arxiv, 2016, [[pdf](https://arxiv.org/abs/1607.08022)]

**Precomputed real-time texture synthesis with markovian generative adversarial networks**<br>
*C. Li*, *M. Wand*<br>
ECCV, 2016 [[pdf](https://arxiv.org/abs/1604.04382)]
<br>
<br>

---
#### Multiple-Style-Per-Model Offline Neural Methods
---
**A learned representation for artistic style**<br>
*V. Dumoulin*, *J. Shlens*, *M. Kudlur*<br>
ICLR, 2017, [[pdf](https://arxiv.org/abs/1610.07629)]

**Stylebank: An explicit representation for neural image style transfer**<br>
*D. Chen*, *L. Yuan*, *J. Liao*, *N. Yu*, *G. Hua*<br>
CVPR, 2017, [[pdf](https://arxiv.org/abs/1703.09210)]

**Diversified texture synthesis with feed-forward networks**<br>
*Y. Li*, *F. Chen*,  *J. Yang*, *Z. Wang*, *X. Lu*, *M.-H. Yang*<br>
CVPR, 2017, [[pdf](https://arxiv.org/abs/1703.01664)]

**Multi-style generative network for realtime transfer**<br>
*H. Zhang*, *K. Dana*<br>
Arxiv, 2017, [[pdf](https://arxiv.org/abs/1703.06953)]
<br>
<br>

---
#### Arbitrary-Style-Per-Model Offline Neural Methods
---
<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Avatar-Net: Multi-scale Zero-shot Style Transfer by Feature Decoration**<br>
*Lu Sheng*, *Ziyi Lin*, *Jing Shao*, *Xiaogang Wang*<br>
CVPR, 2018, [[pdf](https://arxiv.org/pdf/1805.03857.pdf)]

<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Universal style transfer via feature transforms**<br>
*Y. Li*, *C. Fang*, *J. Yang*, *Z. Wang*, *X. Lu*, *M.-H. Yang*<br>
NIPS, 2017, [[pdf](https://arxiv.org/abs/1705.08086)]

<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Arbitrary style transfer in real-time with adaptive instance normalization**<br>
*X. Huang*, *S. Belongie*<br>
ICCV, 2017, [[pdf](https://arxiv.org/abs/1703.06868)]

**Exploring the structure of a real-time, arbitrary neural artistic stylization network**<br>
*G. Ghiasi*, *H. Lee*, *M. Kudlur*, *V. Dumoulin*, *J. Shlens*<br>
BMVC, 2017, [[pdf](https://arxiv.org/abs/1705.06830)]

**Fast patch-based style transfer of arbitrary style**<br>
*T. Q. Chen*, *M. Schmidt*<br>
NIPS Workshop, 2016, [[pdf](https://arxiv.org/abs/1612.04337)]
<br>
<br>

### Applications
---
#### Semantic Style Transfer
---

**The contextual loss for image transformation with non-aligned data**<br>
*R. Mechrez*, *I. Talmi*, *L. Zelnik-Manor*<br>
ECCV, 2018, [[pdf](https://arxiv.org/abs/1803.02077)]

**Decoder network over lightweight reconstructed feature for fast semantic
style transfer**<br>
*M. Lu*, *H. Zhao*, *A. Yao*, *F. Xu*, *Y. Chen*, *L. Zhang*<br>
ICCV, 2017, [[pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Lu_Decoder_Network_Over_ICCV_2017_paper.pdf)]


**Semantic style transfer and turning two-bit doodles into fine artworks**<br>
*A. J. Champandard*<br>
Arxiv, 2016, [[pdf](https://arxiv.org/abs/1603.01768)]

**Towards deep style transfer: A content-aware perspective**<br>
*Y.-L. Chen*, *C.-T. Hsu*<br>]
BMVC, 2016, [[pdf](https://pdfs.semanticscholar.org/6969/2465952055d6d5702d30f62914c913445fd1.pdf?_ga=2.23953535.450081699.1582152439-637817447.1569507720)]
<br>
<br>

---
#### Doodle Style Transfer
---
**Semantic style transfer and turning two-bit doodles into fine artworks**<br>
*A. J. Champandard*<br>
Arxiv, 2016, [[pdf](https://arxiv.org/abs/1603.01768)]
<br>
<br>

---
#### Video Style Transfer
---
<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Learning Linear Transformations for Fast Image and Video Style Transfer**<br>
*Xueting Li*, *Sifei Liu*, *Jan Kautz*, *Ming-Hsuan Yang*<br>
CVPR, 2019, [[pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Learning_Linear_Transformations_for_Fast_Image_and_Video_Style_Transfer_CVPR_2019_paper.pdf)]

**Artistic style transfer for videos and spherical images**<br>
*Manuel Ruder*, *Alexey Dosovitskiy*, *Thomas Brox*<br>
IJCV, 2018, [[pdf](https://arxiv.org/abs/1708.04538)]

**Real-time neural style transfer for videos**<br>
*H. Huang*, *H. Wang*, *W. Luo*, *L. Ma*, *W. Jiang*, *X. Zhu*, *Z. Li*, *W. Liu*<br>
CVPR, 2017, [[pdf](http://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_Real-Time_Neural_Style_CVPR_2017_paper.pdf)]

**Characterizing and improving stability in neural style transfer**<br>
*A. Gupta*, *J. Johnson*, *A. Alahi*, *L. Fei-Fei*<br>
ICCV, 2017, [[pdf](https://arxiv.org/abs/1705.02092)]

**Coherent online video style transfer**<br>
*D. Chen*, *J. Liao*, *L. Yuan*, *N. Yu*, *G. Hua*<br>
ICCV, 2017, [[pdf](https://arxiv.org/abs/1703.09211)]

**Artistic style transfer for videos**<br>
*M. Ruder*, *A. Dosovitskiy*, *T. Brox*<br>
GCPR, 2016, [[pdf](https://arxiv.org/abs/1604.08610)]
<br>
<br>

---
#### Character Style Transfer
---
<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Multi-content gan for few-shot font style transfer**<br>
*S. Azadi*, *M. Fisher*, *V. Kim*, *Z. Wang*, *E. Shechtman*, *T. Darrell*<br>
CVPR, 2018, [[pdf](https://arxiv.org/abs/1712.00516)]

**Neural font style transfer**<br>
*G. Atarsaikhan*, *B. K. Iwana*, *A. Narusawa*, *K. Yanai*, *S. Uchida*<br>
the IAPR International Conference on Document Analysis and Recognition, 2017, [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8270274)]

<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Awesome typography: Statistics-based text effects transfer**<br>
*S. Yang*, *J. Liu*, *Z. Lian*, *Z. Guo*<br>
CVPR, 2017, [[pdf](https://www.zpascal.net/cvpr2017/Yang_Awesome_Typography_Statistics-Based_CVPR_2017_paper.pdf)]
<br>
<br>

---
#### Photorealistic Style Transfer
---
<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Learning Linear Transformations for Fast Image and Video Style Transfer**<br>
*Xueting Li*, *Sifei Liu*, *Jan Kautz*, *Ming-Hsuan Yang*<br>
CVPR, 2019, [[pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Learning_Linear_Transformations_for_Fast_Image_and_Video_Style_Transfer_CVPR_2019_paper.pdf)]

<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **PairedCycleGAN: Asymmetric Style Transfer for Applying and Removing Makeup**<br>
*Huiwen Chang*, *Jingwan Lu*, *Fisher Yu*, *Adam Finkelstein*<br>
CVPR, 2018, [[pdf](https://adoberesearch.ctlprojects.com/wp-content/uploads/2018/04/CVPR2018_Paper3623_Chang.pdf)]

<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **A Closed-form Solution to Photorealistic Image Stylization**<br>
*Y. Li*, *M.-Y. Liu*, *X. Li*, *M.-H. Yang*, *J. Kautz*<br>
ECCV, 2018, [[pdf](https://arxiv.org/abs/1802.06474)]

<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Style transfer for anime sketches with enhanced residual u-net and auxiliary classifier gan**<br>
*L. Zhang*, *Y. Ji*, *X. Lin*<br>
ACPR, 2017, [[pdf](https://arxiv.org/abs/1706.03319)]

**Deep photo style transfer**<br>
*F. Luan*, *S. Paris*, *E. Shechtman*, *K. Bala*<br>
CVPR, 2017, [[pdf](https://arxiv.org/abs/1703.07511)]

**Photorealistic style transfer with screened poisson equation**<br>
*R. Mechrez*, *E. Shechtman*, *L. Zelnik-Manor*<br>
BMVC, 2017, [[pdf](https://arxiv.org/abs/1709.09828)]
<br>
<br>

---
#### Attribute Style Transfer
---
**Visual attribute transfer through deep image analogy**<br>
*J. Liao*, *Y. Yao*, *L. Yuan*, *G. Hua*, *S. B. Kang*<br>
TOG, 2017, [[pdf](https://arxiv.org/pdf/1705.01088.pdf)]
<br>
<br>

---
#### Fashion Style Transfer
---
<img src="https://github.com/AlenUbuntu/awesome-vision-translation/blob/master/white-right-pointing-backhand-index_1f449.png" width="20"> **Fashion style generator**<br>
*S. Jiang*, *Y. Fu*<br>
IJCAI, 2017, [[pdf](https://www.ijcai.org/Proceedings/2017/0520.pdf)]
<br>
<br>

## Image2Image Translation
