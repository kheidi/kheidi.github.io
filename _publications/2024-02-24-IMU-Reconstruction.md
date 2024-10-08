---
title: "Impact-Aware Foot Motion Reconstruction and Ramp/Stair Detection Using One Foot-Mounted Inertial Measurement Unit"
collection: publications
permalink: /publication/2024-02-24-IMU-Reconstruction
date: 2024-02-24
venue: 'Sensors'
paperurl: 'https://www.mdpi.com/1424-8220/24/5/1480'
---

<a href='https://www.mdpi.com/1424-8220/24/5/1480'>Download paper here</a>

Motion reconstruction using wearable sensors enables broad opportunities for gait analysis outside laboratory environments. Inertial Measurement Unit (IMU)-based foot trajectory reconstruction is an essential component of estimating the foot motion and user position required for any related biomechanics metrics. However, limitations remain in the reconstruction quality due to well-known sensor noise and drift issues, and in some cases, limited sensor bandwidth and range. In this work, to reduce drift in the height direction and handle the impulsive velocity error at heel strike, we enhanced the integration reconstruction with a novel kinematic model that partitions integration velocity errors into estimates of acceleration bias and heel strike vertical velocity error. Using this model, we achieve reduced height drift in reconstruction and simultaneously accomplish reliable terrain determination among level ground, ramps, and stairs. The reconstruction performance of the proposed method is compared against the widely used Error State Kalman Filter-based Pedestrian Dead Reckoning and integration-based foot-IMU motion reconstruction method with 15 trials from six subjects, including one prosthesis user. The mean height errors per stride are 0.03±0.08 cm on level ground, 0.95±0.37 cm on ramps, and 1.27±1.22 cm on stairs. The proposed method can determine the terrain types accurately by thresholding on the model output and demonstrates great reconstruction improvement in level-ground walking and moderate improvement on ramps and stairs.

Recommended citation: Wang, Y., Fehr, K. H., & Adamczyk, P. G. (2024). Impact-Aware Foot Motion Reconstruction and Ramp/Stair Detection Using One Foot-Mounted Inertial Measurement Unit. Sensors, 24(5), Article 5. https://doi.org/10.3390/s24051480