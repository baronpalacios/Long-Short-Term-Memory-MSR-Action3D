# Long-Short-Term-Memory-MSR-Action3D
Experiments with time series data and LSTMs.  Python language and the Keras library

Description: Experiments with time series data and LSTMs.

We are expected to use the Python language and the Keras library. We will prepare a report including your code and results (in a Jupyter Notebook). The report format is shown at the end of this document.

You will use MSR Action3D dataset which can be found at http://research.microsoft.com/en-us/um/people/zliu/actionrecorsrc/. This data set contains 567 actions with 20 action types, 10 subjects. Each action frame has 20 joints (joints are in 3D).
Part 1: Prepare your data
Do appropriate
Part 2: Train an LSTM
Do the following steps:
1. You feed your network frame by frame until the (n-1)st frame .
2. Your generative LSTM network will predict the nth frame.
3. Use the Euclidean distance between the prediction and the actual joint locations for the nth frame as the loss function.
4. Optimize the network using your preferrred algorithm.
Helpful links: https://github.com/spiglerg/RNN_Text_Generation_Tensorflow
Note that this code generates new character, in your case, the character is a frame of action with size 60=20*3.
You will draw your generated skeletons on images and put them together to produce a video of skeleton. Upload your video to youtube.com and include your video address in your submission.
