# awesome-vision-translation
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
**Fast patch-based style transfer of arbitrary style**<br>
*T. Q. Chen*, *M. Schmidt*<br>
NIPS Workshop, 2016, [[pdf](https://arxiv.org/abs/1612.04337)]

<br>
<br>

## Image2Image Translation
