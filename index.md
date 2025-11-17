---
layout: default
title: ""
---

<style>
.page-container {
  max-width: 1100px;
  margin: 40px auto;
  display: flex;
  justify-content: space-between;
  gap: 40px;
}

.page-text {
  flex: 1;
  font-size: 16px;
  line-height: 1.65;
}

.page-image {
  flex: 0 0 35%;     /* 图片不会太大 */
}

.page-image img {
  width: 100%;
  border-radius: 8px;
}

@media(max-width: 768px){
  .page-container {
    flex-direction: column;
  }
  .page-image {
    width: 100%;
  }
}
</style>

<div class="page-container">

  <div class="page-text">
    <p>I'm Shuo Jiang, a researcher and entrepreneur working at the intersection of AI, engineering design, and multidisciplinary innovation.</p>

    <p>I am currently a Research Fellow at City University of Hong Kong with
      <a href="https://www.cityu.edu.hk/stfprofile/jianxiluo.htm" target="_blank">Prof. Jianxi Luo</a>,
      where I pursue <em><a href="https://arxiv.org/pdf/2506.09755" target="_blank">Intelligent Design 4.0</a></em>,
      exploring how Foundation AI Models can support end-to-end engineering design creation.</p>

    <p>I co-founded <a href="https://pitchbook.com/profiles/company/490702-69#overview" target="_blank">DigiCodon</a>,
      where I served as CTO, building
      <a href="https://en.wikipedia.org/wiki/DNA_digital_data_storage" target="_blank">DNA digital data storage</a> technologies.</p>

    <p>
      <a href="https://scholar.google.com/citations?user=HhNfxUAAAAAJ&hl=en">Google Scholar</a> ·
      <a href="mailto:shuo.jiang@cityu.edu.hk">Email</a>
    </p>
  </div>

  <div class="page-image">
    <img src="/assets/profile.jpg" alt="profile photo">
  </div>

</div>
