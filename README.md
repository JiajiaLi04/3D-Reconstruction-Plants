<!-- omit in toc -->
# Awesome 3D Reconstruction in Plant Phenotyping: A Comprehensive Review

[![Awesome](https://awesome.re/badge.svg)](https://github.com/JiajiaLi04/3D-Reconstruction-Plants
) ![](https://img.shields.io/github/stars/JiajiaLi04/3D-Reconstruction-Plants?style=social)

![](https://img.shields.io/github/last-commit/JiajiaLi04/Agriculture-Foundation-Models?color=#00FA9A) ![](https://img.shields.io/badge/PaperNumber-39-blue) ![](https://img.shields.io/badge/PRs-Welcome-red) 

A curated list of awesome **3D Reconstruction in Plant Phenotyping** papers 🔥🔥🔥. 

Currently maintained by <ins>[Jiajia Li](https://sites.google.com/view/lijiajia) @ MSU</ins>. 

**<font color='red'>Work still in progress</font>**  🚀, **we appreciate any suggestions and contributions** ❤️.

---

<!-- What is instruction learning?
Why instruction learning?
-->

<!-- TODO
## Our scope:
We aim to stay up-to-date with the most innovative developments in the field and gain valuable insights into the future of instruction-learning technology.👀 organize a systematic and comprehensive overview of instructional learning.

1. Stay up-to-date with the most innovative developments in this field.
2. Gain valuable insights into the future of instruction-learning technology.
3. 
-->


<!-- omit in toc -->
## How to contribute?

If you have any suggestions or find any missed papers, feel free to reach out or submit a [pull request](https://github.com/JiajiaLi04/3D-Reconstruction-Plants/pulls):

1. Use following markdown format.

```markdown
*Author 1, Author 2, and Author 3.* **Paper Title.**  <ins>Conference/Journal/Preprint</ins> Year. [[pdf](link)]; [[other resources](link)].
```
<!-- >1. **Paper Title.** *Author 1, Author 2, and Author 3.* Conference/Journal/Preprint Year. [[pdf](link)]. -->

2. If one preprint paper has multiple versions, please use **the earliest submitted year**.
   
3. Display the papers in a **year descending order** (the latest, the first).


<!-- omit in toc -->
## Citation

Find this repository helpful? 😊  

Please consider citing our paper. 👇👇👇

```
Coming Soon...
```

<!-- omit in toc -->
## 🔍 Table of Contents 

- [1. 💁🏽‍♀️ Introduction](#1-️-introduction)
- [2. 🎓 Surveys and Tutorials](#2--surveys-and-tutorials)
- [3. 🗂️ Taxonomy](#3-️-taxonomy)
  - [3.1 Classical Methods](#31-classical-methods)
  - [3.2 Neural radiance fields](#32-neural-radiance-fields)
  - [3.3 3D Gaussian splitting](#33-3d-gaussian-splitting)
- [4. 🤖 Applications](#4--applications)
  - [4.1 Applications Classical Methods](#41-applications-classical-methods)
  - [4.2 Applications Neural radiance fields](#42-applications-neural-radiance-fields)
  - [4.3 Applications 3D Gaussian splitting](#43-applications-3d-gaussian-splitting)

## 1. 💁🏽‍♀️ Introduction
3D reconstruction in Plant Phenotyping? How many methods we included:
- 👉 **Classical Methods.** Active methods based on depth sensors & Passive methods based on Structure from Motion (SfM).
- 👉 **Neural radiance fields (NeRF).** A novel method for synthesizing photo-realistic views of 3D objects by learning a continuous volumetric scene representation.
- 👉 **3D Gaussian splitting (3DGS).** An explicit method that models scenes using learnable 3D Gaussian distributions. 

## 2. 🎓 Surveys and Tutorials
1. Fiorani, Fabio, and Ulrich Schurr. "Future scenarios for plant phenotyping." Annual review of plant biology 64, no. 1 (2013): 267-291. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=%40article%7Bfiorani2013future%2C+++title%3D%7BFuture+scenarios+for+plant+phenotyping%7D%2C+++author%3D%7BFiorani%2C+Fabio+and+Schurr%2C+Ulrich%7D%2C+++journal%3D%7BAnnual+review+of+plant+biology%7D%2C+++volume%3D%7B64%7D%2C+++number%3D%7B1%7D%2C+++pages%3D%7B267--291%7D%2C+++year%3D%7B2013%7D%2C+++publisher%3D%7BAnnual+Reviews%7D+%7D&btnG=) [[Paper]](https://www.annualreviews.org/content/journals/10.1146/annurev-arplant-050312-120137)
2. Li, Lei, Qin Zhang, and Danfeng Huang. "A review of imaging techniques for plant phenotyping." Sensors 14, no. 11 (2014): 20078-20111. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=%40article%7Bli2014review%2C+++title%3D%7BA+review+of+imaging+techniques+for+plant+phenotyping%7D%2C+++author%3D%7BLi%2C+Lei+and+Zhang%2C+Qin+and+Huang%2C+Danfeng%7D%2C+++journal%3D%7BSensors%7D%2C+++volume%3D%7B14%7D%2C+++number%3D%7B11%7D%2C+++pages%3D%7B20078--20111%7D%2C+++year%3D%7B2014%7D%2C+++publisher%3D%7BMDPI%7D+%7D&btnG=)  [[Paper]](https://www.mdpi.com/1424-8220/14/11/20078)
3. Pieruschka, Roland, and Uli Schurr. "Plant phenotyping: past, present, and future." Plant Phenomics (2019).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=%40article%7Bpieruschka2019plant%2C+++title%3D%7BPlant+phenotyping%3A+past%2C+present%2C+and+future%7D%2C+++author%3D%7BPieruschka%2C+Roland+and+Schurr%2C+Uli%7D%2C+++journal%3D%7BPlant+Phenomics%7D%2C+++year%3D%7B2019%7D%2C+++publisher%3D%7BAAAS%7D+%7D&btnG=)  [[Paper]](https://spj.science.org/doi/full/10.34133/2019/7507131)
4. Costa, Corrado, Ulrich Schurr, Francesco Loreto, Paolo Menesatti, and Sebastien Carpentier. "Plant phenotyping research trends, a science mapping approach." Frontiers in plant science 9 (2019): 1933.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=%40article%7Bcosta2019plant%2C+++title%3D%7BPlant+phenotyping+research+trends%2C+a+science+mapping+approach%7D%2C+++author%3D%7BCosta%2C+Corrado+and+Schurr%2C+Ulrich+and+Loreto%2C+Francesco+and+Menesatti%2C+Paolo+and+Carpentier%2C+Sebastien%7D%2C+++journal%3D%7BFrontiers+in+plant+science%7D%2C+++volume%3D%7B9%7D%2C+++pages%3D%7B1933%7D%2C+++year%3D%7B2019%7D%2C+++publisher%3D%7BFrontiers+Media+SA%7D+%7D&btnG=)  [[Paper]](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2018.01933/full)
5. Das Choudhury, Sruti, Ashok Samal, and Tala Awada. "Leveraging image analysis for high-throughput plant phenotyping." Frontiers in plant science 10 (2019): 508. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=%40article%7Bdas2019leveraging%2C+++title%3D%7BLeveraging+image+analysis+for+high-throughput+plant+phenotyping%7D%2C+++author%3D%7BDas+Choudhury%2C+Sruti+and+Samal%2C+Ashok+and+Awada%2C+Tala%7D%2C+++journal%3D%7BFrontiers+in+plant+science%7D%2C+++volume%3D%7B10%7D%2C+++pages%3D%7B508%7D%2C+++year%3D%7B2019%7D%2C+++publisher%3D%7BFrontiers+Media+SA%7D+%7D&btnG=)  [[Paper]](https://www.frontiersin.org/articles/10.3389/fpls.2019.00508/full)
6. Li, Zhenbo, Ruohao Guo, Meng Li, Yaru Chen, and Guangyao Li. "A review of computer vision technologies for plant phenotyping." Computers and Electronics in Agriculture 176 (2020): 105672.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=%40article%7Bli2020review%2C+++title%3D%7BA+review+of+computer+vision+technologies+for+plant+phenotyping%7D%2C+++author%3D%7BLi%2C+Zhenbo+and+Guo%2C+Ruohao+and+Li%2C+Meng+and+Chen%2C+Yaru+and+Li%2C+Guangyao%7D%2C+++journal%3D%7BComputers+and+Electronics+in+Agriculture%7D%2C+++volume%3D%7B176%7D%2C+++pages%3D%7B105672%7D%2C+++year%3D%7B2020%7D%2C+++publisher%3D%7BElsevier%7D+%7D&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0168169920307511?casa_token=dHguEmayB0AAAAAA:zpKQsCw-YkGjrmAMnZ4KYy5lY1qQDbdc0CZ5UiVmv3mQManE4siq5bu8l76Jp7Ka3yJCcyX1d91E)
7. Jiang, Yu, and Changying Li. "Convolutional neural networks for image-based high-throughput plant phenotyping: a review." Plant Phenomics (2020).   [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Convolutional+neural+networks+for+image-based+high-throughput+plant+phenotyping%3A+a+review%7D%2C+++author%3D%7BJiang%2C+Yu+and+Li%2C+Changying%7D%2C+++journal%3D%7BPlant+Phenomics%7D%2C+++year%3D%7B2020%7D%2C+++publisher%3D%7BAAAS%7D+%7D&btnG=)  [[Paper]](https://spj.science.org/doi/full/10.34133/2020/4152816?adobe_mc=MCMID%3D13000078418609464879081490540568399952%7CMCORGID%3D242B6472541199F70A4C98A6%2540AdobeOrg%7CTS%3D1670976000)
8. Atefi, Abbas, Yufeng Ge, Santosh Pitla, and James Schnable. "Robotic technologies for high-throughput plant phenotyping: Contemporary reviews and future perspectives." Frontiers in plant science 12 (2021): 611940.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Robotic+technologies+for+high-throughput+plant+phenotyping%3A+Contemporary+reviews+and+future+perspectives%7D%2C+++author%3D%7BAtefi%2C+Abbas+and+Ge%2C+Yufeng+and+Pitla%2C+Santosh+and+Schnable%2C+James%7D%2C+++journal%3D%7BFrontiers+in+plant+science%7D%2C+++volume%3D%7B12%7D%2C+++pages%3D%7B611940%7D%2C+++year%3D%7B2021%7D%2C+++publisher%3D%7BFrontiers+Media+SA%7D+%7D&btnG=)  [[Paper]](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2021.611940/full)
9. Guo, Wei, Matthew E. Carroll, Arti Singh, Tyson L. Swetnam, Nirav Merchant, Soumik Sarkar, Asheesh K. Singh, and Baskar Ganapathysubramanian. "UAS-based plant phenotyping for research and breeding applications." Plant Phenomics (2021).   [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=UAS-based+plant+phenotyping+for+research+and+breeding+applications&btnG=)  [[Paper]](https://spj.science.org/doi/full/10.34133/2021/9840192?adobe_mc=MCMID%3D13000205405683999525849378418609464876%7CMCORGID%3D242B6472541199F70A4C98A6%2540AdobeOrg%7CTS%3D1683331200)
10. Sarić, Rijad, Viet D. Nguyen, Timothy Burge, Oliver Berkowitz, Martin Trtílek, James Whelan, Mathew G. Lewsey, and Edhem Čustović. "Applications of hyperspectral imaging in plant phenotyping." Trends in plant science 27, no. 3 (2022): 301-315. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Applications+of+hyperspectral+imaging+in+plant+phenotyping&btnG=)  [[Paper]](https://www.cell.com/trends/plant-science/abstract/S1360-1385(21)00346-0)
11. Kolhar, Shrikrishna, and Jayant Jagtap. "Plant trait estimation and classification studies in plant phenotyping using machine vision–A review." Information Processing in Agriculture 10, no. 1 (2023): 114-135.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Plant+trait+estimation+and+classification+studies+in+plant+phenotyping+using+machine+vision--A+review%7D%2C+++author%3D%7BKolhar%2C+Shrikrishna+and+Jagtap%2C+Jayant&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S2214317321000238)
12. Akhtar, Muhammad Salman, Zuhair Zafar, Raheel Nawaz, and Muhammad Moazam Fraz. "Unlocking plant secrets: A systematic review of 3D imaging in plant phenotyping techniques." Computers and Electronics in Agriculture 222 (2024): 109033.   [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Unlocking+plant+secrets%3A+A+systematic+review+of+3D+imaging+in+plant+phenotyping+techniques&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0168169924004241?casa_token=oOZ8gR5tLbcAAAAA:WalBMeU_x3stZeMI4pQvc62I5l2EirXLem6ROeJmhO8tlMoUB2B6kKCCMlQv5rMHUQ8jb0AOSRHQ)
13. Song, Hongli, Weiliang Wen, Sheng Wu, and Xinyu Guo. "Comprehensive review on 3D point cloud segmentation in plants." Artificial Intelligence in Agriculture (2025).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Comprehensive+review+on+3D+point+cloud+segmentation+in+plants&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S2589721725000066)


## 3. 🗂️ Taxonomy

In our paper, we divide the textual instructions into three categories.

### 3.1 Classical Methods
1. Wang, Yinghua, Songtao Hu, He Ren, Wanneng Yang, and Ruifang Zhai. "3DPhenoMVS: A low-cost 3D tomato phenotyping pipeline using 3D reconstruction point cloud based on multiview images." Agronomy 12, no. 8 (2022): 1865.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=3DPhenoMVS%3A+A+low-cost+3D+tomato+phenotyping+pipeline+using+3D+reconstruction+point+cloud+based+on+multiview+images&btnG=)  [[Paper]](https://www.mdpi.com/2073-4395/12/8/1865)
   
### 3.2 Neural radiance fields
1. Mildenhall, Ben, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, and Ren Ng. "Nerf: Representing scenes as neural radiance fields for view synthesis." Communications of the ACM 65, no. 1 (2021): 99-106.   [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Nerf%3A+Representing+scenes+as+neural+radiance+fields+for+view+synthesis&btnG=)  [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503250)
2. Barron, Jonathan T., Ben Mildenhall, Matthew Tancik, Peter Hedman, Ricardo Martin-Brualla, and Pratul P. Srinivasan. "Mip-nerf: A multiscale representation for anti-aliasing neural radiance fields." In Proceedings of the IEEE/CVF international conference on computer vision, pp. 5855-5864. 2021.   [[Google Scholar]](https://scholar.google.com/scholar?cluster=9302627546751271499&hl=en&as_sdt=0,25)  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Barron_Mip-NeRF_A_Multiscale_Representation_for_Anti-Aliasing_Neural_Radiance_Fields_ICCV_2021_paper.html)
3. Barron, Jonathan T., Ben Mildenhall, Dor Verbin, Pratul P. Srinivasan, and Peter Hedman. "Mip-nerf 360: Unbounded anti-aliased neural radiance fields." In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition, pp. 5470-5479. 2022.   [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Mip-nerf+360%3A+Unbounded+anti-aliased+neural+radiance+fields.&btnG=)  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Barron_Mip-NeRF_360_Unbounded_Anti-Aliased_Neural_Radiance_Fields_CVPR_2022_paper.html)
4. Chen, Gerry, Sunil Kumar Narayanan, Thomas Gautier Ottou, Benjamin Missaoui, Harsh Muriki, Cédric Pradalier, and Yongsheng Chen. "Hyperspectral neural radiance fields." arXiv preprint arXiv:2403.14839 (2024).   [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Hyperspectral+neural+radiance+fields&btnG=)  [[Paper]](https://arxiv.org/abs/2403.14839)

### 3.3 3D Gaussian splitting
1. Thirgood, Christopher, Oscar Mendez, Erin Chao Ling, Jon Storey, and Simon Hadfield. "HyperGS: Hyperspectral 3D Gaussian Splatting." arXiv preprint arXiv:2412.12849 (2024).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=HyperGS%3A+Hyperspectral+3D+Gaussian+Splatting&btnG=)  [[Paper]](https://arxiv.org/abs/2412.12849)
2. Kerbl, Bernhard, Georgios Kopanas, Thomas Leimkühler, and George Drettakis. "3d gaussian splatting for real-time radiance field rendering." ACM Trans. Graph. 42, no. 4 (2023): 139-1.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=3d+gaussian+splatting+for+real-time+radiance+field+rendering&btnG=)  [[Paper]](https://sgvr.kaist.ac.kr/~sungeui/ICG_F23/Students/[CS482]%203D%20Gaussian%20Splatting%20for%20Real-Time%20Radiance%20Field%20Rendering.pdf)


## 4. 🤖 Applications
### 4.1 Applications Classical Methods
1. Gené-Mola, Jordi, Eduard Gregorio, Fernando Auat Cheein, Javier Guevara, Jordi Llorens, Ricardo Sanz-Cortiella, Alexandre Escolà, and Joan R. Rosell-Polo. "Fruit detection, yield prediction and canopy geometric characterization using LiDAR with forced air flow." Computers and Electronics in Agriculture 168 (2020): 105121.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Fruit+detection%2C+yield+prediction+and+canopy+geometric+characterization+using+LiDAR+with+forced+air+flow&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0168169919313390?casa_token=sL-24HPph50AAAAA:Lj3-BDdjLYqMMFsQ7oOV89_AtEmSdyMvuYsxp2HRfDdkRfxPix5sbID3TK4CRXlcq4-VfcZjR4Xy)
2. Zhang, Yonglong, Yaling Xie, Jialuo Zhou, Xiangying Xu, and Minmin Miao. "Cucumber seedling segmentation network based on a multiview geometric graph encoder from 3D point clouds." Plant Phenomics 6 (2024): 0254.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Cucumber+seedling+segmentation+network+based+on+a+multiview+geometric+graph+encoder+from+3D+point+clouds&btnG=)  [[Paper]](https://spj.science.org/doi/full/10.34133/plantphenomics.0254)
3. Wang, Yinghua, Songtao Hu, He Ren, Wanneng Yang, and Ruifang Zhai. "3DPhenoMVS: A low-cost 3D tomato phenotyping pipeline using 3D reconstruction point cloud based on multiview images." Agronomy 12, no. 8 (2022): 1865.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=3DPhenoMVS%3A+A+low-cost+3D+tomato+phenotyping+pipeline+using+3D+reconstruction+point+cloud+based+on+multiview+images&btnG=)  [[Paper]](https://www.mdpi.com/2073-4395/12/8/1865)
3. Shen, Peng, Xueyao Jing, Wenzhe Deng, Hanyue Jia, and Tingting Wu. "PlantGaussian: Exploring 3D Gaussian splatting for cross-time, cross-scene, and realistic 3D plant visualization and beyond." The Crop Journal (2025).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=PlantGaussian%3A+Exploring+3D+Gaussian+splatting+for+cross-time%2C+cross-scene%2C+and+realistic+3D+plant+visualization+and+beyond&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S2214514125000261)
4. Chen, Haibo, Shengbo Liu, Congyue Wang, Chaofeng Wang, Kangye Gong, Yuanhong Li, and Yubin Lan. "Point cloud completion of plant leaves under occlusion conditions based on deep learning." Plant Phenomics 5 (2023): 0117.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Point+Cloud+Completion+of+Plant+Leaves+under+Occlusion+Conditions+Based+on+Deep+Learning&btnG=)  [[Paper]](https://spj.science.org/doi/full/10.34133/plantphenomics.0117)

### 4.2 Applications Neural radiance fields
1. Jignasu, Anushrut, Ethan Herron, Talukder Zaki Jubery, James Afful, Aditya Balu, Baskar Ganapathysubramanian, Soumik Sarkar, and Adarsh Krishnamurthy. "Plant geometry reconstruction from field data using neural radiance fields." In 2nd AAAI Workshop on AI for Agriculture and Food Systems. 2023.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Plant+geometry+reconstruction+from+field+data+using+neural+radiance+fields&btnG=)  [[Paper]](https://openreview.net/forum?id=TvKKqWn_-6)
2. Arshad, Muhammad Arbab, Talukder Jubery, James Afful, Anushrut Jignasu, Aditya Balu, Baskar Ganapathysubramanian, Soumik Sarkar, and Adarsh Krishnamurthy. "Evaluating Neural Radiance Fields for 3D Plant Geometry Reconstruction in Field Conditions." Plant Phenomics 6 (2024): 0235.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Evaluating+Neural+Radiance+Fields+for+3D+Plant+Geometry+Reconstruction+in+Field+Conditions&btnG=)  [[Paper]](https://spj.science.org/doi/full/10.34133/plantphenomics.0235)
3. Chopra, Samarth, Fernando Cladera, Varun Murali, and Vijay Kumar. "AgriNeRF: Neural Radiance Fields for Agriculture in Challenging Lighting Conditions." arXiv preprint arXiv:2409.15487 (2024).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=AgriNeRF%3A+Neural+Radiance+Fields+for+Agriculture+in+Challenging+Lighting+Conditions&btnG=)  [[Paper]](https://arxiv.org/abs/2409.15487)
4. Zhao, Junhong, Wei Ying, Yaoqiang Pan, Zhenfeng Yi, Chao Chen, Kewei Hu, and Hanwen Kang. "Exploring Accurate 3D Phenotyping in Greenhouse through Neural Radiance Fields." arXiv preprint arXiv:2403.15981 (2024).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Exploring+Accurate+3D+Phenotyping+in+Greenhouse+through+Neural+Radiance+Fields&btnG=)  [[Paper]](https://arxiv.org/abs/2403.15981)
5. Hu, Kewei, Wei Ying, Yaoqiang Pan, Hanwen Kang, and Chao Chen. "High-fidelity 3D reconstruction of plants using Neural Radiance Fields." Computers and Electronics in Agriculture 220 (2024): 108848.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=High-fidelity+3D+reconstruction+of+plants+using+Neural+Radiance+Fields&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0168169924002394?casa_token=aZCf7hACmUIAAAAA:VEbbjuqYwBx25rP5O8Q0Ch0oakOEX68wmRDIFHnAc-ILtTjOnm_N6NCMZOG4YwmFpKOnGLQ7ErGt)
6. Yang, Xin, Xuqi Lu, Pengyao Xie, Ziyue Guo, Hui Fang, Haowei Fu, Xiaochun Hu, Zhenbiao Sun, and Haiyan Cen. "PanicleNeRF: low-cost, high-precision in-field phenotyping of rice panicles with smartphone." Plant Phenomics 6 (2024): 0279.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=PanicleNeRF%3A+low-cost%2C+high-precision+in-field+phenotyping+of+rice+panicles+with+smartphone&btnG=)  [[Paper]](https://spj.science.org/doi/full/10.34133/plantphenomics.0279)
7. Saeed, Farah, Jin Sun, Peggy Ozias-Akins, Ye Juliet Chu, and Changying Charlie Li. "PeanutNeRF: 3D radiance field for peanuts." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 6254-6263. 2023.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=PeanutNeRF%3A+3D+radiance+field+for+peanuts&btnG=)  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023W/AgriVision/html/Saeed_PeanutNeRF_3D_Radiance_Field_for_Peanuts_CVPRW_2023_paper.html)
8. Choi, Hong-Beom, Jae-Kun Park, Soo Hyun Park, and Taek Sung Lee. "NeRF-based 3D reconstruction pipeline for acquisition and analysis of tomato crop morphology." Frontiers in Plant Science 15 (2024): 1439086.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=NeRF-based+3D+reconstruction+pipeline+for+acquisition+and+analysis+of+tomato+crop+morphology&btnG=)  [[Paper]](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2024.1439086/full)
9. Zhu, Xinghui, Zhongrui Huang, and Bin Li. "Three-dimensional phenotyping pipeline of potted plants based on neural radiation fields and path segmentation." Plants 13, no. 23 (2024): 3368.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Three-dimensional+phenotyping+pipeline+of+potted+plants+based+on+neural+radiation+fields+and+path+segmentation&btnG=)  [[Paper]](https://pmc.ncbi.nlm.nih.gov/articles/PMC11644607/)

  
### 4.3 Applications 3D Gaussian splitting
1. Jiang, Lizhi, Changying Li, Jin Sun, Peng Chee, and Longsheng Fu. "Estimation of cotton boll number and main stem length based on 3D gaussian splatting." In 2024 ASABE Annual International Meeting, p. 1. American Society of Agricultural and Biological Engineers, 2024.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Estimation+of+cotton+boll+number+and+main+stem+length+based+on+3D+gaussian+splatting&btnG=)  [[Paper]](https://elibrary.asabe.org/abstract.asp?aid=54807)
2. Ojo, Tommy, Thai La, Andrew Morton, and Ian Stavness. "Splanting: 3D plant capture with gaussian splatting." In SIGGRAPH Asia 2024 Technical Communications, pp. 1-4. 2024.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=Splanting%3A+3D+plant+capture+with+gaussian+splatting.%22+In+SIGGRAPH+Asia+2024+Technical+Communications&btnG=)  [[Paper]](https://dl.acm.org/doi/full/10.1145/3681758.3698009?casa_token=hoNmElyZvLcAAAAA%3AIHWMINIaSAesaW4T3NYKWpzx2x_FXRrvMiQEjYBSoSpnwP7Iu1bKWXrFva1pP8UKhEv962orkJR3ngY)
3. Shen, Peng, Xueyao Jing, Wenzhe Deng, Hanyue Jia, and Tingting Wu. "PlantGaussian: Exploring 3D Gaussian splatting for cross-time, cross-scene, and realistic 3D plant visualization and beyond." The Crop Journal (2025).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C25&q=PlantGaussian%3A+Exploring+3D+Gaussian+splatting+for+cross-time%2C+cross-scene%2C+and+realistic+3D+plant+visualization+and+beyond&btnG=)  [[Paper]](https://www.sciencedirect.com/science/article/pii/S2214514125000261)

