---
title: Challenge Description
feature_text: |
  ## Short-duration Speaker Verification (SdSV) Challenge 2021
  Evaluate New Technologies in Short Duration Senarios
feature_image: "https://picsum.photos/1300/400?image=866"
excerpt: "A Short Description of SdSV Challenge 2021"
aside: True
---

## Welcome to SdSV Challenge 2021! 

Following the success of the SdSV Challenge 2020, the SdSV Challenge 2021 focuses on systematic benchmark and analysis on varying degrees of phonetic variability on short-duration speaker recognition.

The SdSV Challenge 2021 consists of two tasks: 

- Task 1 is defined as speaker verification in a text-dependent mode where the lexical content (in both English and Persian) of the test utterances is also taken into consideration.
- Task 2 is defined as speaker verification in a text-independent mode with same- and cross-language trials.

The evaluation dataset of the challenge is drawn from the recently released multi-purpose DeepMine dataset[1]. The dataset has three parts and among them, Part 1 is used for TD-SV while Part 3 is for TI-SV.

[1] H. Zeinali, L. Burget, J. Cernocky, A multi-purpose and large scale speech corpus in Persian and English for speaker and speech recognition:  the DeepMine database, in:  Proc. ASRU 2019 The 2019 IEEE Automatic Speech Recognition and Understanding Workshop, 2019 (2019).

The Kaldi baseline recipe for both tasks can be found in [this link](/assets/sdsvc2020_kaldi_xvector_baseline.tar.gz). For running the baseline you should first download both VoxCeleb1 and VoxCeleb2 datasets. Then after downloading the challenge data, by putting the baseline code in the Kaldi egs directory you can run this code.

The full challenge evaluation plane version 1.0 can be found in [this link](/assets/SdSV_Challenge_2021_Evaluation_Plan.pdf). If you have any more questions regarding the challenge you can contact organizers via [sdsv.challenge\[at\]gmail.com](mailto:sdsv.challenge\[at\]gmail.com).

---
### Objective
The main purpose of this challenge is to encourage participants on building single but competitive systems, to perform analysis as well as to explore new ideas, such as multi-task learning, unsupervised/self-supervised learning, single-shot learning, disentangled representation learning, and so on, for short-duration speaker verification. The participating teams will get access to a train set and the test set drawn from the DeepMine corpus which is the largest public corpus designed for short-duration speaker verification with voice recordings of 1800 speakers. The challenge leaderboard is hosted at CodaLab.

---
### Schedule[modified]
<table border="0">
 <tr>
    <td>
    Jan 10, 2021
    </td>
    <td>
    Release of evaluation plan
    </td>
 </tr>
 <tr>
    <td>
    Jan 15, 2021
    </td>
    <td>
    Evaluation platform open
    </td>
 </tr>
 <tr>
    <td>
    Jan 15, 2021
    </td>
    <td>
    Release of train, development and evaluation sets
    </td>
 </tr>
 <tr>
    <td>
    Mar 20, 2021 
    </td>
    <td>
    Challenge deadline
    </td>
 </tr>
 <tr>
    <td>
    Mar 29, 2021 
    </td>
    <td>
    Interspeech submission deadline
    </td>
 </tr>
 <tr>
    <td>
    Aug 20 - Sep 03, 2021
    </td>
    <td>
    SdSV Challenge 2021 special session at Interspeech
    </td>
 </tr>
 <tr><td> &nbsp; </td></tr>
</table>


---
### Sponsors
<table border="0">
 <tr>
    <td>
	<a href="http://deepmine.ir/">Sharif DeepMine Ltd.</a> 
    </td>
    <td>
	<a href="http://deepmine.ir/"><img align="right" width="120" src="/images/deepmine.jpg"></a>
    </td>
 </tr>
</table>




















