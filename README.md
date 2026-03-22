# Bilingual Garden-Path Sentences Corpus

---

### Overview
This repository contains the Bilingual DO/SC Garden-Path Sentences corpus and experimental code for the paper:

> **Can Large Language Models Analyze Garden Path Sentences? -An Empirical Study based on Cross-Lingual Data**
> 
> *Authors: [Li Qi], [Yue Ji], [Hongzheng Li]* 
> 
> *Journal/Conference: [ACL Anthology], [2025]*

### Corpus Description
The corpus consists of English and Chinese garden path sentences with the **Direct Object/Sentential Complement (DO/SC)** structure. The corpus follows a 2 (Verb Bias: Object-biased vs. Complement-biased) × 2 (Plausibility: Plausible vs. Implausible) × 2 (Ambiguity: Garden-path vs. Non-Garden-path) design.

| Language | GPs | Non-GPs | Total |
|----------|-----------|---------------|-------|
| English  | 160       | 160           | 320   |
| Chinese  | 128       | 128           | 256   |

### File Structure
```
LLM-Garden-Path/
├── data/           # Raw corpus data
├── code/           # Experimental code
├── results/        # Experimental results (tables and figures)
└── LICENSE         # MIT License
```

### Requirements
```bash
pip install -r code/requirements.txt
```

### Citation
If you use this corpus or code in your research, please cite:

```bibtex
@inproceedings{qi2025daiyuyan,
  title={大语言模型可以分析花园幽径句吗?—基于跨语言数据集的实证研究},
  author={Qi, Li and Ji, Yue and Li, Hongzheng},
  booktitle={ACL Anthology},
  year={2025}
}
```


### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
