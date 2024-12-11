---
title: "PUMC-Colposcopy report interpretation assistant"
collection: projects
type: "med-llm"
permalink: /projects/assistant
venue: "HKUST(GZ) Medical Data Inteligence Lab, "
date: 2024-11-01
location: "HKUST(GZ)"
---

<p float="left" style="display: flex;justify-content:center; align-items: center;">
  <img src="/images/assistant_architecture.jpeg" width="100%" />
</p>

## Introduction

This project, in collaboration with Peking Union Medical College (北京协和医学院), aims to develop an intelligent medical system focused on interpreting colposcopy reports, independently completed by me. The primary goal of the project is to help patients better understand their examination reports and provide diagnostic support to doctors, thus reducing doctor-patient pressure and enhancing clinical efficiency. The system’s technical architecture and features are composed of the following key modules.

<small> if you are interested in this project or want to try it out, please contact us by email📮: <czhangcn@connect.ust.hk> .</small>

## Features

**1. LLM & Multimodal Recognitions**

Users can upload their colposcopy reports **(pdf, txt, images)** through mobile or desktop platforms. The system employs a multimodal large language model (MLLM) for text extraction and image information processing. Utilizing Prompt Engineering techniques, the system translates complex medical terminology into clear, accessible language, helping patients to understand their health status more easily, and alleviating the pressure on doctors during consultations.


<div>
  <p float="left" style="display: flex;justify-content:center; align-items: center;">
    <img src="/images/diagnostic_assistant1.jpeg" width="25%" style="padding:10px;" />
    <img src="/images/diagnostic_assistant2.jpeg" width="25%" style="padding:10px" />
    <img src="/images/diagnostic_assistant3.jpeg" width="25%" style="padding:10px" />
    <p style="text-align:center"><small style="font-weight: bolder;">Using mobile phone take pictures and interpret reports</small></p>
  </p>
  
</div>


**2. Colposcopy Medical Knowledge Base with RAG**

A colposcopy knowledge base, based on data from Peking Union Medical College, has been established. Through Retrieval-Augmented Generation (RAG), the system precisely retrieves authoritative medical knowledge from knowledge graphs and vector databases, providing a scientific basis for diagnosis.

<div>
  <p float="left" style="display: flex;justify-content:center; align-items: center;">
    <img src="/images/assistant_RAG.jpeg" width="75%" style="padding:10px;" />
    <p style="text-align:center"><small style="font-weight: bolder;">RAG from colposcopy knowledge base</small></p>
  </p>
</div>


**3. CoT (Chain of Thought) Reasoning**

The system incorporates Chain of Thought (CoT) reasoning methods aligned with doctors’ diagnostic logic, providing a complete workflow from report interpretation to diagnostic recommendations. This closed-loop process for information parsing and decision support enables the system to generate clinically compliant explanations and aid doctors in their diagnostic decisions.

<div>
  <p float="left" style="display: flex;justify-content:center; align-items: center;">
    <img src="/images/assistant_cot.jpeg" width="75%" style="padding:10px;" />
    <p style="text-align:center"><small style="font-weight: bolder;">CoT is used for in-depth analysis of the problem</small></p>
  </p>
</div>

## Evaluation

Here is a simple evaluation comparing with gpt-4o which shows that our interpretation works better. On the left are the gpt-4o results, and on the right are our results.Each criteria is scored on a scale of 0-10, and the scoring criteria are:
- **Comprehensiveness**: How much detail does the answer provide to cover all aspects and details of the question? 
- **Diversity**: How diverse and rich are the answers in providing different perspectives and insights on issues? 
- **Empowerment**: To what extent do the answers help the reader understand and make informed judgments about the topic? 
- **Directness**: How does the answer address the problem concretely and clearly?

<div>
  <p float="left" style="display: flex;justify-content:center; align-items: center;">
    <img src="/images/gpt4o-interpretation.jpeg" width="40%" style="padding:10px;" />
    <img src="/images/ours_interpretation.jpeg" width="35%" style="padding:10px" />
    <p style="text-align:center"><small style="font-weight: bolder;">Report interpretation results</small></p>
  </p>
</div>

<div>
  <p float="left" style="display: flex;justify-content:center; align-items: center;">
    <img src="/images/gpt4o_evaluation.jpeg" width="40%" style="padding:10px;" />
    <img src="/images/ours_evaluation.jpeg" width="40%" style="padding:10px" />
    <p style="text-align:center"><small style="font-weight: bolder;">Evaluation results</small></p>
  </p>
</div>


## Conclusion

This system not only improves patient comprehension of report content but also significantly alleviates the workload on doctors, providing a more efficient and intelligent solution for colposcopy examination and subsequent clinical care.