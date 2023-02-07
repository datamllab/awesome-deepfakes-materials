# Awesome-LLM-Generated-Text-Detection-Materials [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but probably biased and incomplete, list of LLM-generated text detection resources.

If you want to contribute to this list, feel free to pull a request. Also you can contact [Ruixiang Tang](https://www.ruixiangtang.net/) from the [Data Lab](http://faculty.cs.tamu.edu/xiahu/) at Rice University through email: rt39@rice.edu.


## What is LLM-generated Text Detection?

The emergence of large language models (LLMs) has resulted in the production of LLM-generated texts that is highly sophisticated and almost indistinguishable from texts written by humans. However, this has also sparked concerns about the potential misuse of such texts, such as spreading misinformation and causing disruptions in the education system. This repro aims to provide an overview of existing LLM-generated text detection techniques and enhance the control and regulation of language generation models.

we group exitsting methods into two categories: black-box detection and white-box detection. Black-box detection methods are limited to API-level access to LLMs. They rely on collecting text samples from human and machine sources, respectively, to train a classification model that can be used to discriminate between LLM- and human-generated texts. An alternative is white-box detection, in this scenario, the detector has full access to the LLMs and can control the model's generation behavior for traceability purposes. In practice, black-box detectors are commonly constructed by external entities, whereas white-box detection is generally carried out by LLM developers.

## Table of Contents

* [Black-Box Detection](#Black-Box Detection)
  * [Generation Papers](#generation-papers)
  * [Generation Codes](#generation-codes)
  * [Detection Papers](#detection-papers)
  * [Detection Codes](#detection-codes)
  * [Datasets and Challenges](#datasets-and-challenges)
  * [General Online Articles of Deepfake Videos](#general-online-articles-of-deepfake-videos)
* [White-Box Detection](#White-Box Detection)
  * [Papers Mainly on Detection](#papers-mainly-on-detection)
  * [Codes Mainly on Detection](#codes-mainly-on-detection)
  * [General Online Articles of Neural Fake News](#general-online-articles-of-neural-fake-news)
  


## Black-Box Detection
## White-Box Detection


### Generation Papers
* [HeadOn: Real-time Reenactment of Human Portrait Videos](https://arxiv.org/abs/1805.11729)
* [Face2Face: Real-time Face Capture and Reenactment of RGB Videos](https://web.stanford.edu/~zollhoef/papers/CVPR2016_Face2Face/paper.pdf)
* [Synthesizing Obama: Learning Lip Sync from Audio](https://grail.cs.washington.edu/projects/AudioToObama/siggraph17_obama.pdf)


### Generation Codes
* [FaceSwap](https://github.com/deepfakes/faceswap)
* [Faceswap-GAN](https://github.com/shaoanlu/faceswap-GAN)
* [faceswap-pytorch](https://github.com/Oldpan/Faceswap-Deepfake-Pytorch)
* [faceswap-pytorch2](https://github.com/jinfagang/faceswap_pytorch)
* [DeepFaceLab](https://github.com/iperov/DeepFaceLab)
* [face2face](https://github.com/datitran/face2face-demo)
* [Synthesizing Obama](https://github.com/supasorn/synthesizing_obama_network_training)
 

### Detection Papers

* Review and General Papers
  * [Deep Learning for Deepfakes Creation and Detection](https://arxiv.org/abs/1909.11573)
  * [DeepFakes and Beyond: A Survey of Face Manipulation and Fake Detection](https://arxiv.org/abs/2001.00179)
  * [Media Forensics and DeepFakes: an overview](https://arxiv.org/abs/2001.06564)
  * [Will Deepfakes Do Deep Damage?](https://cacm.acm.org/magazines/2020/1/241708-will-deepfakes-do-deep-damage/fulltext)


* Relying on Artifacts
  * [Exposing DeepFake Videos By Detecting Face Warping Artifacts](https://arxiv.org/abs/1811.00656)
  * [Exposing Deep Fakes Using Inconsistent Head Poses](https://arxiv.org/abs/1811.00661)
  * [In Ictu Oculi: Exposing AI Generated Fake Face Videos by Detecting Eye Blinking](https://arxiv.org/abs/1806.02877)
  * [Exploiting Visual Artifacts to Expose Deepfakes and Face Manipulations](https://ieeexplore.ieee.org/document/8638330)
  * [Protecting World Leaders Against Deep Fakes](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Media%20Forensics/Agarwal_Protecting_World_Leaders_Against_Deep_Fakes_CVPRW_2019_paper.pdf)

* Binary Classifiers
  * [Capsule-Forensics: Using Capsule Networks to Detect Forged Images and Videos](https://arxiv.org/abs/1810.11215)
  * [FaceForensics++: Learning to Detect Manipulated Facial Images](https://arxiv.org/abs/1901.08971)
  * [Deepfake Video Detection Using Recurrent Neural Networks](https://engineering.purdue.edu/~dgueraco/content/deepfake.pdf)

* Generalization performance
  * [Towards Generalizable Forgery Detection with Locality-aware AutoEncoder](https://arxiv.org/abs/1909.05999)
  * [ForensicTransfer: Weakly-supervised Domain Adaptation for Forgery Detection](https://arxiv.org/abs/1812.02510)
  * [Face X-ray for More General Face Forgery Detection](https://arxiv.org/abs/1912.13458)
  * [On the generalization of GAN image forensics](https://arxiv.org/abs/1902.11153)
  * [Fake Face Detection Methods: Can They Be Generalized?](https://ieeexplore.ieee.org/document/8553251)


### Detection Codes
* [Deepfake detection for the masses](https://github.com/Baukebrenninkmeijer/FakeFynder-Hackathon-for-Good-2019)
* [Exposing DeepFake Videos By Detecting Face Warping Artifacts](https://github.com/danmohaha/CVPRW2019_Face_Artifacts)
* [Vulnerability assessment and detection of Deepfake videos](https://gitlab.idiap.ch/bob/bob.report.deepfakes)


### Datasets and Challenges

* [FaceForensics++](https://github.com/ondyari/FaceForensics)
* [Celeb-DF](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html)
* [Deepfakes detection challenge by Facebook, Microsoft, etc.](https://ai.facebook.com/blog/deepfake-detection-challenge?from=timeline&isappinstalled=0)
* [DeepfakeTIMIT](https://www.idiap.ch/dataset/deepfaketimit)
* [Kaggle Deepfake Detection Challenge](https://www.kaggle.com/c/deepfake-detection-challenge/overview?utm_medium=email&utm_source=intercom&utm_campaign=deepfake-competition-2019)




### General Online Articles of Deepfake Videos

* [Deepfake: The Good, The Bad and the Ugly - Medium](https://medium.com/twentybn/deepfake-the-good-the-bad-and-the-ugly-8b261ecf0f52)
* [DeepFakes: AI-powered deception machines](http://www.computervisionblog.com/2018/05/deepfakes-ai-powered-deception-machines.html)
* [Exploring DeepFakes - KDnuggets](https://www.kdnuggets.com/2018/03/exploring-deepfakes.html)
* [Family fun with deepfakes. Or how I got my wife onto the Tonight Show - Towards Data Science](https://towardsdatascience.com/family-fun-with-deepfakes-or-how-i-got-my-wife-onto-the-tonight-show-a4454775c011)
* [Deepfake propaganda is not a real problem - The Verge](https://www.theverge.com/2019/3/5/18251736/deepfake-propaganda-misinformation-troll-video-hoax)





## Deepfake Texts

### Papers Mainly on Detection
* [GLTR: Statistical Detection and Visualization of Generated Text](https://arxiv.org/abs/1906.04043)
* [Defending Against Neural Fake News](https://arxiv.org/abs/1905.12616)
* [CTRL: A Conditional Transformer Language Model for Controllable Generation](https://arxiv.org/abs/1909.05858)


### Codes Mainly on Detection
* [GLTR: Giant Language Model Test Room](https://github.com/HendrikStrobelt/detecting-fake-text)
* [Grover](https://github.com/rowanz/grover)
* [CTRL - A Conditional Transformer Language Model for Controllable Generation](https://github.com/salesforce/ctrl)

### General Online Articles of Neural Fake News
* [OpenAI: Please Open Source Your Language Model](https://thegradient.pub/openai-please-open-source-your-language-model/)
* [OpenAI Shouldn’t Release Their Full Language Model](https://thegradient.pub/openai-shouldnt-release-their-full-language-model/)
* [Better fact-checking for fake news](http://news.mit.edu/2019/better-fact-checking-fake-news-1017)




## Deepfake Voices

### Papers Mainly on Generation
* [Tacotron: Towards End-to-End Speech Synthesis](https://arxiv.org/abs/1703.10135)
* [Neural Voice Cloning with a Few Samples](https://arxiv.org/abs/1802.06006)
* [Deep Voice 3: Scaling Text-to-Speech with Convolutional Sequence Learning](https://arxiv.org/abs/1710.07654)
* [Deep Voice 3: Efficiently Trainable Text-to-Speech System Based on Deep Convolutional Networks with Guided Attention](https://arxiv.org/abs/1710.08969)


### Codes Mainly on Generation
* [deep-voice-conversion](https://github.com/andabi/deep-voice-conversion)
* [Tacotron](https://github.com/keithito/tacotron)
* [mimic2](https://github.com/MycroftAI/mimic2)
* [Neural Voice Cloning with Few Samples](https://github.com/Sharad24/Neural-Voice-Cloning-with-Few-Samples)
* [Deepvoice3_pytorch](https://github.com/r9y9/deepvoice3_pytorch)
* [Real-Time Voice Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning)
* [DeepFake Audio Detection](https://github.com/dessa-public/fake-voice-detection)



### General Online Articles of Deepfake Voices
* [You can now speak using someone else’s voice with Deep Learning](https://towardsdatascience.com/you-can-now-speak-using-someone-elses-voice-with-deep-learning-8be24368fa2b)
* [A Voice Deepfake Was Used To Scam A CEO Out Of $243,000](https://www.forbes.com/sites/jessedamiani/2019/09/03/a-voice-deepfake-was-used-to-scam-a-ceo-out-of-243000/)
