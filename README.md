# Han Instruction Dataset
Han instruction dataset: Thai instruction dataset

🪿 Han (ห่าน or goose) Instruction Dataset is a Thai instruction dataset by PyThaiNLP. This dataset collects all Thai instruct datasets that were made by humans and our old model. The dataset can be used to train Instruction Following models like ChatGPT or others.

Hugging Face dataset: [https://huggingface.co/datasets/pythainlp/han-instruction-dataset](https://huggingface.co/datasets/pythainlp/han-instruction-dataset)

GitHub: [https://github.com/wannaphong/han-instruction-dataset](https://github.com/wannaphong/han-instruction-dataset)

Data sources:
- [Reference desk at Thai wikipedia](https://th.wikipedia.org/wiki/%E0%B8%A7%E0%B8%B4%E0%B8%81%E0%B8%B4%E0%B8%9E%E0%B8%B5%E0%B9%80%E0%B8%94%E0%B8%B5%E0%B8%A2:%E0%B8%9B%E0%B8%B8%E0%B8%88%E0%B8%89%E0%B8%B2-%E0%B8%A7%E0%B8%B4%E0%B8%AA%E0%B8%B1%E0%B8%8A%E0%B8%99%E0%B8%B2).
- [Law from justicechannel.org](https://justicechannel.org/)
- [pythainlp/final_training_set_v1_enth](https://huggingface.co/datasets/pythainlp/final_training_set_v1_enth): Human checked and edited.
- Self-instruct from [WangChanGLM](https://huggingface.co/pythainlp/wangchanglm-7.5B-sft-en)
- [Wannaphong.com](https://www.wannaphong.com)
- [Blognone](https://www.blognone.com)
- Synthetic dataset from LLM
- Human annotators

### Supported Tasks and Leaderboards

- ChatBot
- Instruction Following


### Languages

Thai

## Dataset Structure

### Data Fields

- messages: ChatML

### Considerations for Using the Data
The dataset can be biased by human annotators and LLM annotators. We recommend you check the dataset to select or remove an instruction before training the model or using it to at your risk.

### Licensing Information

CC-BY-SA 4.0

### Citation

If you use `Han Instruction Dataset` in your project or publication, please cite the dataset as follows:

> Phatthiyaphaibun, W. (2026). Han Instruction Dataset [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.22860746

or

```bib
@dataset{phatthiyaphaibun_2026_22860746,
  author       = {Phatthiyaphaibun, Wannaphong},
  title        = {Han Instruction Dataset},
  month        = sep,
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.22860746},
  url          = {https://doi.org/10.5281/zenodo.22860746},
}
```

Zenodo: [https://doi.org/10.5281/zenodo.22860746](https://doi.org/10.5281/zenodo.22860746)