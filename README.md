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
  - [3.1 Language foundation models](#31-language-foundation-models)
  - [3.2 Vision foundation models](#32-vision-foundation-models)
  - [3.3 Multimodal foundation models](#33-multimodal-foundation-models)
  - [3.4 Reinforcement learning foundation models](#34-reinforcement-learning-foundation-models)
- [4. 🤖 Applications](#4--applications)


## 1. 💁🏽‍♀️ Introduction
3D reconstruction in Plant Phenotyping? How many methods we included:
- 👉 **Classical Methods.** Active methods based on depth sensors & Passive methods based on Structure from Motion (SfM).
- 👉 **Neural radiance fields (NeRF).** A novel method for synthesizing photo-realistic views of 3D objects by learning a continuous volumetric scene representation.
- 👉 **3D Gaussian splitting (3DGS).** An explicit method that models scenes using learnable 3D Gaussian distributions. 

## 2. 🎓 Surveys and Tutorials  [[Google Scholar]]()  [[Paper]]()
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

In our paper, we divide the textual instructions into four categories.

### 3.1 Language foundation models 
1. Devlin, Jacob, et al. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv preprint arXiv:1810.04805 (2018). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=BERT+Pre-training+of+Deep+Bidirectional+Transformers+for+Language+Understanding&btnG=) [[Paper]](https://arxiv.org/abs/1810.04805)
2. Du, Nan, et al. "Glam: Efficient scaling of language models with mixture-of-experts." International Conference on Machine Learning. PMLR, 2022. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=GLaM+Efficient+Scaling+of+Language+Models+with+Mixture-of-Experts&btnG=) [[Paper]](https://proceedings.mlr.press/v162/du22c.html)
3. Claude 3 [[Website]](https://www.anthropic.com/news/claude-3-family)
   
### 3.2 Vision foundation models 
1. Yuan, Lu, et al. "Florence: A new foundation model for computer vision." arXiv preprint arXiv:2111.11432 (2021). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=Florence+A+New+Foundation+Model+for+Computer+Vision&btnG=) [[Paper]](https://arxiv.org/abs/2111.11432)
2. Ramesh, Aditya, et al. "Hierarchical text-conditional image generation with clip latents." arXiv preprint arXiv:2204.06125 (2022). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=DALLE2-Hierarchical+Text-Conditional+Image+Generation+with+CLIP+Latents&btnG=) [[Paper]](https://arxiv.org/abs/2204.06125)
3. Saharia, Chitwan, et al. "Photorealistic text-to-image diffusion models with deep language understanding." Advances in Neural Information Processing Systems 35 (2022): 36479-36494. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=-Imagen-Photorealistic+Text-to-Image+Diffusion+Models+with+Deep+Language+Understanding&btnG=) [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/ec795aeadae0b7d230fa35cbaf04c041-Abstract-Conference.html)
4. Rombach, Robin, et al. "High-resolution image synthesis with latent diffusion models." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=Stable+Diffusion_High-Resolution+Image+Synthesis+with+Latent+Diffusion+Models&btnG=) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html)
5. Kang, Minguk, et al. "Scaling up gans for text-to-image synthesis." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=GigaGAN-Scaling+up+GANs+for+Text-to-Image+Synthesis&btnG=) [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Kang_Scaling_Up_GANs_for_Text-to-Image_Synthesis_CVPR_2023_paper.html)
6. Cao, Yunkang, et al. "Segment Any Anomaly without Training via Hybrid Prompt Regularization." arXiv preprint arXiv:2305.10724 (2023). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=SAA%2B-Segment+Any+Anomaly+without+Training+via+Hybrid+Prompt+Regularization&btnG=) [[Paper]](https://arxiv.org/abs/2305.10724)
7. Zou, Xueyan, et al. "Segment everything everywhere all at once." arXiv preprint arXiv:2304.06718 (2023).  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=Segment+everything+everywhere+all+at+once&btnG=) [[Paper]](https://arxiv.org/abs/2304.06718)

### 3.3 Multimodal foundation models 
1. Cherti, Mehdi, et al. "Reproducible scaling laws for contrastive language-image learning." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=OpenCLIP-Reproducible+scaling+laws+for+contrastive+language-image+learning&btnG=) [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Cherti_Reproducible_Scaling_Laws_for_Contrastive_Language-Image_Learning_CVPR_2023_paper.html)
2. Li, Junnan, et al. "Blip: Bootstrapping language-image pre-training for unified vision-language understanding and generation." International Conference on Machine Learning. PMLR, 2022. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=BLIP_Bootstrapping+Language-Image+Pre-training+for+Unified+Vision-Language+Understanding+and+Generation&btnG=) [[Paper]](https://proceedings.mlr.press/v162/li22n.html)
3. Alayrac, Jean-Baptiste, et al. "Flamingo: a visual language model for few-shot learning." Advances in Neural Information Processing Systems 35 (2022): 23716-23736. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=-Flamingo_a+Visual+Language+Model+for+Few-Shot+Learning&btnG=) [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/960a172bc7fbf0177ccccbb411a7d800-Abstract-Conference.html)
4. Huang, Shaohan, et al. "Language is not all you need: Aligning perception with language models." arXiv preprint arXiv:2302.14045 (2023). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0,23&q=KOSMOS-1-Language+Is+Not+All+You+Need+Aligning+Perception+with+Language+Models) [[Paper]](https://arxiv.org/abs/2302.14045)
5. Girdhar, Rohit, et al. "Imagebind: One embedding space to bind them all." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Girdhar_ImageBind_One_Embedding_Space_To_Bind_Them_All_CVPR_2023_paper.pdf)
6. Wei, Longhui, et al. "Mvp: Multimodality-guided visual pre-training." European Conference on Computer Vision. Cham: Springer Nature Switzerland, 2022.[[Arxiv]](https://arxiv.org/pdf/2203.05175.pdf)
7. Gemini 1.5. [[Website]](https://deepmind.google/technologies/gemini/#introduction)

### 3.4 Reinforcement learning foundation models 
1. Reed, Scott, et al. "A generalist agent." arXiv preprint arXiv:2205.06175 (2022). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=A+Generalist+Agent&btnG=) [[Paper]](https://arxiv.org/abs/2205.06175)
2. Team, Adaptive Agent, et al. "Human-timescale adaptation in an open-ended task space." arXiv preprint arXiv:2301.07608 (2023). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=Human-Timescale+Adaptation+in+an+Open-Ended+Task+Space&btnG=) [[Paper]](https://arxiv.org/abs/2301.07608)

## 4. 🤖 Applications
1. Xu, Yunbi, et al. "Smart breeding driven by big data, artificial intelligence, and integrated genomic-enviromic prediction." Molecular Plant 15.11 (2022): 1664-1695. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=Smart+breeding+driven+by+big+data%2C+artificial+intelligence%2C+and+integrated+genomic-enviromic+prediction&btnG=) [[Paper]](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.cell.com/molecular-plant/pdf/S1674-2052(22)00295-7.pdf)
2. Williams, Dominic, Fraser MacFarlane, and Avril Britten. "Leaf Only SAM: A Segment Anything Pipeline for Zero-Shot Automated Leaf Segmentation." arXiv preprint arXiv:2305.09418 (2023). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=Leaf+Only+SAM+A+Segment+Anything+Pipeline+for+Zero-Shot+Automated+Leaf+Segmentation&btnG=) [[Paper]](https://arxiv.org/abs/2305.09418)
3. Yang, Xiao, et al. "SAM for Poultry Science." arXiv preprint arXiv:2305.10254 (2023). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C23&q=SAM+for+Poultry+Science&btnG=) [[Paper]](https://arxiv.org/abs/2305.10254)
4. Stella, Francesco, Cosimo Della Santina, and Josie Hughes. "How can LLMs transform the robotic design process?." Nature Machine Intelligence 5.6 (2023): 561-564.  [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=How+can+LLMs+transform+the+robotic+design+process%3F&btnG=) [[Paper]](https://www.nature.com/articles/s42256-023-00669-7)
5. Tzachor, Asaf, et al. "Large language models and agricultural extension services." Nature Food 4.11 (2023): 941-948. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=Large+language+models+and+agricultural+extension+services&btnG=) [[Paper]](https://www.nature.com/articles/s43016-023-00867-x)
6. Lu, Guoyu, et al. "Agi for agriculture." arXiv preprint arXiv:2304.06136 (2023). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=Agi+for+agriculture&btnG=) [[Paper]](https://arxiv.org/abs/2304.06136)
7. Yang, Xianjun, et al. "Pllama: An open-source large language model for plant science." arXiv preprint arXiv:2401.01600 (2024). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=Pllama%3A+An+open-source+large+language+model+for+plant+science&btnG=) [[Paper]](https://arxiv.org/abs/2401.01600)
8. Shutske, John M. "Harnessing the Power of Large Language Models in Agricultural Safety & Health." Journal of Agricultural Safety and Health (2023): 0. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=Harnessing+the+Power+of+Large+Language+Models+in+Agricultural+Safety%26Health&btnG=) [[Paper]](https://elibrary.asabe.org/azdez.asp?JID=3&AID=54486&t=2&v=0&i=0&CID=j0000&downPDF=Y&directPDF=Y)
9. Kuska, Matheus Thomas, Mirwaes Wahabzada, and Stefan Paulus. "Ai-Chatbots for Agriculture-Where Can Large Language Models Provide Substantial Value?." Available at SSRN 4685971. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=Ai-Chatbots+for+Agriculture-Where+Can+Large+Language+Models+Provide+Substantial+Value%3F&btnG=) [[Paper]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4685971)
10. Cao, Yiyi, et al. "Cucumber disease recognition with small samples using image-text-label-based multi-modal language model." Computers and Electronics in Agriculture 211 (2023): 107993. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=Cucumber+disease+recognition+with+small+samples+using+image-text-label-based+multi-modal+language+model&btnG=) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0168169923003812?casa_token=eK3Lkip3GtgAAAAA:HbuFU3XUGseIHIfd9mOc43hSe02exDy_Fubf_fWP9DIs3xDDBFUUI17oCpHZIL19NXOGwO4bNRWm)
11. Stella, Francesco, Cosimo Della Santina, and Josie Hughes. "How can LLMs transform the robotic design process?." Nature Machine Intelligence 5.6 (2023): 561-564. [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=How+can+LLMs+transform+the+robotic+design+process%3F&btnG=) [[Paper]](https://www.nature.com/articles/s42256-023-00669-7)
12. Tan, Chenjiao, et al. "On the promises and challenges of multimodal foundation models for geographical, environmental, agricultural, and urban planning applications." arXiv preprint arXiv:2312.17016 (2023). [[Google Scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C47&q=On+the+promises+and+challenges+of+multimodal+foundation+models+for+geographical%2C+environmental%2C+agricultural%2C+and+urban+planning+applications&btnG=) [[Paper]](https://arxiv.org/abs/2312.17016)
13. Zhao, Xinyan, Baiyan Chen, Mengxue Ji, Xinyue Wang, Yuhan Yan, Jinming Zhang, Shiyingjie Liu, Muyang Ye, and Chunli Lv. "Implementation of Large Language Models and Agricultural Knowledge Graphs for Efficient Plant Disease Detection." Agriculture 14, no. 8 (2024): 1359.[[Paper]](https://www.mdpi.com/2077-0472/14/8/1359)
14. Fattepur, Bhumika, A. Sakshi, A. Abhishek, and Sneha Varur. "Cultivating Prosperity: A Fusion of IoT Data with Machine Learning and Deep Learning for Precision Crop Recommendations." In 2024 5th International Conference for Emerging Technology (INCET), pp. 1-6. IEEE, 2024. [[Paper]](https://ieeexplore.ieee.org/abstract/document/10593556)
15. Chen, Dong, and Yanbo Huang. "Integrating reinforcement learning and large language models for crop production process management optimization and control through a new knowledge-based deep learning paradigm." Computers and Electronics in Agriculture 232 (2025): 110028. [[Paper]](https://www.sciencedirect.com/science/article/pii/S0168169925001346)
16. Truong, Thanh-Dat, Hoang-Quan Nguyen, Xuan-Bac Nguyen, Ashley Dowling, Xin Li, and Khoa Luu. "Insect-Foundation: A Foundation Model and Large Multimodal Dataset for Vision-Language Insect Understanding." arXiv preprint arXiv:2502.09906 (2025). [[Paper]](https://arxiv.org/abs/2502.09906)
17. Xie, Yiqun, Zhihao Wang, Weiye Chen, Zhili Li, Xiaowei Jia, Yanhua Li, Ruichen Wang, Kangyang Chai, Ruohan Li, and Sergii Skakun. "When are Foundation Models Effective? Understanding the Suitability for Pixel-Level Classification Using Multispectral Imagery." arXiv preprint arXiv:2404.11797 (2024).
18. Qing, Jiajun, Xiaoling Deng, Yubin Lan, and Zhikai Li. "GPT-aided diagnosis on agricultural image based on a new light YOLOPC." Computers and electronics in agriculture 213 (2023): 108168.
19. Dofitas, Cyreneo, Yong-Woon Kim, and Yung-Cheol Byun. "Advanced Agricultural Query Resolution Using Ensemble-Based Large Language Models." IEEE Access (2025).
20. Zhu, Hongfei, Weiming Shi, Xinyu Guo, Shiting Lyu, Ranbing Yang, and Zhongzhi Han. "Potato disease detection and prevention using multimodal AI and large language model." Computers and Electronics in Agriculture 229 (2025): 109824.
21. Jiang, Xue, Jiashi Wang, Kai Xie, Chenxi Cui, Aobo Du, Xianglong Shi, Wanneng Yang, and Ruifang Zhai. "PlantCaFo: An efficient few-shot plant disease recognition method based on foundation models." Plant Phenomics (2025): 100024.
