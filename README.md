# Face2Text
Face2Text is a model that will take the image of a face as it's input and describe the face according to facial features and emotional state in the form of a gramatically coherent sentence.

# Data

<ul>
<li>Dataset used is the one described in the paper <a href="https://arxiv.org/abs/1803.03827" >Face2Text: Collecting an Annotated Image Description Corpus for the Generation of Rich Face Descriptions</a> </li>

<li>It was made available to us on request. The data can be obtained by contacting either the RIVAL group or the authors of the aforementioned paper.</li>

<li>The dataset consists of the around 5685 annotated images chosen randomly from CelebA dataset.</li>

<li>The annotations describe the images as naturally as possible and focus on capturing the person's facial expression and/or their emotional state.</li>

<li>To our knowledge, we seem to be the first to work on this dataset for task of face description. </li></ul>

# How to run code

1) Clone this repo.
2) Get the data by either contacting the RIVAL group or the authors of the paper add raw.json file in the data\ subdirectory.
3) Download <a href="https://www.kaggle.com/jessicali9530/celeba-dataset" >CelebA dataset</a> and extract it to the data\ subdirectory.
4) Run the jupyter notebook Face2Text_notebook_Xception.ipynb in the notebooks\ subdirectory.
5) For Real Time face description, run the jupyter notebook RealTime.ipynb in the notebooks\ subdirectory.

# Model's Performance 

The following are model's predictions for image descriptions:

![Test Image 1](https://github.com/jani-boop/AI_Hackathon/blob/master/test1.png)

![Test Image 2](https://github.com/jani-boop/AI_Hackathon/blob/master/test2.png)

![Test Image 3](https://github.com/jani-boop/AI_Hackathon/blob/master/test3.png)

# Future Improvements

<ul><li>Use a pretrained network trained for face recognition task to get image encodings. This can help identify the nuances in facial features and give better performance</li>

<li>Fine tune beam search</li>

<li>Perform hyperparameter tuning</li>

</ul>
