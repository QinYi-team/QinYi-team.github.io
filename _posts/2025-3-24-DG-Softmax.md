# DG-Softmax

Many unsupervised domain adaptation models have been explored to tackle the fault transfer diagnosis issues. Nevertheless, their achievements completely rely on the availability of target domain samples during training. Unfortunately, these testing samples are usually unavailable in advance due to routine maintenance and long designed life. Towards the real-time diagnosis demands in actual engineering, this study proposes a decision margin-based domain generalization framework that can indirectly achieve the distribution alignment between source and unseen target domains. Based on the framework, a novel DG-Softmax loss considering the class-level decision margin is proposed to enhance the feature separability. A novel adaptive and anti-interference selection mechanism of class-level decision margin named ACADM mechanism is established to select the decision margin in DG-Softmax loss adaptively. Furthermore, the DG-Softmax model, which only includes a task-related loss without any other auxiliary loss terms, is established to improve the computational efficiency and the diagnosis precision. A two-stage training scheme is utilized, including pre-training and training phases. The proposed DG-Softmax is evaluated on two cross-bearing transfer tasks from laboratory bearing to actual wind-turbine bearing and six cross-speed transfer tasks of the system-level planetary gearbox, and the experimental results validate that it outperforms other typical methods.



For the detail, please see: Quan Qian, Qijun Wen, Rui Tang, Yi Qin. DG-Softmax: a new domain generalization intelligent fault diagnosis method for planetary gearboxes, Reliability Engineering & System Safety, 2025.

[Code Download](https://github.com/QinYi-team/DG-Softmax) 

