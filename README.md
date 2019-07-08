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

<img src="https://camo.githubusercontent.com/64ac3bd428d0eeb7a529ed1b66d1863e17d26fec/68747470733a2f2f692e696d6775722e636f6d2f53514d4a7032302e706e67" width="1000">


PS: learning rate here did not include the adaptive part for each weight, an example of actual weight change with learning rate = 1000:

<img src="https://camo.githubusercontent.com/535d3c5a5683a0ca8b44488e9c44630d4b28fbb6/68747470733a2f2f692e696d6775722e636f6d2f33626e3947514a2e706e67" width="300">

An example of weights trained with distribution loss:

before

<img src="https://camo.githubusercontent.com/bef918aca3da1f8d801b2beef4d70ee8f614f5e5/68747470733a2f2f692e696d6775722e636f6d2f3255794d4564572e706e67" width="400">

after

<img src="https://camo.githubusercontent.com/cb34420233f5376be9dfc5243e233f9b2e63dce4/68747470733a2f2f692e696d6775722e636f6d2f77415a796c6b432e706e67" width="400">


*This is a 2019 summer intern project under Dr.Hong Wang in NTRC.*

