🎧 Speech-to-Text Pipeline Using Whisper + Audio Preprocessing
This project builds a complete automatic speech recognition (ASR) workflow using OpenAI Whisper, combined with robust audio preprocessing and post-processing steps. The notebook handles the entire pipeline: loading audio, cleaning it, transcribing it using Whisper, and generating a final submission file.

🔹 Key Features
Audio Preprocessing:
Used librosa to load, resample, trim silence, and normalize audio signals for consistent Whisper input.

Whisper Model Integration:
Loaded an OpenAI Whisper model (base/small/medium depending on your code), generated transcriptions, handled batching, GPU/CPU fallback, and decoding optimizations.

Prediction & Post-processing:
Converted raw model output into clean text, applied formatting rules, and validated the transcription quality.

Submission File Generation:
Created a final submission.csv by combining generated text with the required dataset structure.

📁 Technologies Used
Python

OpenAI Whisper

Librosa (audio processing)

Torch (model inference)

Pandas (data handling)
