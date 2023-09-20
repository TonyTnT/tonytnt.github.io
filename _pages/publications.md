---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}


<html>
  <head>
  <meta name="generator" content="HTML Tidy for Linux/x86 (vers 11 February 2007), see www.w3.org">
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
  <style type="text/css">
  @import url(https://fonts.googleapis.com/css?family=Roboto:400,400italic,500,500italic,700,700italic,900,900italic,300italic,300);
  /* @import url(https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Roboto+Slab:100,300,400,500,700|Material+Icons); */
    /* Color scheme stolen from Sergey Karayev */
    .one
    {
    position: relative;
    }
    .two
    {
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
    }
    .fade {
     transition: opacity .2s ease-in-out;
     -moz-transition: opacity .2s ease-in-out;
     -webkit-transition: opacity .2s ease-in-out;
    }
    span.highlight {
        background-color: #ffffd0;
    }
  </style>

<hr>

  You can also find my articles on my <a href="https://scholar.google.com/citations?user=5lKm5ZMAAAAJ&hl=zh-CN" target="_blank">Google Scholar profile</a>.

<hr>

<heading><strong>Domain Knowledge Powered Deep Learning for Breast Cancer Diagnosis Based on Contrast-Enhanced Ultrasound Videos</strong> </heading>
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">  
    <td width="40%">
      <div class="one">
      <img src="/images/publications/domainknowledge.png" width="100%"> </div>
    </td>
    <td valign="top" width="75%">
          <papertitle>
          <strong>
            <a href="/files/pdf/research/Domain_Knowledge_Powered_Deep_Learning_for_Breast_Cancer_Diagnosis_Based_on_Contrast-Enhanced_Ultrasound_Videos.pdf" target="_blank">Domain Knowledge Powered Deep Learning for Breast Cancer Diagnosis Based on Contrast-Enhanced Ultrasound Videos</a>
          </strong>
          </papertitle>
    <br>
        <strong>Chen Chen</strong>,
        Yong Wang,
        <a href="https://scholar.google.com/citations?user=KOciOtEAAAAJ&hl=zh-CN&oi=sra" target="_blank">Jianwei Niu</a>,
        Xuefeng Liu,
        <a href="https://scholar.google.com/citations?user=ePDAxAkAAAAJ&hl=zh-CN&oi=sra" target="_blank">Qingfeng Li</a>,
        Xuantong Gong
      <br>
        <em>IEEE Transactions on Medical Imaging(<strong>TMI</strong>), 2021</em>
      <br>
      <!-- <a href="https://github.com/zhangganlin/GlobalSfMpy" target="_blank">Github Repo</a> |  -->
      <a href="https://ieeexplore.ieee.org/document/9425559" target="_blank">IEEE TMI</a>
      <br>
In recent years, deep learning has been widely used in breast cancer diagnosis, and many high-performance models have emerged. However, most of the existing deep learning models are mainly based on static breast ultrasound (US) images. In actual diagnostic process, contrast-enhanced ultrasound (CEUS) is a commonly used technique by radiologists. Compared with static breast US images, CEUS videos can provide more detailed blood supply information of tumors, and therefore can help radiologists make a more accurate diagnosis. In this paper, we propose a novel diagnosis model based on CEUS videos. The backbone of the model is a 3D convolutional neural network. More specifically, we notice that radiologists generally follow two specific patterns when browsing CEUS videos. One pattern is that they focus on specific time slots, and the other is that they pay attention to the differences between the CEUS frames and the corresponding US images. To incorporate these two patterns into our deep learning model, we design a domain-knowledge-guided temporal attention module and a channel attention module. We validate our model on our Breast-CEUS dataset composed of 221 cases. The result shows that our model can achieve a sensitivity of 97.2% and an accuracy of 86.3%. In particular, the incorporation of domain knowledge leads to a 3.5% improvement in sensitivity and a 6.0% improvement in specificity. Finally, we also prove the validity of two domain knowledge modules in the 3D convolutional neural network (C3D) and the 3D ResNet (R3D). </br>
    </td>
</table>
<hr>
