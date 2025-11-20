# VideoLLM Benchmarks \& Datasets


***

## Quick Navigation

- [2017 – Early VideoQA on short clips](#2017--early-videoqa-on-short-clips)
- [2018 – TV show understanding](#2018--tv-show-understanding)
- [2019 – Complex long web videos](#2019--complex-long-web-videos)
- [2020 – Instructional "how-to" videos](#2020--instructional-how-to-videos)
- [2021 – Causal \& temporal reasoning](#2021--causal--temporal-reasoning)
- [2023 – Long-form egocentric \& auto-eval / toolkits](#2023--long-form-egocentric--auto-eval--toolkits)
- [2024 – Temporal, multimodal, long-form \& edited video benchmarks](#2024--temporal-multimodal-long-form--edited-video-benchmarks)
- [2025 – Spatio-temporal reasoning, hour-long videos \& streaming video understanding](#2025--spatio-temporal-reasoning-hour-long-videos--streaming-video-understanding)


***

## 2017 – Early VideoQA on short clips

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **MSRVTT-QA** | Open-domain VideoQA on **MSR-VTT** web clips; factoid questions from captions. | 2,990 | 2,990 | 72,821 | 15.2 | [paper](https://aclanthology.org/2022.emnlp-main.432.pdf) · [data/code](https://github.com/xudejing/video-question-answering) |
| **MSVD-QA** | VideoQA on **MSVD** YouTube clips; open-ended QA generated from descriptions. | 504 | 504 | 13,157 | 9.8 | [paper](https://aclanthology.org/2022.emnlp-main.432.pdf) · [data/code](https://github.com/xudejing/video-question-answering) |
| **TGIF-QA** | GIF-based VideoQA for **repetition counting, state transitions, frame QA**. | 9,575 | 9,575 | 8,506 | 3.0 | [paper](https://arxiv.org/abs/1704.04497) · [data/code](https://github.com/YunseokJANG/tgif-qa) |


***

## 2018 – TV show understanding

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **TVQA** | Large-scale multi-choice VideoQA on **6 TV shows** with video + subtitles. | 2,179 | 15,253 | 15,253 | 11.2 | [paper](https://arxiv.org/abs/1809.01696) · [project / data](http://tvqa.cs.unc.edu) |


***

## 2019 – Complex long web videos

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **ActivityNet-QA** | VideoQA on **complex ActivityNet web videos**, emphasizing long-term temporal reasoning. | 800 | 800 | 8,000* | 111.4 | [paper](https://arxiv.org/abs/1906.02467) · [data/code](https://github.com/MILVLG/activitynet-qa) |


***

## 2020 – Instructional "how-to" videos

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **How2QA** | Multi-choice VideoQA on **HowTo** instructional clips (e.g., how-to videos with narrations). | 1,166 | 2,852 | 2,852 | 15.3 | [HERO paper (introduces How2QA)](https://arxiv.org/abs/2005.00200) · [dataset info](https://hyper.ai/en/datasets/19252) |


***

## 2021 – Causal \& temporal reasoning

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **NExT-QA** | VideoQA benchmark for **causal \& temporal action reasoning** in daily activity videos. | 1,000 | 1,000 | 8,564 | 39.5 | [paper](https://arxiv.org/abs/2105.08276) · [data/code](https://github.com/doc-doc/NExT-QA) |


***

## 2023 – Long-form egocentric \& auto-eval / toolkits

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **EgoSchema** | **Very long-form** egocentric VideoQA (Ego4D-based); multiple-choice QA over ~250 hours of egocentric video. | 5,063 | 5,063 | 5,063 | 180.0 | [paper](https://arxiv.org/abs/2308.09126) · [Kaggle / data](https://www.kaggle.com/competitions/egoschema-public) |
| **AutoEval-Video** | Automatically constructed **open-ended VideoQA benchmark** with LLM-as-a-judge evaluation. | 327 | 327 | 327 | 14.6 | [paper](https://arxiv.org/abs/2311.14906) · [code](https://github.com/Xiuyuan-Chen/AutoEval-Video) |
| **MVBench** | **20-task multi-modal video benchmark** for temporal skills from perception to cognition. | 3,641 | 3,641 | 4,000 | 16.0 | [paper](https://arxiv.org/abs/2311.17005) · [code (Ask-Anything)](https://github.com/OpenGVLab/Ask-Anything) |
| **Video-Bench** | Comprehensive **evaluation toolkit + benchmark** for Video-LLMs (10 tasks over 3 ability levels). | 5,917 | 5,917 | 17,036 | 56.0 | [paper](https://arxiv.org/abs/2311.16103) · [code](https://github.com/PKU-YuanGroup/Video-Bench) |


***

## 2024 – Temporal, multimodal, long-form \& edited video benchmarks

### 2024 – Temporal \& long-form reasoning

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **STAR** | **Situated reasoning** in real-world videos (interaction, sequence, prediction, feasibility questions). | 914 | 7,098 | 7,098 | 11.9 | [paper](https://arxiv.org/abs/2405.09711) · [project](https://bobbywu.com/STAR/) |
| **TempCompass** | Temporal perception benchmark: ordering, duration, concurrency, etc., for VideoLLMs. | 410 | 500 | 7,540 | 11.4 | [paper](https://arxiv.org/abs/2403.00476) · [code](https://github.com/llyx97/TempCompass) |
| **Video-MME** | **Full-spectrum multi-modal evaluation** (visual, audio, text) for video MLLMs across domains and durations. | 900 | 900 | 2,700 | 1,017.9 | [project](https://video-mme.github.io/home_page.html) · [code](https://github.com/MME-Benchmarks/Video-MME) |
| **VideoVista** | Versatile VideoQA benchmark across **diverse content, durations, and abilities**, including cultural splits. | 894 | 3,400 | 25,000 | 131.0 | [paper](https://arxiv.org/abs/2406.11303) · [project](https://videovista.github.io/) · [code](https://github.com/HITsz-TMG/VideoVista) |
| **CinePile** | Long-form VideoQA on **movie-style videos**; emphasizes real long-context understanding. | 9,396 | 9,396 | 303,828 | 160 | [paper](https://arxiv.org/abs/2405.08813) · [project](https://ruchitrawal.github.io/cinepile/) |
| **SFD (Short Film Dataset)** | Story-level benchmark on **1,078 short films**; focuses on narrative and story comprehension. | 1,078 | 1,078 | 4,885 | 780 | [paper](https://arxiv.org/abs/2406.10221) |
| **InfiniBench** | Very-long video benchmark (movies + TV shows), **avg ~4,460 s per video**, multi-skill QA (MCQ + open-ended). | 1,219 | 1,219 | 108,200 | 4,460.4 | [paper](https://arxiv.org/abs/2406.19875) · [project/code](https://github.com/Vision-CAIR/InfiniBench) |
| **MLVU** | Multi-task long video understanding with **flexible video lengths (3 min to 2 hours)** across diverse genres. | 1,334 | – | 3,500 | 720 | [paper](https://arxiv.org/abs/2406.04264) · [code](https://github.com/JUNJIE99/MLVU) · [CVPR 2025] |
| **LVBench** | **Extreme long video** benchmark with average duration of ~68 minutes; diverse tasks for long-term comprehension. | 1,011 | 1,011 | 3,505 | 4,101 | [paper](https://arxiv.org/abs/2406.08035) · [project](https://lvbench.github.io) · [ICCV 2025] |
| **LongVideoBench** | Long-context **video-language interleaved** inputs up to an hour long; tests multimodal reasoning. | 3,763 | 3,763 | 6,678 | ~1,800 | [paper](https://arxiv.org/abs/2407.15754) · [code](https://github.com/longvideobench/LongVideoBench) · [NeurIPS 2024] |

### 2024 – Knowledge, multimodality \& world-model evaluation

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **SOK-Bench** | **Situated open-world commonsense reasoning** in videos, with aligned knowledge graphs and rich rationales. | 10,000 | 10,000 | 44,000 | – | [paper](https://arxiv.org/abs/2405.09713) · [code](https://github.com/csbobby/SOK-Bench) |
| **MMWorld** | Multi-discipline, multi-faceted **world model evaluation in videos** (explanation, counterfactual, prediction, etc.). | 1,910 | 1,910 | 1,599 | 102.3 | [paper](https://arxiv.org/abs/2406.08407) · [code](https://github.com/eric-ai-lab/MMWorld) |
| **VELOCITI** | Video–language **compositional reasoning with strict entailment**; entailment tests over complex movie clips. | 900 | 900 | – | 10.0 | [paper](https://arxiv.org/abs/2406.10889) · [code](https://github.com/katha-ai/VELOCITI) |

### 2024 – Edited \& social-media videos

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **EditVid-QA** | VideoQA on **edited TikTok-style videos** (effect, funny, meme, game); tests understanding of edited content. | 32,000 | 32,000 | 204,000 | – | [paper](https://arxiv.org/abs/2406.10484) |

### 2024 – Specialized domains

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **ViCaS** | Combines **holistic and pixel-level** video understanding with detailed captions and segmentation masks. | 4,000+ | 4,000+ | – | – | [paper](https://arxiv.org/abs/2412.09754) · [code](https://github.com/Ali2500/ViCaS) · [CVPR 2025] |
| **SCBench** | **Sports commentary** generation benchmark with 6-dimensional SCORES metric for fine-grained evaluation. | 5,775 | 5,775 | 5,775 | – | [paper](https://arxiv.org/abs/2412.17637) |


***

## 2025 – Spatio-temporal reasoning, hour-long videos \& streaming video understanding

### 2025 – Hour-long video benchmarks

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **HLV-1K** | Large-scale **hour-long video** benchmark with time-aware queries across frame, event, and long-term reasoning levels. | 1,009 | – | 14,847 | 3,600+ | [paper](https://arxiv.org/abs/2501.01645) · [code](https://github.com/Vincent-ZHQ/HLV-1K-Long-Video-Understanding-Benchmark) · [ICME 2025] |

### 2025 – Spatio-temporal \& multi-turn reasoning

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **V-STaR** | **Video spatio-temporal reasoning** benchmark evaluating "when", "where", and "what" with chain-of-thought logic. | – | – | – | – | [paper](https://arxiv.org/abs/2503.11495) |
| **SVBench** | **Streaming video** understanding with temporal multi-turn dialogues evaluating 9 critical skills. | 1,353 | – | 49,979 | 300-480 | [paper](https://arxiv.org/abs/2502.10810) · [code](https://github.com/yzy-bupt/SVBench) |
| **SCVBench** | **Story-centric video** understanding with multi-turn dialogues and event ordering tasks. | 925 | – | 1,253 | – | [paper](https://www.ijcai.org/proceedings/2025/255) · [IJCAI 2025] |
| **VideoEval-Pro** | Robust long video understanding benchmark with **open-ended short-answer** questions requiring full video comprehension. | 465 | – | 1,289 | 2,295 | [paper](https://arxiv.org/abs/2505.14640) · [code](https://github.com/TIGER-AI-Lab/VideoEval-Pro) |

### 2025 – Narrative \& series understanding

| Benchmark | Short description | \#Videos | \#Clips | \#QA pairs | Avg len (s) | Links |
| :-- | :-- | --: | --: | --: | --: | :-- |
| **SeriesBench** | **Narrative-driven drama series** understanding with 28 specialized tasks across 105 series. | 105 series | – | – | – | [paper](https://arxiv.org/abs/2504.21435) · [CVPR 2025] |


***

## At-a-glance (flat list)

### Pre-2024

- **ActivityNet-QA** (2019) – 800 videos, 8,000 QA, avg 111.4 s
- **AutoEval-Video** (2023) – 327 videos, 327 QA, open-ended auto-eval
- **EgoSchema** (2023) – 5,063 egocentric videos, 5,063 QA, very long clips
- **How2QA** (2020) – 1,166 videos, 2,852 QA, instructional how-to
- **MSRVTT-QA** (2017) – 2,990 videos, 72,821 QA
- **MSVD-QA** (2017) – 504 videos, 13,157 QA
- **MVBench** (2023) – 3,641 videos, 4,000 QA
- **NExT-QA** (2021) – 1,000 videos, 8,564 QA
- **TGIF-QA** (2017) – 9,575 GIF clips, 8,506 QA
- **TVQA** (2018) – 2,179 videos, 15,253 QA
- **Video-Bench** (2023) – 5,917 videos, 17,036 QA


### 2024

- **CinePile** (2024) – 9,396 videos, 303,828 QA, long-form movies
- **EditVid-QA** (2024) – 32,000 edited clips, 204,000 QA
- **InfiniBench** (2024) – 1,219 videos, 108,200 QA, avg 4,460.4 s
- **LongVideoBench** (2024) – 3,763 videos, 6,678 QA, interleaved video-language
- **LVBench** (2024) – 1,011 videos, 3,505 QA, extreme long videos (avg 68 min)
- **MLVU** (2024) – 1,334 videos, 3,500 QA, 3 min to 2 hours
- **MMWorld** (2024) – 1,910 videos, 1,599 QA
- **SCBench** (2024) – 5,775 sports video clips, sports commentary
- **SFD** (2024) – 1,078 short films, 4,885 QA
- **SOK-Bench** (2024) – 10,000 clips, 44,000 QA
- **STAR** (2024) – 914 videos, 7,098 QA
- **TempCompass** (2024) – 410 videos, 7,540 QA
- **VELOCITI** (2024) – 900 videos, entailment-style tests
- **ViCaS** (2024) – 4,000+ videos with captions and segmentation
- **Video-MME** (2024) – 900 videos, 2,700 QA
- **VideoVista** (2024) – 894 videos, 25,000 QA


### 2025

- **HLV-1K** (2025) – 1,009 hour-long videos, 14,847 QA
- **SCVBench** (2025) – 925 videos, 1,253 QA, story-centric with multi-turn dialogues
- **SeriesBench** (2025) – 105 drama series, narrative understanding
- **SVBench** (2025) – 1,353 streaming videos, 49,979 QA with temporal dialogues
- **V-STaR** (2025) – Spatio-temporal reasoning benchmark
- **VideoEval-Pro** (2025) – 465 videos, 1,289 open-ended QA

***

