---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div style="float:left">
<img class="logoImg amplifyImg" src="/images/multilingualNLP.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Parameter-efficiency for distributed multilingual NLP</b>
<small><br>We found that multilingual NLP is a suitable scenario for discussing federated learning since multilingual datasets are often distributed across various locations. However, using large language models introduces a significant communication burden due to the need to exchange a large number of parameters. In this project, we propose a meta-learning-based adaptive parameter selection methodology to improve the communication efficiency of model transmissions from clients in federated multilingual NLP.
<br>
<a href="https://arxiv.org/abs/2401.07456">[The Web Conf'24 - FL@FM]</a></a></small>
</div>
<div style="clear:both"></div>
<hr> 


<div style="float:left">
<img class="logoImg amplifyImg" src="/images/CIKM.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>Improving prediction fairness for minority students in online educational scenarios</b>
<small><br>Traditional learning-based approaches to student modeling often generalize poorly to underrepresented student groups due to biases in data availability. We propose a personalized method for predicting student performance based on their online learning activities, optimizing inference accuracy across diverse demographic groups, including race and gender. This project introduces distributed machine learning with meta-learning to customize models for subgroup heterogeneity. Experiments on real-world datasets from online courses demonstrate that our approach significantly outperforms existing student modeling baselines, providing improved predictions of student learning outcomes for all subgroups.
<br>
<a href="https://arxiv.org/abs/2212.02985">[CIKM '22]</a>, <a href="https://arxiv.org/abs/2212.02985">[IEEE TETC]</a></small>
</div>
<div style="clear:both"></div>
<hr> 


<div style="float:left">
<img class="logoImg amplifyImg" src="/images/ACL_rank.png" align="left" width="200px" height="200px" >
</div>
<div style="margin:8px;float:left;width:75%;text-align:justify;line-height:18px">
<b>The first reference-free evaluation metric for visual storytelling</b>
<small><br>It remains unclear whether conventional automatic evaluation metrics for text generation are applicable to Visual Storytelling (VIST). We collect VHED (VIST Human Evaluation Data) dataset, which first re-purposes human evaluation results for automatic evaluation; hence develop VRank (VIST ranker), a novel reference-free VIST metric learned from VHED. Experimental results show that our metric's prediction is significantly more aligned to human evaluation than other metrics with almost 30% higher accuracy when ranking story pairs. Moreover, we demonstrate that only VRank shows human-like behavior in its strong ability to find better stories when the quality gap between two stories is high.
<br>
<a href="https://aclanthology.org/2022.acl-long.441.pdf">[ACL-IJCNLP'22]</a></small>
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
<a href="https://arxiv.org/abs/2105.06950?context=cs.AI">[ACL-IJCNLP'21 Findings]</a></small>
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
<a href="/files/StretchVIST.pdf" target="_blank">[ACL-IJCNLP'21 Demo]</a></small>
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
<a href="/files/AAAI21_Workshop_VIST_Question.pdf" target="_blank">[AAAI'21 - DIAL]</a></small>
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
<a href="/files/TASL_final_paper.pdf">[IEEE/ACM TASLP]</a>, <a href="https://arxiv.org/abs/2001.06206">[AAAI'20 - DSTC]</a></small>
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
<a href="https://arxiv.org/abs/2005.12516">[SIGIR'20]</a></small>
</div>
<div style="clear:both"></div>
<hr> 



