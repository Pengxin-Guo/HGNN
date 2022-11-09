# Deep multi-task augmented feature learning via hierarchical graph neural network

## Prerequisites:

- Python3
- Tensorflow==1.15.0
- Numpy

## Dataset:

For the classification tasks:

- imageclef.txt
- office_caltech_10.txt
- office_home.txt

For the regression tasks:

- sarcos_2000.txt

You can download the pre-processed datasets from the URL below and put them at  the directory "./data".

[https://drive.google.com/drive/folders/1eqRDifM7tCZ9xnT-f68RwImXKwV9n2YU?usp=sharing](https://drive.google.com/drive/folders/1eqRDifM7tCZ9xnT-f68RwImXKwV9n2YU?usp=sharing)

## Training:

You can modify the code "datafile=./data/\*.txt" in "\*.py" before you run the code for training different datasets. 

You can run "\*\_HGNN.py" to train and evaluate on the classification tasks and run "\*\_HGNN\_reg.py" to train and evaluate on the regression tasks.

## Citation

If you use this code for your research, please consider citing:

```
@inproceedings{guo2021deep,
  title={Deep multi-task augmented feature learning via hierarchical graph neural network},
  author={Guo, Pengxin and Deng, Chang and Xu, Linjie and Huang, Xiaonan and Zhang, Yu},
  booktitle={Joint European Conference on Machine Learning and Knowledge Discovery in Databases},
  pages={538--553},
  year={2021},
  organization={Springer}
}
```

## Contact

If you have any problem about our code, feel free to contact [12032913@mail.sustech.edu.cn](mailto:12032913@mail.sustech.edu.cn).