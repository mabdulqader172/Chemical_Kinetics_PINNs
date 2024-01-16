# Chemical Kinetics Applications of Physics Informed Neural Networks (PINNs)
The following repository is designed as a demonstration of Physics Informed Neural Networks (PINNs) to chemical kinetics. 
The applications demonstrated are focused mainly on protein folding kinetics, enzyme kinetics, and folding coupled to 
binding kinetic models.

## What Are PINNs?
In laymen terms, neural networks (NNs) are often used as the black box method that determines the function between some
input vector and the desired output value. Neural networks are often trained with an optimizer and a loss function. The
optimizer is an algorithm that searches for necessary parameters of the neural network using the loss function as the
guide to the optimal parameters. This is often done via computing the Mean Squared Error of the NN output to the true 
values of the data.

The *Physics Informed* (PI part) is an extension of the well-designed NN pipeline where the loss function now includes 
a governing function which is designed to "teach" the NN physical laws that must exist between our input and output 
data. The first key demonstrations of this novel framework has been on well characterized ordinary and partial 
differential equations (ODE and PDE respectively). A well demonstrated example is 
[Ben Moseley's blog post](https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/) 
on teaching a NN to predict the position of a dampened harmonic oscillator given some value of time.

## Why This Project?
The work demonstrated on PINNs inspired me to apply this technique to my own work. Where my research is focused on 
determining what properties of protein structure and sequence predict protein folding kinetics. Protein Kinetic models 
are often mathematicized into ODEs and I intend to apply various protein and enzyme kinetics models to PINNs.
