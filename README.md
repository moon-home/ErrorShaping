## Project overview:
<img src="./imgs/overview.png" width="1000">

An example for the meaning of distribution loss:

<img src="./imgs/lossmeaning.png" width="1000">

Benchmark NN structure:

<img src="./imgs/benchmarkNNstructure.png" width="400">

MSE along training for benchmark NN:

<img src="./imgs/MSE.png" width="300">

## Priliminary Results:

 With learning rate = 100, epochs = 50:
 
<img src="./imgs/loss.png" width="1000">

The change of errors distribution is very subtle after 50 epochs:

<img src="./imgs/errorsdistribution.png" width="1000">

When learning rate(1000) is too large, the model diverges:

<img src="./imgs/diverge.png" width="1000">


PS: learning rate here did not include the adaptive part for each weight, an example of actual weight change with learning rate = 1000:

<img src="./imgs/realdelta.png" width="300">

An example of weights trained with distribution loss:

before

<img src="./imgs/weightsbefore.png" width="400">

after

<img src="./imgs/weightafter.png" width="400">


*This is a 2019 summer intern project under Dr.Hong Wang in NTRC.*

