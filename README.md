# Analyzing Machine Learning Models with Yellowbrick
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/parulnith/Analysing-Machine-Learning-Models-with-Yellowbrick/master?filepath=Analysing%20Machine%20Learning%20Models%20with%20Yellowbrick.ipynb)

Visualization thus has a critical role to play throughout the analytical process and is a, frankly, a must-have for any effective analysis, for model selection, and for evaluation. This article aims to discuss a diagnostic platform called **Yellowbrick** that allows data scientists to visualize the entire model selection process to steer us towards better, more explainable models—and avoid pitfalls and traps along the way.

![](https://cdn-images-1.medium.com/max/800/1*a9Po3znWlW2M_iFBKMB3EA.png)

## Yellowbrick
[Yellowbrick](https://www.scikit-yb.org/en/latest/about.html) is an open source, Python project that extends the scikit-learn API with visual analysis and diagnostic tools. The Yellowbrick API also wraps matplotlib to create interactive data explorations.

It extends the scikit-learn API with a new core object: the Visualizer. Visualizers allow visual models to be fit and transformed as part of the scikit-learn pipeline process, providing visuals throughout the transformation of high-dimensional data.

## Advantages
Yellowbrick isn’t a replacement for other data visualization libraries but helps to achieve the following:

* Model Visualization
* Data visualization for machine learning
* Visual Diagnostics
* Visual Steering

## Installation
Yellowbrick can either be installed through pip or through conda distribution. For detailed instructions, you may want to refer the [documentation](https://www.scikit-yb.org/en/latest/quickstart.html#installation).

### via pip
```
pip install yellowbrick
```
### via conda
```
conda install -c districtdatalabs yellowbrick
```
## Usage
The Yellowbrick API should appear easy if you are familiar with the scikit-learn interface.

![](https://cdn-images-1.medium.com/max/800/1*3zNcu8BnQDQ8KSTd8_6miw.png)

The primary interface is a Visualizer – an object that learns from data to produce a visualization. In order to use visualizers, import the visualizer, instantiate it, call the visualizer’s fit() method, and then, in order to render the visualization, call the visualizer’s poof() method, which does the magic!

## Blog
[Analyzing Machine Learning Models with Yellowbrick](https://heartbeat.fritz.ai/analyzing-machine-learning-models-with-yellowbrick-37795733f3ee)

![](https://cdn-images-1.medium.com/max/600/1*BGycbd7Wu-6X4AavrYAP9w.png)

## References
* [Documentation](https://www.scikit-yb.org/en/latest/quickstart.html#installation)

