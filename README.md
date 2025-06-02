# Awesome Text-to-Audio Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)

This is a repository for organizing papers, codes and other resources related to Text-to-Audio Generation (TTA), where **audio** denotes primarily **ambiant sound or music**.


Note: Resources related to speech synthesis are not included in this repo.  

Welcome to PR if you want to add some resources !
<!-- - [x] Add T2A resources  -->
<!-- - [] Add V2A resources -->

## Papers

### Foundational TTA Models

- Fugatto 1: Foundational Generative Audio Transformer Opus 1 [ICLR 2025] [Paper](https://openreview.net/forum?id=B2Fqu7Y2cd)


- AudioX: Diffusion Transformer for Anything-to-Audio Generation [arXiv 2025] [Paper](https://arxiv.org/abs/2412.09892)

- TangoFlux: Super Fast and Faithful Text to Audio Generation with Flow Matching and Clap-Ranked Preference Optimization [arXiv 2025] [Paper](https://arxiv.org/abs/2412.21037) / [Code](https://github.com/declare-lab/TangoFlux)

- CosyAudio: Improving Audio Generation with Confidence Scores and Synthetic Captions [arXiv 2025] [Paper](https://arxiv.org/abs/2501.16761)


- ETTA: Elucidating the Design Space of Text-to-Audio Models [arXiv 2024] [Paper](https://arxiv.org/abs/2412.19351)

- Make Some Noise: Towards LLM audio reasoning and generation using sound tokens [ICASSP 2025] [Paper](https://arxiv.org/abs/2503.22275)

- MambaFoley: Foley Sound Generation using Selective State-Space Models [ICASSP 2025] [Paper](https://arxiv.org/abs/2409.09162)

- EzAudio: Enhancing Text-to-Audio Generation with Efficient Diffusion Transformer [arXiv 2024] [Paper](https://arxiv.org/abs/2409.10819) / [Code](https://github.com/haidog-yaqub/EzAudio)

- GenAU: Taming Data and Transformers for Audio Generation [arXiv 2024] [Paper](https://arxiv.org/abs/2406.19388) / [Code](https://github.com/snap-research/GenAU)

- Stable-Audio-Open [arXiv 2024] [Paper](https://arxiv.org/abs/2407.14358) / [Code](https://github.com/Stability-AI/stable-audio-tools)

- Stable-Audio 2: Long-form music generation with latent diffusion [arXiv 2024] [Paper](https://arxiv.org/abs/2404.10301) 

- Stable Audio 1: Fast Timing-Conditioned Latent Audio Diffusion [ICML 2024] [Paper](https://arxiv.org/abs/2402.04825)

- Masked Audio Generation using a Single Non-Autoregressive Transformer [ICLR 2024] [Paper](https://arxiv.org/abs/2401.04577) / [Code](https://github.com/facebookresearch/audiocraft/blob/main/docs/MAGNET.md)

- SpecMaskGIT: Masked Generative Modeling of Audio Spectrograms for Efficient Audio Synthesis and Beyond [arXiv 2024] [Paper](https://arxiv.org/abs/2406.17672v2) 

- FlashAudio: Rectified Flows for Fast and High-Fidelity Text-to-Audio Generation [arXiv 2024] [Paper](https://arxiv.org/abs/2410.12266)

- AudioLDM 2: Learning Holistic Audio Generation with Self-supervised Pretraining [TASLP 2024] [Paper](https://arxiv.org/abs/2308.05734) / [Code](https://github.com/haoheliu/audioldm2)

- LAFMA: A Latent Flow Matching Model for Text-to-Audio Generation [Interspeech 2024] [Paper](https://arxiv.org/abs/2406.08203) / [Code](https://github.com/gwh22/LAFMA)

- Auffusion: Leveraging the Power of Diffusion and Large Language Models for Text-to-Audio Generation [arXiv 2024] [Paper](https://arxiv.org/abs/2401.01044) / [Code](https://github.com/happylittlecat2333/Auffusion)

- AudioGen: Textually Guided Audio Generation [ICLR 2023] [Paper](https://arxiv.org/abs/2209.15352)

- Make-An-Audio 2: Temporal-Enhanced Text-to-Audio Generation [arXiv 2023] [Paper](https://arxiv.org/abs/2305.18474) / [Code](https://github.com/Text-to-Audio/Make-An-Audio)

- Tango: Text-to-Audio Generation using Instruction-Tuned LLM and Latent Diffusion Model [ACM MM 2023] [Paper](https://arxiv.org/abs/2304.13731) / [Code](https://github.com/declare-lab/tango)

- Make-An-Audio: Text-To-Audio Generation with Prompt-Enhanced Diffusion Models [ICML 2023] [Paper](https://arxiv.org/abs/2301.12661) / [Code](https://github.com/Text-to-Audio/Make-An-Audio)

- AudioLDM: Text-to-Audio Generation with Latent Diffusion Models [ICML 2023] [Paper](https://arxiv.org/abs/2301.12503) / [Code](https://github.com/haoheliu/AudioLDM)

- Diffsound: Discrete Diffusion Model for Text-to-sound Generation [TASLP 2022] [Paper](https://arxiv.org/abs/2207.09983) / [Code](https://github.com/yangdongchao/Text-to-sound-Synthesis)


### TTA with Fine-grained Control
- T-FOLEY: A Controllable Waveform-Domain Diffusion Model for Temporal-Event-Guided Foley Sound Synthesis [ICASSP 2024] [Paper](https://arxiv.org/abs/2401.09294) / [Code](https://github.com/YoonjinXD/T-foley)

- Sketch2Sound: Controllable Audio Generation via Time-Varying Signals and Sonic Imitations [ICASSP 2025] [Paper](https://arxiv.org/abs/2412.08550)

- SILA: Signal-to-Language Augmentation for Enhanced Control in Text-to-Audio Generation [arXiv 2024] [Paper](https://arxiv.org/abs/2412.09789)

- RiTTA: Modeling Event Relations in Text-to-Audio Generation [arXiv 2024] [Paper](https://arxiv.org/abs/2412.15922)

- PicoAudio: Enabling Precise Timestamp and Frequency Controllability of Audio Events in Text-to-audio Generation [ICASSP 2025] [Paper](https://arxiv.org/abs/2407.02869) / [Code](https://github.com/zeyuxie29/PicoAudio)

- Controllable Text-to-Audio Generation with Training-Free Temporal Guidance Diffusion [ICME 2024] [Paper](https://ieeexplore.ieee.org/document/10687830) 

- Continuous descriptor-based control for deep audio synthesis [ICASSP 2023] / [Code](https://github.com/neurorave/neurorave)

- AudioComposer: Towards Fine-grained Audio Generation with Natural Language Descriptions [ICASSP 2025] [Paper](https://arxiv.org/abs/2409.12560) / [Code](https://github.com/lavendery/AudioComposer/tree/main)

- Audio Generation with Multiple Conditional Diffusion Model [AAAI 2024] [Paper](https://arxiv.org/abs/2308.11940) / [Code](https://conditionaudiogen.github.io/conditionaudiogen/)


### TTA with Inference Acceleration

- Stable-Audio-Small: Fast Text-to-Audio Generation with Adversarial Post-Training [arXiv 2025] [Paper](https://arxiv.org/abs/2505.08175) / [Code](https://github.com/Stability-AI/stable-audio-tools)


- SoundCTM: Uniting Score-based and Consistency Models for Text-to-Sound Generation [ICLR 2025] [Paper](https://arxiv.org/abs/2405.18503)


- FlashAudio: Rectified Flows for Fast and High-Fidelity Text-to-Audio Generation [arXiv 2024] [Paper](https://arxiv.org/abs/2410.12266)

- ConsistencyTTA: Accelerating Diffusion-Based Text-to-Audio Generation with Consistency Distillation [Interspeech 2024] [Paper](https://arxiv.org/abs/2309.10740) / [Code](https://github.com/Bai-YT/ConsistencyTTA)

- AudioLCM: Text-to-Audio Generation with Latent Consistency Models [ACM MM 2024] [Paper](https://arxiv.org/abs/2406.00356) / [Code](https://github.com/Text-to-Audio/AudioLCM)



### TTA with Reinforcement Learning 
- T2A-Feedback: Improving Basic Capabilities of Text-to-Audio Generation via Fine-grained AI Feedback [ACL 2025] [Paper](https://www.arxiv.org/abs/2505.10561) 


- Tango 2: Aligning Diffusion-based Text-to-Audio Generations through Direct Preference Optimization [ACM MM 2024] [Paper](https://arxiv.org/abs/2404.09956) / [Code](https://github.com/declare-lab/tango)

- BATON: Aligning Text-to-Audio Model with Human Preference Feedback [IJCAI 2024] [Paper](https://arxiv.org/abs/2402.00744) / [Code](https://github.com/hannieliao/Baton)


### TTA with Retrieval-Augmented Generation
- SonicRAG : High Fidelity Sound Effects Synthesis Based on Retrival Augmented Generation [arXiv 2025] [Paper](https://arxiv.org/abs/2505.03244)

- TangoFlux: Super Fast and Faithful Text to Audio Generation with Flow Matching and Clap-Ranked Preference Optimization [arXiv 2025] [Paper](https://arxiv.org/abs/2412.21037) / [Code](https://github.com/declare-lab/TangoFlux)

- Audiobox TTA-RAG: Improving Zero-Shot and Few-Shot Text-To-Audio with Retrieval-Augmented Generation [arXiv 2024] [Paper](https://arxiv.org/abs/2411.05141)

- Retrieval-Augmented Text-to-Audio Generation [ICASSP 2024] [Paper](https://arxiv.org/abs/2309.08051)


### Spatial Audio Generation

- OmniAudio: Generating Spatial Audio from 360-Degree Video [ICML 2025] [Paper](https://arxiv.org/abs/2504.14906) / [Code](https://github.com/liuhuadai/OmniAudio)

- ImmerseDiffusion: A Generative Spatial Audio Latent Diffusion Model [ICASSP 2025] [Paper](https://arxiv.org/pdf/2410.14945) 

- Both Ears Wide Open: Towards Language-Driven Spatial Audio Generation [ICLR 2025] [Paper](https://arxiv.org/abs/2410.10676) / [Code](https://github.com/PeiwenSun2000/Both-Ears-Wide-Open)

- AudioSpa: Spatializing Sound Events with Text [arXiv 2025] [Paper](https://arxiv.org/abs/2502.11219)

## Datasets

- AudioTime: A Temporally-aligned Audio-text Benchmark Dataset [ICASSP 2025] [Paper](https://arxiv.org/abs/2407.02857) / [Code](https://github.com/zeyuxie29/AudioTime)

 

- Sound-VECaps: Improving Audio Generation with Visual Enhanced Captions [ICASSP 2025] [Paper](https://arxiv.org/abs/2407.04416) / [Code](https://github.com/yyua8222/Sound-VECaps)

- Improving Text-To-Audio Models with Synthetic Captions [Interspeech 2024] [Paper](https://arxiv.org/abs/2406.15487)

## Metrics
TODO 

## Toolbox 
TODO