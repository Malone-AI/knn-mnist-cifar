Experiments are carried out on mnist dataset and cifar10 dataset to analyze the error rate of K-nearest neighbor algorithm. Among them, mnist data set is loaded through scikit-learn library, while cifar10 data set is too large to upload. So if you want to run the jupyter notebook in this repository, Mnist.ipynb can run it directly, while Cifar10.ipynb needs you to go
https://www.cs.toronto.edu/~kriz/cifar.html download cifar10 data sets, and extract the, the last of the file structure is similar to this:
workdir
│  Cifar10.ipynb
│  Mnist.ipynb
│  report.pdf
│
└─data
    └─cifar-10-batches-py
            batches.meta
            data_batch_1
            data_batch_2
            data_batch_3
            data_batch_4
            data_batch_5
            readme.html
            test_batch
