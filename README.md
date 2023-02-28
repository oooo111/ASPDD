# ASPDD

This is the code for MDKD implemented on [Attention Model](https://github.com/jieyibi/AMDKD/tree/main/AMDKD-AM).

We provide codes combinatorial optimization problems:

- Traveling Salesman Problem (TSP)

## Evaluation

```
python eval.py ./data/tsp_uniform50_10000.pkl --model outputs/epoch-best.pt --decode_strategy greedy --eval_batch_size 256
```




### Other options and help
```
python run.py -h
python eval.py -h
```
## Dependencies

- Python>=3.8
- gurobipy==9.5.2
- matplotlib==3.5.1
- numpy==1.22.3
- ortools==9.4.1874
- scikit_learn==1.1.2
- scipy==1.8.0
- setuptools==58.0.4
- six==1.16.0
- tensorboard_logger==0.1.0
- tensorflow==2.10.0
- torch==1.11.0+cu113
- tqdm==4.62.3

## Acknowledgements

This code is originally implemented based on [Attention Model](https://github.com/wouterkool/attention-learn-to-route), which is source code of the paper _Attention, Learn to Solve Routing Problems!_ accepted at ICLR 2019.

This code is originally implemented based on [AMDKD](https://github.com/jieyibi/AMDKD/tree/main/AMDKD-AM), which is source code of the paper _ Learning Generalizable Models for Vehicle Routing Problems via Knowledge Distillation!_ accepted at Neurips 2022.
