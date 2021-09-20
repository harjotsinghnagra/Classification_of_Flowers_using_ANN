# Classification of Flowers using ANN
This Model is going to classify the iris flowers for us using Artificial Neural Networks (ANN).<br/>
__Live Link__ - https://iris-flower-classification-app.herokuapp.com/
 
![image](https://miro.medium.com/max/1400/0*Uw37vrrKzeEWahdB)
 
## Problem Statement:
Create the model that can classify the different species of the Iris flower.
<br>
 <h2>Model</h2>


The network itself was implemented using **transfer learning**. The MobileNet V2 model developed at Google was used as a base model for feature extraction from our data. A custom classification layer was added on top and trained separately. You can learn more about this approach [here](https://www.tensorflow.org/tutorials/images/transfer_learning). The notebook I used to implement the model on Google Colab can be found [here](https://github.com/Vipul1947/classify_fruits_and_its_freshness/blob/main/notebooks/FruitNetTransferLearning.ipynb).
<br><br>


## Dataset:
- __150 Sample__
- __3 Labels__: Species of Iris (Iris setosa, Iris virginica and Iris versicolor)
- __4 Features__: Sepal length, Sepal width, Petal length, Petal Width in cm.
 
![image](https://miro.medium.com/max/1400/0*7H_gF1KnslexnJ3s)

<br>
<br>
<h2> FLOW CHART </h2>




<br>

## Requirement:
- Anaconda
- IDE: VS Code, Sublime Text, etc
- Python 3.7

<br><br>
<h2>IO Screenshots</h2>

![image](https://user-images.githubusercontent.com/80465715/133967467-9e424b63-f87c-460c-a6c3-24c189fa66c7.png)

![image](https://user-images.githubusercontent.com/80465715/133967541-c07ad74e-1402-49da-a65b-87533e1aab9b.png)



<br>

<h2> Install and run on local host</h2>

<h4>To install and run local host:</h4>

```bash
git clone https://github.com/harjotsinghnagra/Classification_of_Flowers_using_ANN.git
cd Classification_of_Flowers_using_ANN
pip install -r requirements.txt
python app.py
```
