# Wavelet ridge signal decomposition

Signal decomposition is a widely-used approach for multicomponent signal processing. To improve the accuracy and anti-noise performance of multicomponent decomposition, this paper proposes a novel multicomponent signal decomposition method based on wavelet ridge extraction, called the Wavelet ridge signal decomposition (WRSD). A wavelet ridge extraction algorithm is introduced. We find that this algorithm can obtain the wavelet ridge of one component in a multicomponent signal and the initial scale will determine the wavelet ridge of which component is extracted. Since the instantaneous frequency obtained by wavelet ridge has small frequency fluctuation, low-pass filtering is used to increase the accuracy of instantaneous frequency estimation. With the improved instantaneous frequency, the synchronous demodulation method is used to separate the corresponding component from the signal composition. By repeating this process, all components can be adaptively and automatically obtained. This method is employed to analyze three typical simulated vibration signals and compared with Hilbet vibration decomposition and empirical mode decomposition. The comparison results demonstrate its superiority in decomposition accuracy and noise insensitivity. Finally, the proposed WRSD method is successfully applied to the diagnosis of a shaft misalignment fault and a gearbox wear fault.

For the detail, please see: Yi Qin, Baoping Tang, Yongfang Mao.	Adaptive signal decomposition based on wavelet ridge and its application. Signal Processing, 2016, 120: 480-494.

[Code Download](https://github.com/QinYi-team/Code/tree/master/Wavelet%20ridge%20signal%20decomposition)