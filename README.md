# DenseNet_CIFAR10_Classification

DenseNet implementation on CIFAR10


## Team
Anusha Gajinkar - D19008 </br>
Arjun Kumar Singh - D19009 </br>
Swetha R  - D19031 </br>
Sree Soundarya -D19030 </br>
Vasundhara Singh - D19034 </br>

We used CIFAR-10 dataset for our experiments with DenseNet Architecture. 

#### No of params in model is  931420

#### Accuracy : 91.81(35 epochs)

The directory is defined as 

![](dir_struct.png)

## For Training

[Run Training Notebook file](TrainingNotebook.ipynb)



## For Inference

 we need Cifar-10 data for inference. Execute the below to generate 10 random images from cifar-10 test data.

```bash
cd data
python generate_valid_data.py
```

Run [Inference Notebook file](InferenceNotebook.ipynb)



## Model Serving on Flask.

For Serving this model as a website. First generate  test images by executing above commands and then.


```bash
python flask_api/app.py
```
