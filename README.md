# SAIL

### Spatial Audio Intelligence with Large Language Models via Disentangled Acoustic-Spatial Encoding and Dual-Stream Q-Former

> Submitted to **IEEE/ACM TASLP**. Code and pretrained models will be released after the review process.

<p align="center">
  <img src="https://github.com/user-attachments/assets/5bfc81d4-1c6d-477c-a204-1e16e19f08d9" width="95%">
</p>

## Highlights

- **Disentangled Spatial Audio Transformer (DSAT):** separately encodes Mel-based acoustic cues and IPD-based spatial cues.
- **Source-discriminative task queries:** learn event, direction, and distance information for each source.
- **Dual-Stream Q-Former:** preserves acoustic-spatial separation and source-level correspondence during LLM alignment.

## Performance

<p align="center">
  <img src="https://github.com/user-attachments/assets/353f2be3-ee3f-4481-a403-4a310fe461bf" width="95%">
</p>

Compared with BAT on SpatialSoundQA, SAIL:

- improves dual-source detection mAP from **8.05 to 10.02**;
- improves dual-source DoA accuracy from **35.12% to 46.65%**;
- reduces dual-source distance DER from **52.85% to 47.25%**;
- improves average binary spatial reasoning accuracy from **75.12% to 81.44%**;
- improves open-ended relative-direction accuracy from **50.68% to 62.78%**.

For two-source encoder evaluation, DSAT improves detection mAP from **15.52 to 31.66** and reduces angular MAE from **54.45° to 29.59°** compared with Spatial-AST.

## Citation

```bibtex
@article{luo2026sail,
  title={SAIL: Spatial Audio Intelligence with Large Language Models via Disentangled Acoustic-Spatial Encoding and Dual-Stream Q-Former},
  author={Luo, Zhengding and Wu, Jinyang and Ma, Haozhe and Zhou, Yanghao and Gan, Woon-Seng and Wang, Wenwu},
  journal={arXiv preprint arXiv:2609.34347},
  year={2026}
}
```

## Acknowledgments

We thank the authors of [BAT](https://github.com/X-LANCE/SLAM-LLM/tree/main/examples/seld_spatialsoundqa) for releasing their code and pretrained models.
