---
title: "Text to PPT Builder"
excerpt: "Developed a tool that converts text input into well-structured PowerPoint presentations. The project automates slide creation, making content organization neatly & efficient.<br/><br/><img src='/images/proj1_textToPpt.png'>"
collection: portfolio
---

Developed a tool that converts text input into well-structured PowerPoint presentations using Mistral models. The project automates slide creation, making content organization neatly and efficient.

### Technologies used:
- Python (pptx library for rendering content in PPT)
- Mistral 7b Model

### Approach: Hierarchical Content Generation
- Topic Input: User provides an initial topic, which is used to generate slide titles through the model.
- Title Breakdown: For each generated slide title, the model is prompted to generate main topics.
- Content Expansion: For each main topic, the model generates detailed content, which is compiled into slides.

### Skills I gained:
- Python PPTX library.
- Running inference using quantization techniques.
- Prompt engineering.

### Link to project:
[Google Colab](https://colab.research.google.com/drive/1CshMtRMqz2Rz7TIBpAcrFtNTq9N3k0KA?usp=sharing)

### Example generated ppt:
[View File](https://docs.google.com/presentation/d/1zBhbRqZcri863_3wp-qUqukleYqw7rye/edit?usp=sharing&ouid=102047571824249781095&rtpof=true&sd=true)

### Feel free to contribute :)
