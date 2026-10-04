# SAIL

### Spatial Audio Intelligence with Large Language Models via Disentangled Acoustic-Spatial Encoding and Dual-Stream Q-Former

> Submitted to **IEEE/ACM TASLP**. Code and pretrained models will be released after the review process.

<p align="center">
  <img src="https://github.com/user-attachments/files/33016330/Main.SAIL.LLM.pdf" width="95%">
</p>


## Highlights

- **Disentangled Spatial Audio Transformer (DSAT):** separately encodes Mel-based acoustic cues and IPD-based spatial cues.
- **Source-discriminative task queries:** learn event, direction, and distance information for each source.
- **Dual-Stream Q-Former:** preserves acoustic-spatial separation and source-level correspondence during LLM alignment.

## Performance

Compared with BAT on SpatialSoundQA, SAIL:

- improves dual-source detection mAP from **8.05 to 10.02**;
- improves dual-source DoA accuracy from **35.12% to 46.65%**;
- reduces dual-source distance DER from **52.85% to 47.25%**;
- improves average binary spatial reasoning accuracy from **75.12% to 81.44%**;
- improves open-ended relative-direction accuracy from **50.68% to 62.78%**.

For two-source encoder evaluation, DSAT improves detection mAP from **15.52 to 31.66** and reduces angular MAE from **54.45° to 29.59°** compared with Spatial-AST.

<p align="center">
  <img src="assets/performance.png" width="95%">
</p>

## Release

- [ ] Code
- [ ] Pretrained models
- [ ] Training and inference scripts
- [ ] Evaluation tools

## Citation

The citation will be added when the paper becomes publicly available.

## Acknowledgments

We thank the authors of [BAT](https://github.com/X-LANCE/SLAM-LLM/tree/main/examples/seld_spatialsoundqa) for releasing their code and pretrained models.
