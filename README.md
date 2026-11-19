# Editor Skill - model mirror

AI models used by Editor Skill, mirrored on GitHub so they can be fetched where only github.com is reachable. Large files are split into 95 MB parts (`*.partNNN`); `scripts/model_pack.py fetch` joins them.

| Folder | Model | Licence | Source |
|---|---|---|---|
| whisper-large-v3-turbo | Whisper large-v3-turbo (CTranslate2) | MIT (OpenAI) | mobiuslabsgmbh/faster-whisper-large-v3-turbo |
| w2v | wav2vec2-large-xlsr-53-th, ONNX, weights quantized to int8 | CC-BY-SA 4.0, (c) VISTEC-depa AI Research Institute of Thailand | airesearch/wav2vec2-large-xlsr-53-th |
| rembg | U^2-Net (u2net.onnx, u2net_human_seg.onnx) | Apache-2.0 | danielgatis/rembg, xuebinqin/U-2-Net |
| yunet | YuNet face detector 2023mar | MIT | opencv/opencv_zoo |

The int8 wav2vec2 file is a modified (quantized) version of the original model and is shared under the same CC-BY-SA 4.0 licence.
