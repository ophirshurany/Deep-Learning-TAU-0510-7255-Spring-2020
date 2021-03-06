Files and Structure:
The shared folder contains:
- “Train_LSTM.ipynb” notebook used to train 2 LSTM based models from scratch for 70 epochs.
- “Train_GRU.ipynb” notebook used to train 2 GRU based models from scratch for 70 epochs.
- “TestingRNN.ipynb” notebook used to load pre-trained weights for all 4 models and evaluate the
constructed models on the train, validation, and test data.
Training Notebooks:
The relevant notebooks can be run from scratch to train the 4 different LSTM/GRU models. The code
creates, fits and evaluates the models on the Penn Tree Bank dataset and plots perplexity metrics vs. the
number of trained epochs.
The default settings will run on batches of 20 data points, 25 words sequences and test non-regularized
and “drop-out applied” models.
In addition, the notebook creates and saves Tensor Board logs and model weights for later usage.
Model Testing:
The relevant notebook can be run independently, using the pre-saved weights and history fitting data.
The data was created from the Training Notebooks and saved on publicly shared Dropbox.
The reconstructed models are evaluated versus Penn Tree Bank dataset and perplexity/loss metrics are
reported for each dataset.
In addition the relevant loss/perplexity graphs are plotted to show the training process which created
the reconstructed models.
Important Note:
Both the training and the testing notebooks use the Penn Tree Bank dataset and load the files from
Dropbox hosted folder.
The testing notebooks load pre-trained weights and fitting history from publicly shared Dropbox folder.
This was done for more convenient development process: using multiple accounts to train on multiple
notebooks and to eliminate the need of manual confirmation of GDrive.
If for some reason the process on downloading, unzipping or inflating the files is not convenient – the
same files are saved in the models shared folder.
Links:
Final GRU and LSTM models’ weights can be accessed at:
https://www.dropbox.com/sh/gglqoauqm3yts1g/AAAFNhmeOmdz1gjXAXRWAC62a?dl=0
Or in the models shared folder