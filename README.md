---
language:
- zh
- en
tags:
- glm
- chatglm
- thudm
- ryzenai-npu
base_model: THUDM/chatglm3-6b
---

# chatglm3-6b
- ## Introduction
  This model was created using Quark Quantization, followed by OGA Model Builder, and finalized with post-processing for NPU deployment.
- ## Quantization Strategy
  - AWQ / Group 128 / Asymmetric / BF16 activations / UINT4 weights
    
- ## Quick Start
For quickstart, refer to [Ryzen AI doucmentation](https://ryzenai.docs.amd.com/en/latest/npu_oga.html)

#### Evaluation scores
The perplexity measurement is run on the wikitext-2-raw-v1 (raw data) dataset provided by Hugging Face. Perplexity score measured for prompt length 2k is 29.81679.



#### License
Modifications copyright(c) 2024 Advanced Micro Devices,Inc. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.