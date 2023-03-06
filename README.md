# Visualizing-convolutions 

I recently started learning about *convolutional neural networks* and even though I could create one in [tensorflow](https://www.tensorflow.org/api_docs/python/tf/keras/layers/Conv2D), I was havaing a hard time understanding what convolutions are and what is going on under the hood. 
I couldn't understand how convolutions could filter image features using just a dot product:


![image](https://upload.wikimedia.org/wikipedia/commons/1/19/2D_Convolution_Animation.gif "found this on Wikipedia")

By Michael Plotke - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=24288958

I used numpy arrays, simple math and some images (real and created from 0s and 1s) to visualize the process, which definetely helped!
