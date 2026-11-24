# Awesome-Real-Time-Voice-AI-Conversational-Voice

# Awesome-Real-Time-Voice-AI-Conversational-Voice

# Top Real-Time Voice AI & Conversational Voice Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Low-Latency Voice Agents, Speech-to-Speech Models, WebRTC Audio Pipelines, STT/TTS & Turn-Detection*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Real-Time Voice AI & Conversational Voice**. These tools power ultra-low-latency voice agents, natural barge-in/interruption handling, real-time speech recognition (ASR), expressive text-to-speech (TTS), telephony SIP bridges, and multimodal conversational interfaces.

**Examples** include Vapi.ai, Retell AI, Bland AI, Hume AI, PlayHT Voice Agents, ElevenLabs Conversational, Deepgram Nova, Daily.co Bots, LiveKit Agents, Tavus, and `entropyconquers/gpt-voice` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted voice agent orchestration, open-weights speech-to-speech models, fast neural TTS, real-time Whisper STT, and WebRTC audio pipelines — ideal for AI engineers, voice app builders, telephony developers, and open-source researchers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Vapi.ai](https://vapi.ai)**  
  Developer-centric voice AI orchestration platform for building, testing, and deploying low-latency phone and web voice agents at scale.

- **[Retell AI](https://retellai.com)**  
  Enterprise conversational voice AI platform specializing in natural turn-taking, telephony integration, and high-concurrency call agents.

- **[Bland AI](https://bland.ai)**  
  Ultra-realistic AI phone calling infrastructure designed for automated enterprise inbound and outbound voice workflows.

- **[Hume AI (Empathic Voice Interface)](https://hume.ai)**  
  Emotionally intelligent speech-to-speech API capable of detecting vocal prosody and responding with nuanced tone and empathy.

- **[PlayHT Voice Agents](https://play.ht)**  
  Low-latency conversational voice synthesis and agent platform offering instant voice cloning and multilingual real-time streaming.

- **[ElevenLabs Conversational AI](https://elevenlabs.io)**  
  End-to-end real-time voice agent platform combining ultra-realistic low-latency TTS with custom LLM and knowledge-base orchestration.

- **[Deepgram (Nova & Voice Agent API)](https://deepgram.com)**  
  High-speed speech-to-text (Nova), text-to-speech (Aura), and unified real-time Voice Agent API engineered for sub-second latency.

- **[Daily.co Bots](https://daily.co)**  
  Real-time WebRTC audio/video infrastructure and cloud bot hosting powering low-latency conversational AI pipelines.

- **[LiveKit Cloud (Agents)](https://livekit.io)**  
  Managed global WebRTC edge network and cloud deployment platform for real-time multimodal and voice AI agents.

- **[Tavus](https://tavus.io)**  
  Real-time conversational video and voice avatar platform rendering expressive, low-latency human replicas alongside natural speech.


## Open-Source GitHub Projects

- **[entropyconquers/gpt-voice](https://github.com)**  
  Lightweight open-source real-time voice assistant bridging speech recognition, LLM reasoning, and streaming voice synthesis for natural hands-free conversations.

- **[Pipecat (Daily.co)](https://github.com)**  
  Vendor-neutral, open-source Python framework for building real-time voice and multimodal conversational AI pipelines over WebRTC and WebSockets.

- **[LiveKit Agents](https://github.com)**  
  Open-source framework for building programmable real-time voice and video AI agents with built-in turn detection, VAD, and SIP telephony bridges.

- **[Vocode](https://github.com)**  
  Open-source library for building voice-based LLM agents across phone calls, Zoom meetings, and browser audio streams.

- **[Bolna](https://github.com)**  
  Open-source end-to-end conversational voice AI framework tailored for telephony agents, multilingual Indian/global languages, and low-latency streaming.

- **[Moshi (Kyutai)](https://github.com)**  
  Open-source full-duplex speech-to-speech foundation model capable of listening and speaking simultaneously with sub-200ms latency.

- **[Ultravox (Fixie.ai)](https://github.com)**  
  Fast, open-weights multimodal speech LLM that directly ingests audio tokens without a separate ASR bottleneck.

- **[Kokoro TTS](https://github.com)**  
  Lightweight, open-weights 82M-parameter neural TTS model delivering studio-grade expressive speech synthesis faster than real-time on CPU and GPU.

- **[Piper TTS](https://github.com)**  
  Fast, local open-source neural text-to-speech system optimized for Raspberry Pi, edge devices, and ultra-low-latency streaming.

- **[Faster-Whisper](https://github.com)**  
  High-speed open-source reimplementation of OpenAI's Whisper using CTranslate2, enabling real-time streaming speech-to-text transcription.

- **[WhisperLive](https://github.com)**  
  Nearly-live open-source speech-to-text server built on Faster-Whisper for continuous real-time microphone and WebSocket audio streams.

- **[Silero VAD](https://github.com)**  
  Enterprise-grade, lightweight open-source Voice Activity Detector (VAD) essential for accurate speech segmentation and barge-in interruption handling.

- **[TEN Framework (The Open-Source Conversational AI Agent Framework)](https://github.com)**  
  Open-source framework for building real-time multimodal voice and vision agents with low-latency audio/video transport and plugin extensions.

- **[RealtimeSTT & RealtimeTTS](https://github.com)**  
  Fast, easy-to-use open-source Python libraries providing low-latency microphone voice activity detection, transcription, and streaming audio playback.

- **[Fish Speech](https://github.com)**  
  Open-source zero-shot multilingual TTS and voice cloning engine engineered for low-latency streaming conversational applications.

- **[CosyVoice (Alibaba)](https://github.com)**  
  Open-source multilingual large voice generation model supporting zero-shot cloning, cross-lingual synthesis, and streaming inference.

- **[Wyoming Protocol (Home Assistant)](https://github.com)**  
  Open-source peer-to-peer protocol for connecting local wake-word detectors (`openWakeWord`), STT, and TTS services into private voice assistants.

### Additional Strong Open-Source Options

- **[openWakeWord](https://github.com)** for lightweight, open-source custom wake-word detection on edge hardware.
- **[Whisper.cpp](https://github.com)** for dependency-free C/C++ real-time speech recognition on Apple Silicon, CPUs, and mobile devices.
- **[Chatterbox TTS (Resemble AI)](https://github.com)** and **[Orpheus TTS](https://github.com)** for expressive, open-weights emotion-controlled voice synthesis.
- **[LiveKit SIP & Asterisk / FreeSWITCH](https://github.com)** for bridging open-source VoIP/PSTN telephony trunks directly into WebRTC voice agents.
- Many community **semantic turn-detection models**, **WebRTC echo-cancellation (`SpeexDSP` / `RNNoise`)** filters, and **local Ollama voice wrappers** for fully offline conversational AI.

**Frameworks for building custom systems**: Combine **Pipecat** or **LiveKit Agents**, **Silero VAD**, **Faster-Whisper**, and **Kokoro TTS / Piper** with **Ollama / vLLM** for fully self-hosted, sub-second conversational voice agents.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Automated outbound voice calling and call recording are subject to telecommunications and privacy laws (e.g., TCPA, TRAI DND regulations, GDPR); always obtain proper consent and disclose AI usage where required.
- Voice cloning technologies should only be used with explicit permission from the voice owner.

---

**Made for voice AI engineers, WebRTC developers, telephony architects, and open-source builders.**  
Let's make conversational voice AI faster, more natural, and radically open.
