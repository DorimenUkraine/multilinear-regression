# multilinear-regression
Build a model to approximate a dependant variable with 2 independant variables.

A random dataset is generated as follow :

<img src="http://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;1&space;&&&space;x_{1,1}&space;&&&space;x_{1,2}&space;\\&space;1&space;&&&space;x_{2,1}&space;&&&space;x_{2,2}&space;\\&space;\dots&space;&&&space;\dots&space;&&&space;\dots&space;\\&space;1&space;&&&space;x_{n,1}&space;&&&space;x_{n,2}&space;\end{pmatrix}" title="\begin{pmatrix} 1 && x_{1,1} && x_{1,2} \\ 1 && x_{2,1} && x_{2,2} \\ \dots && \dots && \dots \\ 1 && x_{n,1} && x_{n,2} \end{pmatrix}" />

And random Y data as well.

The main purpose is to find the best parameters that fits the equation :

<img src="http://latex.codecogs.com/gif.latex?y&space;=&space;\alpha_1&space;&plus;&space;\alpha_2x_1&space;&plus;&space;\alpha_2x_2" title="y = \alpha_1 + \alpha_2x_1 + \alpha_2x_2" />

Here the two independant variables are <img src="http://latex.codecogs.com/gif.latex?x_1,x_2" title="x_1,x_2" />.

The *Mean Square Error* loss function is used and minimzed to find these coefficients and Nadam optimizer is implemented to speed it up.
