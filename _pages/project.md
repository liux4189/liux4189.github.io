---
title: "Featured Projects"
permalink: /projects/
author_profile: true
header:
  image: header-about.jpg
---

Sensing and AI
======
Wireless radios can be leveraged as a sensor to preceive people and environment. My research interest lies in various emerging wireless sensing techniques (e.g., mmWave, UWB, and acoustic) and multi-modal sensor fusion among wireless and heterogeneous sensors (e.g., camera and IMU). 

![]({{site.url}}{{site.baseurl}}/images/mmEgo.png){: .align-left}
<b>Egocentric Human Pose Estimation using Head-mounted mmWave Radar.</b> <br>
We present mmEgo, the first egocentric human pose estimation design using a head-mounted mmWave radar, which offers ubiquitous pose tracking with high mobility, robustness to complex environments, and privacy preservation. To tackle the unique challenges of radar sensing from the egocentric perspective (e.g., random radar motion and the scarcity of information on the lower body), we propose a novel mmWave radar and IMU fusion design.
[[Sensys'23]](https://liux4189.github.io/files/mmEgo_sensys23.pdf) 
{:style="clear: left"}


![]({{site.url}}{{site.baseurl}}/images/Ubicomp22.jpg){: .align-left}
<b>Cross Vision-RF Gait Re-identification with Low-cost RGB-D Cameras and mmWave Radars.</b> <br>
This work studies the problem of cross-modal human re-identification between camera-allowed regions (e.g., streets) and camera-restricted regions (i.e., monitored by mmWave radars). We propose novel signature synthesis algorithm and  cross-modal deep metric learning model. 
[[Ubicomp'22]](https://arxiv.org/abs/2207.07896) 
{:style="clear: left"}

![]({{site.url}}{{site.baseurl}}/images/SECON22.jpg){: .align-left}
<b>Pedestrian Liveness Detection Based on mmWave Radar and Camera Fusion.</b> <br> 
In autonomous driving, a camera is vulnerable to visual inferences (e.g., billboard with human potraits). We propose a sensor fusion of mmWave radar and vision based on attention mechanism to robustly detect living pedestrians. 
[[SECON'22]](https://liux4189.github.io/files/SECON22_CameraReady.pdf)
{:style="clear: left"}


Network performance & Security
======
How the physical and MAC layer of wireless protocols impact the overall performance of the application and user experience about a mobile device? My research investigates the issues with in-depth measurements.   
![]({{site.url}}{{site.baseurl}}/images/WiFi6.jpg){: .align-left}
<b>A First Look at Wi-Fi 6 in Action: Throughput, Latency, Energy Efficiency, and Security.</b> <br> 
This is the first performance measurement of Wi-Fi 6 using real
experiments with a focus on multi-client scenarios. The results reveal the impact of the new
channel access mechanisms (i.e., OFDMA and TWT) on the spectrum efficiency, energy consumption, latency,
and network security. 
[[SIGMETRICS'23]](https://dl.acm.org/doi/10.1145/3579451) [[Data]](https://github.com/liux4189/wifi-ax-measurement)
{:style="clear: left"}


Wireless Network
======
Cross-Technology Communication (CTC) is a new IoT network paradigm that provides direct interconnectivity and cooperations among heterogeneous wireless technologies (e.g, WiFi, LTE, Bluetooth, ZigBee and LoRa), achieving seamless connections between heterogeneous wireless devices with only software update. To achieve this, we address the incompatibility of PHY/MAC in heterogeneous wireless devices. My research starts from physical-layer designs using signal processing techniques to novel CTC applications. CTC is proved technically feasbile on commodity devices and  commercially viable in the real applications. 

![]({{site.url}}{{site.baseurl}}/images/WiBeacon.jpg){: .align-left}
<b>WiBeacon: Expanding BLE Location-based Services via WiFi.</b> <br> 
WiBeaon repurposes billions of commodity Wi-Fi infrastructure to serve as the virtual Bluetooth beacon that provide low-cost, scalable, and easy-to-maintain location services for Bluetooth devices. 
[[Project]](http://liux4189.github.io/publications/WiBeacon) [[MobiCom'21]](https://liux4189.github.io/files/WiBeacon_MobiCom_CameraReady.pdf)
{:style="clear: left"}

![]({{site.url}}{{site.baseurl}}/images/XFi.JPG){: .align-left}
<b>XFi: Cross-technology IoT Data Collection via Commodity WiFi.</b> <br> 
With XFi, mobile devices (e.g., smartphone) can directly collect data from heterogeneous IoT devices (e.g., ZigBee and LoRa) using their WiFi interface. XFi is the first design that enables CTC from narrowband IoT radios to <i>commodity</i> WiFi. 
[[Project]](http://liux4189.github.io/publications/XFi) [[ICNP'19]](https://liux4189.github.io/files/XFi_Icnp_CameraReady.pdf)
{:style="clear: left"}

![]({{site.url}}{{site.baseurl}}/images/lte2b.jpg){: .align-left}
<b>LTE2B: Time-Domain Cross-Technology Emulation under LTE Constraints.</b> <br> 
LTE2B enables WAN/WLAN devices, e.g., LTE smartphone, WiFi access points to directly share data to low-power IoT devices, e.g., Bluetooth and ZigBee. The key intellectual merit of 
LTE2B is <i>Time-domain Emulation</i> which allows WAN/WLAN transmitters to accurately produce Bluetooth and ZigBee waveform. 
[[Project]](http://liux4189.github.io/publications/LTE2B) [[Sensys'19]](https://liux4189.github.io/files/LTE2B_Sensys_CameraReady.pdf) 
{:style="clear: left"}

<br>
![]({{site.url}}{{site.baseurl}}/images/bluebee.jpg){: .align-left}
<b>BlueBee: a 10,000x Faster Cross-Technology Communication via PHY Emulation.</b> <br>
BlueBee is a CTC technique from Bluetooth to ZigBee. This project proposes physical-layer CTC scheme in which by carefully choosing the payload for one wireless technology, e.g., Bluetooth,
the transmitter can create legitimate waveform of another wireless technology, e.g., ZigBee. Physical-layer CTC opens the door for the communications between heterogeneous
devices with high data rates. [[Sensys'17]](https://dl.acm.org/citation.cfm?id=3131678)
{:style="clear: left"}

<br>

Past Projects 
======
I developed industrial Internet-of-things in wireless embedded system. I was the team leader to implement ISA100.11a standards including hardware, software protocol stack 
and real-time scheduling algorithm. 
{:style="clear: left"}
