# DOA Estimation Based on Compressed Sensing: 1-Bit Direction of Arrival Estimation [with MATLAB Code]

The 1-bit analog-to-digital converter (ADC) can significantly reduce system complexity and power consumption. Therefore, this paper investigates the use of 1-bit measurement values from a large number of antenna elements for direction of arrival (DoA) estimation. We extend the binary iterative hard thresholding (BIHT) algorithm to complex-valued signals and multiple measurement vectors, making it suitable for multi-shot 1-bit DoA estimation. By comparing the obtained complex-valued BIHT (CBIHT) algorithm with subspace and CS-based methods in terms of DoA estimation performance and computational complexity, we show that CBIHT is highly suitable for scenarios with many antenna elements and few shots.
Introduction
The deployment of a large number of antenna elements in base stations for Massive MIMO technology is key to future cellular networks. The use of a large number of antenna elements can enhance spectral efficiency through beamforming (i.e., transmitting and receiving signals through narrow directional beams), and expand available spectrum by utilizing the underutilized millimeter wave bands. However, one major drawback of Massive MIMO is the high complexity and power consumption caused by the large number of antenna elements. The ADC, being one of the most power-consuming devices, has its power consumption reduced exponentially with lower resolution. Moreover, 1-bit quantization can greatly simplify the design of other radio frequency components such as amplifiers and mixers. Therefore, this paper investigates how to utilize the 1-bit measurement values from a large number of antenna elements for direction of arrival (DoA) estimation, which can be used for beamforming.
The study of unquantized DoA estimation based on Compressed Sensing (CS) has been researched, which formulates the problem as a sparse recovery issue and develops powerful solutions such as Basis Pursuit Denoising (BPDN). Additionally, there are CS recovery algorithms explicitly considering 1-bit quantization of measurement values like Binary Iterative Hard Thresholding (BIHT). However, BIHT was initially designed for real-valued signals and single measurement vector (SMV) scenarios. To extend it to multi-fast-sampling 1-bit DoA estimation, we have extended it to complex-valued signals and multiple measurement vectors (MMV) scenarios, resulting in the algorithm called Complex-Valued BIHT (CBIHT). Simulations show that CBIHT's 1-bit DoA estimation performance can be comparable to BPDN and subspace-based MUSIC, ESPRIT methods, even better, and with relatively lower computational complexity when the number of antenna elements is large and the number of fast-sampling is small.
This paper is structured as follows: Section 2 introduces the 1-bit DoA estimation measurement model based on Uniform Linear Array (ULA), and expresses 1-bit DoA estimation as a sparse recovery issue; Section 3 describes the BPDN and CBIHT algorithms used to solve the sparse recovery problem; Section 4 compares the DoA estimation performance of BPDN, CBIHT, MUSIC, and ESPRIT through simulations; Section 5 compares the computational complexity of each method; Section 6 summarizes the entire paper.
Figures included in the article.
Conclusion
This paper investigates the problem of DoA estimation using a large number of antenna elements with 1-bit measurement values. After introducing the measurement model and representing 1-bit DoA estimation as a sparse recovery problem, we introduce the BPDN and BIHT methods for solving sparse recovery problems in the CS field. Since BIHT was initially designed for real-valued signals and single measurement vector scenarios, we extend it to complex-valued signals and multiple measurement vector scenarios, making the resulting CBIHT algorithm applicable to multi-shot 1-bit DoA estimation. Simulation results show that in scenarios with many antenna elements and few shots, the 1-bit DoA estimation performance of CBIHT can be comparable to that of BPDN and subspace-based MUSIC, ESPRIT methods, and even better. Comparative complexity analysis indicates that CBIHT has lower computational complexity than other methods. Therefore, CBIHT is very suitable for large-scale MIMO scenarios with many antenna elements and few shots.

## Images

![(DOA Estimation)1-bit Direction of Arrival Estimation Based on Compressed Sensing [with MATLAB Code]](01.jpg)
![(DOA Estimation)1-bit Direction of Arrival Estimation Based on Compressed Sensing [with MATLAB Code]](02.jpg)
![(DOA Estimation)1-bit Direction of Arrival Estimation Based on Compressed Sensing [with MATLAB Code]](03.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
