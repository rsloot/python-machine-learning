# Machine Learning in Python
 - This is my follow-along code to the book <a href=https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka/dp/1783555130/>Python Machine Leaning</a> by <a href="https://github.com/rasbt">Sebastian Raschka</a>


Phenomenal book! Great insight of the math and statistics behind a handful of the most implemented ML algorithms today.
This book is a little different than most I have read through, in that we implement the algorithm from scratch (greedy often)
to gain intuition and a firm understanding about what is going on inside the algorithms. And once we have an stable implementation
of the algorithm, it shows how to implement using scikit-learn. 

### Highlights
 - Chapters 1-4 are very good introduction to ML and Data Science, cleaning, preprocessing, and intro to sklearn, logistic reg,
 	sets the foundation for the rest of the book.
 - Chapter 5 (Dimensionality Reduction): describes PCA and LDA in some detail; one of the more important chapters
 	in the book. PCA is one of the more difficult algorithms to implement from scratch, pretty math heavy, but solid 
 	explanations stepping through the algorithms and example use cases for each!
 - Chapters 6-10: we get introduced to pipelines, which allow for simplified, easier to read code. Optimizing hyper-parameters via grid search,
 	as well as algorithm selections using cross validation. Plotting characteristics: ROC curves, AUC. Majority voting principle - stacking. 
 	Boosting weak learners (Adaboost). Sentiment Analysis on IMDB data. Serializing estimators and building web-app with sentiment analysis
 	model (pickle). Regression analysis.
 - Chapter 11 (Clustering Analysis): Cool chapter! have learned a descent amount before about kmeans and hierarchical clustering, but this
 	book did a really nice job with the visualizations to introduce some new methods I had not seen before for example DBSCAN. Which essentially
 	is more flexible than kmeans and hierarchical clustering because it does not assume circular clusters, there are drawbacks.
 - <b>Chapter 12 (Training Artificial Neural Networks)</b>: the chapter I was looking forward to the most! It does not disappoint, brings the whole
 	book together. A feed forward multi-layer perceptron, the book explains the different layers of ANNs, forward propagation (using sigmoid), and backpropagation(!), supplemented this section by re-watching Andrew Ng's ML videos on neural nets. Debugging neural nets with gradient checking. Gives intuition on the convergence in neural nets, convolution neural networks, and recurrent neural networks.
 - Chapter 13: A nice tutorial/intro to parallelizing with Theano. The GPU in the computer I was using at the time of going through this book was crap, I need to re-work this chapter.
