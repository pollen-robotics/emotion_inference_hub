Here’s the final, cleaned-up version of your `README.md` with the updated repo name and correction applied:

---

# 🎙️ Emotion Inference Hub

**Input**: Voice (Audio Stream)
**Output**: Emotion Name (from a Predefined List)

---

## 📚 Overview

This repository tackles the following **Sound2Emotion** problem:

> *Given a voice input, determine the most appropriate emotion to play from a predefined list.*

The emotion list and their corresponding descriptions are defined in [`emotions_description.txt`](./emotions_description.txt).

This work has been used to drive the emotional expressiveness of **Reachy2**, the humanoid robot from [Pollen Robotics](https://www.pollen-robotics.com/).

---

## 🤖 Related Projects and Demos

* 🎬 [Short Demo of Reachy2 Emotions](https://www.youtube.com/watch?v=b5gSHDUwPQc)
* 📖 [Full Explanation of the Emotion System](https://www.youtube.com/watch?v=uNXPGMOEOhk)
* 📦 [Reachy2 Emotion Library (Record, Replay, API)](https://github.com/pollen-robotics/reachy2_emotions)
* 📦 [Docker installation of the Reachy2 stack](https://hub.docker.com/r/pollenrobotics/reachy2)

---

## 📈 Project Goals

* ✅ Provide an **open-source** solution for the Sound2Emotion task. Close-source solutions are accepted too.
* ✅ Achieve **low latency** and **high precision** emotion detection.
* ✅ Support both **external APIs** (Hugging Face, OpenAI, etc.) and **local inference**.
* ✅ Compare different approaches with standardized **latency** and **accuracy metrics**.

---

## 🚀 Current Approaches

| Approach            | Inference Type | Status           | Latency  | Notes                     |
| ------------------- | -------------- | ---------------- | -------- | ------------------------- |
| GPT-4 Realtime      | API (OpenAI)   | ✔️ Used in demos | TBD      | Baseline system           |
| Vosk + Mistral      | Local          | 🧪 In Progress   | TBD      |                           |
| Hugging Face Models | API / Local    | 🧪 In Progress   | TBD      |                           |

📌 **First implementation:**
[OpenAI Realtime Console (Baseline, used in the videos above)](https://github.com/pollen-robotics/openai-realtime-console/tree/main)

---

## 📏 Metrics

* **Latency**: Time between the end of audio input and receiving the emotion classification.
* **Accuracy**: (To be defined) Benchmarking the correctness of emotion predictions. We currently only have the Speech2Text WER metric
* **Hardware Requirements**: Aim for reasonable requirements when going for a local approach.

---

## 🙌 Contributions

Contributions are highly welcome!

> *All the cards are on the table. If you have an idea for improving latency, accuracy, or hardware efficiency, join the project!*

A fully **local solution** with competitive performance would be a major step forward.

---

## 📬 Contact

For any questions or to share your progress, feel free to open an issue or a pull request.


