
# HyperSpectralImageClassification

## Dataset
 Scene acquired by the ROSIS sensor during a flight campaign over Pavia, nothern Italy.
 The dataset is represented by a $(610, 340, 103)$ array.

# Solutions
Here we've tried two approches:
* First we use a neural network with dense Layer and we achived $98\%$ of accuracy on test data.
* We then tried with CNN wich made us achive  $99.98\%$ of accuracy

> To reduce the use of memory and speed things up, we applied a PCA.
Almost all the variation is along the **ten first PC**.  We then use them to reconstruct the image. We swich to a $(610, 340, 10)$ as shape.

For more detail about the structure of the model, please take a look at the codes.
