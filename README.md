<h2>Incident-Root-Cause-Analysis-Deep-Learning-Classifcation</h2>
<h4>Dataset</h4>
A Data Center Team uses a system monitoring tool to track CPU memory application latency for all their servers becuase they wanted to predict causes of uses reported by customer.
<br>
This dataset has variabls such as <b>ID,CPU_LOAD,MEMORY_LEAK_LOAD,DELAY,ERROR_1000,ERROR_1001,ERROR_1002,ERROR_1003 and ROOT_CAUSE</b><br>
Dataset is available for each incident indicating if any load isues or errors was observed during that problem<br>
<br>
<img src="dataset.png">

<h4>Implimentation</h4>

1.Verbose = 1 <br>
2.Batch = 64 <br>
3.Epochs = 20 <br>
4.Hidden_nodes = 128 <br>
5.Validation_split = 0.2 <br>

<br>
<h4>Model Summary</h4>
<img src="Model_Summary.png">
<br>
<br>

<h4>Evaluation against Test Dataset</h4>
<img src="Evaluvation.png">
<br>
<br>
<h4>Predicting Root Causes </h4>
<img src="Predicting_Root_Cause.png">
