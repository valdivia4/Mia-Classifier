# Mia-Classifier

This repository contains a jupyter notebook that does the following:
1. Gathers images of tuxedo cats scraped from Google Images.
2. Shows images of Mia (my cat) and non-Mia tuxedo cats as a sanity check that data was properly gathered.
3. Trains a PyTorch resnet-34 which was pretrained on ImageNet using two methods: first, by freezing the last layers and second, by fine-tuning of the whole network.
4. Achieves 99% accuracy of detecting whether an image of a tuxedo cat is Mia or is not Mia on a held-out validation set.

This project was made using the template notebook found at: https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb. It makes use of the [fastai](https://docs.fast.ai/) tools built on top of PyTorch, which allow for incredibly quick experimentation and state-of-the-art results. The notebook is part of their course found at: https://course.fast.ai/.

This work stemmed from my mom saying that a lot of cats out there were like Mia, but I disagreed and argued that she was one-of-a-kind. I hope that the fact that even a computer program can see how Mia differs from other tuxedo cats is a sufficient disproof of her statement. I would think Mia agrees.

<img src="https://github.com/valdivia4/Mia-Classifier/blob/master/img/mia.png" height="160" width="90">
