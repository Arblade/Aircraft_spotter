# Aircraft_spotter

<p align="center">
![image](icon_spotter.png)
</p>

This repo has two main objectives :

- first create a CNN to recognize aircrafts
- secondly create a program to localize on a satelite image aircrafts of interest

Finally, we could combine both and apply it on main airbase of a built database.

## Find aircaft database

[FGVC database](https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/) as Fine Grained Visual Classification of Aircrafts.
Following Fine-Grained Visual Classification of Aircraft, S. Maji, J. Kannala, E. Rahtu, M. Blaschko, A. Vedaldi, arXiv.org, 2013
However this database is not adapted, aircraft are seen from edge, and we seek more an satelitte view.

![image](fgvc_planes.png)

[Planet Satellite ImageShip](https://www.kaggle.com/rhammell/planesnet) has the satelittte view. But images are of poor quality. This is done to localize planes on satelittes images. So more for the **second task**.

![image](planet_satellite.png)

## Recognize aircraft

## Spot aircraft

[Nice tuto from towards data science](https://towardsdatascience.com/airplanes-detection-for-satellite-using-faster-rcnn-d307d58353f1)

[An other one related to a published paper](https://medium.com/the-downlinq/rareplanes-dataset-paper-and-code-release-5b0cba300a0d)

[Rare planes Project](https://www.cosmiqworks.org/rareplanes-public-user-guide/) Very interesting, but dont know if it allows to classify panes by models (not sure).

