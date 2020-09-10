# Introduction to Artificial Intelligence and Deep Learning

Welcome!
This is the course repository for XBUS-512 - Introduction to AI and Deep Learning, offered by Georgetown University's School of Continuing Studies.

## Quickstart
This course assumes that you have Python >= 3.5 installed as well as a package manager (`pip` or `conda`).

Clone the repository and go into the top-level directory:

```bash
$ git clone git@github.com:rebeccabilbro/intro-to-dl.git
$ cd intro-to-dl
```

Requirements can be installed with:

```bash
$ pip install -r requirements/requirements.txt
```

## Course Description
Of the many machine learning algorithms used today in industry and research, artificial neural models are quickly become the state of the art. For most of their ~70 year history, neural networks could not have been considered a practical machine learning method, but this has changed rapidly over the last two decades thanks to advances in distributed computing, optimizations in learning rates, and open source libraries like TensorFlow, Keras, and PyTorch. Perhaps even more importantly, unlike traditional models, which face performance plateaus as data size increases, neural models show particular promise because they continue to improve given more training data.

In this course we will use open source deep learning libraries to build machine learning models and develop practical strategies for prototyping, testing, visualizing, tuning, and deploying neural models to solve a range of real-world problems.

## Course Objectives
Upon successful completion of the course, students will be able to:

- Assess use cases in which AI and deep learning methods are well-suited.

- Articulate tradeoffs between deep learning and traditional machine learning models.

- Distinguish between experimental and production-ready AI and deep learning tools.

- Prepare strategies for the deployment of deep neural models.

- Leverage several deep learning libraries in Python such as TensorFlow, PyTorch, and Keras, able to appraise their affordances and limitations.

- Compare and contrast the results of deep learning experiments across a wide search space of hyperparameter and network architecture choices.

- Evaluate the effectiveness and efficacies of models using statistical methods.

- Experiment with different deep learning architectures such as multilayer perceptrons, recurrent neural networks, and convolutional neural networks.



## Repository Structure

```bash
├── LICENSE
├── README.md
├── fixtures
├── notebooks
|   ├── lab_1_sklearn_mlp.ipynb
|   ├── lab_2_tensorflow_mlp.ipynb
|   ├── lab_3_keras_image_clf.ipynb
|   ├── lab_4_pytorch_time_series.ipynb
|   └── lab_5_generative_adversarial_networks.ipynb
├── requirements
|   └── requirements.txt
└── results
```