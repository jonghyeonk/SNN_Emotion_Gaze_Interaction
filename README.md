# Non-Contact Neuromorphic Emotion Inference via Gaze Interaction

Official implementation of the paper: **"Non-Contact Neuromorphic Emotion Inference via Gaze Interaction"**.

This repository provides the spiking neural network (SNN) simulation framework built on **snnTorch**, incorporating device-calibrated RRAM (h-BN/WSe2) characteristics and Variation-Aware Training (VAT) to achieve robust, low-power social emotion decoding.

---

## 🚀 Overview
- **Pupillometry Feature Extraction:** Extracts single and interactive multidimensional pupillary features (hippus dynamics, cross-symmetry, accommodation speed) from non-contact IR recordings.
- **Spiking Neural Network (SNN):** Optimized SNN architecture implemented with snnTorch, utilizing solid spike encoding and spike-event loss ($L_{spike}$).
- **Hardware-Aware Simulation:** Emulates RRAM crossbar array non-idealities (differential-pair mapping, stochastic conductance variation, 5-bit weight quantization) and applies Variation-Aware Training (VAT) for hardware resilience.

## 📄 Data and Code Availability
In strict compliance with the privacy regulations governed by our Institutional Review Board (IRB protocols BE2013-9 and BE2016-02), raw time-series pupillometry datasets are not included in this repository. Instead, this repository stores the **anonymized, preprocessed feature datasets** along with the complete execution codes for both the proposed Spiking Neural Network (SNN) and baseline models, enabling full reproducibility of the study.

---

## 🛠️ Requirements & Installation

This code is tested on Python 3.13.9 with PyTorch and snnTorch.

