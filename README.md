# Index Replicator

This notebook compares different type of loss measures - mean square, maximum of squared difference, maximum of absolute difference and cumulative mean quared return difference.

Replicaitng model is a standard CNN.

Set loss function with, for eample, ```lossfn=mse```.

Loss statistics are stored in a log folder. Live progress can be monitored with tensorboard. This requires Julia packages ```TensorBoardLogger``` and ```Logging```.

Install tensorboard with ```pip install tensorboard```.

Run the notebook. Open a terminal, cd into the folder of the notebook and execute ```tensorboard -logdir log/``` and follow the instructions. Copy the server address into a browser and refresh the page to monitor the training progress.