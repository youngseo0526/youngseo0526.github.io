---
permalink: /
title: "Youngseo Kim"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p style="font-size: 0.9rem; line-height: 1.7;">
I am a MS student at <a href="https://www.kaist.ac.kr/en/">KAIST</a>, advised by professor Junyoung Noh in the <a href="https://vml.kaist.ac.kr/home">Visual Media Lab</a>. My research focuses on Generative Models, with a particular interest in areas such as deepfake detection, NSFW content moderation, copyright protection, and privacy-preserving AI systems.
</p>

## Latest News

<ul style="font-size: 0.9rem; line-height: 1.7;">
  <li>APRIL 2026: 1 Paper accepted to <strong>SIGGRAPH 2026</strong></li>
</ul>

<ul style="font-size: 0.9rem; line-height: 1.7;">
  <li>FEB 2026: 1 Paper accepted to <strong>CVPR 2026</strong></li>
</ul>



## Selected Publications

<style>
  .selected-publications {
    margin-top: 1rem;
    font-size: 0.9rem;
    line-height: 1.45;
  }

  .selected-publication {
    display: flex;
    align-items: flex-start;
    gap: 2rem;
    margin: 1.75rem 0 3rem;
  }

  .selected-publication__thumbnail {
    flex: 0 0 170px;
    max-width: 170px;
    padding-top: 0.15rem;
  }

  .selected-publication__thumbnail img {
    display: block;
    width: 100%;
    height: auto;
    border: 0;
  }

  .selected-publication__title {
    color: #000;
    font-weight: 700;
  }

  .selected-publication__links {
    margin-top: 0.05rem;
  }

  .selected-publication__description {
    margin-top: 0.85rem;
    color: #000;
  }

  @media (min-width: 641px) {
    .selected-publications {
      width: min(900px, calc(100% + 8rem), calc(100vw - 3rem));
    }

    .selected-publication {
      gap: 1.5rem;
    }

    .selected-publication__thumbnail {
      flex-basis: 150px;
      max-width: 150px;
    }
  }

  @media (max-width: 640px) {
    .selected-publication {
      flex-direction: column;
      gap: 0.9rem;
      margin: 1.5rem 0 2.5rem;
    }

    .selected-publication__thumbnail {
      flex-basis: auto;
      max-width: 220px;
      width: 100%;
    }
  }
</style>

