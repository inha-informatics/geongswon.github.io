---
layout: post
title: Flowtron: an Autoregressive Flow-based Network for Text-to-Mel-spectrogram Synthesis
tags: [speech synthesis, style transfer, paper review]
image: '/images/posts/flowtron.PNG'
---




##### Introduction

##### Related Work

* 기존 TTS의 접근 방식
> 사람과 유사한 결과를 얻은 접근법은 tesxt에서 acoustic features를 합성하는데 초점을 맞추고, non-textual information은 black box 취급함
> non-textual information에 대한 label이 부족하기 때문에 이를 다루기 위하여

1.  이와 상관관계가 있다고 생각하는 audio를 기반으로 hand-engineered statistics을 찾는 접근법도 존재

: 이 접근법은 기본 주파수와 같이 training data로부터 직접 계산할 수 있는 audio statistics에 대한 발음이 조건화 됨

 → 논문 저자가 대략적으로 예상하고자 하는 통계는 선행기술에 따라 결정되어야 하고, 
 이 통계에 대한 target value는 합성 전에 결정되어야 함
 
2.  prosody나 global style에 대한 latent embedding을 학습 

: a bank of embeddings나 a latent embedding space of prosody는 unlabelled data로부터 학습됨

 → latent variables를 다루는 것은 expressive characteristics of speech에 대한 coarse control만 제공
 
3. unsupervised 방법으로 학습된 latent embeddings과 engineered statistics을 결합 

: 발음을 audio statistics과 reference acoustic representation으로부터 도출된 latent embedding of acoustic features 모두에서 조건화

 → 이 방법 역시 합성하기 전에 이러한 통계가 결정되어야 함

##### Graphic design

> Graphic design is the paradise of individuality, eccentricity, heresy, abnormality, hobbies, and humors. - George Santayana

Vim te case nihil oblique, has partem interpretaris ne, ad admodum accusamus nam. Usu utinam dissentias referrentur ne, vim accusam voluptua pertinacia no. Est no posse utinam inermis, brute errem mentitum et ius, te prompta albucius quo. In pro simul soleat regione.

![alt](https://images.unsplash.com/photo-1433785567155-bf5530cab72c?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&w=1080&fit=max&s=1348aea714b9493fa61a09a8c01113e6)


