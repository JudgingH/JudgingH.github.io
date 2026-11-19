# JudgingH.github.io

## 模型结构图谱

- [DeepSeek-V4.1-Flash 模型结构交互图谱](https://judgingh.github.io/deepseek-v41-flash-atlas.html)

  基于官方发布配置与固定版本源码，介绍 Causal Encoder–Decoder、CSA2 稀疏注意力、MoE、Single-Pass mHC、Engram、视觉编码及 DSpark 草稿路径。支持 40 层模式切换、节点公式与张量维度、官方源码链接、配置检索和 KV 缓存估算。

  页面为自包含 HTML，无本地文件引用或外部运行依赖；下载仓库中的 [deepseek-v41-flash-atlas.html](./deepseek-v41-flash-atlas.html) 后即可离线打开，也可仅将这个 HTML 文件分享给其他人。查看外部源码链接时需要联网。

  模型源码固定版本：`314113f8a7dadb388215396ba5fbee2c610a04d6`。图谱用于结构讲解，不执行模型推理；缓存估算不代表实际设备显存或性能测试结果。

## 技术报告

- [DeepSeek-V4.1 昇腾适配：vllm-ascend 与 DeepInfer 功能对照](https://judgingh.github.io/deepseek-v41-ascend-comparison.html)  
  对比两个框架在昇腾上的硬件适配、注意力与缓存、DSpark、并行调度和服务能力，并提供源码依据与验收建议。

- [DeepSeek-V4.1 EPLB 专家并行负载均衡](https://judgingh.github.io/deepseek-v41-eplb.html)  
  以 vllm-ascend MRV2 部署为例，通过交互演示介绍专家映射、异步提交、STAIR 与 default 策略、强制路由，以及 P/D 节点的 step 计算方式。
