---
layout: default
lang: en
title: Simone Filippi
tagline: Backend engineer
---

[Italiano](/it/)
{: style="text-align: right"}

# Simone Filippi

I'm a backend engineer based in Rome. At work I write .NET services that talk to each other over Kafka and RabbitMQ, for an online gaming platform. Outside work I mostly play around with audio processing and machine learning, in Rust and Python.

## Projects

### [Spatial Audio Upmixer](https://github.com/coderynx/spatial-audio-upmixer)

Upmixes stereo and surround mixes to multichannel beds up to 7.1.4, exported as WAV or ADM-BWF, with neural stem separation and a mastering chain. The DSP core is written in Rust and shared by the offline renderer and the browser preview. Python is the layer around it, chosen for the separation models (SCNet on MLX, BS-RoFormer, Mel-Band RoFormer), alongside a FastAPI backend, a React mixer and a Tauri desktop app. I also wrote an evaluation harness on MUSDB18-HQ.

### [Flownodes](https://github.com/coderynx/flownodes)

An IoT automation platform built on Microsoft Orleans virtual actors. It connects devices and other data sources, and custom integrations are loaded as plugins.

## Other projects

- [MessagingKit](https://github.com/coderynx/messaging-kit): lightweight messaging framework for .NET (RabbitMQ).
- [MediatorKit](https://github.com/coderynx/mediator-kit): a mediator for .NET, as an alternative to MediatR.
- [Functional](https://github.com/coderynx/functional): Option and Result types for C#, with ASP.NET Core extensions.
- [MediaBedrock](https://github.com/coderynx/media-bedrock): media processing pipelines with plugins (C#).
- [Slip & Fall](https://github.com/coderynx/slipandfall): fall detection using image classification (C#, ML.NET).
- [Train Delta Forecasting](https://github.com/coderynx/train-delta-forecasting): predicts train delays from geospatial data (C#, ML.NET, LightGBM, PostGIS).
- [x86 Operating System](https://github.com/coderynx/os): a small x86 kernel with its own shell (C, assembly, QEMU).
- Homelab: a self-hosted micro data center with containers, mixing local hardware and Azure (Proxmox, Docker, Kubernetes).

## Contact

The easiest way to reach me is by [email](mailto:coderynx@proton.me). I'm also on [LinkedIn](https://linkedin.com/in/coderynx) and [GitHub](https://github.com/coderynx).
