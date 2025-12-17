# API Surface

AI4I-Orchestrate exposes a unified API surface for Language AI services.

#### ASR APIs

* Streaming and batch speech-to-text
* Inputs: audio, language, domain
* Outputs: transcript, confidence, segmentation

#### NMT APIs

* Text translation between language pairs
* Inputs: source text, source language, target language, domain
* Outputs: translation, alternatives, model metadata

#### TTS APIs

* Text-to-speech synthesis
* Inputs: text, language, voice parameters
* Outputs: audio stream, model version

#### LLM APIs

* Text generation and reasoning
* Inputs: prompt, system instructions, generation parameters
* Outputs: generated text, token usage

#### OCR APIs

* Text extraction from images and documents

#### Metadata APIs

* Discovery of available models, tenants, and policy configurations
