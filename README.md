# Training SAEs wth an activation of topk by absolute value

## Acknowledgements
Thanks to Alice Rigg, James Oldfield, taha_yssne, Kabir Kumar, and Yixiong Hao for helpful discussion and comments. 

## Overview
This repository contains code for training Sparse Autoencoders (SAEs) using a modified activation function. The activation selects the top-k neurons by absolute value, but preserves the original sign (positive or negative) of the selected neurons.

## Purpose

The main questions we aim to answer are:
- Are there any features that exhibit a change in polarity at the center of their activation range?
- How does the top-k by absolute value activation function perform in comparison to the standard top-k and ReLU activation functions?
- What are the effects of restricting the dictionary to a limited number of features with signed values?

## Referencess

- https://cdn.openai.com/papers/sparse-autoencoders.pdf
