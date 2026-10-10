---
layout: default
lang: it
title: Simone Filippi
tagline: Backend engineer
description: "Backend engineer: servizi .NET con Kafka e RabbitMQ. Nel tempo libero progetti di elaborazione audio e machine learning, in Rust e Python."
---

[English](/)
{: style="text-align: right"}

# Simone Filippi

Sono un backend engineer e vivo a Roma. Di giorno scrivo servizi .NET che si parlano tramite Kafka e RabbitMQ, per una piattaforma di gaming online; nel tempo libero mi diverto con l'elaborazione audio e il machine learning, in Rust e Python.

## Progetti

### [Spatial Audio Upmixer](https://github.com/coderynx/spatial-audio-upmixer)

Converte mix stereo e surround in bed multicanale fino a 7.1.4, esportati come WAV o ADM-BWF, con separazione neurale degli stem e una catena di mastering. Il nucleo DSP è scritto in Rust ed è condiviso tra il render offline e l'anteprima nel browser. Intorno c'è uno strato in Python, scelto per far girare i modelli di separazione (SCNet su MLX, BS-RoFormer, Mel-Band RoFormer), insieme a un backend FastAPI, un mixer in React e un'app desktop con Tauri. Ho scritto anche un harness di valutazione su MUSDB18-HQ.

### [Flownodes](https://github.com/coderynx/flownodes)

Una piattaforma di automazione IoT costruita sui virtual actor di Microsoft Orleans. Collega dispositivi e altre fonti di dati, e le integrazioni personalizzate si caricano come plugin.

## Altri progetti

- [MessagingKit](https://github.com/coderynx/messaging-kit): framework di messaggistica leggero per .NET (RabbitMQ).
- [MediatorKit](https://github.com/coderynx/mediator-kit): un mediator per .NET, pensato come alternativa a MediatR.
- [Functional](https://github.com/coderynx/functional): tipi Option e Result per C#, con estensioni per ASP.NET Core.
- [MediaBedrock](https://github.com/coderynx/media-bedrock): pipeline di elaborazione multimediale con plugin (C#).
- [Slip & Fall](https://github.com/coderynx/slipandfall): rilevamento delle cadute tramite classificazione di immagini (C#, ML.NET).
- [Train Delta Forecasting](https://github.com/coderynx/train-delta-forecasting): prevede i ritardi dei treni a partire da dati geospaziali (C#, ML.NET, LightGBM, PostGIS).
- [x86 Operating System](https://github.com/coderynx/os): un piccolo kernel x86 con una shell tutta sua (C, assembly, QEMU).
- Homelab: un micro data center self-hosted a base di container, tra hardware locale e Azure (Proxmox, Docker, Kubernetes).

## Contatti

Il modo più semplice per contattarmi è l'[email](mailto:coderynx@proton.me). Mi trovi anche su [LinkedIn](https://linkedin.com/in/coderynx) e [GitHub](https://github.com/coderynx).
