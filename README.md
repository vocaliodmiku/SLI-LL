<div align="center">

<h2><span style="font-size:12px">Spoken Language Intelligence of Large Language Models for Language Learning</span> </h2> 

  <a href='https://arxiv.org/abs/2211.14758'><img src='https://img.shields.io/badge/ArXiv-2211.14758-red'></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href='https://vocaliodmiku.github.io/SLI-LL/'><img src='https://img.shields.io/badge/Project-Page-Green'></a>


<div>
    <a href='https://vocaliodmiku.github.io'>Linkai Peng<sup>1</sup> </a>&emsp;
    <a href='https://boroooo.github.io' target='_blank'>Baorian Nuchged<sup>2</a>&emsp;
    <a href='yingming.gao@bupt.edu.cn' target='_blank'>Yingming Gao<sup>3</sup></a>&emsp;
</div>
<br>
<div>
    <sup>1</sup> NetEase Youdao &emsp; <sup>2</sup> The University of Texas at Austin &emsp; <sup>3</sup> Beijing University of Posts and Telecommunications
</div>
<!-- <br>
<i><strong><a href='https://sa2022.siggraph.org/' target='_blank'>SIGGRAPH Asia 2022 Conferenence Track</a></strong></i>
<br> -->
<br>
<div align="justify"> We introduce a new multiple-choice question dataset to evaluate the effectiveness of LLMs in Spoken Language Learning, including understanding and application of spoken language knowledge. We investigate the influence of various prompting techniques such as zero- and few-shot method (prepending the question with question-answer exemplars), chain-of-thought (CoT, think step-by-step), in-domain exampler and external tools (Google, Wikipedia). We conducted large-scale evaluation on popular LLMs (20 distinct models) using these methods, and advanced method achieved significant performance improvements compared to the zero-shot baseline in the practical questions reasoning (GPT-3.5, 49.1% -> 63.1%; LLaMA2-70B-Chat, 42.2% -> 48.6%). We found that models of different sizes have good understanding of concepts in phonetics, phonology, and second language acquisition, but show limitations in reasoning for real-world problems. Additionally, we also explore preliminary findings on conversational communication. <strong>These performances highlight the impressive Spoken Language Intelligence exhibited by LLMs, and Chatbots based on large language models possess significant potential to enhance conversational spoken language learning.</strong>
</div>
<img src="./docs/static/pdfs/Q111.png?raw=true" width="768px" background-color=rgba(255,255,255,1)>
<br>

<!-- <p>
<img alt='pipeline' src="./docs/static/images/pipeline.png?raw=true" width="768px"><br>
<em align='center'>Pipeline</em>
</p> -->

</div>

## SLIQ-LL Dataset
The data is stored in the "data" directory in the form of JSON format.

Knowledge & Concept subset 
* concept_dev.json
* concept_test.json

Application Questions
* capt_dev.json
* capt_test.json

## Citation

If you find our work useful in your research, please consider citing:

```

```


##  Disclaimer

This is not an official product of NetEase Youdao. This repository can only be used for personal/research/non-commercial purposes.