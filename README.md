## Project overview:
<img src="https://camo.githubusercontent.com/1df62bf05259c7e6ccc0bbc5f9c94fcbde71b3e4/68747470733a2f2f692e696d6775722e636f6d2f45667a547177632e706e67" width="1000">

An example for the meaning of distribution loss:

<img src="https://camo.githubusercontent.com/b3a512e68008240523d2a04a6032cf1cbe5bb012/68747470733a2f2f692e696d6775722e636f6d2f646446726a57432e706e67" width="1000">

Benchmark NN structure:

<img src="https://camo.githubusercontent.com/3b09dcc91d2248c2bee21aa7d83df7fc075b7afc/68747470733a2f2f692e696d6775722e636f6d2f736632463976782e706e67" width="400">

MSE along training for benchmark NN:
MSE.png
<img src="./imgs/MSE.png" width="300">

## Priliminary Results:

 With learning rate = 100, epochs = 50:
 
<img src="https://camo.githubusercontent.com/cc01f3e75965b1f219152a400948d257eca97977/68747470733a2f2f692e696d6775722e636f6d2f7631364f6e6e642e706e67" width="1000">

The change of errors distribution is very subtle after 50 epochs:

<img src="https://camo.githubusercontent.com/ffff0d7a6e77377ade637c7cfefac28fb455b6f8/68747470733a2f2f692e696d6775722e636f6d2f74346d726869322e706e67" width="1000">

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

