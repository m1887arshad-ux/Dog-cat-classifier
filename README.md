# Dog-cat-classifier
<p align="center">
	<img src="https://storage.googleapis.com/kaggle-competitions/kaggle/3362/media/woof_meow.jpg">
</p>

# Cat Vs Dog Classifier

### About

In this project, we build an algorithm, a deep learning model to classify whether images contain either a dog or a cat.  This is easy for humans, dogs, and cats. Computers find it a bit more difficult.

### Data

The dataset is available at Kaggle and has been provided officially by Microsoft Research.You can find it [here](https://www.kaggle.com/c/dogs-vs-cats/data).

```
torch==1.1.0
torchvision==0.3.0
Flask==1.0.3
Pillow==6.0.0
numpy==1.15.4
pandas==0.23.4
matplotlib==3.0.2
requests==2.22.0
```

### Benchmarks

Our algorithm or model matched an average of 98% accuracy on test set. The best submission on Kaggle for the same is 98.9%. For more details you can check the [leaderboard](https://www.kaggle.com/c/dogs-vs-cats/leaderboard).

Below is the snapshot that was generated when we were training the model and validating its performance.

<p align="center">
    <img src="https://raw.githubusercontent.com/amitrajitbose/cat-v-dog-classifier-pytorch/master/data/training.png">
