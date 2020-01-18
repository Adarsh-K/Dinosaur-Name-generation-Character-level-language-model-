# I've implemented a Dinosaur Name generator using Character level language model. The code is in Python.
Note: All the files are well documented and commented wherever I felt necessary

Run the file named Dinosaur Name generation-Character level language model.ipynb which does the following:
1. Loads the dataset dinos.txt
2. Makes 2 Dictionaries-
  char -> index
  index -> char
3. Implements Gradient Clipping to prevent Exploding Gradients problem
4. Sampler- sample a sequence of characters according to a sequence of probability distributions of the output of the RNN
5. Executes one step of the optimization to train the model-
  Forward Propogate -> Back Propogate -> Clip Gradients -> Update Parameters
6. Now I train the model and generates dinosaur names
