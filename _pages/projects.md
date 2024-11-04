---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
<!-- 
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
{% include base_path %} -->

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

---

<style>
.project {
  display: flex;
  align-items: flex-start;
  margin-bottom: 20px;
}

.project-image {
  position: relative;
  width: 30%; /* 可以根据需要调整图片大小 */
  margin-right: 20px;
}

.project-description {
  position: relative;
  width: 70%; /* 可以根据需要调整图片大小 */
  margin-right: 20px;
}

.project-image img {
  width: 100%;
  border-radius: 8px;
}

.project-label {
  position: absolute;
  top: 8px;
  left: 8px;
  background-color: #003366; /* 标签背景色 */
  color: #ffffff;
  padding: 4px 8px;
  border-radius: 4px;
  font-size: 0.8em;
}

.project-description h3 {
  position: relative;
  margin-top: 0;
  font-size: 1.0em;
}

.project-description p {
  position: relative;
  margin: 8px 0;
  font-size: 0.9em;
}

.project-description ul {
  margin: 8px 0;
  padding-left: 20px;
  font-size: 0.8em;
}

.project-description a {
  color: #034b94;
  text-decoration: none;
}
</style>


<div class="project">
  <div class="project-image">
    <img src="/images/architecture.jpg" alt="Project Image">
  </div>
  <div class="project-description">
    <h3>
        <a href="/projects/annotation">Semi-automatic intelligent labeling</a>
        <a href="https://github.com/HKUSTMDI/mdi-sam-server" target="_blank">
            <img src="https://img.shields.io/github/stars/HKUSTMDI/mdi-sam-server?style=social" alt="GitHub stars">
        </a>
    </h3>
    <p>This is the first open-source project applying the SAM model to real-time annotation of whole slide images (WSI) in the medical field which I developed. This project utilizes models from the SAM family (e.g., SAM, SAM2, etc.) to assist medical personnel in annotating WSI case slides, significantly improving the speed and efficiency of medical researchers' annotation work. It provides accurate and reliable data for model training.</p>
    <ul>
      <li>The first open-source project applying the SAM model to real-time annotation WSI</li>
      <li>Surpport SAM family</li>
      <li>significantly improving the speed and efficiency of annotation work</li>
    </ul>
  </div>
</div>

---

<div class="project">
  <div class="project-image">
    <img src="/images/chatbot_2.jpeg" alt="Project Image">
  </div>
  <div class="project-description">
    <h3>
        <a href="/projects/med-llm">Medical MLLM Agent </a>
    </h3>
    <p>Medical MLLM Agent (Project in Progress), this service is a collaboration with Guangzhou LBP Medicine Science & Technology Co., Ltd.(688393.SH). Based on the MLLM Agent, it aims to complete multimodal retrieval and generation of a case library. It can search patient case records, diagnostic images, and other medical records, and provide MLLM consultation, offering reliable diagnostic assistance to medical personnel and patients. We are still conducting this research.</p>
  </div>
</div>

---

<div class="project">
  <div class="project-image">
    <img src="/images/data-manager.jpeg" alt="Project Image">
  </div>
  <div class="project-description">
    <h3>
        <a href="/projects/data-manager">Medical Data Manager </a>
    </h3>
    <p>This is the medical data management platform I developed, supporting storage and management operations for medical data. The specific features are as follows:</p>
    <ul>
      <li>Data upload, download, and modification management.</li>
      <li>Whole slide image（WSI） and regular image preview.</li>
      <li>🌟 Initiate data-driven deep learning tasks.</li>
    </ul>
  </div>
</div>

---

<div class="project">
  <div class="project-image">
    <img src="/images/redunet_result.png" alt="Project Image">
  </div>
  <div class="project-description">
    <h3>
        <a href="/projects/annotation">MDI Data Evaluation </a>
    </h3>
    <p>This project aims to briefly evaluate the annotation results of doctors on a cell electron microscope dataset using various methods, including feature information calculation, training, and data screening, to improve the quality and accuracy of the dataset annotations.</p>
  </div>
</div>

---