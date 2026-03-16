# SONA8 DeepSpeech Plan

- Goal: lightweight CPU fallback for edge transcription
- Checklist
  - [ ] Build Docker image with Mozilla DeepSpeech 0.9 + KenLM scorer
  - [ ] Convert latest SONA8 acoustic data to 16k mono wav
  - [ ] Measure latency on Intel NUC + Raspberry Pi 5
  - [ ] Compare WER vs Whisper-small for noisy cafÃ©s
- Deliverables
  1. Minimal FastAPI wrapper
  2. Batch evaluation notebook