---
title: Module 05 — Bike Rentals, Project
---

## Overview

After a few more meetings, your team has been assigned to address the following issues asked by the stakeholders:

<div class="dialogue">
	<img src="{{URLROOT}}/shared/img/zhao.jpg">
	<h5>Zhao, CEO of WelcomeBike</h5>
	<blockquote><p>So, there's not a lot to discuss at this point. We need a neural network that can predict the number of bikes we can expect to rent on a given day. I'll leave it up to you to decide which factors matter there.</p></blockquote>
</div>

<div class="dialogue">
	<img src="{{URLROOT}}/shared/img/johnny.jpg">
	<h5>Johnny, the data science intern</h5>
	<blockquote><p>Given how many variables there are in building neural networks, and how long it takes to train and test them, we probably need everyone on the team working on building and testing neural networks.</p><p>I'd suggest that you coordinate how to tackle that in a smart way.</blockquote>
</div>

!!!warning "Executive Summary"
	By now you know what level of quality we expect from you in terms of analysis summaries. From this point on, you will not be provided with an executive summary template.

	While you now have some leeway in the styling of this report, please ensure that what you turn in has the same level of quality and professionalism as previous templates.

## More Tips from Johnny

!!!note "Data Dictionary"
	Use this [data dictionary](./bikes-dictionary.txt) to help explain the values and sources of different columns in the dataset.
	
!!!note "Keras vs Sci-Kit Learn"
	Just because you're using keras and tensor flow to build the actual neural network, that doesn't mean you can't take advantage of some of the preprocessing and analysis modules in sci-kit learn. 

	Keras also provides [two wrappers](https://www.tensorflow.org/api_docs/python/tf/keras/wrappers/scikit_learn) that allow you to use sklearn pipeline style code with keras neural networks.

	For more information, see:
	
	* [How to insert Keras model into scikit-learn pipeline?](https://stackoverflow.com/questions/42415076/how-to-insert-keras-model-into-scikit-learn-pipeline)

	* [How to Grid Search Hyperparameters for Deep Learning Models in Python With Keras](https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/)


!!!warning "keras vs tf.keras"
	As [mentioned in the reading](./keras.html), Keras used to be a standalone library, but as of September 2019, it is part of Google's TensorFlow library.

	Keep that in mind if you're looking at any tutorial that was written prior to that date. Most of the API and functions will be the same, but your import statements will likely be different. 

	For more information, [see this article on the change](https://www.pyimagesearch.com/2019/10/21/keras-vs-tf-keras-whats-the-difference-in-tensorflow-2-0/).



<div class="dialogue">
	<img src="{{URLROOT}}/shared/img/johnny.jpg">
	<h5>Johnny, the Data Science Intern, catches you after work:</h5>
	<blockquote><p>Hey, I know you're probably busy, I was going to put together some hints and sample code for you like I usually do, but everything you should need is in those <a href="./keras.html">keras tutorials</a>, so be sure to read over those.</p></blockquote>
</div>


[^1]: [Lead Singer photo by Brian Lundquist on Unsplash](https://unsplash.com/photos/3Uf-aRahKcc)

[^2]: [Head of Marketing photo by LinkedIn Sales Navigator on Unsplash](https://unsplash.com/photos/pAtA8xe_iVM)

[^3]: [Data Science Intern photo by Fábio Lucas on Unsplash](https://unsplash.com/photos/iczrMDNuvzkml-pxK0Ovmw)