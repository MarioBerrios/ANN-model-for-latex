# Custom ANN model figure for latex
This repository contains the code needed to create a Artificial Neural Network (ANN) model figure for latex using Tikz. It contains different commands to customize it as you want. Those commands are
- \inputnum: number of neurons in the input layer
- \hiddennum: number of neurons in the hidden layer. Every hidden layer would have the same number of neurons (WIP: choose the number of neurons in each layer by providing the architecture i.e {3:2:5:3:2})
- \outputnum: number of neurons in the output layer
- \layernum: number of hidden layers (WIP: choose the number of layers by providing the architecture i.e {3:2:5:3:2})
- \yoffset: separation between neurons in the same layer
- \xoffset: separation between layers
- \showbias: show the bias node in each layer but the output one (0 or 1)
- \countbias: count bias to center the output layer (0 or 1). Only use 1 if \showbias command is 1
- \shownamelayer: show the name of each layer. (WIP: use the language given, right now the default is spanish, but you can change it on the code)

An examplo of an output would be something like this