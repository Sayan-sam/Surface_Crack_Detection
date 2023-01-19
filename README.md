
# L&T EduTech Hackathon
#### Problem Domain: AI Solutions for Industrial and Societal Problems
**PS1 -**

**Description -** Concrete cracking is a major issue in Bridge Engineering. Detection of cracks facilitates the design, construction and maintenance of bridges effectively.
**Requirement Specification:**

-   Use open source dataset (From the link:  [https://cutt.ly/PS_1_dataset](https://cutt.ly/PS_1_dataset))
-   Develop a suitable Deep Learning framework which can detect the crack in the image from the dataset
-   Transfer Learning based DL framework would be appreciated

**Judging Metrics:** Provide  Precision, Recall and F1 score as Judging metrics


![Cracked Wall](https://media.istockphoto.com/id/171151393/photo/a-big-crack-on-an-old-rotten-wall.jpg?b=1&s=170667a&w=0&k=20&c=cYpp2kkFuDKFmzjdYVSaU_B76qGG9Do5Wz564hemeH0=)
### Dataset Visualization
![DataSet](resources/data.png)
![DataSet](resources/augment.png)
### Model Architecture
VGG16(224,224,3) -> Dense(112, relu) -> Dense(52, relu) -> Output(1, sigmoid) 
### Training Graphs
![Metrics](resources/metric1.png)
![F1Score](resources/metric2.png)
### Metrics
|Dataset|Accuracy  |Precision  |Recall|F1 Score|
|--|--| --| --|--|
|Training (3000)  | 100% | 100% | 100% | 100%
|Validation (800)  | 98.25% | 97.54% | 99% | 98.11%
|Testing (200)  | 100% | 100% | 100% | 100%

### Prediction over higher resolution images
![Image1](resources/predict1.png)
![Image1](resources/7742b149-0702-49da-9ad5-ab7d80ab3fba.png)
