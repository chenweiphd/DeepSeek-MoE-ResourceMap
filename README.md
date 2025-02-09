# DeepSeek-MoE-ResourceMap

![image](https://github.com/user-attachments/assets/63e68241-e4c9-49a8-a608-52dd05324581)


## 1 Introduction



This is a repo about DeepSeek model architecture, training, deploy and distill

## 2 How to Use DeepSeek



## 3 DeepSeek and MoE Model Explain

### 3.1 Architecture

| Classification | Title                                                      | Link                                     |
| -------------- | ---------------------------------------------------------- | ---------------------------------------- |
| Summary        | DeepSeek V3-R1 Deep Explain (1) -v1.31                     | https://zhuanlan.zhihu.com/p/21208287743 |
| Summary        | DeepSeek V3-R1 Deep Explain (2) -v1.31                     | https://zhuanlan.zhihu.com/p/21755758234 |
|                |                                                            |                                          |
| MoE            | MoE Explain                                                | https://zhuanlan.zhihu.com/p/674698482   |
| DeepSeekMoE    | DeepSeek MOE—From Switch Transformers to DeepSeek v1/v2/v3 | https://zhuanlan.zhihu.com/p/21584562624 |
| MLA            | DeepSeek-V2 MLA KV Cache                                   | https://zhuanlan.zhihu.com/p/714761319   |
| MLA            | DeepSeekV2 Multi-head Latent Attention                     | https://zhuanlan.zhihu.com/p/714686419   |
| MTP            | DeepSeek V3: Multi-token Prediction                        | https://zhuanlan.zhihu.com/p/16540775238 |
| MTP            | Multi-Token Prediction                                     | https://zhuanlan.zhihu.com/p/15823898951 |





### 3.2 Training

| Classification     | Title                                                        | Link                                                         |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| GRPO               | GRPO：Group Relative Policy Optimization                     | https://zhuanlan.zhihu.com/p/20021693569                     |
| Rejection Sampling | LLM-Rejection Sampling                                       | https://zhuanlan.zhihu.com/p/4547529049                      |
| Rejection Sampling | LLM Training Trick (1) -Rejection Sampling                   | https://zhuanlan.zhihu.com/p/649731916                       |
| Fill in the Middle | Efficient Training of Language Models to Fill in the Middle  | https://huggingface.co/papers/2207.14255                     |
| Fill in the Middle | OpenAI Presents a Simple and Efficient Training Strategy to Boost Language Models’ Text-Infilling Capabilities | https://syncedreview.com/2022/08/04/openai-presents-a-simple-and-efficient-training-strategy-to-boost-language-models-text-infilling-capabilities/ |
| Fill in the Middle | “Where’s the Beef”, Codestral’s Fill-In-the-Middle Magic     | https://auro-227.medium.com/wheres-the-beef-codestral-s-fill-in-the-middle-magic-c0804094a424 |
|                    |                                                              |                                                              |



### 3.3 DeepSeek Related Paper



| Item                        | Title                                                        | Link                                |
| --------------------------- | ------------------------------------------------------------ | ----------------------------------- |
| R1                          | DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning | https://arxiv.org/abs/2501.12948    |
| V3                          | DeepSeek-V3 Technical Report                                 | https://arxiv.org/abs/2412.19437    |
| V2                          | DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model | https://arxiv.org/abs/2405.04434    |
| Coder-V2                    | DeepSeek-Coder-V2: Breaking the Barrier of Closed-Source Models in Code Intelligence | https://arxiv.org/abs/2406.11931    |
| HAI Platform（Not a model） | Fire-Flyer AI-HPC: A Cost-Effective Software-Hardware Co-Design for Deep Learning | https://arxiv.org/html/2408.14158v2 |
|                             |                                                              |                                     |
| Fill in the Middle          | Efficient Training of Language Models to Fill in the Middle  | https://arxiv.org/pdf/2207.14255    |



## 4 DeepSeek Deploy

### 4.1 Memory Requirements(From Xinference)

| Model                | # parameters | Data type | Memory Requirements |
| -------------------- | ------------ | --------- | ------------------- |
| R1                   | 685B         | FP8       | ≥890GB              |
| R1                   | 685B         | INT4      | ≥450GB              |
| V3                   | 671B         | FP8       | ≥870GB              |
| V3                   | 671B         | INT4      | ≥440GB              |
| R1-Distill-Llama-70B | 70B          | BF16      | ≥180GB              |
| R1-Distil1-Qwen-32B  | 32B          | BF16      | ≥80GB               |
| R1-Distil1-Qwen-14B  | 14B          | BF16      | ≥40GB               |
| R1-Disti11-Llama-8B  | 8B           | BF16      | ≥22GB               |
| R1-Distill-Qwen-7B   | 7B           | BF16      | ≥20GB               |
| R1-Disti11-0wen-1.5B | 1.5B         | BF16      | ≥5GB                |

### 4.2 Deploy

| Item                        | Title                                | Link                                     |
| --------------------------- | ------------------------------------ | ---------------------------------------- |
|                             |                                      |                                          |
| Ollama                      | DeepSeek Simple Local Deploy         | https://zhuanlan.zhihu.com/p/21311556084 |
| SiliconFlow                 | DeepSeek Simple Local API            | https://zhuanlan.zhihu.com/p/21170425824 |
| Ollama+Dynamic Quantization | DeepSeek-R1 671B Simple Local Deploy | https://zhuanlan.zhihu.com/p/21856074485 |
|                             |                                      |                                          |
|                             |                                      |                                          |
|                             |                                      |                                          |



## 5 Distill

| Item           | Title                                          | Link                                 |
| -------------- | ---------------------------------------------- | ------------------------------------ |
|                |                                                |                                      |
| Custom Distill | Train your own R1 reasoning model with Unsloth | https://unsloth.ai/blog/r1-reasoning |
|                |                                                |                                      |
|                |                                                |                                      |
|                |                                                |                                      |
|                |                                                |                                      |
|                |                                                |                                      |





## 6 Comment about DeepSeek

| Author       | Title                           | Link                                                    |
| ------------ | ------------------------------- | ------------------------------------------------------- |
| Dario Amodei | On DeepSeek and Export Controls | https://darioamodei.com/on-deepseek-and-export-controls |
|              |                                 |                                                         |
|              |                                 |                                                         |
|              |                                 |                                                         |



## 7 DeepSeek Model Link

| Item                        | Link                                             |
| --------------------------- | ------------------------------------------------ |
| R1                          | https://github.com/deepseek-ai/DeepSeek-R1       |
| V3                          | https://github.com/deepseek-ai/DeepSeek-V3       |
| V2                          | https://github.com/deepseek-ai/DeepSeek-V2       |
| Coder-V2                    | https://github.com/deepseek-ai/DeepSeek-Coder-V2 |
| MoE                         | https://github.com/deepseek-ai/DeepSeek-MoE      |
| HAI Platform（Not a model） | https://github.com/HFAiLab/hai-platform          |
|                             |                                                  |



## Discussion Group

| DeepSeek and MoE Discussion Group                            | ![MoEgroup](https://github.com/user-attachments/assets/9f55810b-d5f1-4846-a34e-0960088cc425) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 请添加群助理，加入相应讨论群。添加时请注明：称呼-所在单位-要加入的群 | ![image](https://github.com/user-attachments/assets/6b757bea-a656-4aac-8e5d-83525130db20) |




