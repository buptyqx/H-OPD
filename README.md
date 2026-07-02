<div align="center">

<h1> H-OPD: Confidence Aware Heterogeneous Multi-Teacher Multimodal On-policy Distillation </h1>

<h5 align="center">

Qixiang Yin<sup>1,6</sup>, Huanjin Yao<sup>2</sup>, Cai Yuchen<sup>3</sup>, Jianghao Chen<sup>6</sup>, Ziyi Wang<sup>1</sup>, Min Yang<sup>2,*</sup>, Fei Su<sup>1,4,5</sup>, Zhicheng Zhao<sup>1,4,5,*</sup>

<sup>1</sup> Beijing University of Posts and Telecommunications, <sup>2</sup> ByteDance, <sup>3</sup> USTC

<sup>4</sup> Beijing Key Laboratory of Network System and Network Culture

<sup>5</sup> Key Laboratory of Interactive Technology and Experience System, Ministry of Culture and Tourism

<sup>6</sup> Zhongguancun Academy, Beijing, China

<sup>*</sup> Corresponding Author

</h5>
</div>

On-policy distillation (OPD) has recently emerged as an effective post-training paradigm by providing supervision on student-generated trajectories. 
However, existing OPD methods for multimodal reasoning usually rely on a static teacher routing, assigning each sample to a single teacher based on modality or task type. This ignores that visual grounding and abstract reasoning may dominate different decoding steps, making a single teacher insufficient for the full trajectory.
To this end, H-OPD is proposed as a confidence-aware heterogeneous multi-teacher OPD framework for multimodal reasoning. By verifying the complementarity of heterogeneous teachers in the same reasoning process, H-OPD replaces task or sample level teacher routing with token-level teacher arbitration along the shared student trajectory. H-OPD employs vision-to-language description transfer to enable text-only teachers to access key visual semantics, and uses a confidence-aware arbitration mechanism to dynamically combine vision-language teacher and text-only teachers at each token. 
Extensive evaluations over 11 widely-used reasoning benchmarks showcase the superior performance of our method.
