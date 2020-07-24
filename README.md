# ranked_accuracy

```
Rank-1 accuracy is the number of times our ground-truth label equals 
our class label with the largest probability. Rank-5 accuracy extends 
on rank-1 accuracy, allowing it to be a bit more “lenient” – here we 
compute rank-5 accuracy as the number of times our ground-truth label 
appears in the top-5 predicted class labels with the largest probability

We typically report rank-5 accuracy on large, challenging datasets such as 
ImageNet where it is often hard for even humans to correctly label the image. 
In this case, we’ll consider a prediction for our model to be “correct” if 
the ground-truth label simply exists in its top-5 predictions.
```
