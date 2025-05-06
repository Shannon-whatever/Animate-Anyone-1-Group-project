# APAI3010 Group Project - Animate Anyone: Reproduction, Analysis, and Extensions

## Description:
This repository contains our reproduction, analysis, and extension of the Animate Anyone pose-driven character animation framework. We reproduced the model using Moore Threads’ unofficial implementation, evaluated its performance on standard benchmarks and a custom dataset, and explored extensions to improve facial animation. Our work highlights both the strengths and limitations of the current state-of-the-art in image-to-video character animation.

## Group Members:
- Li Ka Lam (u3605873@connect.hku.hk)
- Chen Shiyang (whatever@connect.hku.hk)
- Chechneva Kseniia (u3646503@connect.hku.hk)
  
## Key Components:

### Reproduction:

We faithfully reproduced the Animate Anyone framework by leveraging Moore Threads’ unofficial implementation, following the original pipeline for pose-driven character animation. Our experiments were conducted on public benchmarks—including the UBC Fashion and TikTok datasets—as well as a custom dataset featuring diverse human and non-human characters. The reproduction process involved replicating the model’s inference workflow, evaluating its performance in terms of temporal consistency, detail preservation, and generalization ability, and comparing our results with those reported in the original paper. This stage allowed us to systematically assess the strengths and shortcomings of the official approach in real-world scenarios.

Here are some reproduction results we generated.

![UBC Examples (png)](https://github.com/Shannon-whatever/Animate-Anyone-1-Group-project/blob/main/Figures/UBC_fashion_comparison.png)
[UBC Examples (mp4)](https://github.com/Shannon-whatever/Animate-Anyone-1-Group-project/tree/main/demos/ubc)

![TikTok Examples (png)](https://github.com/Shannon-whatever/Animate-Anyone-1-Group-project/blob/main/Figures/TikTok_comparison.png)
[TikTok Examples (mp4)](https://github.com/Shannon-whatever/Animate-Anyone-1-Group-project/tree/main/demos/tiktok)



### Extensions & Innovations:

- Algorithmic Enhancements: Introduced [specific improvements, e.g., "a temporal coherence module to reduce frame flickering" or "an adaptive pose encoder for sparse input handling"].
- Performance Optimization: Streamlined inference pipelines, achieving a [X]% reduction in computational overhead while maintaining visual fidelity.
- Novel Applications: Explored adaptations for [specific use cases, e.g., "real-time animation" or "cross-domain stylization"].

## Contributions:

- Delivered a modular, well-documented codebase to support academic and industrial research in human animation.
- Published quantitative/qualitative comparisons between original and extended results, highlighting trade-offs and advancements.
- Provided actionable insights for future work at the intersection of pose estimation and generative models.

## Collaboration:
We welcome feedback, issue reports, and constructive dialogue from the community. For course-related inquiries, please contact u3605873@connect.hku.hk.
