## 🎧 Speech-to-Text Pipeline Using Whisper + Audio Preprocessing

A complete Automatic Speech Recognition (ASR) workflow built using OpenAI Whisper, enriched with strong audio preprocessing, transcription, and output generation steps.
This project handles everything end-to-end — from loading raw audio to producing a final submission.csv.

## ✨ Features
🔊 Audio Preprocessing

Librosa-based pipeline for loading audio files.

Resampling, silence trimming, and normalization for high-quality transcription.

Ensures consistent and Whisper-friendly input formats.

🤖 Whisper Model Integration

Loads OpenAI Whisper models (base/small/medium).

Handles GPU/CPU fallback, batching, and efficient decoding.

Produces accurate text transcriptions from raw audio clips.

📝 Prediction & Post-processing

Converts Whisper model outputs into clean, readable text.

Applies formatting rules, quality checks, and corrections.

Ensures prediction stability across diverse audio samples.

📄 Submission File Generation

Automatically creates submission.csv with:

IDs from the dataset

Whisper-generated transcriptions

Ready for evaluation or competition submissions.

## 📁 Technologies Used

Python

OpenAI Whisper

Librosa (audio preprocessing)

Torch (model inference)

Pandas (data handling)
