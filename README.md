# CLSum

![](https://img.shields.io/badge/version-v1.0-blue.svg)
![](https://img.shields.io/badge/language-ENG-lightgrey.svg)
[![](https://img.shields.io/badge/license-ODCBy-green.svg)](https://opendatacommons.org/licenses/by/1-0/)
[![](https://img.shields.io/badge/author-@sq-red.svg)](https://stevenlau6.github.io/)


CLSum is a dataset for common law court judgment summarization

CLSum covers court judgments from four common law jurisdictions: the United Kingdom, Canada, Australia, and Hong Kong SAR.

Paper <a href="https://arxiv.org/pdf/2403.04454.pdf">[Arxiv PDF]</a> <a href="https://www.sciencedirect.com/science/article/abs/pii/S0306457324001511">[Published Version]</a>

Huggingface Datasets Page <a href="https://huggingface.co/datasets/Shuaiqi/CLSum">[Link]</a>

## License
CLSum is licensed under [ODC-BY](https://opendatacommons.org/licenses/by/1-0/).

## Download

Download from Google Drive [link](https://drive.google.com/drive/folders/1qAUr1uUxTFhX6Uuceu8wR2Uhl_mQGs3T?usp=drive_link)

When using the CLSum dataset in a product or service, or including data in a redistribution, please cite the following paper:

```
@article{liu2024low,
  title={Low-resource court judgment summarization for common law systems},
  author={Liu, Shuaiqi and Cao, Jiannong and Li, Yicong and Yang, Ruosong and Wen, Zhiyuan},
  journal={Information Processing \& Management},
  volume={61},
  number={5},
  pages={103796},
  year={2024},
  publisher={Elsevier}
}
```


## FAQ

Q1: How to use this dataset?

A1: You can find four subsets named CLSum-UK, CLSum-CA, CLSum-AUS, and CLSumHK from four common law jurisdictions: the United Kingdom, Canada, Australia, and Hong Kong SAR. Each subset has train, validation, and test sets. 
"src.txt" and "tgt.txt" files contain judgement doucments and corresponding target summaries.

Q2: Does each line of src.txt​ and tgt.txt​ files contain the source documents and the target summary, respectively?

A2: Yes



