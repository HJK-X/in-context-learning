This repository contains the code for our project based on:

**What Can Transformers Learn In-Context? A Case Study of Simple Function Classes** <br>
*Shivam Garg\*, Dimitris Tsipras\*, Percy Liang, Gregory Valiant* <br>
Paper: http://arxiv.org/abs/2208.01066 <br><br>

![](setting.jpg)


## Getting started
You can start by checking out our notebooks:
- The `original.ipynb` notebook contains code from the original paper to trian models, plot the pre-computed metrics, and evaluate them on new data.
- The `single-degree-polynomial-regression.ipynb` notebook tests the ability of a transformer to learn single-degree polynomial regression
- The `polynomial-regression.ipynb` notebook tests the ability of a transformer to learn general polynomial regression.
- The `knn-classification.ipynb` notebook tests the ability of a transformer to learn knn-based classification.

```bibtex
    @InProceedings{garg2022what,
        title={What Can Transformers Learn In-Context? A Case Study of Simple Function Classes},
        author={Shivam Garg and Dimitris Tsipras and Percy Liang and Gregory Valiant},
        year={2022},
        booktitle={arXiv preprint}
    }
```
