# Deep Learning Challenges
This is the repo for the challenges of the **Artificial Neural Networks and Deep Learning** course at Polytechnic University of Milan, 2020/2021.

There are 3 kaggle competitions based on 3 different tasks that cover the most important topics learned during the course. We decided to use *Google Colab* to exploit the powerful GPU offered by *Google*. The main library used for building the neural network architectures is *TensorFlow* as explained throughout the course.

---

## Image Classification  ##

The goal of the challenge is to classify images of people wearing masks ( thanks Covid-19 ). The different labels are described below.
* All the people in the image are wearing a mask 
* No person in the image is wearing a mask
* Someone in the image is not wearing a mask.

#### Accuracy results from kaggle ####

| Model from scratch | Transfer learning model |
|------------|----------|
|0.895|0.955|

**Top 15% out of 192 participants.** 🎉

Our main ideas and their implementation can be found [here](https://github.com/calde97/Deep_Learning_Challenge/tree/main/first_challenge)

The kaggle competition can be found [here](https://www.kaggle.com/c/artificial-neural-networks-and-deep-learning-2020/)

---

## Image Segmentation  ##

The goal of the challenge is to perform precise automatic crop and weed segmentation for the agricoltural sector.

Input Image            |  Expected segmentation
:-------------------------:|:-------------------------:
<img src="second_challenge/images/Bipbip_haricot_im_00321.jpg" alt="Snow" width="250"> |  <img src="second_challenge/images/Bipbip_haricot_im_00321.png" alt="Snow" width="250"> 


Our main ideas and their implementation can be found [here](https://github.com/calde97/Deep_Learning_Challenge/tree/main/second_challenge)

The *codalab* competition can be found [here](https://competitions.codalab.org/competitions/27176)

---

## Visual question answering  ##

The goal of the challenge is to answer questions using the information provided by the corresponding image and question pair. 

<img src="third_challenge/images/vqa.png" alt="Snow" width="250">

*<b>Q</b>: Is the man's shirt blue?*
 *<b>A</b>: yes*

Our main ideas and their implementation can be found [here](https://github.com/calde97/Deep_Learning_Challenge/tree/main/third_challenge)

The *Kaggle* competition can be found [here](https://www.kaggle.com/c/anndl-2020-vqa)

**Top 9% out of 146 participants.** 🎉

---

 ## Project Members ##
 
 * [Juan Felipe Calderon](https://github.com/calde97)
 * [Marco Giuseppe Caruso](https://github.com/MarkNuar)
 * [Robert Stefano Chinga](https://github.com/robertsteven97)
