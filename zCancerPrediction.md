---
title: Predicting Breast Cancer with Binary Classification 
layout: page
description: 'Predicting Breast Cancer with Binary Classification'
image: assets/images/1.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Predicting Breast Cancer - Binary Classification </h2>
		</header>
		<p>I chose to work with the Wisconsin breast cancer dataset. The question at hand is whether there are characteristics that can

accurately predict whether a tumor is a benign one or malignant. This is an important question since if such characteristics can be found having much predictive power, potentially malignant tumors could be identified earlier and lives will be saved. This is not a truly causal question, since the shape or size of the tumor does not cause it to be malignant, but rather could be highly correlated; therefore, it is more of a descriptive question. For true causal inference, matching or ATE for some treatment should be calculated. Classification tasks such as this one are good to gauge a descriptive understanding.

</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/Screen Shot 2018-02-24 at 21.20.53.png %}" alt="" 
			data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>The Model</h3>
				</header>
				<p>
                The target variable is the observation — malignant or benign. Class distribution: 357 benign, 212 malignant
                Since this is a case-study classic dataset I didn’t need to transform any variable. While numerous variables exist, and there could be a whole study regarding feature selection based on this data, since our focus is on the model specification and not feature selection I will choose only one variable (“Cell.size”) to shed light on model differences.
                </p>
				<ul class="actions">
					<li><a href="http://rpubs.com/oba2311/binary-classification-breast-cancer" class="button">R code</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>