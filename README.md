# JGAT
This is the demo code for the paper: JGAT: A Joint Spatio-Temporal Graph Attention Model for Brain Decoding, implemented by the Tensorflow.

General_A.mat file contains the summation of 200 by 200 binary adjacency matrices from 48 subjects. Selecting a threshold between 0 to 48 can control the number of edges and extreact a General adjacency matrix.

Social_dataset.mat is the fMRI time series of Social cognitive stimuli from the same 48 subjects. Each subject has 8 experimental trials: 4 Mental trials and 4 Random trials. The file follows the arrangement:

&emsp;&emsp;Subject 1:&ensp; 4 Mental trials  
&emsp;&emsp;Subject 1:&ensp; 4 Random trials  
&emsp;&emsp;Subject 2:&ensp; 4 Mental trials  
&emsp;&emsp;Subject 2:&ensp; 4 Random trials  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;⦙  
&emsp;&emsp;Subject 48: 4 Mental trials  
&emsp;&emsp;Subject 48: 4 Random trials  


JGAT_model.ipynb is a Python notebook containing the basic architecture of the JGAT model. You can download and run it on the Google Colab or other jupyter environment.
