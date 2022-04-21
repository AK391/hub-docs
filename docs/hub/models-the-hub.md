---
title: The Model Hub
---

<h1>The Model Hub</h1>

## What is the Model Hub?

The Model Hub is where the members of the Hugging Face community can host all of their model checkpoints for simple storage, discovery, and sharing. Pre-trained models are available to be downloaded using [TODO]

You can refer to the following video for a guide on navigating the Model Hub:

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/XvSGPZFEjDY" title="Model Hub Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Exploring Models

TODO

### Searching with the UI

TODO

### Tasks

TODO:

(Also adding new tasks) -- Am I sure that this needs to be in here? There's currently no documentation on this, and my goal right now isn't to write new content...

### Searching the Hub with Python

[TODO: At the moment this has an entire page, written as a tutorial... should I split it up?]

## Libraries

The Hub supports a number of libraries and we're working on expanding this support! We're happy to welcome to the Hub a set of Open Source libraries that are pushing Machine Learning forward.

The table below summarizes the supported libraries and how they are integrated. Find all our supported libraries [here](https://github.com/huggingface/hub-docs/blob/main/js/src/lib/interfaces/Libraries.ts)! 

| Library               | Description                                                                   | Inference API | Widgets | Download from Hub | Push to Hub |
|-----------------------|-------------------------------------------------------------------------------|---------------|-------:|-------------------|-------------|
| [🤗 Transformers](https://github.com/huggingface/transformers)         | State-of-the-art Natural Language Processing for Pytorch, TensorFlow, and JAX |       ✅       |    ✅   |         ✅         |      ✅      |
| [Adapter Transformers](https://github.com/Adapter-Hub/adapter-transformers)  | Extends 🤗Transformers with Adapters.                                          |       ❌       | ❌      |         ✅         |      ✅      |
| [AllenNLP](https://github.com/allenai/allennlp)              | An open-source NLP research library, built on PyTorch.                        |       ✅       |    ✅   |         ✅         |      ❌      |
| [Asteroid](https://github.com/asteroid-team/asteroid)              | Pytorch-based audio source separation toolkit                                 |       ✅       | ✅     |         ✅         |      ❌      |
| [docTR](https://github.com/mindee/doctr) | Models and datasets for OCR-related tasks in PyTorch & TensorFlow | ✅ | ✅ | ✅ | ❌ |
| [ESPnet](https://github.com/espnet/espnet)                | End-to-end speech processing toolkit (e.g. TTS)                               |       ✅       | ✅      |         ✅         |      ❌      |
| [Flair](https://github.com/flairNLP/flair)                 | Very simple framework for state-of-the-art NLP. |       ✅       |    ✅   |         ✅         |      ❌      |
| [Pyannote](https://github.com/pyannote/pyannote-audio)              | Neural building blocks for speaker diarization.                               |       ❌       |    ❌   |         ✅         |      ❌      |
| [PyCTCDecode](https://github.com/kensho-technologies/pyctcdecode)                  | Language model supported CTC decoding for speech recognition                |       ❌       |    ❌   |         ✅         |      ❌      |
| [Sentence Transformers](https://github.com/UKPLab/sentence-transformers) | Compute dense vector representations for sentences, paragraphs, and images.   |       ✅       |    ✅   |         ✅         |      ✅      |
| [spaCy](https://github.com/explosion/spaCy)                 | Advanced Natural Language Processing in Python and Cython.                    |       ✅       |    ✅   |         ✅         |      ✅      |
| [Speechbrain](https://speechbrain.github.io/)                 | A PyTorch Powered Speech Toolkit. |       ✅       |    ✅   |         ✅         |      ❌      |
| [TensorFlowTTS](https://github.com/TensorSpeech/TensorFlowTTS)         | Real-time state-of-the-art speech synthesis architectures.                    |       ❌       |    ❌   |         ✅         |      ❌      |
| [Timm](https://github.com/rwightman/pytorch-image-models)                  | Collection of image models, scripts, pretrained weights, etc.                 |       ❌       |    ❌   |         ✅         |      ❌      |
| [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3)                  | Set of reliable implementations of deep reinforcement learning algorithms in PyTorch                  |       ❌       |    ❌   |         ✅         |      ✅      |


### How can I add a new library to the Inference API?

Read about it in [Adding a Library Guide](/docs/hub/adding-a-library).