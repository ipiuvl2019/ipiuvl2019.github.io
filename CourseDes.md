---
title: Course Description
nav: true
---

# Vision-based localization: Principles and Applications 

The term visual localization refers to a wide spectrum of problems where visual data is utilized to localize the camera's position and/or orientation in a given referential. Visual localization is crucial for various applications including but not limited to: virtual/augmented reality, 3D reconstruction, robotics and vehicular applications (e.g. assisted and autonomous driving).

This tutorial covers visual localization from basics to applications including a comprehensive review of recent approaches in the field.
This course is composed of five main parts:
The first session reminds the fundamentals of visual localization and the traditional feature-based visual localization in a tri-dimensional map.
Modern and highly effective deep-learning based approaches will be introduced in the second part of this talk. The creation of a synthetic dataset simulating challenging conditions (e.g. lighting variations, occlusions, etc.) for learning purpose will also be discussed.
Following these talks, NAVER LABS will present a concrete example of technology for a Scalable and Semantic Indoor Mapping (SSIM). This overview incorporates the key elements of their system including robotics technologies and localization. 
Another, application of short-term localization for connected vehicles will also be introduced as another use case where visual localization plays a crucial role.
Finally, this tutorial will be concluded on a deep learning based techniques for visual localization.

## 1. Basic approaches of visual feature-based localization <sup>(Dr. Deokhwa Kim, Naver Labs)</sup>

In order to estimate a 6-D pose by using only a visual sensor in a device, various technologies are needed. Simultaneous localization and mapping techniques alongside with visual information are used to generate a map for aimed environments, and visual localization are applied to estimate a 6-D pose in the generated map. In the visual localization, there are two main approaches, which are feature-based and deep-learning-based. In this talk, I will give a brief overview of visual localization procedures, and talk about feature-based visual localization approaches in detail. 

## 2. Modern approaches of visual localization <sup>(Dr. Martin Humenberger, Naver Labs Europe)</sup>

Visual localization refers to estimating the 6DOF camera pose within a given 3D scene model using images. In this talk I will first present a quick overview about different methods, and second, I will detail more recent approaches which utilise deep learning techniques for visual localization. Traditional methods use descriptor matching between the query image and the 3D scene model as basis for pose computation, while modern learning-based approaches try to directly regress the pose or intermediate results of the localization pipeline. Furthermore, I will introduce a new synthetic dataset which explicitly targets challenging situations such as lighting changes and occlusions.

## 3. Scalable and Semantic Indoor Mapping in NAVER LABS <sup>(Dr. Donghwan Lee, Naver Labs)</sup>

3D indoor maps are useful in various ways, from helping people find their way at complex transit interchanges to supporting more efficient logistics. However, creating and updating those maps are labor-intensive tasks that require many human professionals. Scalable and Semantic Indoor Mapping (SSIM) is a technology that creates, maintains, and publishes 3D maps of indoor environments such as airports, train stations, and shopping malls with minimal human intervention. In NAVER LABS’ SSIM scenario, the mapping robot, M1, is capturing high-precision data to create accurate 3D indoor maps. The maps will then be kept updated using the information gathered by AROUND, our service robot. Finally, deep learning based image recognition technology will recognize venues and detect changes automatically for semantic mapping. This talk will give an overview of our robotics, localization, and image recognition technologies, which are key elements of SSIM.

## 4. Mapping and Localization for Connected Cars <sup>(Dr. Francois Rameau, KAIST)</sup>

Accurate, reliable and fast vehicle localization is desirable for a wide spectrum of applications in assisted and autonomous driving. Recently, the progress in network and communication paves the way to collaborative localization techniques.
In this tutorial, we will present the challenges, the tools and the practical deployment of a multi-car localization approach relying exclusively on visual data and standard LTE connection.
This talk will also introduce, an original augmented-reality application taking advantage of multi-car localization: the multi-car see-through system.

## 5. Learning based approaches of visual localization <sup>(Prof. In So Kweon, KAIST)</sup>

Recent advances in Deep Learning have shown breakthrough perforamnces in many computer vision problems.
For geometric vision, however, conventional approaches show better performances in challenging conditions.
In this talk, we will give a brief overview about geometric vision approaches to estimate the camera pose and the 3D scene geometry.

​ 
