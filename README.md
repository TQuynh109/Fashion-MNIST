# Fashion-MNIST

## Description

This project focuses on classifying fashion images from the Fashion-MNIST dataset using [Logistic Regression](https://www.ibm.com/think/topics/logistic-regression) and [Support Vector Machines (SVM)](https://www.ibm.com/think/topics/support-vector-machine). The main steps include:

* **Data Preprocessing & EDA**: Load, normalize, split the dataset, and visualize sample images.

* **Model Training**: Implement and evaluate `Logistic Regression` and `SVM (linear & RBF kernel)`.

* **Dimensionality Reduction**: Apply `PCA` or `LDA` to reduce the feature dimensions from 784 to 100 or 50.

* **Performance Evaluation**: Compare accuracy, precision, recall, F1-score, confusion matrix, and training time.

* **Visualization & Analysis**: Plot performance metrics, compare models, and discuss the advantages/disadvantages of each approach.

### Labels

Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

### Folders

| **Folder**              | **Description**                                              |
|-------------------------|--------------------------------------------------------------|
| Data                    | Contains the original dataset used for training and testing. |
| Fashion_MNIST_Classifier| Source code for classifying items, evaluating the performance of classification models, and tuning the models.|
| Reports                 | Documented reports and presentations summarizing the project findings. |
| Setup                   | Contains the environment setup files and dependencies required to run. |


## About Fashion-MNIST Data

`Fashion-MNIST` is a dataset of [Zalando](https://jobs.zalando.com/tech/)'s article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. `Fashion-MNIST` is a direct **drop-in replacement** for the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/) for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

Here's an example of how the data looks (each class takes three-rows):

![](Docs/Images/fashion-mnist-sprite.png)

## Get the Data

[Many ML libraries](#loading-data-with-other-machine-learning-libraries) already include Fashion-MNIST data/API, give it a try!

You can use direct links to download the dataset. The data is stored in the **same** format as the original [MNIST data](http://yann.lecun.com/exdb/mnist/).

| Name  | Content | Examples | Size | Link |
| --- | --- |--- | --- |--- |
| `train-images-idx3-ubyte.gz`  | training set images  | 60,000|26 MBytes | [Download](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-images-idx3-ubyte.gz)|
| `train-labels-idx1-ubyte.gz`  | training set labels  |60,000|29 KBytes | [Download](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-labels-idx1-ubyte.gz)|
| `t10k-images-idx3-ubyte.gz`  | test set images  | 10,000|4.3 MBytes | [Download](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-images-idx3-ubyte.gz)|
| `t10k-labels-idx1-ubyte.gz`  | test set labels  | 10,000| 5.1 KBytes | [Download](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-labels-idx1-ubyte.gz)|

## Contributors

| **Name**| **Major**| **University**|
|-|-|-|
| Kieu Thi Ngoc Vui     | Data Science  | University of Science (VNUHCM) |
| Nguyen Ngoc Thanh Thu | Data Science  | University of Science (VNUHCM) |
| Phan Binh Phuong      | Data Science  | University of Science (VNUHCM) |
| Huynh Thao Quynh      | Data Science  | University of Science (VNUHCM) |
| Ly Vinh Thuan         | Data Science  | University of Science (VNUHCM) |
| Nguyen Tran Le Hoang  | Data Science  | University of Science (VNUHCM) |
| Nguyen Thuan Phat     | Data Science  | University of Science (VNUHCM) |
| Duong Thanh Phong     | Data Science  | University of Science (VNUHCM) |


## Git Commit Message Rule
After performing the **`git add .`** command, the **`git commit`** message should follow this structure:

    git commit -m "[folder/file updated] - [task description]"

**Example:**
    
    git commit -m "Fashion_MNIST_Classifier/ItemClassification.ipynb - Reducing dimensions using PCA."

Task description should provide enough information for other members to understand what was updated or changed, e.g., fixing bugs, adding features, refactoring code.

After that, use the **`git push`** command to push into the GitHub repository.


