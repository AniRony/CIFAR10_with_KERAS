# CIFAR10_with_KERAS
DNN on CIFAR10 Dataset from Keras API and then Checking Accuracy of the Model with inbuilt test dataset and also from images downloaded from Google to see the efficiency of the model in real life.
Model size is around 28 Mb after 60+60 = 120 epochs so couldn't be uploaded.
Our main aim was to cross check how the model works with real world present pictures on Google with this very old low (32x32x3) Pixel RGB images.
So as expected it's not so accurate as we reached 88% accuracy on dataset validation set only.
Many predictions failed specially between horse and bird or horse and dog
Also fialed many times between airplane and birds like eagles with big wings.
Accuracy was good enough, though the images were super pixelated and many human eyes can fail recognising the image which DNN actually recognises and learns so good and even sometimes better than humans.
This shows how powerful tool is DNN.
It can take this things to very high level accuracy with higher pixel images but at the cost of time and Free 12Gb GPUs on Google Collab.
You can try it as your self project if the accuracy actually increases if you can inrease the pixel information of those images to approximately(50x50x3)
