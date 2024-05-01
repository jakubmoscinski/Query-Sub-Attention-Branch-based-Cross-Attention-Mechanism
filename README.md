# Query-Sub-Attention-Branch-based-Cross-Attention-Mechanism

## Overview and Purpose
* This repository aims to present and allow for testing my proposed Query Sub-Attention Branch-based Cross-Attention Mechanism. 
* This mechanism is an alternative type of attention mechanism in Transformer-based architectures.
* My proposed mechanism helped to improve the accuracy of the Dense-TNT model (trained on the Argoverse 2 - Motion Forecasting Dataset) in predicting vehicle motion. (Min-FDE reduction of between 5.13% and 6.19%). The results are described in the article "Traffic Motion Forecasting with Lightweight Network: A Novel Query Sub-Attention Branch-based Cross-Attention Mechanism" (the article is currently under review).
* Further works aim to implement the mechanism in other models and test on other datasets

## Results reproduction
At this point, I would like to encourage all interested parties to test my solution (especially by comparing the performance with the base model).
* The exact instructions for training and evaluation are the same as for the orginal Dense-TNT: (https://github.com/Tsinghua-MARS-Lab/DenseTNT or check the README.md in the model subdirectory)
* Link to the dataset used: (https://www.argoverse.org/av2.html). Please look for Argoverse 2 Motion Forecasting Dataset on the bottom of the page.

## What was changed
* In the DenseTNT the proposed mechanism was applied in: Application of Query Sub-Attention Branch-based Cross-Attention/src/modeling/lib.py
* The rest of the basebone model remain unchanged.
* I strongly encourage you to compare the differences between my version and the original model
