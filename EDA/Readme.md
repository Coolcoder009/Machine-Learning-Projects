# The Kaggle dataset is downloaded directly into Colab storage using the Kaggle API, without being saved to the local machine.<br>
## The code used to achieve this,<br>
!pip install -q kaggle <br>
from google.colab import files <br>
files.upload() <br>
!mkdir ~/.kaggle <br>
!cp kaggle.json ~/.kaggle <br>
!kaggle datasets download -d sobhanmoosavi/us-accidents <br>
