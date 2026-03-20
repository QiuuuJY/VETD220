# VETD220

Official repository of **VETD220**, a **visible-event multimodal benchmark** for **anti-UAV tracking**.

## Overview

Anti-UAV tracking in real-world environments is challenging due to factors such as fast motion, small targets, illumination variation, background clutter, and motion blur. To support research in this direction, we present **VETD220**, a visible-event multimodal dataset designed for anti-UAV tracking.

VETD220 contains **220 videos** and **68,379 visible-event sequence pairs**, covering **6 real-world scenarios** and **15 challenging attributes**. The dataset provides synchronized visible frames and event streams, supporting both **model training** and **fair evaluation** for visible-event anti-UAV tracking.

## Features

- Visible-event multimodal data for anti-UAV tracking
- 220 videos and 68,379 visible-event sequence pairs
- 6 real-world scenarios
- 15 challenging attributes
- Supports both training and evaluation
- Designed for single-object tracking

## Benchmark Task

VETD220 is designed for **single-object anti-UAV tracking** with visible-event multimodal input.

### Evaluation Metrics
We adopt the standard single-object tracking metrics:
- **SR**: Success Rate
- **PR**: Precision Rate

## Dataset Split

The dataset is divided into:
- **Training set:** 160 videos
- **Validation set:** 20 videos
- **Test set:** 40 videos

## Dataset Structure

A recommended folder structure is as follows:


```text
VETD220/
├── train/
│   ├── sequence_001/
│   │   ├── aps/
│   │   ├── event/
│   │   └── label.txt
│   ├── sequence_002/
│   │   ├── aps/
│   │   ├── event/
│   │   └── label.txt
│   ├──  ...
│   └──  list_train.txt
├── test/
│   ├── sequence_001/
│   │   ├── aps/
│   │   ├── event/
│   │   └── label.txt
│   ├── sequence_002/
│   │   ├── aps/
│   │   ├── event/
│   │   └── label.txt
│   ├──  ...
│   └──  list_test.txt
