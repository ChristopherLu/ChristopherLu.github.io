---
layout: page
permalink: /research/
title: research
description: Ongoing and completed research projects by MAPS Lab
nav: true
navigation_weight: 15
---

---
## **Scaling Foundation Models for Enhanced Perception in Embodied Agents**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/scale_foundation_models.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Scaling large foundation models (e.g., CLIP, DINO and SAM) to local compute holds the promise of revolutionizing how embodied agents, such as robots, AR, and IoT devices, interact with and comprehend their environments. At the heart of this endeavor is the integration of advanced **visual and visual-language** understanding capabilities into these agents, enabling them to interpret and respond to the complex, dynamic world around them. Recent advancements in AI and machine learning have paved the way for such models to be adapted for use in real-world settings, where they can offer unparalleled context-awareness in a zero-shot way. However, deploying these foundation models in diverse and often unpredictable environments poses significant challenges. These include ensuring **generalization across different sensors** carried by the agents, optimizing for **computational efficiency** on limited hardware, and achieving **seamless interaction** with human users and other machines. In our research, we explore the full spectrum of these challenges, from adapting the models for efficient real-time processing to enhancing their understanding across different sensor inputs. *This is a new research line in the lab*, more research outputs are expected. 

Research Output: [<a href="https://arxiv.org/abs/2403.04908">ECCV'24a</a>],[<a href="https://tsagkas.github.io/click2grasp/">IROS'24</a>], [<a href="https://tsagkas.github.io/vl-fields/">ICRA-W'2023</a>]

## **Robust Spatial Perception for Autonomous Vehicles in the Wild**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/av.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Autonomous driving, aka. mobile autonomy, promises to radically change the cityscape and save many human lives. A pillar component for achieving mobile autonomy is **spatial perception - the ability for vehicles to understand the ambient environment and localize themselves on the road**. Thanks to the recent advances in computer vision and solid-state technology, great improvement in spatial perception has been witnessed in controlled environments. Nevertheless, the perception robustness of many systems is still far off the safety requirement of autonomous driving when it comes to the wild condition, such as bad weather, poor illumination, various dynamic objects or even malicious attacks. In the MAPS lab, we study the robust spatial perception problems in full-stack, ranging from the single-modality based methods to multi-sensory fusion, and to the perception uncertainty quantification. More recently, a traction to my lab is unfolding the potential of **4D automotive radar in localization and scene understanding**. As an emerging sensor, automotive radars are reputable for their sensing robustness against bad weather and adverse illumination. However, due to their significantly lower data quality, it remains largely unknown how one can transform the radar sensing robustness to vehicle perception effectiveness - a question my team keen to answer. 

Research Output: [<a href="https://arxiv.org/abs/2405.14014">NeurIPS'2024</a>], [<a href="https://arxiv.org/abs/2309.09737">ICRA'2024a</a>], [<a href="https://arxiv.org/abs/2309.17336">ICRA'2024b</a>], [<a href="https://toytiny.github.io/publication/23-cmflow-cvpr/index.html">CVPR'2023</a>], [<a href="https://arxiv.org/abs/2112.02469">IROS'2023</a>], [<a href="http://arxiv.org/abs/2209.14602">RA-L'2023</a>], [<a href="https://www.research.ed.ac.uk/en/publications/metawave-attacking-mmwave-sensing-with-meta-material-enhanced-tag">NDSS'2023</a>], [<a href="https://arxiv.org/abs/2203.01137">RA-L/IROS'2022</a>], [<a href="https://arxiv.org/abs/2203.01851">IROS'2022a</a>], [<a href="https://www.pure.ed.ac.uk/ws/portalfiles/portal/289946438/Pedestrian_Liveness_LI_DOA18072022_AFV.pdf">SECON'2022</a>], [<a href="https://intranet.csc.liv.ac.uk/~ramdrop/autoplace.html">ICRA'2022a</a>], [<a href="https://qqqgpe.github.io/2022-02-11/DC-Loc">ICRA'2022b</a>], [<a href="https://arxiv.org/abs/1912.13077">TNNLS'2022</a>], [<a href="https://arxiv.org/pdf/1908.03918.pdf">TNNLS'2021</a>], [<a href="http://arxiv.org/abs/1909.03557">AAAI'2020</a>], [<a href="http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Selective_Sensor_Fusion_for_Neural_Visual-Inertial_Odometry_CVPR_2019_paper.html">CVPR'2019</a>]

---
## **Privacy-aware and Low-Cost Human Motion Sensing**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ips.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Despite a plethora methods being proposed over recent decades, today's human sensing systems — primarily those designed to track location and monitor activities — often rely on RGB cameras. These methods encounter difficulties in adverse lighting conditions and raise increasing privacy concerns in domestic environments. Moving away from camera-centric solutions, the challenge intensifies when designing for **low-resolution sensors, such as mmWave, WiFi, UWB, BLE, and inertial measurement units**. This complexity arises because humans do not naturally interact with these modalities, complicating the application of our everyday experiences to improve algorithms for these sensors. Leveraging the latest advancements in machine learning, we advocate for **AI-empowered methods** to analyze data from these sensors, extending their utility. Our research also delves into whether these low-cost, low-resolution sensors can be utilized for fine-grained pose estimation, such as gestures and hand movements, beyond mere localization. Importantly, we aim to develop methods that are more acceptable by users, particularly for the aging population, ensuring our solutions are both effective and sensitive to the privacy and usability needs of this demographic.

Research Output: [<a href="https://arxiv.org/abs/2403.09871">SenSys’25</a>], [<a href="http://arxiv.org/abs/2306.17010">ECCV'24b</a>], [<a href="https://arxiv.org/abs/2311.10601">ICRA'2024c</a>], [<a href="https://arxiv.org/abs/2305.10345">NeurIPS’2023
</a>], [<a href="http://arxiv.org/abs/2207.07859">Patterns'2023</a>], [<a href="https://www.pure.ed.ac.uk/ws/portalfiles/portal/327349383/Human_Parsing_WANG_DOA20012023_AFV_CC_BY.pdf">UbiComp'2023</a>], [<a href="http://arxiv.org/abs/2111.03976">IoT-J'2023</a>], [<a href="https://arxiv.org/pdf/2207.07896.pdf">UbiComp'2022</a>], [<a href="https://arxiv.org/pdf/2208.14326.pdf">IoT-J'2022</a>],[<a href="https://arxiv.org/abs/2103.01055">ICCV'2021</a>], [<a href="https://ieeexplore.ieee.org/document/8937008">TMC'2021</a>], [<a href="https://ieeexplore.ieee.org/document/9547669">TNNLS'2021</a>], [<a href="https://doi.org/10.1109/ICRA40945.2020.9197437">ICRA'2020</a>], [<a href="https://ieeexplore.ieee.org/document/8402111">TMC'2019</a>], [<a href="https://doi.org/10.1609/aaai.v33i01.33018009">AAAI'2019</a>], [<a href="https://doi.org/10.1109/DCOSS.2019.00028">DCOSS'2019</a>], [<a href="http://arxiv.org/abs/1802.02209">AAAI'2018</a>], [<a href="http://www.cs.ox.ac.uk/files/10769/%5BMobiCom2018%5Demr_slam.pdf">MobiCom'2018</a>], [<a href="https://doi.org/10.1109/TWC.2015.2487963">TWC'2016</a>]

---
## **Robust and Rapid Sense Augmentation Support for First Responders (completed)**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/firefighters.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<!-- <div class="caption">
    Example Submodular Settings
</div> -->

From the equator to the Arctic, fire disasters are going to happen more often as a result of anthropogenic climate change. This consequently results in more frequent duty calls of firefighters. However, at the present, firefighting is still regarded as one of the most strenuous and dangerous jobs in the world. A fire incident is often accompanied by a variety of airborne obscurants (e.g., smoke and dust) and poor illumination, making firefighters difficult to navigate themselves and understand the fire ground. We aim to design robust yet real-time **localization, mapping and scene understanding** services that can be directly integrated into the **augmented reality wearables and firefighting robots**. These support systems will, in turn, enhance firefighters' operational capacity and safety in visually-degraded conditions and on resource-constrained platforms.

Research Output: [<a href="https://arxiv.org/abs/2307.03623">EWSN'2023</a>], [<a href="https://arxiv.org/abs/2104.07196">TR-O'2022</a>], [<a href="https://arxiv.org/abs/2206.01589">IROS'2022b</a>], [<a href="https://arxiv.org/pdf/2112.05665.pdf">CPS-ER'2022</a>], [<a href="https://ieeexplore.ieee.org/document/9561738">ICRA'2021</a>], [<a href="https://arxiv.org/abs/2006.02266">SenSys'2020</a>], [<a href="https://arxiv.org/abs/1911.00398">MobiSys'2020</a>], [<a href="https://ieeexplore.ieee.org/document/8968430">RA-L'2020</a>]

Media Exposure: [BBC News](https://www.bbc.co.uk/news/av/uk-scotland-63075749), [BBC Good
 Morning Scotland](https://www.bbc.co.uk/sounds/play/m001cg5x), [STV](http://www.pressdata.co.uk/viewbroadcast.asp?a_id=27804277), [Planet Radio](https://planetradio.co.uk/borders/local/news/firefighters-smart-helmets-heriot-watt/), [Sky News](http://www.pressdata.co.uk/viewbroadcast.asp?a_id=27806734), [Evening
 Standard Tech & Science Daily](https://podcasts.apple.com/gb/podcast/ai-smart-helmets-give-firefighters-superhero-ability/id1516299890?i=1000580906865), [Scottish
 Daily Express](https://www.scottishdailyexpress.co.uk/news/scottish-news/firefighters-could-soon-smart-helmets-28099105), [The Independent](https://www.independent.co.uk/news/uk/experts-scotland-edinburgh-innovation-university-of-edinburgh-b2176943.html), [Scottish
 Field](https://www.scottishfield.co.uk/living/firefighters-get-hi-tech-help-from-robotarium/), [Scottish Daily Mail](https://www.scottishdailyexpress.co.uk/news/scottish-news/firefighters-could-soon-smart-helmets-28099105), [Italy
 24 News](https://news.italy-24.com/trends/115673/Helmets-with-artificial-intelligence-to-help-firefighters.html), [Irish
 News](https://www.irishnews.com/magazine/technology/2022/09/28/news/firefighters_could_soon_have_smart_helmets_to_help_locate_blaze_victims-2842709/), [Engineering
 & Technology](https://eandt.theiet.org/content/articles/2022/09/smart-helmets-could-help-firefighters-locate-blaze-victims/), [Digit
 News](https://www.digit.fyi/scots-firefighters-national-robotarium-smart-helmet/)


---
## **Robust Identity Inference across Digital and Physical Worlds (completed)**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/human_id.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Key to realizing the vision of human-centred computing is the ability for machines to recognize people, so that spaces and devices can become truly personalized. However, the unpredictability of real-world environments impacts robust recognition, limiting usability. In real conditions, human identification systems have to handle issues such as out-of-set subjects and domain deviations, where conventional supervised learning approaches for training and inference are poorly suited. With the rapid development of Internet of Things (IoT), we advocate a new labelling method that exploits signals of opportunity hidden in heterogeneous IoT data. The key insight is that **one sensor modality can leverage the signals measured by other co-located sensor modalities to improve its own labelling performance**. If identity associations between heterogeneous sensor data can be discovered, it is possible to automatically label data, leading to more robust human recognition, without manual labelling or enrolment. On the other side of the coin, we also study the privacy implication for such cross-modal identity association.

Research Output: [<a href="https://arxiv.org/abs/2001.08211">WWW'2020</a>], [<a href="https://arxiv.org/abs/1908.09002">WWW'2019</a>], [<a href="https://ieeexplore.ieee.org/document/8755294">IoT-J'2019</a>], [<a href="https://arxiv.org/abs/1912.04836">UbiComp'2018</a>], [<a href="https://dl.acm.org/doi/10.1145/3267242.3267252">ISWC'2018</a>], [<a href="https://dl.acm.org/doi/10.1145/3055031.3055073">IPSN'2017</a>]