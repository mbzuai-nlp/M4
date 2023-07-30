# M4: Multi-generator, Multi-domain, and Multi-lingual Black-Box Machine-Generated Text Detection

Large language models (LLMs) are becoming mainstream and easily accessible, ushering in an explosion of machine-generated content over various channels, such as news, social media, question-answering forums, educational, and even academic contexts. Recent LLMs, such as ChatGPT and GPT-4, generate remarkably fluent responses to a wide variety of user queries. The articulate nature of such generated text makes LLMs attractive for replacing human labor in many scenarios. However, this has also resulted in concerns regarding their potential misuse, such as spreading misinformation and causing disruptions in the education system. Since humans perform only slightly better than chance when classifying machine-generated vs. human-written text, there is a need to develop automatic systems to identify machine-generated text with the goal of mitigating its potential misuse. 

We mainly:
* construct dataset M4
* leverage diverse features including semantic, stylistic, and statistical based on token prediction probability using GPT-2 (GLTR) and features used for news veracity detection (NELA) to distinguish human-written vs. machine-generated text. 
* analyze the evaluation results from various dimensions: (1) the performance of different detectors across different domains given a specific generator, (2) the performance of different detectors across different generative models for a specific domain, and (3) the impact on the performance by interactions of different domains and generators in a multilingual setting.

<!-- TOC -->

- [Data](#data)
- [Models](#models)
- [Evaluation](#evaluation)
    - [NLP Evaluation](#nlp-evaluation)
    - [Human Evaluation](#human-evaluation)
- [Citation](#citation)

<!-- /TOC -->

## Data
Here are current statistics about the M4 dataset. It will be further extended in SemEval 2014 shared task 8 with surprising generators, domains and languages. 

<p align="center" width="100%">
    <a><img src="data_statistics.png" alt="Title" style="width: 100%; min-width: 300px; display: block; margin: auto;"></a>
</p>


## Citation
Please cite us if you use our data or models, see [arXiv paper](https://arxiv.org/abs/2305.14902):
```bibtex
@article{wang2023m4,
      title={{M4}: Multi-generator, Multi-domain, and Multi-lingual
                   Black-Box Machine-Generated Text Detection}, 
      author={Yuxia Wang and
              Jonibek Mansurov and
              Petar Ivanov and
              Jinyan Su and
              Artem Shelmanov and
              Akim Tsvigun and
              Chenxi Whitehouse and
              Osama Mohammed Afzal and
              Tarek Mahmoud and
              Alham Fikri Aji and
              Preslav Nakov},
      year={2023},
      journal={arXiv:2305.14902},
      primaryClass={cs.CL}
}
```
