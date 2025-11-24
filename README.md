# Adaptive-Fusion-Transformer
This is a hybrid time series model that combines seq2seq, multi-head attention, variable selection, and gating mechanisms. With multiple models combined, it achieves enhanced interpretability and effective long-term dependencies. This study proposes an enhanced model, Adaptive Fusion Transformer for complex time-series forecasting based on TFT.

## TFT Model

This repository includes the Temporal Fusion Transformer (TFT) model implementation from Google Research. The TFT model file is located in `libs/tft_model.py`.

### Attribution

The TFT model (`libs/tft_model.py`) is sourced from the Google Research repository:
- **Source**: https://github.com/google-research/google-research/tree/master/tft
- **License**: Apache License 2.0
- **Copyright**: 2025 The Google Research Authors

### Note on Dependencies

The TFT model file has dependencies on:
- `data_formatters.base` - For input type definitions
- `libs.utils` - For utility functions

These dependencies are not included in this repository and will need to be implemented separately as part of the custom development process.
