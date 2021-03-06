---
layout: post
title: Data Science Resources
categories: resources
---

A living and ever changing library of useful technologies, libraries and platforms for data science.

<!-- more -->

<h3>Contents</h3>

<ul>
	<li><a href="#python">Python</a></li>
	<li><a href="#mathsandstatistics">Maths and Statistics</a></li>
	<li><a href="#machnielearning">Machine Learning, Deep Learning and AI</a></li>
</ul>


<h2 id="python">Python</h2>

<h3><a href="https://github.com/fastai/fastai">fast.ai</a></h3>
Fast.ai is a machine and deep learning library designed by Jeremy Howard with the intention to allow developers without a maths background to develop world class ML/DL models in the shortest time possible. Built on PyTorch.

Accompanying the library is the <a href="http://www.fast.ai/">fast.ai MOOC</a>, which has been the best ML / DL course I have completed to date.

The <a href="http://www.fast.ai/topics/">fast.ai blog</a> is also an invaluable resource

{% highlight python %}
# Installation
pip install fastai
{% endhighlight %}


<h3><a href="https://github.com/fastai/fast_progress">Fast progress</a></h3>
Simple and flexible progress bar for Jupyter Notebook and console, developed by the fast.ai team

{% highlight python %}
# Installation
pip install fast_progress
{% endhighlight %}

<h3><a href="https://github.com/chrispaulca/waterfall">Waterfall Charts</a></h3>
Waterfall charts for visualising marginal value contributions using a starting value (bias). 

{% highlight python %}
# Installation
pip install waterfallcharts
{% endhighlight %}

<h3><a href="https://github.com/EpistasisLab/tpot">TPOT</a></h3>
TPOT (Tree-based Pipeline Optimization Tool) is an automated machine learning tool that optimizes machine learning pipelines using genetic programming.

TPOT is built on top of Scikit-learn and it automates the most tedious parts of machine learning like feature selection, model selection, feature construction, etc, by exploring thousands of possible pipelines to find the best one for the data. It then provides you with the Python code for the best pipeline it found for manual exploration and tweaking.

Follow the installation instructions: <a href="http://epistasislab.github.io/tpot/installing/">Installation Guide</a>

{% highlight python %}
# Then install TPOT
pip install tpot
{% endhighlight %}

<h3><a href="https://www.featuretools.com/">FeatureTools</a></h3>
Featuretools is a framework to perform automated feature engineering. It excels at transforming temporal and relational datasets into feature matrices for machine learning.

{% highlight python %}
# Installation
pip install featuretools
{% endhighlight %}
Then follow the quickstart guide: <a href="https://docs.featuretools.com/#minute-quick-start">5 minute Quick Start</a>


<h3><a href="https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html">Jupyter nbextensions</a></h3>
The jupyter_contrib_nbextensions package contains a collection of community-contributed unofficial extensions that add functionality to the Jupyter notebook. These extensions are mostly written in Javascript and will be loaded locally in your browser.

{% highlight python %}
# Install Python package
pip install jupyter_contrib_nbextensions

# Install JavaScript and CSS files
jupyter contrib nbextension install --user
{% endhighlight %}
<a href="https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html">Documentation</a>

<h3><a href="https://github.com/ResidentMario/missingno">Missingno</a></h3>
A great Python package to visually display the extent of missing values in a dataset.

{% highlight python %}
# Install Python package
pip install quilt
quilt install ResidentMario/missingno_data

# Import
import missingno as msno

# Bar chart example
msno.bar(collisions.sample(1000))

{% endhighlight %}
<a href="https://github.com/ResidentMario/missingno">Documentation</a>

<h2 id="mathsandstatistics">Maths and Statistics</h2>

<h3 id="linearalgebra">Linear Algebra</h3>

<ul>
	<li><a href="https://stanford.edu/~shervine/teaching/cs-229/refresher-algebra-calculus.html">Stanford CS 229 Linear Algebra Cheat Sheet</a></li>
</ul>

<h3 id="statistics">Statistics</h3>

<ul>
	<li><a href="https://stanford.edu/~shervine/teaching/cs-229/refresher-probabilities-statistics.html">Stanford CS 229 Probabilities and Statistics Cheat Sheet</a></li>
</ul>

<h2 id="machnielearning">Machine Learning, Deep Learning and AI</h2>

<ul>
	<li><a href="https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning.html">Stanford CS 229 Supervised Learning Cheat Sheet</a></li>
	<li><a href="https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-unsupervised-learning.html">Stanford CS 229 Unsupervised Learning Cheat Sheet</a></li>
	<li><a href="https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-deep-learning.html">Standford CS 229 Deep Learning Cheat Sheet</a></li>
	<li><a href="https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks.html">Standford CS 229 Machine Learning Tips and Tricks Cheat Sheet</a></li>
</ul>