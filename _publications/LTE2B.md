---
title: "LTE2B: Time-Domain Cross-Technology Emulation under LTE Constraints."
collection: publications
permalink: /publications/LTE2B
citation: '<b>Ruofeng Liu</b>, Zhimeng Yin, Wenchao Jiang, Tian He. <i>17th ACM Conference on Embedded Networked Sensor Systems </i>. <b>(ACM Sensys 2019)</b>.'
---
[[PDF]](https://liux4189.github.io/files/LTE2B_Sensys_CameraReady.pdf) [[Demo]](https://youtu.be/DomGy6Az8ew)
## Abstract
Conventional gateway solutions are limited in satisfying the demand for ubiquitous connections among heterogeneous wireless devices, e.g., wide-area and personal-area network devices, due to the deployment complexity, high cost, and the incurred extra traffic. Recent advances propose the physical layer cross-technology communication to address these issues. However, existing CTC techniques commonly emulate the target waveform in the frequency domain (FDE). Despite their success, these FDE based techniques inherently suffer from high quantization errors and are insufficient for IoT applications that require high communication reliability.
<br>
To improve the emulation accuracy, we are the first to introduce the time-domain emulation (TDE) that significantly outperforms FDE techniques in reducing quantization errors and offers reliable emulation even with limited sources, e.g., low modulation schemes. To validate our idea, we propose LTE2B, the first TDE based CTC work that enables LTE devices (e.g., smartphones) to transmit data frames demodulatable by ZigBee and Bluetooth low energy (BLE) devices.
<br>
We implement the LTE2B on commodity devices (Nexus 5X smartphone and CC2530/CC1350 ZigBee/BLE SoC) with only payload embedding by penetrating the extremely complicated LTE stack. Our extensive evaluation demonstrates that TDE outperforms FDE, while LTE2B can achieve a robust ( > 99% accuracy), long distance ( > 400 m ) CTC performance under a full range of wireless configurations including indoor/outdoor, mobility, and duty-cycle settings.

## Demo
<iframe width="560" height="315" src="https://www.youtube.com/embed/DomGy6Az8ew" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>