# EDA-Exploratory Data Analysis <br>
### Exploratory Data Analysis (EDA) is highly advantageous when applied to large datasets. It serves as a powerful tool for uncovering hidden patterns and trends within the data, providing invaluable insights that facilitate informed decision-making. Furthermore, EDA plays a crucial role in assessing the quality of the dataset, allowing for a thorough examination of data integrity by identifying outliers and anomalies. In the context of large datasets, EDA becomes particularly significant for understanding feature importance. It aids in the identification of key variables, guiding the selection of features essential for effective modeling. Additionally, EDA contributes to informed model selection by providing a comprehensive understanding of data characteristics and relationships between variables. By strategically applying EDA techniques, one can optimize resource utilization, ensuring a balance between computational efficiency and the extraction of meaningful insights from vast and complex datasets.

## The Kaggle dataset is downloaded directly into Colab storage using the Kaggle API, without being saved to the local machine.<br>
### The code used to achieve this,<br>
!pip install -q kaggle <br>
from google.colab import files <br>
files.upload() <br>
!mkdir ~/.kaggle <br>
!cp kaggle.json ~/.kaggle <br>
!kaggle datasets download -d sobhanmoosavi/us-accidents <br>
