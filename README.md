Explainable AI with Grad-CAM (ResNet18)

A quick demo showing how Grad-CAM highlights what parts of an image a ResNet18 model looks at to make predictions.

What is Grad-CAM?

Grad-CAM creates heatmaps from the model's last convolutional layer gradients to explain its decisions.

Demo

Upload an image to see a heatmap overlay showing important regions.

Tech

PyTorch

Pretrained ResNet18

Matplotlib

How it works

Load the model

Hook activations and gradients

Run inference

Backpropagate

Generate heatmap

Why?

Explainability helps build trust and debug models.

Next steps

Try it on your own images or datasets, or build an interactive app to explore explanations.
![Alt text](dog.png)
