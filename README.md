# Image-Captioning---GIT-model
Retrain Generative-Image-to-Text-model\
**We fine-tuned the [GIT Model](https://github.com/microsoft/GenerativeImage2Text) on non-dominant languages (Hausa, Thai, Kyrgyz ), and get prize of $3000 in this US-national competition.**
Clone original repository by run this code:

    !git clone https://github.com/microsoft/GenerativeImage2Text.git

### Goal
The repository is built for case competition [Data Analytics for good](https://krannert.purdue.edu/events/gscm-case-competition/), jointly sponsored by  the School of Management, Krenicki Center, Microsoft, SIL International, and INFORMS. Our team (Northeastern University) ranked **3rd of 172**.

![image](https://user-images.githubusercontent.com/64514218/213558310-8339a7d3-ea36-4c4c-9d77-997dbb31c3b2.png)

### Background
New text-to-image and image-to-text models (like Stable Diffusion) are taking the AI world by storm. One related task, which has direct business impact, is called "image captioning." This task takes an image as input and generates a text caption as output. Businesses can utilize image captioning models to:

Create HTML header and alt text content for images on their website, which boosts search engine scoring and user acquisition
Tag user-submitted images with relevant text descriptions for improved filtering and search
Ensure that images submitted to websites match tagged categories and/or do not violate terms of use (e.g., containing content in protected categories or content used to spread misinformation).

That's all great. However, there is a problem! Image captioning models only exist for a handful of the world's languages. If you operate a business in Nigeria, for example, your website or content might exist in 100's of languages. These businesses need linguistically diverse content to connect with their target market but supporting that kind of content puts them at a disadvantage in terms of search engine scoring, content tagging, and content filtering via image captioning.

### Data Source
The dataset is called Bloom and it's collected by [SIL](https://www.sil.org/).

Bloom is free, open-source software and an associated website [Bloom Library](https://bloomlibrary.org/), app, and services developed by [SIL International](https://www.sil.org/). Bloom’s primary goal is to equip non-dominant language communities and their members to create the literature they want for their community and children. Bloom also serves organizations that help such communities develop literature and education or other aspects of community development.

Hugging Face Repository: https://huggingface.co/datasets/sil-ai/bloom-captioning
![image](https://user-images.githubusercontent.com/64514218/211631984-ab6081c3-49cd-4d4e-b45d-7829d8c8431c.png)\
![image](https://user-images.githubusercontent.com/64514218/211632017-283354c9-74a6-408b-bcee-d09fcf8f08c9.png)

### Important Steps
<img width="800" alt="image" src="https://user-images.githubusercontent.com/64514218/213556105-b2a1d77b-aa09-451c-9557-3cba5223d38b.png">

<img width="800" alt="image" src="https://user-images.githubusercontent.com/64514218/213556253-87301b2a-5e5d-42e0-a7d2-42020bbe9750.png">

### Reference
[1]Jianfeng Wang, et al. GIT: A Generative Image-to-text Transformer for Vision and Language. arXiv preprint arXiv:2205.14100v4, 2022.\
[2] Lample, Guillaume, and Alexis Conneau. “Cross-lingual language model pretraining.” arXiv preprint arXiv:1901.07291 (2019).\
[3] Conneau et al. Unsupervised Cross-lingual Representation Learning at Scale. ACL 2020)
