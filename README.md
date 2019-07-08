## Project overview:
<img src="http://i64.tinypic.com/19uyh2.png" width="1000">

An example for the meaning of distribution loss:

<img src="https://i.imgur.com/ddFrjWC.png" width="1000">

Benchmark NN structure:

<img src="https://i.imgur.com/sf2F9vx.png" width="400">

MSE along training for benchmark NN:

<img src="https://i.imgur.com/m3WfLtf.png" width="400">

## Priliminary Results:

 With learning rate = 100, epochs = 50:
 
<img src="https://i.imgur.com/v16Onnd.png" width="1000">

The change of errors distribution is very subtle after 50 epochs:

<img src="https://i.imgur.com/t4mrhi2.png" width="1000">

When learning rate(1000) is too large, the model diverges:

<img src="https://i.imgur.com/SQMJp20.png" width="1000">


PS: learning rate here did not include the adaptive part for each weight, an example of actual weight change with learning rate = 1000:

<img src="https://i.imgur.com/3bn9GQJ.png" width="200">

An example of weights trained with distribution loss:

before

<img src="https://i.imgur.com/2UyMEdW.png" width="200">

after

<img src="https://i.imgur.com/wAZylkC.png" width="200">


*This is a 2019 summer intern project under Dr.Hong Wang in NTRC.*

