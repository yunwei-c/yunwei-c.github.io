---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div style="float:left">
<img class="logoImg amplifyImg" src="/images/ACL_rank.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
<b>The first reference-free evaluation metric for visual storytelling</b> 
<small><br>It remains unclear whether conventional automatic evaluation metrics for text generation are applicable to Visual Storytelling (VIST). We collect VHED (VIST Human Evaluation Data) dataset, which first re-purposes human evaluation results for automatic evaluation; hence develop VRank (VIST ranker), a novel reference-free VIST metric learned from VHED. Experimental results show that our metric's prediction is significantly more aligned to human evaluation than other metrics with almost 30% higher accuracy when ranking story pairs. Moreover, we demonstrate that only VRank shows human-like behavior in its strong ability to find better stories when the quality gap between two stories is high.
<br>
<a href="https://aclanthology.org/2022.acl-long.441.pdf">[Paper Link] (ACL-IJCNLP'22)</a></small>
</div>
<div style="clear:both"></div>
<hr> 

<div style="float:left">
<img class="logoImg amplifyImg" src="/images/ACL.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Modeling Storylines for Visual Storytelling</b> 
<small><br>Writing a coherent and engaging story is not easy, especially for automated visual storytelling models. We introduce PR-VIST, a framework that first represents the input image sequence as a story graph in which it finds the best path to form a storyline. PR-VIST then takes this path and learns to generate and refine the final story via Transformer with a human-like discriminator. This framework produces stories that are superior in terms of diversity, coherence, and humanness, per both automatic and human evaluations. An ablation study shows that both plotting and reworking contribute to the model's superiority.
<br>
<a href="https://arxiv.org/abs/2105.06950?context=cs.AI">[Paper Link] (ACL-IJCNLP'21 Findings)</a></small>
</div>
<div style="clear:both"></div>
<hr> 



<div style="float:left">
<img class="logoImg amplifyImg" src="/images/Stretch2.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Getting Flexible With Visual Stories</b>
<small><br>Most visual storytelling models remain limited in terms of the generated stories' fixed length, and the fix-length stories carry limited details and provide ambiguous textual information to the readers. Therefore, we propose Stretch-VST to generate prolonged stories by adding appropriate knowledge. The framework distills representative terms from a sequence of images and find the appropriate relations between terms on knowledge graph by a scoring function. We also design a length-controlled Transformer to generate diverse length stories with better focus and detail compared to the state of the art.
<br>
<a href="https://youtu.be/-uF8IV6T1NU">[Video]</a>, <a href="/files/StretchVIST.pdf" target="_blank">[Paper Link] (ACL-IJCNLP'21 Demo)</a></small>
</div>
<div style="clear:both"></div>
<hr> 

<div style="float:left">
<img class="logoImg amplifyImg" src="/images/fig1_fin.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Conversational Visual Question Generation</b>
<small><br>Explored a novel scenario: a conversation agent views a set of the user's photos and asks an engaging question to initiate a conversation with the user. Introduced a two-phase framework that first generates a visual story for the photo set and then uses the story to produce an interesting question. The human evaluation shows that our framework generates more response-provoking questions for starting conversations than other vision-to-question baselines.
<br>
<a href="/files/AAAI21_Workshop_VIST_Question.pdf" target="_blank">[Paper Link] (AAAI'21 workshop)</a></small>
</div>
<div style="clear:both"></div>
<hr> 

<div style="float:left">
<img src="/images/AAAI_DSTC.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Multi-modal Dialog System</b>
<small><br>Proposed a multi-step joint-modality attention network based on recurrent neural network to reason on multiple modalities, including audio, vision, and language. The model jointly considered both visual and textual representations in each reasoning process to better integrate information from dynamic scenes.
<br>
<a href="/files/TASL_final_paper.pdf">[Paper Link] (IEEE/ACM TASLP)</a>, <a href="https://arxiv.org/abs/2001.06206">[Paper Link] (AAAI'20 workshop)</a></small>
</div>
<div style="clear:both"></div>
<hr> 

<div style="float:left">
<img align="left" width="200px" height="200px" src="/images/SIGIR.png">
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Multiview Items Recommendation</b>
<small><br>Developed a GNN-based recommendation model which provides superior recommendations by describing items from user and entity angles. Designed user-oriented modules that aggregate features to make personalized recommendations and a mixing layer which contrasts layer-wise GCN to obtain comprehensive features from internal entity-entity interactions. 
<br>
<a href="https://arxiv.org/abs/2005.12516">[Paper Link] (SIGIR'20)</a></small>
</div>
<div style="clear:both"></div>
<hr> 


<div style="float:left">
<img align="left" width="200" height="200" src="/images/SW.png">
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Stage-Wise Training for GNN-based Recommender Model</b>
<small><br>Applied stage-wise training on two state-of-the-art recommendation models, RippleNet and Knowledge Graph Convolutional Networks (KGCN), and evaluated the performance on six real world datasets. The result of the experiments showed that stage-wise training strategy can help both models to collect more information from the KG and improve the recommendation performance. 
<br>
<a href="https://arxiv.org/abs/1908.05611">[Paper Link]</a></small>
</div>
<div style="clear:both"></div>
<hr> 


<div style="float:left">
<img align="left" width="200" height="200" src="/images/ACCESS.png">
</div> 
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Luminance Variation Resistant Remote-PPG</b>
<small><br>Collected drivers’ facial dataset (2.7M continuous images) in different outdoor scenarios, including day time and nighttime. Developed an Adaptive Neural Network Model Selection algorithm to dynamically select personalized model and eliminate facial luminance variation noise from rPPG signal. This work successfully reduced the mean absolute error from 14.71 bpm to 4.51 bpm.
<br>
<a href="https://ieeexplore.ieee.org/document/8701432">[Paper Link] (IEEE ACCESS)</a> <a href="https://www.youtube.com/watch?v=cvw8AeakBt8&feature=youtu.be">[Demo Video]</a> </small>
</div>
<div style="clear:both"></div>
<hr> 


<div style="float:left">
<img align="left" width="200" height="150" src="/images/ACCV.png">
</div> 
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Motion Robust Remote-PPG </b>
<small><br>Built a face tracking algorithm to extract heart rate signal from driver’s face in continuous images sequence. Developed machine learning approach to eliminate rPPG noise caused by driver's facial motion. This work is first of its kind as the traditional rPPG work consider only in indoor and stable environment.
<br>
<a href="https://link.springer.com/chapter/10.1007/978-3-319-54407-6_31">[Paper Link] (ACCV'16 workshop)</a> </small>
</div>
<div style="clear:both"></div>
<hr> 
