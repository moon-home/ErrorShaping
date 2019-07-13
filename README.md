## Project overview:
<img src="./imgs/overview.png" width="1000">

An example for the meaning of distribution loss:

<img src="./imgs/lossmeaning.png" width="1000">

Benchmark NN structure:

<img src="./imgs/benchmarkNNstructure.png" width="400">

MSE along training for benchmark NN:

<img src="./imgs/MSE.png" width="300">

 ---

## Priliminary Results:
 
<img src="./imgs/losses.png" width="1000">

The change of errors distribution is very subtle after 50 epochs:

<img src="./imgs/res.png" width="1000">

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


Issues:

tf.keras.optimizers.SGD 

=> tf.train.Optimizer 

=> tf.train.Optimizer.compute_gradients 

=> tf.python.eager.backprop.GradientTape().gradient() 

=> tensorflow.python.eager.imperative_grad.imperative_grad() 

=>tensorflow.python.pywrap_tensorflow.TFE_Py_TapeGradient() 

=> There is no "TFE_Py_TapeGradient()" in "pywrap_tensorflow"

=>https://github.com/tensorflow/tensorflow/issues/29064
