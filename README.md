# Custom ANN model figure for latex
This repository contains the code needed to create a Artificial Neural Network (ANN) model figure for latex using Tikz. It contains different commands to customize it as you want. Those commands are
- \inputnum: number of neurons in the input layer
- \outputnum: number of neurons in the output layer
- \hiddennumarr: number of neurons in the hidden layer. Choose the number of neurons in each layer by providing an array i.e {3,2,5,3,2} (the first hidden layer would have 3 neurons, the second hidden layer 2 neurons, and so on)
- \layernum: number of hidden layers. It has to be the same as the numbers of items in \hiddennumarr.
- \yoffset: separation between neurons in the same layer
- \xoffset: separation between layers
- \showbias: show the bias node in each layer but the output one (0 or 1)
- \countbias: count bias to center the output layer (0 or 1). Only use 1 if \showbias command is 1
- \shownamelayer: show the name of each layer. (WIP: use the language given, right now the default is spanish, but you can change it on the code)

Two example of an output would be something like this
![ANN example 1](https://github.com/MarioBerrios/ANN-model-for-latex/blob/main/ann_example.png)
![ANN example 2](https://github.com/MarioBerrios/ANN-model-for-latex/blob/main/ann_basic-1.png)

### References
[Drawing Neural Networks in TikZ: Short Guide](https://latexdraw.com/drawing-neural-networks-in-tikz-short-guide/)
