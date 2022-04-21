# Spectral-Propagation-Net
This repository contains the codes for paper ***"[High-fidelity Hyperspectral Snapshot of Physical World: System Architecture, Dataset and Model](https://ieeexplore.ieee.org/document/9760181)"
(IEEE Journal of Selected Topics in Signal Processing (JSTSP), VOL. X, 2022)*** by [Erqi Huang](https://erqihuang.github.io/), Maoqi Zhang, [Zhan Ma](https://vision.nju.edu.cn/fc/d3/c29470a457939/page.htm), Linsen Chen, Yiyu Zhuang, [Xun Cao](https://cite.nju.edu.cn/People/Faculty/20190621/i5054.html).

## Contents
1. [Overview](#overview)
2. [System Architecture](#system-architecture)
3. [Dataset](#dataset)
4. [Model](#model)
5. [Usage](#usage)
6. [Citation](#citation)

## Overview
It is extremely challenging to acquire high-fidelity video of physical world at high spectral, high spatial and high temporal resolution (H<sup>3</sup>R) granularities simultaneously. Existing hyperspectral scanning cameras offer groundtruth with sufficient spatiospectral resolutions but largely lack temporal details; while recent hyperspectral snapshot cameras (e.g., CASSI, PMVIS) enable high temporal resolution acquisition but present inferior capacity to measure fine-grained spatiospectral components as groundtruth. This work builds a joint snapshot-scanning spectral system (JS<sup>4</sup>), by means of which the acquired low spatiospectral video-rate snapshots can be guided by synchronous-captured high spatiospectral groundtruth in the hyperspectral propagation. We first register the snapshot-scanning image pairs of the JS<sup>4</sup> using a physical imaging model, and then generate a computational hyperspectral image light dataset (CHILD) having both video-rate snapshot and corresponding scanned groundtruth of a specific scene. Taking advantage of the CHILD, we later develop an end-to-end spectral propagation network (SPN) that applies the spectral guided filter and channel attention mechanism to restore rich, and high-fidelity hyperspectral measurement of the dynamic physical world from limited spatiospectral snapshot. The proposed SPN is evaluated extensively using non-blind, blind and semi-blind experiments. For the proposed CHILD and other abundant datasets, our SPN outperforms the state-of-the-art methods greatly.

## System Architecture
Joint Snapshot-Scanning Spectral System (JS<sup>4</sup>)

## Dataset
Computational Hyperspectral Image Light Datase (CHILD)

## Model
Spectral Propagation Network (SPN)

## Usage
### Download the SPN repository
### Training
### Testing

## Citation
If you find our work useful for your research, please consider citing the following papers

```
@ARTICLE{9760181,  
author={Huang, Erqi and Zhang, Maoqi and Ma, Zhan and Chen, Linsen and Zhuang, Yiyu and Cao, Xun},  
journal={IEEE Journal of Selected Topics in Signal Processing},   
title={High-fidelity Hyperspectral Snapshot of Physical World: System Architecture, Dataset and Model},   
year={2022},  
volume={},  
number={},  
pages={1-1},  
doi={10.1109/JSTSP.2022.3167891}}
```

Erqi Huang, Nanjing University, Email: erqihuang@smail.nju.edu.cn

