# Index Replicator

This notebook compares different type of loss measures - mean square, maximum of squared difference, maximum of absolute difference and end of period squared nav difference i.e. cumulative return difference.

Replicaitng model is a standard CNN.

Set loss function with, for eample, ```lossfn=mse```.

Loss statistics are stored in a log folder. Live progress can be monitored with tensorboard. This requires Julia packages ```TensorBoardLogger``` and ```Logging```.

Install tensorboard with ```pip install tensorboard```.

