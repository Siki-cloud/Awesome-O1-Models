# o1-Like Models and Reasoning Research Repository

![image](https://github.com/Siki-cloud/Awesome-o1-Models/blob/main/imgs/logo.png)
*Figure 1: Welcome to the o1-Like Models and Reasoning Research Repository*

This repository is dedicated to collecting and organizing information about **o1-like models** and avaliable **reasoning datasets**. Our goal is to provide researchers and developers with a centralized platform to explore the design principles, performance, and applications of these models.

----

## Timeline
Here are key milestones for this repository:
- **[25/4/9]**  Welcome to see o1-like models research!👀 The repository is officially launched, starting the collection of o1-like model information.

----

## Collected o1-Like Models
We have gathered several models that align with the o1-like definition (i.e., models with built-in chain-of-thought reasoning, reinforcement learning optimization, and a focus on complex reasoning tasks). Below is the current list of recorded models and their details:

### Model Table
#### Table Dimensions Explained
- **o1-like Model**: The family name of the model, indicating its categorization as an o1-like model.
- **Specific Model (Occurrence Time)**: The specific variant of the model and its release or occurrence date (e.g., `DeepSeek-R1-Lite-Preview (671B) (2024-11-20)`).
- **URL**: The acquisition path or source link where the model can be accessed or downloaded (e.g., GitHub or Hugging Face repositories).
- **Open Source**: Indicates whether the model is open-source (`Yes`) or proprietary (`No`).

| o1-like Model                | Specific Model (Occurrence Time)             | URL                                              |Open Source |
|------------------------------|----------------------------------------------|--------------------------------------------------|-------------|
| DeepSeek R1 -*               | DeepSeek-R1-Lite-Preview (671B) (2024-11-20) | [Link](https://github.com/deepseek-ai)           |Yes         |
|                              | DeepSeek-R1-Zero (671B) (2025-1-20)          | [Link](https://github.com/deepseek-ai)           |Yes         |
|                              | DeepSeek-R1 (671B) (2025-1-20)               | [Link](https://github.com/deepseek-ai)           |Yes         |
|                              | DeepSeek-R1-Distill-Qwen-7B                  | [Link](https://huggingface.co/deepseek)          |Yes         |
|                              | DeepSeek-R1-Distill-Qwen-32B                 | [Link](https://huggingface.co/deepseek)          |Yes         |
|                              | DS-R1-Distill-Qwen-1.5B                      | [Link](https://huggingface.co/deepseek)          |Yes         |
|                              | DS-R1-Distill-Qwen-7B                        | [Link](https://huggingface.co/deepseek)          |Yes         |
|                              | DeepSeek-R1-Distill-LLaMA-8B                 | [Link](https://huggingface.co/deepseek)          |Yes         |
|                              | DeepSeek-R1-Distill-LLaMA-70B                | [Link](https://huggingface.co/deepseek)          |Yes         |
| QwQ -* (Alibaba)             | QwQ-32B-Preview ()                           |                                                  |Yes         |
|                              | QwQ-32B (202-3-6)                            |                                                  |Yes         |
|                              | QwQ-32B-plus (Only API)                      |                                                  |Yes         |
| s1 -*                        | s1-32B (2025-01) (train Qwen2.5-32B-Instruct) | [Link](https://www.open-thoughts.ai)             |Yes         |
|                              | s1.1-32B (2025-02)                           | [Link](https://www.open-thoughts.ai)             |Yes         |
| LIMO (GAIR)                  | LIMO-32B (2025/2/5)                          | [Link](https://github.com/GAIR-NLP/LIMO)         |Yes         |
| Open Thinker -* (Open Thoughts) | OpenThinker2-1M/7B/32B (2025/04/03)       | [Link](https://github.com/open-thoughts/open-thoughts) |Yes         |
|                              | OpenThinker-32B (2025/02/12)                 | [Link](https://github.com/open-thoughts/open-thoughts) |Yes         |
| Light-R1 (360 Zhinao & PKU)  | Light-R1-32B (25-3-4)                        | [Link](https://github.com/Qihoo360/Light-R1/blob/main/README.md) |Yes         |
|                              | Light-R1-7B-DS (25-3-12)                     | [Link](https://github.com/Qihoo360/Light-R1/blob/main/README.md) |Yes         |
|                              | Light-R1-14B-DS                              | [Link](https://github.com/Qihoo360/Light-R1/blob/main/README.md) |Yes         |
|                              | Light-R1-32B-DS                              | [Link](https://github.com/Qihoo360/Light-R1/blob/main/README.md) |Yes         |
| Marco-o1 (Alibaba MarcoPolo Team) | Marco-o1-7B (train Qwen2-7B-Instruct) (2024-11-21) | [Link](https://github.com/AIDC-AI/Marco-o1) |Yes         |
| Z1 (Tsinghua & Yale)         | Z1-7B (train Qwen2.5-Coder-7B-Instruct) (2025-4-1) | [Link](https://github.com/efficientscaling/Z1) |Yes         |
| Sky-T1-* (Tiangong)          | Sky-T1-32B-Preview (2025/01/10)              | [Link](https://github.com/NovaSky-AI/SkyThought) |Yes         |
|                              | Sky-T1-32B-Flash (tackle overthinking) (2025/01/23) | [Link](https://github.com/NovaSky-AI/SkyThought) |Yes         |
|                              | Sky-T1-7B, Sky-T1-mini (2025/02/11)          | [Link](https://github.com/NovaSky-AI/SkyThought) |Yes         |
| OpenAI o1 -* (OpenAI)        | openai-o1-preview (2024-9-13), o1-mini, o1, o1-pro, o3-mini | [Link](https://platform.openai.com/docs/overview) |
| Claude (Anthropic)           | claude-3.7-sonnet-20250219                   | [Link](https://docs.anthropic.com/en/docs/about-claude/models/all-models#model-comparison-table) |Yes         |
|                              | claude-3-5-sonnet-20241022                   | [Link](https://docs.anthropic.com/en/docs/about-claude/models/all-models#model-comparison-table) |Yes         |
| Gemini (Google)              | gemini-2.5-pro-preview-03-25                 | [Link](https://ai.google.dev/gemini-api/docs/models?hl=zh-cn#gemini-2.0-flash-lite) |Yes         |
|                              | gemini-2.0-flash                             | [Link](https://ai.google.dev/gemini-api/docs/models?hl=zh-cn#gemini-2.0-flash-lite) |Yes         |
|                              | gemini-2.0-flash-lite                        | [Link](https://ai.google.dev/gemini-api/docs/models?hl=zh-cn#gemini-2.0-flash-lite) |Yes         |
| Grok (Twitter)               | Grok-3 (w/o API)                             | [Link](https://docs.x.ai/docs/overview#featured-models) |Yes         |
| Kimi -* (Moonshot)           | kimi 1.5 (w/o API)                           | [Link](https://platform.moonshot.cn/docs/intro) |Yes         |
