# CGMH-CXR
This project contains NLP disease classification outcome, and the preliminary result of annotation，to demonstration the procedure of medical AI development process and application into medicine fields  


# Introduction:

Chest X-ray image data is often used in routine medical operations, and AI algorithms are used to collaborate with imaging specialists for data annotation. There have been many research results showing that a large number of chest X-ray image data can be classified  into  Normal  or Abnormal through chest X-ray data, in addition to reducing the work pressure of imaging doctors. Through the human-machine cooperation model, the sensitivity of chest diseases diagnosis is also improved, and the chance of misinterpretation is reduced.

# Data processing step:

1.	In the first Data labeling was use NLP tools to pre-label 14 types of chest diseases. The NPL tools label results are shown in Figure 
2.	Second，The preliminary classify results was review by a board of radiologist , The doctor will adjust the classification results of 
    the NLP algorithm based on the X-ray report  to determine the final labels, This procedure will improve about 50 % annotation 
    efficiency, and reduce annotation difficulty.
3.	The current Chest x-ray AI algorithm has an accuracy rate of over 90%, show as Fig3.



# NLP process outcome  
<img src= https://github.com/cgmhaicenter/CGMH-CXR/blob/master/disease%20classification.jpg height="400" width="700" />

Figure1: Output of NLP Diseases Classification 

# input image size (1024 *1024) 
<img src= https://github.com/cgmhaicenter/CGMH-CXR/blob/master/chest%20x-ray-example.png height="150" width="155" />

Fig2. Input image size :1024 *1024

# AI Model performance metrics




# AI Model inference reuslts

<img src= https://github.com/cgmhaicenter/CGMH-CXR/blob/master/inference_result.png height="400" width="700" />

Fig4. AI Mode’s Inference Result 
