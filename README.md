## List of AI Projects 

This is a list of projects that I have conducted at university and various project teams! I plan to create more polished projects through more projects and in-depth learning in the future!

### 1. Used Car Price Prediction Regression Model
During my third year (first semester) Data Mining course at university, I studied regression models and carried out a project to build a regression model that predicts the price of used cars. In order to acquire used car data, I collected data from a used car trading platform called "Bobae Dream". This project allowed me to experience data crawling firsthand and understand the concepts of various regression models (linear regression, Ridge, Lasso, ElasticNet regression, DT, RF, etc.).


[Paper link](https://github.com/Kdavid2355/ai_project/blob/main/project_paper/Used_Car_Price_prediction.pdf) / [Code link](https://github.com/Kdavid2355/ai_project/blob/main/codes/Used%20car%20price%20prediction%20model.ipynb)


###  2. Dacon Wallpaper Defect Type Classification AI Competition
This was a competition to classify 19 types of defects in walls or construction work, such as wallpapering. I thought that the key to this task was to solve the severe imbalance of the given data. Although there were many parts I regret as this was my first AI project, I was able to learn about the concepts of data augmentation, transfer learning, and study various image classification models such as ResNet, DenseNet, and VGG.

####  Lessons Learned
(1) Choosing a model with a small number of layers depending on the amount of data

In a situation where there was not a lot of data, I chose a model with many layers such as ResNet 152, which showed high accuracy in training but not good performance in testing. The evaluation from the organizers showed an accuracy of 54%, and I learned that I should have used a model with fewer layers such as ResNet 18.

(2) Do not perform data augmentation on test data

I performed data augmentation on the entire given data and divided it into a 7:3 ratio for training/evaluation, but I learned that I should only augment the training dataset and separate the test data in advance.






[Paper link](https://github.com/Kdavid2355/ai_project/blob/main/project_paper/Paper%20defect%20type%20classification%20model.pdf) / [Code link](https://github.com/Kdavid2355/ai_project/blob/main/codes/Paper_defect_type_classification_model.ipynb)