<div class="selected-publications">
  <div class="selected-publication">
    <a class="selected-publication__thumbnail" href="https://kwanyun.github.io/StyleID_page/" target="_blank" rel="noopener noreferrer">
      <img src="https://cdn-uploads.huggingface.co/production/uploads/639d445524af4747d8d2af52/1pTEZ88YvwnbDPlV_UqpM.jpeg" alt="StyleID overview thumbnail">
    </a>
    <div class="selected-publication__content">
      <div class="selected-publication__title">StyleID: A Perception-Aware Dataset and Metric for Stylization-Agnostic Facial Identity Recognition</div>
      <div>
        <a href="https://kwanyun.github.io/" target="_blank" rel="noopener noreferrer">Kwan Yun</a>,
        Changmin Lee,
        Ayeong Jeong,
        <strong>Youngseo Kim</strong>,
        Seungmi Lee,
        <a href="https://vml.kaist.ac.kr/main/people/person/1" target="_blank" rel="noopener noreferrer">Junyong Noh</a>
      </div>
      <div>SIGGRAPH 2026; TOG</div>
      <div class="selected-publication__links">
        <a href="https://kwanyun.github.io/StyleID_page/" target="_blank" rel="noopener noreferrer">project page</a>
        |
        <a href="https://arxiv.org/abs/2604.21689" target="_blank" rel="noopener noreferrer">paper</a>
        |
        <a href="https://github.com/kwanyun/StyleID" target="_blank" rel="noopener noreferrer">code</a>
        |
        <a href="https://huggingface.co/kwanY/styleid" target="_blank" rel="noopener noreferrer">model</a>
      </div>
      <br>
      <p class="selected-publication__description">
        Perception-aware dataset and metric for facial identity recognition that remains robust under stylized images, supporting identity similarity measurement, retrieval, and evaluation.
      </p>
    </div>
  </div>

  <div class="selected-publication">
    <a class="selected-publication__thumbnail" href="https://youngseo0526.github.io/X-AVDT/" target="_blank" rel="noopener noreferrer">
      <img src="https://seokhyeonhong.github.io/assets/images/research/kim2026xavdt.png" alt="X-AVDT overview thumbnail">
    </a>
    <div class="selected-publication__content">
      <div class="selected-publication__title">X-AVDT: Audio-Visual Cross-Attention for Robust Deepfake Detection</div>
      <div>
        <strong>Youngseo Kim</strong>,
        <a href="https://kwanyun.github.io/" target="_blank" rel="noopener noreferrer">Kwan Yun</a>,
        <a href="https://seokhyeonhong.github.io/" target="_blank" rel="noopener noreferrer">Seokhyeon Hong</a>,
        <a href="https://chacorp.github.io/sihuncha/" target="_blank" rel="noopener noreferrer">Sihun Cha</a>,
        <a href="https://sj0414.github.io/colette-koo/" target="_blank" rel="noopener noreferrer">Colette Suhjung Koo</a>,
        <a href="https://vml.kaist.ac.kr/main/people/person/1" target="_blank" rel="noopener noreferrer">Junyong Noh</a>
      </div>
      <div>CVPR 2026</div>
      <div class="selected-publication__links">
        <a href="https://youngseo0526.github.io/X-AVDT/" target="_blank" rel="noopener noreferrer">project page</a>
        |
        <a href="https://arxiv.org/abs/2603.08483" target="_blank" rel="noopener noreferrer">paper</a>
        |
        <a href="https://github.com/youngseo0526/X-AVDT" target="_blank" rel="noopener noreferrer">code</a>
        |
        <a href="https://huggingface.co/datasets/zaqxsw0526/MMDF" target="_blank" rel="noopener noreferrer">dataset</a>
        |
        <a href="https://www.youtube.com/watch?v=ctbPMKSGmGM" target="_blank" rel="noopener noreferrer">video</a>
      </div>
      <br>
      <p class="selected-publication__description">
        Robust deepfake detection method and cross-generator dataset by leveraging cross-attention features to capture audio-visual correlations.
      </p>
    </div>
  </div>

  <div class="selected-publication">
    <a class="selected-publication__thumbnail" href="https://diffsketch.github.io/" target="_blank" rel="noopener noreferrer">
      <img src="https://diffsketch.github.io/static/images/teaser5.PNG" alt="DiffSketch teaser thumbnail">
    </a>
    <div class="selected-publication__content">
      <div class="selected-publication__title">Stable Diffusion Feature Extraction for Sketching with One Example</div>
      <div>
        <a href="https://kwanyun.github.io/" target="_blank" rel="noopener noreferrer">Kwan Yun</a><sup>*</sup>,
        <strong>Youngseo Kim<sup>*</sup></strong>,
        <a href="https://seokg.github.io/" target="_blank" rel="noopener noreferrer">Kwanggyoon Seo</a>,
        <a href="https://vml.kaist.ac.kr/main/people/person/155" target="_blank" rel="noopener noreferrer">Chang Wook Seo</a>,
        <a href="https://vml.kaist.ac.kr/main/people/person/1" target="_blank" rel="noopener noreferrer">Junyong Noh</a>
      </div>
      <div>CVM 2025</div>
      <div class="selected-publication__links">
        <a href="https://diffsketch.github.io/" target="_blank" rel="noopener noreferrer">project page</a>
        |
        <a href="https://arxiv.org/pdf/2401.04362" target="_blank" rel="noopener noreferrer">paper</a>
        |
        <a href="https://github.com/kwanyun/diffsketch" target="_blank" rel="noopener noreferrer">code</a>
      </div>
      <br>
      <p class="selected-publication__description">
        Stable Diffusion feature extraction for sketching with one example, enabling diverse stylized sketch generation and efficient distilled sketch extraction.
      </p>
    </div>
  </div>
</div>
