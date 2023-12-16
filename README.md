 <!-- Replace your images here! -->
<div align="center">
  <div align="center">
      <a href="https://www.sysu-hcp.net/">
      <img src="Images/u-m_logo-horizontal-hex.png" width="400"/>
      </a>
    <a href="">
    <img src="Images/u-m_logo-horizontal-hex.png" width="400"/>
    </a>
  </div>
    </div> 

 
## [Summary/abstract of this projects.]

404 not found.
  
[![PyPI](https://img.shields.io/pypi/v/0.0.1)]()
[![docs](https://img.shields.io/badge/docs-latest-blue)](docs/index.md)
[![license](https://img.shields.io/github/license/HCPLab-SYSU/CausalVLR)](LICENSE)
[![open issues](http://isitmaintained.com/badge/open/HCPLab-SYSU/CausalVLR.svg)](https://github.com/HCPLab-SYSU/CausalVLR/issues)
[![issue resolution](http://isitmaintained.com/badge/resolution/HCPLab-SYSU/CausalVLR.svg)](https://github.com/HCPLab-SYSU/CausalVLR/issues)

[📘Documentation](docs/index.md) |
[🛠️Installation](docs/getting_started.md#installation) |
[👀Model Zoo](docs/method.md#model-zoo) |
[🆕Update News](docs/method.md#update-news) |
[🚀Ongoing Projects](docs/method.md#ongoing-projects) |
[🤔Reporting Issues](https://github.com/BioMed-AI-Lab-U-Michgan)


---
## <a id="table-of-contents">📄 Table of Contents </a>

- [📄 Table of Contents](#table-of-contents)
- [📚 Introduction](#introduction)
- [🚀 What's New](#whats-new)
- [👨‍🏫 Get Started](#get-started)
- [👀 Model Zoo](#model-zoo)
- [🎫 License](#license)
- [🖊️ Citation](#️c)
- [🙌 Contribution](#contribution)
- [🤝 Acknowledgement](#acknowledgement)
- [🏗️ Projects in BioMed-AI-Lab](#️hcp)


## <a id="introduction">📚 Introduction <a href="#table-of-contents">🔝</a> </a>

This is a project for xxx, corresponding to CVPR 202X, for more detailed information, please see on [Documentation](docs/index.md).

<div>
<p> </p>
</div>


<div align="center"><font size=5>
Framework Overview
</font>
</div>

![Image](Images/tutu.jpg)  

<details open>
<summary>Major features</summary>


- **Modular Design**
  
  Your methods.

- **Support of multiple tasks**
  
  Your settings.

- **State of the art**
  
  Your experiment results.

</details>


❗ **Note:** 

## <a id="whats-new">🚀 What's New <a href="#table-of-contents">🔝</a> </a>


### 🔥 **2023.12.12**.
- 10086 paper has been accepted in DREAMER2077

---

<div>
<br>

### ✨  **CaCo-CoT**-Towards CausalGPT: A Multi-Agent Approach for Faithful Knowledge Reasoning via Promoting Causal Consistency in LLMs


<div align=center>

![Image](projects/CaCo-CoT/CaCo_demo.gif)

</div>

<div align="center">

| Method   | ScienceQA| Com2sence | BoolQ     |
|:----:    |:-----:|:-----:|:-----:|
| GPT-3.5-turbo | 79.3 | 70.1|71.7|
| CoT | 78.4|63.6|71.1|
| SC-CoT | 84.0|66.0|71.4|
| C-CoT | 82.5|68.8|70.5|
| **CaCo-CoT** | **86.5(+2.5)**|**73.5(3.4)**|**73.5(1.8)**|
</div>


## <a id="get-started">👨‍🏫 Getting Started <a href="#table-of-contents">🔝</a> </a>
Please see Overview for the general introduction of <a hraf="">CausalVLR</a>.

For detailed user guides and advanced guides, please refer to our [documentation](docs/index.md), and here is the code structure of toolbox.

  
![Image](Images/framework.gif) 

### Installation

Please refer to Installation for [installation](docs/getting_started.md) instructions in documentation.

```
pip install XXX
```

### Running examples

For causal discovery, there are various running examples in the **test** directory.

For the implemented modules, we provide unit tests for the convenience of developing your own methods.

<h2 id="model-zoo">👀 Model Zoo <a href="#table-of-contents">🔝</a> </h2>

Please feel free to let us know if you have any recommendation regarding datasets with high-quality. We are grateful for any effort that benefits the development of causality community.

<div align="center">

|Task | Model | Benchmark |
| --- | ----- | --------- |
| Medical Report Generation |  VLCI     |    [IU-Xray](https://pubmed.ncbi.nlm.nih.gov/26133894/), [MIMIC-CXR](https://physionet.org/content/mimic-cxr/2.0.0/#files-panel)       |
| VQA |  CMCIR     |  [SUTD-TrafficQA](https://sutdcv.github.io/SUTD-TrafficQA/#/), [TGIF-QA](https://github.com/YunseokJANG/tgif-qa), [MSVD-QA](https://github.com/xudejing/video-question-answering), [MSRVTT-QA](https://github.com/xudejing/video-question-answering)        |
| Visual Causal Scene Discovery |  VCSR     |    [NExT-QA](https://github.com/doc-doc/NExT-QA), [Causal-VidQA](https://github.com/bcmi/Causal-VidQA), and [MSRVTT-QA](https://github.com/xudejing/video-question-answering)       |
| Model Generalization and Robustness |  Robust Fine-tuning     |    ImageNet-V2, ImageNet-R, ImageNet-Sketch, ObjectNet, ImageNet-A      |
| Causality-Aware Medical Diagnosis |  CAMDA     | [MuZhi](https://aclanthology.org/P18-2033.pdf), [DingXiang](https://github.com/fantasySE/Dialogue-System-for-Automatic-Diagnosis)        |
| Faithful Reasoning in LLMs |  CaCo-CoT     | [ScienceQA](https://scienceqa.github.io/), [Com2Sense](https://github.com/PlusLabNLP/Com2Sense), [BoolQ](https://github.com/google-research-datasets/boolean-questions)|
</div>

## <a id="license"> 🎫 License <a href="#table-of-contents">🔝</a> </a>

This project is released under the <a hraf="https://github.com/BioMed-AI-Lab-U-Michgan/Template/LICENSE">Apache 2.0 license</a>.


## <a id="citation"> 🖊️ Citation <a href="#table-of-contents">🔝</a> </a>

If you find this project useful in your research, please consider cite:   

``` 

``` 

## <a id="contribution"> 🙌 Contribution <a href="#table-of-contents">🔝</a> </a>


## <a id="acknowledgement"> 🤝 Acknowledgement <a href="#table-of-contents">🔝</a> </a>


### 🪐 The review paper here can provide some help


```

```

## <a id="hcp">🏗️ Projects in BioMed-AI-Lab<a href="#table-of-contents">🔝</a> </a>

- [HCP-Diffusion](https://github.com/7eu7d7/HCP-Diffusion)
  is a toolbox for Stable Diffusion models based on 🤗 Diffusers. It facilitates flexiable configurations and component support for training, in comparison with webui and sd-scripts.
