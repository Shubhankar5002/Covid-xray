# COVID-19 Detection from X-Rays of Patients

## A descriptive analysis for Attention based CNN models.

### Dataset
![](https://github.com/Shubhankar5002/Covid-xray/blob/main/images/xray.jpg)


Conventional CNN architecture models take more epochs to converge and doesn't perform well on the given tasks. The notebooks show a comparative study of the different architectures.

### CNN without attention model performances
After 20 epochs the model has the following results : 

![Classification report](https://github.com/Shubhankar5002/Covid-xray/blob/main/images/cnn_classi.jpg)

![Confusion Matrix](https://github.com/Shubhankar5002/Covid-xray/blob/main/images/cnn_confusion.jpg)

### CNN model with attention
After 20 epochs the model has the following results :

![Classificaition report](https://github.com/Shubhankar5002/Covid-xray/blob/main/images/attention_classi.jpg)

![Confusion matrix](https://github.com/Shubhankar5002/Covid-xray/blob/main/images/extended_confusion.jpg)


Attention model's performance on extended dataset:


![Extended performance](https://github.com/Shubhankar5002/Covid-xray/blob/main/images/attention_extended.png)

### Final comparisions of the model 
![](https://github.com/Shubhankar5002/Covid-xray/blob/main/images/performance.png)