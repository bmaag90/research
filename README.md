# Research Overview

## Main Projects

### Enhancing Multi-Hop Sensor Calibration with Uncertainty Estimates

***Best Innovation Paper Award***

Low-cost sensors, installed on mobile vehicles, pro-vide a cost-effective way for fine-grained urban air pollution monitoring. 
However, frequent calibration is crucial for low-cost sensors to consistently deliver accurate measurements.
Multi-hop calibration is a common practice to calibrate mobile sensor deployments, but is prone to severe error accumulation over hops. 
Prior research mitigates error accumulation by designing special calibration models, which only apply to linear models. 
In this paper, we propose an orthogonal approach by selecting reliable measurements for calibration at each hop. 
We analyze the impact of different data-induced uncertainties on calibration errors and devise a scheme to estimate these uncertainties of the calibrated outputs. 
We further propose an uncertainty-based metric for data filtering at each hop. 
We evaluate the effectiveness of our method in a real-world ozone
sensor deployment. 
Experimental results show that our method works with both linear and non-linear calibration models and reduces calibration errors in multi-hop setups by up to 25% compared with existing techniques.


**Authors**: Balz Maag, Zimu Zhou and Lothar Thiele<br>
**Published:**  IEEE International Conference on Ubiquitous Intelligence and Computing (UIC 2019). <br>
**Paper**: [PDF](./UIC2019/uic2019_paper.pdf)<br>
**Code**: [https://github.com/bmaag90/code_uncertainty](https://github.com/bmaag90/code_uncertainty)


### A Survey on Sensor Calibration in Air Pollution Monitoring Deployments 
In this article, we review the state-of-the-art low-cost air pollution sensors, identify their major error sources, and comprehensively survey calibration
models as well as network re-calibration strategies suited for different sensor deployments.

**Authors**: Balz Maag, Zimu Zhou and Lothar Thiele<br>
**Published:** In IEEE Internet of Things Journal, 2018, Vol 5., No. 6, Dec. 2018, pages 4857-4870. <br>
**DOI:** [10.1109/JIOT.2018.2853660](http://doi.org/10.1109/JIOT.2018.2853660)<br>
**Paper**: [PDF](./IOTJ2018/iotj2018_paper.pdf)<br>

### W-Air: Enabling Personal Air Pollution Monitoring on Wearables 

In this project we design W-Air, an accurate personal multi-pollutant monitoring platform for wearables. We discovered that human emissions introduce non-linear interference when low-cost gas sensors are integrated into wearables, which is overlooked in existing studies. W-Air adopts a sensor-fusion calibration scheme to recover high-fidelity ambient pollutant concentrations from the human interference. It also leverages a neural network with shared hidden layers to boost calibration parameter training with fewer measurements and utilizes semi-supervised regression for calibration parameter updating with little user intervention.

**Authors**: Balz Maag, Zimu Zhou and Lothar Thiele<br>
**Published:** In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT), Vol.2, No.1<br>
**DOI:** [10.1145/3191756](https://doi.org/10.1145/3191756)<br>
**Paper**: [PDF](./IMWUT2018/imwut2018_paper.pdf)<br>
**Presented at:** UBCIOMP 2018, Singapore, [Slides](./IMWUT2018/imwut2018_slides.pdf)

### BARTON: Low Power Tongue Movement Sensing with In-ear Barometers 

***Best Paper Award***

Sensing tongue movements enables various applications in hands-free interaction and alternative communication. We propose BARTON, a BARometer based low-power and robust TONgue movement sensing system. Using a low sampling rate of below 50 Hz, and only extracting simple temporal features from in-ear pressure signals, we demonstrate that it is plausible to distinguish important tongue gestures (left, right, forward) at low power consumption. We prototype BARTON with commodity earpieces integrated with COTS barometers for in-ear pressure sensing and an ARM micro-controller for signal processing.

**Authors**: Balz Maag, Zimu Zhou, Olga Saukh and Lothar Thiele<br>
**Published:** In Proceedings of the International Conference on Parallel and Distributed Systems (ICPADS 2017)<br>
**Paper**: [PDF](./ICPADS2017/icpads2017_paper.pdf)<br>
**Presented at:** ICPADS 2017, Shenzhen, China, [Slides](./ICPADS2017/icpads2017_slides.pdf)


### SCAN: Multi-Hop Calibration for Mobile Sensor Arrays

Urban air pollution monitoring with mobile, portable, low-cost sensors has attracted increasing research interest for their wide spatial coverage and affordable expenses to the general public. However, low-cost air quality sensors not only drift over time but also suffer from cross-sensitivities and dependency on meteorological effects. Therefore calibration of measurements from low-cost sensors is indispensable to guarantee data accuracy and consistency to be fit for quantitative studies on air pollution. In this work we propose sensor array network calibration (SCAN), a multi-hop calibration technique for dependent low-cost sensors. SCAN is applicable to sets of co-located, heterogeneous sensors, known as sensor arrays, to compensate for cross-sensitivities and dependencies on meteorological influences. SCAN minimizes error accumulation over multiple hops of sensor arrays, which is unattainable with existing multi-hop calibration techniques.

**Authors**: Balz Maag, Zimu Zhou, Olga Saukh and Lothar Thiele<br>
**Published:** In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT), Vol.1, No.2<br>
**DOI:** [10.1145/3090084](https://doi.org/10.1145/3090084)<br>
**Paper**: [PDF](./IMWUT2017/imwut2017_paper.pdf)<br>
**Presented at:** UBICOMP 2017, Maui, USA, [Slides](./IMWUT2017/imwut2017_slides.pdf)<br>
**Code**: [https://github.com/bmaag90/code_scan](https://github.com/bmaag90/code_scan)

### Pre-Deployment Testing, Augmentation and Calibration of Cross-Sensitive Sensors 

In this work, we propose a novel method to conduct infield testing of low-cost sensors. The algorithm proposed is based on multiple least-squares and leverages the physical variation of urban air pollution to quantify the amount of explained and unexplained sensor signal. We verify (i) whether a sensor is feasible for air quality monitoring in a given environment, (ii) model sensor cross-sensitivities to interfering gases and environmental effects and (iii) compute the optimal sensor array and its calibration parameters for stable and accurate sensor measurements over long time periods.

**Authors**: Balz Maag, Olga Saukh, David Hasenfratz and Lothar Thiele<br>
**Published:** In Proceedings of the 13th European Conference on Wireless Sensor Networks (EWSN 2016)<br>
**Paper**: [PDF](./EWSN2016/ewsn2016_paper_1.pdf)<br>
**Presented at:** EWSN 2016, Graz, Austria, [Slides](./EWSN2016/ewsn2016_slides_1.pdf)


## Collaborations

### Quantle: Fair and Honest Presentation Coach in Your Pocket 

Accurate time synchronization is an important prerequisite for many applications. Synchronization down to submicrosecond precision, as required by distributed control in automation or network event analysis, is prevalently a domain of wired or expensive GPS-enabled systems. Existing time synchronization protocols for wireless embedded systems exhibit errors that are orders of magnitude higher. We identify propagation delay compensation as a key requirement to achieve sub-microsecond precision in typical deployments. As a result, we present the Time-of-Flight Aware Time Synchronization Protocol (TATS), a new protocol that combines fast multi-hop flooding and message delay compensation at similar message cost as existing delay-unaware protocols.

**Authors**: Olga Saukh and Balz Maag<br>
**Published:** In IEEE/ACM International Conference on Information Processing in Sensor Networks (IPSN 2019)<br>
**Paper**: [PDF](./IPSN2019/IPSN2019_paper.pdf)<br>


### Time-of-Flight Aware Time Synchronization for Wireless Embedded Systems 

Accurate time synchronization is an important prerequisite for many applications. Synchronization down to submicrosecond precision, as required by distributed control in automation or network event analysis, is prevalently a domain of wired or expensive GPS-enabled systems. Existing time synchronization protocols for wireless embedded systems exhibit errors that are orders of magnitude higher. We identify propagation delay compensation as a key requirement to achieve sub-microsecond precision in typical deployments. As a result, we present the Time-of-Flight Aware Time Synchronization Protocol (TATS), a new protocol that combines fast multi-hop flooding and message delay compensation at similar message cost as existing delay-unaware protocols.

**Authors**: Roman Lim, Balz Maag and Lothar Thiele<br>
**Published:** In Proceedings of the 13th European Conference on Wireless Sensor Networks (EWSN 2016)<br>
**Paper**: [PDF](./EWSN2016/ewsn2016_paper_2.pdf)<br>

### A Testbed for Fine-Grained Tracing of Time Sensitive Behavior in Wireless Sensor Networks

This paper introduces TRACELAB, a new testbed architecture that allows for fine-grained tracing of time sensitive behavior of low-power wireless embedded systems. Such traces help to systematically analyze code execution to find software errors, measure bounds for execution times, or to verify functional program properties. TRACELAB builds on the idea of GPIO tracing: by including short GPIO instructions into node applications, the program behavior can be traced in a minimally invasive manner, simultaneously on all observed nodes. TRACELAB enables fine-grained distributed tracing by overcoming the limits of existing testbed architectures with respect to timing accuracy and peak event rates.

**Authors**: Roman Lim, Balz Maag, Benjamin Dissler, Jan Beutel and Lothar Thiele<br>
**Published:** In IEEE Workshop on Practical Issues in Building Sensor Network Applications (SenseApp 2015)<br>
**Paper**: [PDF](./Senseapp2015/Senseapp2015_paper.pdf)<br>


