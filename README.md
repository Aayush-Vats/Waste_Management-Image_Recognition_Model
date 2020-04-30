# ENiAC-Environment-DevHacks
Waste segregation process leads to recycling of waste, energy generation out of waste, reduction of waste and lessening of land fills. Our system helps to enable the sustainability of the waste management sector with participation from both the municipalities and private agencies .The purpose of our smart waste collection system is to propose a method of identification that performs detection using images to identify the different types of waste containers.The main goal is to be able to successfully identify and classify waste containers in a reliable manner.The economic value of waste is best comprehended when it is segregated. The waste becomes valuable if it is segregated and recycled using the recent advancements in technology thereby becomes a useful entity. This conversion method of waste can be employed to generate synthetic gas made up of carbon monoxide and hydrogen. The gas after burning can be used to produce steam and electricity, and for generation of bio fuels.Using convolution neural network, a class of deep, feed-forward artificial neural network has successfully been applied to analyze the image. Thus, in waste segregation using deep learning involves acquiring images from camera with detection, object recognition, prediction and classification into categories as biodegradable and non- biodegradable.For this system to be sustainable,awareness of household preferences is essential for design of this system.With the advent of deep network architectures that deals with Big Data, provides the best in class performance in terms of accuracy, scalability, adaptability without any feature engineering.
Libraries required -

Tensorflow-cpu/gpu
Open-Cv
Steps to run

Clone the repository to a directory
For personal training run the "tr.py" file
For using the fully trained model for direct prediction run "prediction.py" file
For Connection to Raspberry Pi-

Transfer the model to Raspberry Pi
Install tensorflow and replace opencv with picamera
Use the prediction to rotate the servo motor in desired direction using "servo.py" file
