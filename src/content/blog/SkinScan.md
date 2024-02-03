---
layout: ../../layouts/LayoutBlogPost.astro
title: "Skin Scan - AI & ML"
description: "The background regarding my Skin Scan project."
pubDate: 2023-02-2
category: "intro"
---

Skin scan was a proof of concept application, that explored how ML and AI can be used in medical applications. <br /> 
<br /> 
<br /> 
I created Skin Scan, alongside my group members as a part of WPI's Great Problems Seminar Class, wherein students are tasked with "solving problems of global importance". The class is a semester long class, where first year students are "immerse(d) into university-level research and introduces them to the project-based curriculum at WPI."<br /> 
<br />
<br /> 

For our group, our focus was regarding the inequitity in Melanona diagnosis, specifcally regarding Black Americans. We found that there was a 25% difference between the survial rate between Black Americans and their white counterparts when it came to Melanoma (from 92% 5 year survival rate for White Americans, to 67% for Black Americans.) <br />
<br /> 
<br /> 

We found that this was mainly due to three factors:<br /> 
    <br /> 
    - A lack of doctor's educations, specifcally regarding darker skin tones<br /> 
    - Bias in diagnostics tools used by doctors and patients<br /> 
    - A later diagnosis period for Black Americans compared to White Americans.<br />
    <br /> 
Therefore, we decided to develop Skin Scan as a possible solution to this problem.<br /> 
<br /> 
<br /> 

Skin Scan used Machine Learning (specifcally a CNN model), to create a model to compare the differences between Cancerous and Non Cancerous skin samples. This model was trained, then attached to a web-front end (Anvil), so users could submit photos of their skin, then have the model "grade" whether it was Cancerous or not.<br /> 
<br /> 
<br /> 

Example of a Cancerous Sample
![Alt](/Images/Skin%20Scan%20Cancerous.jpeg)
<br />
<br />

Example of a Non Cancerous Sample
![Alt](/Images/Skin%20Scan%20Noncancerous.jpeg)
<br /> 
<br /> 

Furthermore, Skin Scan incorportated AI Large Language Models (specifically LLama2, via Ollama and LangChain incorportation) to act as an educational chatbot, wherein users could ask questions such as "What are some actions that I can take to prevent melanoma?", and "What are the five warning signs related to melanoma?" 

<br /> 
<br /> 

![Alt](/Images/SkinScanAIChat.jpeg)


