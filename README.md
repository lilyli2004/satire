## [A Multi-Modal Method for Satire Detection using Textual and Visual Cues](https://www.aclweb.org/anthology/2020.nlp4if-1.4/)

This project uses [this](https://github.com/lilyli2004/mmf) fork of Facebook's MMF framework.

### Our dataset on HuggingFace🤗
Our dataset is available on the [HuggingFace's Datasets hub](https://huggingface.co/datasets). Here is an example of how you can load the [dataset](https://huggingface.co/datasets/phosseini/multimodal_satire):

```python
from datasets import load_dataset

dataset = load_dataset("phosseini/multimodal_satire")
```

### How to cite our work?
You can cite our [paper](https://www.aclweb.org/anthology/2020.nlp4if-1.4/):

```bibtex
@inproceedings{li-etal-2020-multi,
    title = "A Multi-Modal Method for Satire Detection using Textual and Visual Cues",
    author = "Li, Lily and Levi, Or and Hosseini, Pedram and Broniatowski, David",
    booktitle = "Proceedings of the 3rd NLP4IF Workshop on NLP for Internet Freedom: Censorship, Disinformation, and Propaganda",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "International Committee on Computational Linguistics (ICCL)",
    url = "https://www.aclweb.org/anthology/2020.nlp4if-1.4",
    pages = "33--38",
}
```
