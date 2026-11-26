# AraMMSD: Arabic Multi-Modal Sarcasm Detection Dataset

AraMMSD is an Arabic image–text sarcasm detection benchmark. It was built by translating the captions of the English MMSD benchmark (Cai et al., 2019) into Levantine colloquial Arabic, preserving hashtags, emojis and the original sarcasm labels. It keeps MMSD's images and train/validation/test split.

## Files

| File | Sentences | Sarcastic | Not sarcastic |
|---|---|---|---|
| train.json | 19,557 | 8,385 | 11,172 |
| valid.json | 2,387 | 937 | 1,450 |
| test.json | 2,373 | 925 | 1,448 |

Each entry has:
- `image_id`: the ID of the image in the original MMSD dataset
- `text`: the Arabic (Levantine) caption
- `label`: 1 = sarcastic, 0 = not sarcastic

## Images

The images are those of the original MMSD dataset, available at:
https://github.com/headacheboy/data-of-multimodal-sarcasm-detection

## Citation

If you use AraMMSD, please cite:

> Joukhadar R, Ghneim N, Rebdawi G. An Arabic Benchmark and Multiview CLIP Model for Multimodal Sarcasm Detection. Under review.

Please also cite the original MMSD dataset:

> Cai Y, Cai H, Wan X (2019) Multi-modal sarcasm detection in Twitter with hierarchical fusion model. In: Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, pp 2506–2515.

## License

The AraMMSD annotations and Arabic captions are released under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See [LICENSE](LICENSE). The images belong to the original MMSD dataset and are subject to its terms.

## Contact

Raghad Joukhadar — raghad.joukhadar@hiast.edu.sy
