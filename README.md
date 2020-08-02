# Mask-detection-using-openCV
Detect in real-time if the person is wearing mask or not.
# DATA
<p>I collected dataset which already contains augmented data.</p>
<p>I link for the dataset is <a href="https://github.com/prajnasb/observations/tree/master/mask_classifier/Data_Generator">here</a></p>
# STEPS
<p>1. I seperated the dataset into test and train.</p>
<p>2. I defined the no. of epoches[10] and the batch size[32].</p>
<p>3. I used MobileNetV2 to classify the images either wearing mask or not wearing mask.</p>
<p>4. I trained the model on the dataset.</p>
<p>5. I then tested the model on the test dataset.</p>
<p> 6. I then used opencv to analyse real-time video and to make real-timeprediction if the person is wearing mask or not.</p>

![Alt text](FaceMask Detection.gif) / ![](FaceMask Detection.gif)


