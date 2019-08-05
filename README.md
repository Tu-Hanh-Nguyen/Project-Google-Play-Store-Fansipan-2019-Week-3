# Full-time Machine Learning Course
# WEEK 3 PROJECT - GOOGLE PLAY STORRE

### Team 2: Nguyen Thi Diem Hang
###         Nguyen Hanh Tu
___

The project focus on data analysis of Google Play Store dataset which is provide by Kaggle. Each app (row) has values for catergory, rating, size, and more.

## Project Management

1. Create the google colab file
2. Write Description for the git hub 
3. Write the cleaning program in Jupyter
4. Make the report with Google Data Studio
5. Review and Revise
6. Make the presentation
____

##Questions for team

1. How to share the google colab file with your team?
```On the top right of Google Colab workspace, click "share"```

2. How to import the data to Google Colab
```
import pandas as pd 
from google.colab import drive
drive.mount('/content/drive')```
df=pd.read_csv('/content/drive/My Drive/google-play-store.csv')

3. How to clean the data?
Do it in sequence. First, clear the duplicates and missing values. Then, start cleaning the individual columns.

