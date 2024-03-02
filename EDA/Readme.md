# EDA-Exploratory Data Analysis <br>
Exploratory Data Analysis (EDA) is a crucial step in the machine learning pipeline that involves examining and understanding the dataset before applying any models. EDA helps in uncovering patterns, trends, and insights in the data, and it aids in making informed decisions about data preprocessing and model selection.


## The Kaggle dataset is downloaded directly into Colab storage using the Kaggle API, without being saved to the local machine.<br>
### The code used to achieve this,<br>
!pip install -q kaggle <br>
from google.colab import files <br>
files.upload() <br>
!mkdir ~/.kaggle <br>
!cp kaggle.json ~/.kaggle <br>
!kaggle datasets download -d sobhanmoosavi/us-accidents <br>
