Lungs CT-based Classification for COVID19-vs-Non
COVID19

Data set information

https://github.com/Sagar610/CE888-Covid19
CT_COVID
CT_NonCOVID

this two folder contain 349 and 397 images of covid and noncovid

Execution

CE888_VGG16_COVID19.ipynb  this colab file contain all codes 

Binary image classification using CNN model 
there are severals models but I used VGG16 for COVID19
* VGG16 and VGG19: This is a keras model with 16 and 19 layer network that has an input size of 224X224
* ResNet50
* DenseNet
* MobileNet


# TransferLearning_COVID19

#### VGG16 improve Accuracy

|  Metrics |  Performance | 
|---|---|
|  Train Accuracy: | 1.00 |
|  Val Accuracy:   | 0.89 |
|  Test Accuracy:  | 0.92 |
|   Precision:     | 0.85 |
|   Recall:        | 0.92 |
| F1 Score:        | 0.89 |
| AUC:             | 0.92 |


## Baseline results:

#### Feature extractor based transfer learning

|  Metrics |  Performance | 
|---|---|
|  Train Accuracy: | 0.88 |
|  Val Accuracy:   | 0.74 |
|  Test Accuracy:  | 0.84 |
|   Precision:     | 0.94 |
|   Recall:        | 0.72 |
| F1 Score:        | 0.82 |
| AUC:             | 0.84 |

***

#### Fine tuning based transfer learning

|  Metrics |  Performance | 
|---|---|
|  Train Accuracy: | 0.99 |
|  Val Accuracy:   | 0.91 |
|  Test Accuracy:  | 0.88 |
|   Precision:     | 0.97 |
|   Recall:        | 0.79 |
| F1 Score:        | 0.87 |
| AUC:             | 0.88 |

