This repository contains the code for our project based on:

**What Can Transformers Learn In-Context? A Case Study of Simple Function Classes** <br>
*Shivam Garg\*, Dimitris Tsipras\*, Percy Liang, Gregory Valiant* <br>
Paper: http://arxiv.org/abs/2208.01066 <br><br>

![](setting.jpg)


## Getting started
You can start by checking out our notebooks:
- The `original.ipynb` notebook contains code from the original paper to trian models, plot the pre-computed metrics, and evaluate them on new data.
- The `polynomial-regression.ipynb` notebook tests the ability of a transformer to learn fixed degree or descending degree polynomial regression.
- The `knn-classification.ipynb` notebook tests the ability of a transformer to learn knn-based classification. This is very slow due to clustering and k-nearest neighbor operations.

- To recreate our models, run the `polynomial-regression.ipynb` notebook. This will create the full model from scratch, which will take around two hours. You can vary the args.training.task_kwargs["degree"] parameter to change the degree of the polynomial or the args.training.task parameter to change the learned task.
- To create smaller models, run the `polynomial-regression.ipynb` notebook and vary the args.training.train_steps parameter to decrease the number of iteration steps.

To recompute our plots:
- The `review.ipynb` notebook contains code to plot the metrics of our pre-trained models and evaluate them on new data.

```bibtex
    @InProceedings{garg2022what,
        title={What Can Transformers Learn In-Context? A Case Study of Simple Function Classes},
        author={Shivam Garg and Dimitris Tsipras and Percy Liang and Gregory Valiant},
        year={2022},
        booktitle={arXiv preprint}
    }
```
