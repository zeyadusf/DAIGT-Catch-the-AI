<div align="center" id="top"> 
  
# DAIGT | CATCH THE AI
</div>

<p>
  I am pleased to present to you our graduation project that includes 9 member. "AI-generated media (Audio, Image, and Text) Detection"  or as we called it, <b>"Catch the AI"</b>.
  <br>
</p>
<p>
  <b>Catch The AI</b>: It is a complete system that enables you to have your account to save what you have recorded from previous media. With this system, you can display it on different media (text, audio, and image), each of which is self-contained.
<br>Register now to be able to catch the AI: </p>

- <b>Demo :</b> [catchtheai](https://www.catchtheai.tech/)<br>
- <b>Main Repo on github :</b> [private repo](https://github.com/romanyn36/Graduation-project) <br>
- <b> Can use all models <i> RoBERTa,DeBERTa,DistilBERT,BERT,FeedForwardWithRoBERTaDeBERTa</i> of DAIGT on SpaceHuggingface </b> :[DAIGT Space](https://huggingface.co/spaces/zeyadusf/DAIGT)
<br>

![image](https://github.com/zeyadusf/DAIGT-Catch-the-AI/assets/83798621/54fdb71b-0b30-4c4d-878b-e00819467468)

<hr>

## :dart: About ##

<div align="center" > 

# Detect AI Generated Text (DAIGT).

 </div>

This is part of our graduation project, I was working on this project on the Detect AI-Generated Text *DAIGT* model. <br>about this repo Here I present to you everything related to my work on the text model, from the stages of data collection to testing some models to the final model...
 
 
### ↪️ Problem definition 

<!--p>One of the most important goals of LLMs like *GPT 3.5, GPT 4, Gemini,...*  is to create text that resembles what a human writes. 
  With the wide and many uses of these models, it will become difficult to differentiate between these essays, 
  so the <b> CATCH THE AI team </b> decided to come up with a solution on the scene.</p>-->

  &nbsp; &nbsp; &nbsp;One of the goals of Large Language Models “LLMs” is to create texts similar to what humans write and after the many LLMs currently available and ready for use, such as *GPT 4, Gemini, etc*. The open-source models that you can train on your data and your task, such as *Mistral*. And as we use them a lot in many tasks, it will become difficult to differentiate between these texts and their authors.<br><br> &nbsp; &nbsp; &nbsp;This will affect many things, such as Students using LLMs for homework; this will affect their academic level, and it will be difficult for the teacher to determine the level of his students, and his estimation of these students will be wrong. Another example that we encountered during the data collection stage is the lack of trust in articles. We always wondered who wrote this article. If we consider that the one who wrote it was one of the LLMs, and our suspicion was wrong, this reduces the quality of the data that the model will be trained on.

These are some of the simple examples and cases in which you want the DAIGT model to intervene to help you, and in “<b>Catch The AI</b>”.

<br>

### ↪️ DAIGT Solution 

 &nbsp; &nbsp; &nbsp;After many stumbles and experiments to obtain data and a suitable architecture capable of achieving our goals of building a robust and generalized model. We trained many models, including <b>from scratch</b> *Bi-LSTM, Conv1D, etc.*, and we used different <b>tokenizers</b> in them, such as *ELMo model, BERT-tokenizer* and <b>pre-trained models</b> such as *Mistral-7B, BERT, DistilBERT, RoBERTa, and DeBERTa.* <br>
* Here is an explanation of the latest architecture:<br>
 &nbsp; &nbsp; &nbsp;In the DAIGT model, we relied on **two models** that proved their efficiency in some of the data that they were not trained on **RoBERTa and DeBERTa**. Therefore, we decided to use them together and create an **ensemble technique** through the **Feedforward Layer**  '*ReLU* activation function', consisting of *32 neurons* that were trained on the outputs coming out of *RoBERTa and DeBERTa*.

<div align="center" > 

![image](https://github.com/zeyadusf/DAIGT-Catch-the-AI/assets/83798621/53fde6f0-5f3f-41ea-8dab-8bd9bab4ae87)
![image](https://github.com/zeyadusf/DAIGT-Catch-the-AI/assets/83798621/df578fc7-8e5b-4a94-9a2c-ab7ee877d95f)
</div>

## ❓ How can you catch Ai-Generated Text?


<b> ⏲️ *Time-Line* :</b> [Timeline ](https://github.com/zeyadusf/DAIGT-Catch-the-AI/tree/main/timeline%20of%20work)  &nbsp;All **results** and **notebooks** can be accessed here.<br>

<b> 🗞️ *All details about final version is here*: </b>
[Documant of text model](https://github.com/zeyadusf/DAIGT-Catch-the-AI/blob/main/Document%20of%20Text%20Model.pdf)<br>

<b> 🔗*Links of Notebooks and dataset* 'final version':<br></b>

> Data was collected from different areas on Kaggle and HuggingFace, and you can access it through this link:<br>
- [DAIGT | Catch The AI](https://www.kaggle.com/datasets/zeyadusf/daigt-all-data-for-competition) 
- [DAIGT | EDA](https://www.kaggle.com/code/zeyadusf/daigt-eda)<br>
- [DAIGT | BERT](https://www.kaggle.com/code/zeyadusf/daigt-bert)<br>
- [DAIGT | DistilBERT](https://www.kaggle.com/code/zeyadusf/daigt-distilbert)<br>
- [DAIGT | RoBERTa](https://www.kaggle.com/code/zeyadusf/daigt-roberta)<br>
- [DAIGT | DeBERTa](https://www.kaggle.com/code/zeyadusf/daigt-deberta)<br>
- [DAIGT | Model Analysis](https://www.kaggle.com/code/zeyadusf/daigt-models-analysis)
- You can use all of them or retrain them. You will find them on my account on **HuggingFace**: [zeyadusf](https://huggingface.co/zeyadusf)


<hr>

<div align="center">


# CATCH THE AI Team 

<p align="left">We did not just work as a team, but we were a family. 
  These people are truly skilled and creative. Follow them and wait for their wonderful projects, from which they learn a lot and benefit a lot of people.❤️ </p>

<table>
  <tr>
    <td><a href="https://github.com/romanyn36">Romani Nasrat Shawqi</a></td>
    <td><a href="https://github.com/Abdalla312">Abdalla Mohammed</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/mohannadAyman">Mohannad Ayman</a></td>
    <td><a href="https://github.com/abdeldayem02">Mohammed Abdeldayem</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhmedAboElkassem">Ahmed Abo-Elkassem</a></td>
    <td><a href="https://github.com/SaraReda8">Sara Reda</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/goodprogrrammer">Reham Mostafa</a></td>
    <td><a href="https://github.com/rawanazizsaad">Rawan Aziz</a></td>
  </tr>
</table>
</div>

<hr>

## 📞 Contact :

<p align="center">
  <a href="mailto:ziayd.usf@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-E0331F?style=flat&logo=gmail&logoColor=white" alt="Gmail" />
</a>
 <a href="https://www.facebook.com/ziayd.yosif" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-1877F2?style=flat&logo=facebook&logoColor=white" alt="Facebook" />
</a>
<a href="https://www.instagram.com/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-zeyadusf-white?style=flat&logo=instagram&logoColor=#E65468" alt="Instagram" />
</a>

<a href="https://www.linkedin.com/in/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />

  <a href="https://github.com/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-403E3E?style=flat&logo=github&logoColor=white" alt="GitHub" />
</a>

  <a href="https://www.kaggle.com/zeyadusf" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-0077B5?style=flat&logo=kaggle&logoColor=white" alt="kaggle" />
</a>

</p>


ا
