# Mia-Classifier

This repository contains a jupyter notebook that does the following:
1. Gathers images of tuxedo cats scraped from Google Images.
2. Shows images of mia and non-mia tuxedo cats to verify that data was properly gathered.
3. Trains a pytorch resnet-34 pretrained on ImageNet using freezing the last layers and fine-tuning of the whole network
4. Achieves 99% accuracy of detecting whether an image of a tuxedo cat is Mia or not Mia on a held-out validation set.

This project was made using the template notebook found at: https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb. It makes use of the [fastai](https://docs.fast.ai/) tools built on top of PyTorch, which allow for incredibly quick experimentation and state-of-the-art results. The notebook is part of their course found at: https://course.fast.ai/.
