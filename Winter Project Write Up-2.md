Brice Patchou

<patchou@usc.edu>

I used Transfer Learning and Fine Tuning to create a CNN model that can differentiate muffins and chihuahuas.

I was given a dataset from Kaggle of a combined total of about five thousand images. When I preprocessed the data, I made the images the same size, and same orientation(turned them around or flipped them) in order for them to be processed by the model efficiently.

Since I was instructed to use Transfer Learning for this project, I used a CNN model. As I was reviewing the material, I found that using transfer learning is the most efficient way to go about this project as you remove a significant amount of training with a pre-trained model. Although many might have used twenty or more epochs for their model, I only used ten simply because I did not want to wait an hour for results. This also means that I had to adjust my scheduler as well. I made it so that for every epoch, the learning rate would change by 5 percent. There was not a particularly practical reason why I chose a relatively small number of epochs. Usually, one would want to use more epochs for better results, but I was beginning to run out of time. Had I had more time, I would have increased the number of epochs. In the end, I ended up with the best accuracy of 0.994. This is an impressive score given the hyperparameters I used, but it could have been better had I used more epochs and a more efficient scheduler.

This problem is an example of binary classification: a machine-learning technique that is used to classify information into two categories. This concept can easily be expanded beyond differentiating a chihuahua and a muffin. In the finance industry, binary classification can be used to detect fraudulent transactions and prevent financial crimes. In the health industry, binary classification can be used to help doctors diagnose their patients with more precision, which would in turn aid doctors proscribe medicine more effectively.

If I were to continue the project, I would either have the model take into account the background of the images to help with classification or create a website where a user would submit an image and the output would be the classification.
