# Plate detection-counting

![hate](https://user-images.githubusercontent.com/61036755/95574233-42d44f80-0a4a-11eb-91ab-4736a7fb5c00.jpg)
<p>This is Hate speech detection model created using Count Vectorizer and XGBoost Classifier with an Accuracy upto 0.9471, train-test split of 70:30, which can be used to predict whether tweets are hate or non-hate.</p>

<hr>

<h3> Dataset: </h3>
<ul>
<li>Dataset creation-Extracted images using frames from video.Created dataset of 250 Images.
•	Created Annotations of 175 Images using “LabelImg tool”, with label as “plate”.
•	Stored the co-ordinates of bounding box in txt file for each annotation.
•	Trained model using YOLO Algorithm.
•	Successfully trained the model with best Accuracy of 0.8416 with loss value of 0.07.
•	Also trained Tiny-yolo model for better performance & optimization, writes 10 to 11 frames in a second whereas in yolo takes 3 to 4 seconds to write a frame.
•	Tiny-yolo gave Accuracy upto 0.82, with loss value of 0.11.
•	Added features: Displaying current date & time in video, saving video with current date & time with mp4 extension, Auto-delete feature for 45 days(1.5 month) using os module.
•	For Auto-delete feature execution the formula used:
No. of days*24*60*60. 
</b></p></li>
</ul>

<hr>

<h3> Tools used for project development: </h3>
<ul>
<li><p><b>Numpy</b></p></li>
<li><p><b>opencv</b></p></li>
<li><p><b>datetime</b></p></li>
<li><p><b>os</b></p></li>
<li><p><b>XGBoost Classifier</b></p></li>
<li><p><b>Random Forest Classifier</b></p></li>
<li><p><b>Decision Tree</b></p></li>
<li><p><b>Support Vector Machine</b></p></li>
<li><p><b>Logistic Regression</b></p></li>
<li><p><b>K Nearest Neighbours</b></p></li>
<li><p><b>Gaussian Naive Bayes Classifier</b></p></li>
</ul>

<hr>

  <p> If you like this repo, please don't forget to give a ⭐.
</p>
