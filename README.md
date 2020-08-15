# Mask-detection-using-openCV
Detects in real-time if the person is wearing a mask or not.
# DATA
<p>I collected dataset which already contains augmented data.</p>
<p>I link for the dataset is <a href="https://github.com/prajnasb/observations/tree/master/mask_classifier/Data_Generator">here</a></p>
<h1>STEPS</h1>
<p>1. I seperated the dataset into test and train.</p>
<p>2. I defined the no. of epoches[10] and the batch size[32].</p>
<p>3. I used MobileNetV2 to classify the images either wearing mask or not wearing mask.</p>
<p>4. I trained the model on the dataset.</p>
<p>5. I then tested the model on the test dataset.</p>
<p> 6. I then used opencv to analyse real-time video and to make real-timeprediction if the person is wearing mask or not.</p>
<h1>DEMO</h1>

![FaceMask Detection](https://user-images.githubusercontent.com/53776611/89124703-9a0fee00-d4f6-11ea-9824-8aa545f9b5ce.gif)
<h1>RUN</h1>
<p>Mask_detection.ipynb notebook contains the main code,you can you can download the notebook 
  and run each cell and check the output.</p>
 <p>1.model contained the saved model with best accuracy,so that you don't have to train every single time.</p>

  



