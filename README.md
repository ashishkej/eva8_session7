# EVA8 Session7 Assignment

## Assignment

- - Follow a code structure to store all models, main.py(training functions), utils.py(misc. funcs) in main repo
  - ResNet18, ResNet34 basic models without Bottleneck layers, Train ResNet18 for 20 Epochs
  - Show 20 Misclassified images
  - Show 20 GradCAM viz for same misclassified images
  - Apply these transforms while training:
      1. RandomCrop(32, padding=4)
      2. CutOut(16x16)
      3. Others

# Submission
[Colab Notebook](https://github.com/ashishkej/eva8_session7/blob/main/EVA8_Session7_Assignment.ipynb)

[Main Repo](https://github.com/ashishkej/eva8-pytorch-models)

- Reached Test Accuracy of ~84% in 20 epochs 
- Got some intuition on pytorch hooks used for debugging and used for GradCAM



## References

* https://jacobgil.github.io/pytorch-gradcam-book/introduction.html
* https://in.coursera.org/projects/deep-learning-with-pytorch-gradcam
* https://medium.com/the-dl/how-to-use-pytorch-hooks-5041d777f904

