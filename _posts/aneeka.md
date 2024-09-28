---
layout: post
title: Aneeka
description: AI, Entertainment, Python, Go, Pytorch, LLM
image: assets/images/nekalow.png
---

### What is Aneeka?
Aneeka is one of my artificial intelligence projects aimed at entertainment and dissemination of topics related to AI.
Aneeka is able to read your Twitch chat and interact, responding in a charismatic and personality-driven manner, as well as being able to interact with the operator if he speaks to her with his microphone.

### What functions does it have?
Aneeka is connected to her chat using the Twitch API. If one or multiple users interact in her chat, Aneeka will read the messages and start a conversation with them using her TTS so that her viewers can hear her, and to be even more visible, she has a VTuber avatar that makes vocal movements and some expressions. depending on what Aneeka is talking about.

In addition to being able to interact with her chat, Aneeka can also talk to the person through the use of a microphone using speech to text. She interacts in the same way as with her Twitch chat but now referring to the person she is talking to. .

### How was it made?
Aneeka makes use of different artificial intelligence technologies, the most important is the LLM based on LLAMA-3.1-8B, its model is executed locally. This receives the prompts that I prepared by code and changing depending on the number of comments and whether you are talking to the person through the microphone or with your chat.

She also uses a TTS to be able to hear what she has to say, this in order to be more interactive and less boring. I have tried several TTS for its voice such as a model that I finetuned from CoquiTTS, its voice did not sound bad at all but it was expensive in terms of computing power and it was slow so I decided to look for more options, not being convinced by a fast TTS and quality I decided to stay with Microsoft's TTS services which give Aneeka her characteristic voice.

In order to hear and understand the user who communicates with her through a microphone, I went through a process of selecting tools for converting voice to text, one of the local and free options that gave me the best results was using the small whisper model, but it is also somewhat expensive in performance and is a bit slow, so to optimize the use of resources on my pc I decided once again to use Microsoft services this time for speech-to-text.

Aneeka was originally programmed in Python using threads and multiprocessing to have the best possible performance, although also for learning reasons and seeking to make it even faster I developed a version in Go with the same features but managing to make it even more efficient in terms of CPU consumption, memory and speed.

### My experience
Developing Aneeka took me a long time but in the end it was worth it, I learned a lot about Python and Go, it gave me an insight into long language models (LLM) and how they work, the technologies that are currently used to fine tune them and quantize them.

It is undoubtedly an enriching project for my knowledge and I would recommend people try to do something similar if they would like to learn more about LLMs since this can give you a good approach and you will learn a lot.

* <a href="https://www.twitch.tv/axelinsz/clip/JoyousTiredSaladDerp-yFTGXZ892XcwLpee?filter=clips&range=all&sort=time">Clip of Aneeka's interaction with her chat</a>