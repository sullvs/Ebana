# Ebana - Stuttering Correction System

Ebana is a stuttering correction system designed to assist people who stutter (PWS) in expressing themselves clearly by transforming stuttered speech into fluent text and voice. This tool utilizes advanced AI methodologies, including Automatic Speech Recognition (ASR), Large Language Models (LLMs), and voice cloning, to enhance the clarity of speech for individuals with stuttering.

## Overview

Stuttering is a speech disorder that impacts an individual’s ability to speak fluently. Ebana offers a novel approach by transforming stuttered voice inputs into clear, stutter-free text and synthesized voice. This allows PWS to share their ideas without the fear of being misunderstood or facing communication barriers.

## Project Motivation

Despite advancements in speech therapy and support for stuttering, there is no cure. Ebana aims to ease the lives of PWS by providing a tool that helps them express themselves more confidently, accurately conveying their intended message.

## Features

1- Automatic Speech Recognition (ASR): Converts speech to text, even with stuttering.
2- Large Language Model (LLM) Correction: Processes the recognized text, removing disfluencies and creating fluent, error-free sentences.
3- Voice Cloning Technology: Re-synthesizes the corrected text as fluent voice output that mimics the user's original tone.
4- Arabic Language Support: Uses an Arabic speech dataset and is tailored for Arabic-speaking PWS.

## Dataset

The dataset used in this project is an Arabic speech dataset collected by our team in collaboration with King Fahd Hospital of the University (KFHU) and publicly available online sources. It includes recorded speech samples from PWS to ensure the model is trained on real-world data.

## Technologies Used

- NeuralSpace ASR: For speech-to-text transformation.
- Gemini LLM: For language model-based text correction.
- Elevenlabs Voice Cloning: For generating a fluent voice that maintains the user's original tone.
- Python: Backend logic and processing.

## Project Architecture

- Speech Input: User provides a stuttered speech input.
- Automatic Speech Recognition (ASR): Speech is converted to raw text.
- Large Language Model (LLM): The text is processed to remove disfluencies and structure coherent sentences.
- Voice Cloning: The corrected text is converted back into synthesized, fluent voice.
- Output: The app outputs fluent text and voice, allowing PWS to share a clear message.
