# Interpreting-CNN-BiLSTM
Code for the term paper of Explainability Methods for Neural Networks seminar. Text classification models - CNN and BiLSTM - are interpreted using Integrated gradients and Layer-wise Relevance Propogation.

The juypter notebook `sentiment_analysis_keras_cnn_innvestigate.ipynb` contains the code for experiments mentioned in the term paper. 

The other two jupyter notebooks contain code for CNN and BiLSTM interpretation using the Integrated Gradients method from the PyTorch library - [Captum](https://captum.ai/).  

Since Captum doesn't support LRP, a CNN classifier was trained in Keras and using, the [iNNvestigate](https://github.com/albermax/innvestigate) framework, a CNN model trained for different number of epochs was analyzed.

Note:
All the Jupyter notebooks can be run independently on Google collab. For my experiments, I used Google Collab and hence, the libaries that are not installed on the collab server will be download on the running the notebook there.