# Exploring Generalization Ability of PLMs on Arithmetic and Logical Reasoning
 The data for NLPCC2021 paper <Exploring Generalization Ability of Pretrained Language Models onArithmetic and Logical Reasoning> [link](https://arxiv.org/abs/2108.06743)

## Statistic

 The overall statistic of six tasks are presented below

| Task           | Train Set | Dev Set | In- + Cross-<br />Distribution Test Set | In- + Cross-<br />Distribution Data Set |
| -------------- | --------- | ------- | --------------------------------------- | --------------------------------------- |
| Counting       | 3744      | 468     | 468+2030                                | 4680+2030                               |
| Listing        | 3744      | 468     | 468                                     | 4680                                    |
| Addition       | 256320    | 32040   | 32040+4000                              | 320400+4000                             |
| Subtraction    | 256320    | 32040   | 32040+4000                              | 320400+4000                             |
| Comparison     | 648000    | 81000   | 81000+5600                              | 810000+5600                             |
| Symbolic Logic | 40000     | 5000    | 5000+2200                               | 50000+2200                              |

## Details

For each task, it contains in-distribution data and cross-distribution test. 

In the in-distribution data folder, there are folders with different numbers. 

Each number indicates that the folder contains this number percentage of  all train data while the dev/test set across  folders are exactly the same. For example, for the Addition task, the '50' means that the folder contains 256320*50% = 128160 training samples while the number of development/testing samples is 32040.

The cross-distribution test folder contain the cross-distribution test data.

## Citation

If you find this project useful, please cite

```
@inproceedings{Wang2021ExploringGA,
  title={Exploring Generalization Ability of Pretrained Language Models on Arithmetic and Logical Reasoning},
  author={Cunxiang Wang and Boyuan Zheng and Yuchen Niu and Yue Zhang},
  booktitle={NLPCC},
  year={2021}
}
```

