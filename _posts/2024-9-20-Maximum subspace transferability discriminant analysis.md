# Maximum subspace transferability discriminant analysis

In the field of fault transfer diagnosis, many approaches only focus on the distribution alignment and knowledge transfer between the source domain and target domain. However, most of these approaches ignore the precondition of whether this transfer task is transferable. Current mainstream transferability
discrimination methods heavily depend on expert knowledge and are extremely vulnerable to the noise interference and variations in feature scale. This limits their applicability due to the intelligent requirements and complex industrial environment. To address the challenges mentioned previously, this paper introduces a novel cross-domain similarity measure called maximum subspace transferability discriminant analysis (MSTDA) with zero-label prior knowledge. MSTDA is comprised of a maximum subspace representation and a similarity measurement criterion. During the phase of maximum subspace representation, a new kernel-induced Hilbert space is designed to map the low-dimensional original samples into the high-dimensional space to maximize the separability of different faults and then solve the separable intrinsic fault features. Following that, a novel similarity measurement criterion that is resistant to variations in feature scale is developed. This criterion is based on the orthogonal bases of intrinsic feature subspaces. The mini-batch sampling strategy is used to ensure the timeliness of MSTDA. Finally, the
experimental results on three cases, particularly in the actual wind turbine dataset, confirm that the proposed MSTDA outperforms other well-known similarity measure methods in terms of transferability evaluation.



For the detail, please see: Quan Qian, Fei Wu, Yi Wang, Yi Qin. Maximum subspace transferability discriminant analysis: a new cross-domain similarity measure for wind-turbine fault transfer diagnosis, Computers in Industry, 2024.

[Code Download](https://github.com/QinYi-team/MSTDA) 

