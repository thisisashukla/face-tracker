# Face Tracker

This repository contains the code for demonstrating different use cases which leverage facial landmark keypoints. The facial landmark model is a Tf-Js implementation of the [paper](https://arxiv.org/pdf/1907.06724.pdf).

## Drowsy Alarm

Using the keypoint [map](./mesh_map.jpg) we can calculate the distance between keypoints of facial part such as eyelids (upper and lower) and lips (upper and lower) and put a threshold on this distance to identify when the person is drowsing off. A moving average smoothing can reduce noise.




