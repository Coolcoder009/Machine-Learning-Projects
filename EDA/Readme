# The Kaggle dataset is downloaded directly into Colab storage using the Kaggle API, without being saved to the local machine.
The code used to achieve this,
!pip install -q kaggle
from google.colab import files
files.upload()
!mkdir ~/.kaggle
!cp kaggle.json ~/.kaggle
!kaggle datasets download -d sobhanmoosavi/us-accidents
