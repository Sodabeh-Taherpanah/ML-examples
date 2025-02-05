# Teaching
Naive base Algorithm: all features are independent

#SVM
supervised learning algorithm used for classification and regression problems.
where:
✅ Text classification (e.g., spam filtering).
✅ Image recognition (e.g., face detection).
✅ Medical diagnosis (e.g., cancer detection).
✅ When a dataset is small & has clear boundaries.
 Sentiment Analysis : reviews or social media comments.
SVM finds the best hyperplane (decision boundary) that maximizes the margin between classes.

    Margin: The distance between the hyperplane and the closest data points (called support vectors).
    Support Vectors: Data points that are closest to the hyperplane; they define the boundary.
    Optimal Hyperplane: The decision boundary that maximizes the margin.

#Linear SVM: 
f(x)=w⋅x+b    w: weight vector: Determines the direction and slope of the decision boundary. 
b: bias term (shifts the hyperplane): Determines the position of the decision boundary (shifts it up/down)   
-> y=sign(w⋅x+b)
Strategy: find two lines  w-b  and w+b   with min w and the line between them is our final line

3Non-Linear SVM (Kernel SVM):
