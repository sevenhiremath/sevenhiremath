# Hi, I'm Swayam

I'm a final year Computer Science student in Bengaluru, graduating in July 2027.

I work mostly with Python, Java, SQL, Linux and AWS. I like building something small, understanding where it breaks, and improving it step by step.

## Main projects

### [Self-healing infrastructure](https://github.com/sevenhiremath/self-healing-infrastructure)

A small Flask service deployed on AWS using Terraform. I use systemd to restart the application process and an Auto Scaling Group to replace unhealthy instances.

The interesting part for me is the difference between recovering a process and replacing a server. The repository includes the deployment configuration and a script for measuring process recovery.

**Python · Linux · systemd · AWS · Terraform · CloudWatch**

### [Interview analytics pipeline](https://github.com/sevenhiremath/edge-Interview-analysis-main-)

My final year project processes interview recordings locally. It extracts audio, transcribes speech, separates speakers and builds a report with speaking metrics and a comparison against a job description.

The code brings together existing speech models. My focus is the pipeline around them: processing stages, cached outputs, speaker alignment and the report.

**Python · FFmpeg · Faster-Whisper · ONNX Runtime · SentenceTransformers**

## Other work

- **[Interview analytics prototype](https://github.com/sevenhiremath/edge-interview-analytics-prototype)** — the earlier version using Vosk. A smaller pipeline for chunking video, transcribing audio and counting filler words.
- **[Flutter contacts app](https://github.com/sevenhiremath/contacts-app-flutter)** — a practice app for adding, editing, searching and marking contacts as favourites.

## What I'm learning

I'm interested in backend and cloud engineering. I'm working on making my projects easier to run, documenting the decisions behind them and understanding failures rather than just getting a successful demo.

[LinkedIn](https://www.linkedin.com/in/swayam-h) · [Email](mailto:SwayamHiremath@outlook.com)
