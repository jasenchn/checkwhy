### CHECKWHY
Glad to be awarded as an outstanding paper award and area chair award. The code and datasets for our ACL 2024 paper: "CHECKWHY: Causal Fact Verification via Argument Structure."

**Note**: we provide the train.json and dev.json in this repo. If you need the test.json, please email me: jiashengsi@qlu.edu.cn


### Datasets
#### Datasets:
- **2 Classes:**
  - `train.json`
  - `dev.json`
  - `test.json`

- **3 Classes (Including 'Not Enough Info'):**
  - `train_nei.json`
  - `dev_nei.json`
  - `test_nei.json`

#### Note:
- `checkwhy-id`: The ID of the dataset.
- `evidences`: 
    - `evidence_id`: ID of the evidence.
    - `useful`: Whether this evidence is useful for verification.
    - `leaf`: Whether this evidence is a leaf node in the argument structure.
- `argument_structure`: The output for Task 3.
- `code_out`: The output for Task 4.

### Citation
Please cite our paper if you use CHECKWHY or the datasets we provided in your work:
```
@inproceedings{si-etal-2024-checkwhy,
    title = "{CHECKWHY}: Causal Fact Verification via Argument Structure",
    author = "Si, Jiasheng  and
      Zhao, Yibo  and
      Zhu, Yingjie  and
      Zhu, Haiyang  and
      Lu, Wenpeng  and
      Zhou, Deyu",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-long.835",
    doi = "10.18653/v1/2024.acl-long.835",
    pages = "15636--15659",
}


```
