# Fake-Review-on-Yelp

In this research, I explored the impact of textual and behavioral features on defining fake reviews signatures. I have conducted the examination in three perspectives i.e. review-centric, reviewer-centric and product-centric to understand their versatility and have trained 7 classifiers under the above-mentioned settings to examine the effectiveness of different features. My results indicate that taking reviewer’s and product’s behavioral and textual features into account will be more useful to the detection than by only using contextual features. Moreover, features belonging to reviewers are more crucial than to products for classification.
However, while the hybrid features outperform the reviewer-centric features, the outperformance is still very marginal. My research also has some limitations: a. I did not combine review-centric features like useful unigram or bigram with features I set up later to test performance, not to mention those features I tried in the exploration stage, b. I did not compare features in each centric to filter some useless features. There are many more content similarity comparison methods, but I only have tried one method and one pre-trained model.
