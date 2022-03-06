# AOS_project.Nagapudi
<br>
<div>
  Used two Machine Learning Algorithms namely Naïve Bayes and Artificial Neural Networks, to classify the data in Data Exfiltration subset extracted from BOT-IoT dataset. The Dataset is created by UNSW and it has open access in IEEE Dataport. Used 80-20 train-test split following Pareto Principle. In terms of accuracy and other machine learning metrics, Naïve Bayes performed better compared to ANN except that Log Loss is more in case of Naïve Bayes.
</div>
<h2>How to Run:</h2>
<p>
  1. Extract the Dataset Data_exfiltration.csv to the parent folder of Source Code(ipynb) file.</br>
  2. Run the code using Jupyter Notebook.</br>
  3. Different scenarios(Program A, Program B, Both Programs) are coded in different cells.</br>
  4. Used threading for running both the programs concurrently.</br>
  5. Removed the metrics like Accuracy, Precision from the table to avoid overloading it.</br>
</p>
<h2>Results:</h2>
<p align="center">
  <img src="https://github.com/Harshitha-Nagapudi/AOS_project.Nagapudi/blob/main/AOS_Project.Nagapudi%20(1).png">
  <img src="https://github.com/Harshitha-Nagapudi/AOS_project.Nagapudi/blob/main/Results.png">
</p>
<h2>Analysis:</h2>
<p>
  1. The run time is more in case of ANN compared to NB, but reduced a bit when ran concurrently with NB.</br>
  2. CPU Usage is more when ran concurrently, indicating that the CPU is busier compared to when running each program alone.</br>
  3. It is obvious that Memory Usage is slighty more when running both programs concurrently than running alone.</br>
  4. Hard Drive Usage is same in all the three cases.</br>
  5. RSS, VMS and Page Faults are more in concurrent running case but when ran individually, they are more in case of ANN compared to NB.</br>
</p>
