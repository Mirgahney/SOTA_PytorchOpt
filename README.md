# SOTA_PytorchOpt
This repository contains a custom optimization library in Pytorch, implementing state  of the art optimization algorithms.  


## Objective 1: 
To experimentally verify how efficient are modern variance reduced stochastic gradient methods are at training deep neural nets.

### Example: 
Test SAG and variants of SVRG. Compare again ADAM (of even the newest version AMSPROP ), RMS_Prop and ADAgrad or other methods mentioned in "Sebastian Ruder. An overview of gradient descent optimization algorithms.  arXiv:1609.04747". 

## Objective 2:
Develop and adapt modern variance reduced stochastic gradient methods so that they can efficiently train deep neural nets. 

### Example:
Develop limited memory versions of SAG or SAGA or even natural gradient descent (will send notes).

