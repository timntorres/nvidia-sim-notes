# Nvidia Simulation Notes

### Contents

- [Overview](#overview)
  - [Omniverse](#omniverse)
- [Examples](#examples)
  - Techman "cobots"
- [Glossary](#glossary)

# Overview

This section describes the core technologies.

## Omniverse

Omniverse is Nvidia's development platform for 3D applications and services, built on [OpenUSD](#openusd).

## Isaac Sim

Isaac Sim is an application, built on top of Omniverse, for robotics simulation environments.

## Cosmos

Cosmos is Nvidia's platform that uses generative AI to assist in designing physical AI systems. It consists of Cosmos Predict, Cosmos Transfer, and Cosmos Reason ([link](https://docs.nvidia.com/cosmos/latest/introduction.html)).

# Examples

- Techman Robot Inc. develops "cobots" for automated quality inspection.
  - They used **Isaac Sim** "to simulate, test, and optimize" their robots.
  - They used Nvidia GPUs "for model training in the cloud and inference on the robots." See also: **NeMo**, **TensorRT**, and **Triton Inference Server** ([link](https://youtu.be/b2yjubjQ5Xs)).

# Glossary

#### OpenUSD

Short for Universal Scene Description, and originally developed by Pixar, OpenUSD is an open-source framework for 3D content. Omniverse is built on OpenUSD.
