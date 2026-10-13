# Hushtype models

Public home for the model files the Hushtype app downloads on first run. The app's source is private; only the models and their manifest are here.

- `manifest.json`: every model file with its download URL, size and SHA-256. The apps fetch it from
  `https://raw.githubusercontent.com/cad861/hushtype-models/main/manifest.json` and verify every file against it.
- Releases (`models-v1`, …): the files themselves, uploaded by `scripts/release-models.sh` in the app repo.

Nothing in this repo is edited by hand.

## Licences and attribution

- Parakeet TDT 0.6B v3 by NVIDIA, CC-BY-4.0. Converted to ONNX int8 by the sherpa-onnx project.
- Moonshine (English) by Useful Sensors, Inc. (Moonshine AI), MIT. Only the English models are distributed.
- Whisper large-v3-turbo and small.en by OpenAI, MIT.
- Silero VAD by the Silero Team, MIT.
- Qwen3 0.6B and 1.7B by Alibaba Cloud (Qwen team), Apache 2.0. GGUF quantisation by Unsloth.
