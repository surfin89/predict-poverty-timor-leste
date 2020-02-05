# predict-poverty-timor-leste

# Order to run Jupyter file
1. "download_nightlights_data.ipynb"

This process download nighttime light data as of 2013

2. "process_survey_data.ipynb"

This process manipulate DHS data to use for further analysis

3. "download_images.ipynb"

This process downlaod images(2km x 2km) of DHS clusters from Google Stats API

4. "train_cnn.ipynb"

Use CNN to train model to estimate nighttime light using daytime light imagery

5. "predict_consumption.ipynb"

Predict DHS welfare status using the model developed in the previous process.

# The result

R2 is 0.62
![image](https://user-images.githubusercontent.com/36351927/73823859-a243e500-4855-11ea-91f4-24d7225de2d4.png)
