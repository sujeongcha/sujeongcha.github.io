---
layout: post
title: Detecting Fake Yelp Reviews 
---

![placeholder](https://sujeongcha.github.io/public/fakeReview.jpg "Photo by Morning Brew on Unsplash")

<div class="message">
  <ul>
    <li> Task: Supervised learning > Classification </li>
    <li> Models: XGBoost, Naive Bayes, Doc2Vec </li>
    <li> Language: Python </li> 
  </ul>
</div>

#### :star::star::star::star::star: but tastes like :poop:?

Online reviews have increasingly gained popularity and become an integral part of customers’ purchasing decisions. According to the Local Consumer Review Survey, 82% of customers regularly read online reviews and find
information about local business, and 76% of people surveyed responded that they trust online reviews as much as the personal recommendations1. As a result, detecting fake reviews has gained much importance for many online
venues in order to provide the customers more credibility and to protect the venue’s reputational risks. This project aims to compare different classification models that detect
fake reviews. The best score was obtained by XGBoost model, combined with engineered features, Doc2Vec features from Gensim library, and TF-IDF probability estimate feature, with the average validation and test
precision score reaching 0.446 and 0.440 respectively.

Final report and Python scripts can be found <a href="https://github.com/sujeongcha/artificial-cilantro">HERE</a>.
