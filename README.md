# Neural-virtual-sensor-for-monitoring-the-fermentation-of-mead-with-jabuticaba-extract.


  Mead is an alcoholic beverage fermented from water and honey, typically produced through the action of yeasts, usually strains of Saccharomyces cerevisae, 
on sugars such as glucose and fructose. Producers often encounter obstacles stemming from limited knowledge and lack of control over key process parameters. 
In light of this, this study aimed to develop an Artificial Neural Network (ANN)-based virtual sensor capable of predicting cell concentration (X), total sugar 
concentration (S), and ethanol concentration (P) during mead fermentation with the addition of jabuticaba peel pulp. To achieve this, the following input variables 
were selected: temperature, pH of the fermenting solution, total soluble solids concentration (°Brix), and optical density (OD). Experimental data from a fermentation 
conducted during Costa's undergraduate research (2020) (FAPESP Project: 19/24444-1) were employed to obtain and simulate the feedforward neural network with supervised
training.

  Neural networks were tested in various configurations, identifying the best training algorithms, activation functions, the number of intermediate layers, and the quantity 
of neurons in each layer to optimize the prediction of output variables by the network. The virtual sensor was successfully employed to monitor and optimize beverage 
production, ensuring high yield, productivity, and product quality. The neural network can be applied to other fermented beverages, mead variations, and process conditions,
provided that the network undergoes retraining.

  Although these ANNs exhibited similar performance (with errors in the range of 10-3 %), the selection of the most suitable network was based on minimizing the number of 
parameters (NP). In this context, the ideal ANN for monitoring mead fermentation was identified as having the architecture 3-15-3, trained with the Levenberg-Marquardt with
Bayesian Regularization algorithm and tansig-purelin activation functions, comprising a total of 108 parameters.



Keywords: Artificial neural networks, mead, alcoholic fermentation, monitoring, virtual sensor, Jabuticaba peel pulp, supervised training, optimization.
