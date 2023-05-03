# Awesome Foundation Models [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
​
> A curated list of Foundation Models.
​
Contributions to this list are welcome. Add links through pull requests or create an issue to start a discussion.
​
## Contents
​
- [ChatGPT Alternatives](#ChatGPT-Alternatives)
- Coming next:
  - [Language Models](#Langauge-Models)
  - [Text-to-Image Models](#text-to-image-models)
​
​
## ChatGPT Alternatives
​
The table below is a collection of both open-source and close-source Langauge models that can be described as ChatGPT alternatives.
The interactive version can be found [our website](https://anania.ai/chatgpt-alternatives).
​
| Model | Size | Creator | Open-Source | Commercial usage | Base Model | Weights on HF | More Info | Online Demo |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LLaMA | 7B, 13B, 33B, 65B | Meta AI | Yes | Disallowed | LLaMA | [Link](https://huggingface.co/elinas/llama-65b-hf-transformers-4.29) | [Link](https://arxiv.org/abs/2302.13971) | [Link](https://huggingface.co/spaces/project-baize/Baize-7B) |
| Alpaca | 7B, 13B | Stanford CRFM | Yes | Disallowed | LLaMA | [Link](https://huggingface.co/chavinlo/alpaca-13b) | [Link](https://crfm.stanford.edu/2023/03/13/alpaca.html) | [Link](https://alpaca-ai.ngrok.io/) |
| Vicuna | 7B, 13B | UC Berkeley, CMU, Stanford, MBZUAI, and UC San Diego | Yes | Disallowed | LLaMA | [Link](https://huggingface.co/elinas/vicuna-13b-4bit) | [Link](https://vicuna.lmsys.org/) | [Link](https://chat.lmsys.org/) |
| Koala | 13B | Berkeley Artificial Intelligence Research Lab (BAIR) | Yes | Disallowed | LLaMA | [Link](https://huggingface.co/Logophoman/koala-13b-diff) | [Link](https://bair.berkeley.edu/blog/2023/04/03/koala/) | [Link](https://chat.lmsys.org/?model=koala-13b) |
| Claude | Unknown | Anthropic | No | Allowed | Unknown |   | [Link](https://www.anthropic.com/index/introducing-claude) |   |
| GPT4-x-Alpaca | 13B | Unknown | Yes | Disallowed | Alpaca | [Link](https://huggingface.co/chavinlo/gpt4-x-alpaca) |   |   |
| WizardML | 7B | Microsoft, Peking University | Yes | Disallowed | LLaMA | [Link](https://huggingface.co/victor123/WizardLM) | [Link](https://github.com/nlpxucan/WizardLM) | [Link](https://487706ba2456b3ec18.gradio.live/) |
| Dolly v1 | 6B | Databricks | Yes | Allowed | GPT-J-6B | [Link](https://huggingface.co/databricks/dolly-v1-6b) | [Link](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html) |   |
| Dolly v2 | 3B, 7B, 12B | Databricks | Yes | Allowed | Pythia | [Link](https://huggingface.co/databricks/dolly-v2-12b) | [Link](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm) |   |
| GPT4ALL | 7B | Nomic AI | Yes | Allowed | GPT-J | [Link](https://huggingface.co/nomic-ai/gpt4all-lora) | [Link](https://static.nomic.ai/gpt4all/2023_GPT4All-J_Technical_Report_2.pdf) | [Link](https://huggingface.co/spaces/rishiraj/GPT4All) |
| StableLM | 3B, 7B | Stability AI | Yes | Disallowed | Unknown | [Link](https://huggingface.co/stabilityai/stablelm-tuned-alpha-7b) | [Link](https://stability.ai/blog/stability-ai-launches-the-first-of-its-stablelm-suite-of-language-models) | [Link](https://huggingface.co/spaces/stabilityai/stablelm-tuned-alpha-chat) |
| StableVicuna | 13B | Stability AI | Yes | Disallowed | Vicuna | [Link](https://huggingface.co/CarperAI/stable-vicuna-13b-delta/) | [Link](https://github.com/stability-AI/stableLM/) | [Link](https://huggingface.co/spaces/CarperAI/StableVicuna/) |
| h2oGPT | 12B, 20B | H2O | Yes | Allowed | GPT-NeoX | [Link](https://huggingface.co/h2oai/h2ogpt-oasst1-512-20b) | [Link](https://github.com/h2oai/h2ogpt) | [Link](https://gpt.h2o.ai/) |
| BARD | Unknown | Google | No | Allowed | LaMDA |   | [Link](https://blog.google/technology/ai/bard-google-ai-search-updates//) |   |
| BLOOMZ | 1B, 3B, 7B, 176B | HuggingFace et al | Yes | Allowed | BLOOM | [Link](https://huggingface.co/bigscience/bloomz) | [Link](https://arxiv.org/abs/2211.01786) | [Link](https://huggingface.co/bigscience/bloomz) |
| mT0 | 1B, 3B | HuggingFace et al | Yes | Allowed | T0 | [Link](https://huggingface.co/bigscience/mt0-xxl) | [Link](https://github.com/bigscience-workshop/xmtf) | [Link](https://huggingface.co/bigscience/mt0-xxl) |
| FastChat-T5 | 3B | Large Model Systems Organization | Yes | Allowed | Flan-t5-xl | [Link](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0) | [Link](https://github.com/lm-sys/FastChat#FastChat-T5) |   |
| ChatGLM | 6B | Data Mining Research Group at Tsinghua University | Yes | Allowed | GLM | [Link](https://huggingface.co/THUDM/chatglm-6b) | [Link](https://github.com/THUDM/ChatGLM-6B/blob/main/README_en.md) | [Link](https://huggingface.co/spaces/ysharma/ChatGLM-6b_Gradio_Streaming) |
| Raven | 7B, 14B | BlinkDL | Yes | Allowed | RWKV | [Link](https://huggingface.co/BlinkDL/rwkv-4-pile-14b) | [Link](https://github.com/BlinkDL/ChatRWKV) | [Link](https://huggingface.co/spaces/BlinkDL/ChatRWKV-gradio) |
| GPT-NeoXT-Chat-Base-20B | 20B | Together Computer | Yes | Allowed | GPT-NeoX | [Link](https://huggingface.co/togethercomputer/GPT-NeoXT-Chat-Base-20B) | [Link](https://github.com/togethercomputer/OpenChatKit/blob/main/docs/GPT-NeoXT-Chat-Base-20B.md) | [Link](https://huggingface.co/spaces/togethercomputer/OpenChatKit) |
| Pythia-Chat-Base-7B | 7B | Together Computer | Yes | Allowed | Pythia | [Link](https://huggingface.co/togethercomputer/Pythia-Chat-Base-7B) | [Link](https://github.com/togethercomputer/OpenChatKit) | [Link](https://huggingface.co/togethercomputer/Pythia-Chat-Base-7B) |
| ColossalChat | 7B | ColossalAI | Yes | Disallowed | LLaMA |   | [Link](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat) | [Link](https://chat.colossalai.org/) |
| BELLE | 7B | BELLE Group | Yes | Allowed | BLOOMZ | [Link](https://huggingface.co/BelleGroup/BELLE-7B-2M) | [Link](https://github.com/LianjiaTech/BELLE/blob/main/README_en.md) | [Link](https://huggingface.co/spaces/liuxiaopai/BelleGroup-BELLE-7B-2M) |
| BELLE LLaMA | 7B, 13B | BELLE Group | Yes | Disallowed | LLaMA | [Link](https://huggingface.co/BelleGroup/BELLE-LLaMA-13B-2M-enc) | [Link](https://github.com/LianjiaTech/BELLE/blob/main/README_en.md) |   |
