# JudgingH.github.io

## 技术报告

- [DeepSeek-V4.1 昇腾适配：vllm-ascend 与 DeepInfer 功能对照](https://judgingh.github.io/deepseek-v41-ascend-comparison.html)  
  对比两个框架在昇腾上的硬件适配、注意力与缓存、DSpark、并行调度和服务能力，并提供源码依据与验收建议。

- [DeepSeek-V4.1 EPLB 专家并行负载均衡](https://judgingh.github.io/deepseek-v41-eplb.html)  
  以 vllm-ascend MRV2 部署为例，通过交互演示介绍专家映射、异步提交、STAIR 与 default 策略、强制路由，以及 P/D 节点的 step 计算方式。
