# Awesome-KV-Cache-In-LLM
A curated collection of research, tools, and implementations focused on optimizing Key-Value (KV) Cache in Large Language Models (LLMs). Includes methods for compression, pruning, quantization, eviction policies, and efficient management to reduce memory footprint and accelerate inference.

一个精选的研究、工具和实现集合，专注于优化大型语言模型（LLMs）中的键值（KV）缓存。包含用于压缩、剪枝、量化、淘汰策略和高效管理的方法，以降低内存占用并加速推理。

## github仓库

1. https://github.com/October2001/Awesome-KV-Cache-Compression
1. https://github.com/Zefan-Cai/Awesome-LLM-KV-Cache
3. https://github.com/NVIDIA/kvpress
4. https://github.com/Zefan-Cai/KVCache-Factory

##  
|Date|Affiliation|Title|Paper|Code|status|
|:---|:---|:---|:---|:---|---|
|2026.1| 上海交通大学 |SmallKV: Small Model Assisted Compensation of KV Cache Compression for Efficient LLM Inference|[[pdf]](https://arxiv.org/pdf/2508.02751) | - | Spotlight
|2025.10| 香港科技大学 |ChunkKV: Semantic-Preserving KV Cache Compression for Efficient Long-Context LLM Inference|[[pdf]](https://arxiv.org/pdf/2502.00299) | [code](https://github.com/NVIDIA/kvpress) | Poster
|2026.1| 微软  |R-KV: Redundancy-aware KV Cache Compression for Reasoning Models|[[pdf]](https://arxiv.org/pdf/2505.24133) | [code](https://zefan-cai.github.io/R-KV.page/) | Poster
|2025.7| UCSD  |KVFlow: Efficient Prefix Caching for Accelerating LLM-Based Multi-Agent Workflows|[[pdf]](https://arxiv.org/pdf/2507.07400) | -| Poster
|2025.10| 首尔国立大学  |Reasoning Path Compression: Compressing Generation Trajectories for Efficient LLM Reasoning|[[pdf]](https://arxiv.org/pdf/2505.13866) | [ReasoningPathCompression](https://github.com/jiwonsong-dev/ReasoningPathCompression) | Poster
|2025.10| 哥伦比亚商学院  |Tail-Optimized Caching for LLM Inference|[[pdf]](https://arxiv.org/pdf/2510.15152) | - | Poster
|2025.10| NVIDIA  |Inference-Time Hyper-Scaling with KV Cache Compression|[[pdf]](https://arxiv.org/pdf/2506.05345) | - | Poster
|2025.10| University of Maryland  |MUSTAFAR: Promoting Unstructured Sparsity for KV Cache Pruning in LLM Inference|[[pdf]](https://arxiv.org/pdf/2505.22913) | [mustafar](https://github.com/dhjoo98/mustafar) | Poster
|2025.10| 中国科学技术大学  |AttentionPredictor: Temporal Patterns Matter for KV Cache Compression|[[pdf]](https://arxiv.org/pdf/2502.04077) | [LLM-AttentionPredictor](https://github.com/MIRALab-USTC/LLM-AttentionPredictor) | Poster
|2025.10| 中国人民大学  |PolarQuant: Leveraging Polar Transformation for Key Cache Quantization and Decoding Acceleration|[[pdf]](https://openreview.net/pdf?id=JCTTLKEBza) | [PolarQuant](https://github.com/ericshwu/PolarQuant) | Poster
|2025.9| 首尔国立大学  |KVzip: Query-Agnostic KV Cache Compression with Context Reconstruction|[[pdf]](https://openreview.net/pdf?id=JCTTLKEBza) | [KVzip](https://github.com/snu-mllab/KVzip) | Oral
|2025.5| 华盛顿大学  |Memory-Efficient Visual Autoregressive Modeling with Scale-Aware KV Cache Compression|[[pdf]](https://arxiv.org/pdf/2505.19602?) | [ScaleKV](https://github.com/StargazerX0/ScaleKV) | Poster
|2025.10| 中国科学技术大学  |Accurate KV Cache Eviction via Anchor Direction Projection for Efficient LLM Inference|[[pdf]](https://openreview.net/pdf?id=Tdl89SZItB) | [LLM-AnDPro](https://github.com/MIRALab-USTC/LLM-AnDPro) | Poster
|2025.10| 北京大学  |Improving Model Representation and Reducing KV Cache via Skip Connections with First Value Heads|[[pdf]](https://arxiv.org/pdf/2510.16807) | [SkipV1Former](https://github.com/Zhoutong-Wu/SkipV1Former) | Poster
|2025.10| 首尔大学  |NSNQuant: A Double Normalization Approach for Calibration-Free Low-Bit Vector Quantization of KV Cache|[[pdf]](https://arxiv.org/pdf/2505.18231) | - | Poster
|2025.10| 上海财经大学  |Homogeneous Keys, Heterogeneous Values: Exploiting Local KV Cache Asymmetry for Long-Context LLMs|[[pdf]](https://arxiv.org/pdf/2506.05410) | [Asymkv](https://github.com/the-scale-lab/AsymKV) | Poster
|2025.10| 北京大学  |MPCache: MPC-Friendly KV Cache Eviction for Efficient Private LLM Inference|[[pdf]](https://arxiv.org/pdf/2501.06807) | [MPCache](https://github.com/zwxandy/MPCache) | Poster
|2025.10| 香港中文大学  |SmartCache: Context-aware Semantic Cache for Efficient Multi-turn LLM Inference|[[pdf]](https://openreview.net/pdf/5bc13f5689dfb66b132abd36782eb71e1da88f36.pdf) | - | Poster
|2025.10| -  |KVLink: Accelerating Large Language Models via Efficient KV Cache Reuse|[[pdf]](https://arxiv.org/pdf/2502.16002) | [KVLink](https://github.com/UCSB-NLP-Chang/KVLink) | Poster
|2025.10| 首尔国立大学 |HiFC: High-efficiency Flash-based KV Cache Swapping for Scaling LLM Inference|[[pdf]](https://openreview.net/pdf?id=onhjdWCxZY) | - | Poster
|2025.10| 厦门大学 |Spotlight Attention: Towards Efficient LLM Generation via Non-linear Hashing-based KV Cache Retrieval|[[pdf]](https://arxiv.org/pdf/2508.19740) | - | Poster
|2025.10| 清华大学 |PrefixKV: Adaptive Prefix KV Cache is What Vision Instruction-Following Models Need for Efficient Generation|[[pdf]](https://arxiv.org/pdf/2412.03409) | [PrefixKV](https://github.com/THU-MIG/PrefixKV) | Poster
|2025.10| 中国科学技术大学 |Ada-KV: Optimizing KV Cache Eviction by Adaptive Budget Allocation for Efficient LLM Inference|[[pdf]](https://arxiv.org/pdf/2407.11550) | [AdaKV](https://github.com/FFY0/AdaKV) | Poster
|2025.10| 高通人工智能研究院 |KeyDiff: Key Similarity-Based KV Cache Eviction for Long-Context LLM Inference in Resource-Constrained Environments|[[pdf]](https://arxiv.org/pdf/2504.15364) | - | Poster
|2025.10| 华中科技大学 |Sim-LLM: Optimizing LLM Inference at the Edge through Inter-Task KV Reuse|[[pdf]](https://openreview.net/pdf/e8355810346fa0731f27685d0e9743b63680e658.pdf) | [SimLLM](https://github.com/CGCL-codes/SimLLM) | Poster
|2025.10| 北京交通大学、字节跳动 |SALS: Sparse Attention in Latent Space for KV Cache Compression|[[pdf]](https://arxiv.org/pdf/2510.24273) | - | Poster