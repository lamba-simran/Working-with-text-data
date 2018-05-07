# Working-with-text-data

In this task, I have solved an imbalanced text classification task.

The dataset can be downloaded from the following links:
https://www.dropbox.com/s/6ot9w3on66gp129/hw5_data_test.csv?dl=1
https://www.dropbox.com/s/71q00c3r3vmsz9j/hw5_data_train.csv?dl=1

The dataset consists of Women’s fashion online shop reviews, consisting of a title, a review
text, and whether the review author would recommend the product. I have tried to determine
whether a reviewer will recommend a product or not based on review title and review.
In a real application this might allow us to find out what is good or bad about certain products
or to feature more typical reviews (like a very critical and a very positive one).

For all tasks, cross-validation has been used to evaluate the results. I used a metric that’s appropriate for
imbalanced classification (AUC or average precision for example), and inspected all models by
visualizing the coefficients.

For each of the tasks, I selected a single best model, explaining my choice, and evaluated this model using
the test set.
