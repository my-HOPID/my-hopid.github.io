# HOPID: Heterogeneous Prompt-Guided Entity Inferring and Distilling for Scene-Text Aware Cross-modal Retrieval

![alt text](hopid.png)

## Abstract
In cross-modal retrieval, comprehensive image understanding is vital while the scene text in images can provide fine-grained information to understand visual semantics. Recent works try to make full use of scene text, but they still suffer from the semantic ambiguity of independent scene text. To address this issue, we propose a novel heterogeneous prompt-guided entity inferring and distilling network to explore the inherent connection of scene text across different modalities and learn property-centric scene text representation. Specifically, we first introduce the discriminative entity inferring module which infers the discriminative entity words in captions to build text prompt. Then we align these words with the scene text in images to narrow the cross-modal gap via heterogeneous prompt learning. Simultaneously, we enhance the contextual information of scene text by locating them in images through visual prompt to alleviate local noise. Furthermore, to secure a robust scene text representation, we design a perceptive entity distilling module that distills the beneficial information of scene text at a fine-grained level. Extensive experiments show that the proposed method significantly outperforms existing approaches on two public cross-modal retrieval benchmarks.

## Task Introduction

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/_intro.png" alt="Introduction Image" style="width: 100%;">
        <figcaption>Introduction Image</figcaption>
    </figure>
    <figure>
        <img src="images/new_visualization.png" alt="New Visualization" style="width: 100%;">
        <figcaption>New Visualization</figcaption>
    </figure>
</div>

### Semantic Ambiguity Issue

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/new_visualization.png" alt="New Visualization" style="width: 100%;">
        <figcaption>New Visualization</figcaption>
    </figure>
</div>

## Attention Maps

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/keshihua.png" alt="t-SNE Image" style="width: 100%;">
        <figcaption>t-SNE Image</figcaption>
    </figure>
</div>

## T-SNE Visualization

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/_t_sne.jpg" alt="t-SNE Visualization" style="width: 80%;">
        <figcaption>t-SNE Visualization</figcaption>
    </figure>
</div>

## TEXT→IMG Retrieval (1/2) 📄🔍🎆
![TEXT→IMG Retrieval (1/2)](images/i2t_1.png)

## TEXT→IMG Retrieval (2/2) 📄🔍🎆
![TEXT→IMG Retrieval (2/2)](images/i2t_2.png)

## IMG→TEXT Retrieval (1/2) 🎆🔍📄
![IMG→TEXT Retrieval (1/2)](images/t2i_1.png)

## IMG→TEXT Retrieval (2/2) 🎆🔍📄
![IMG→TEXT Retrieval (2/2)](images/t2i_2.png)