# A/B Test Analysis
Created: October 7, 2018<br>
Latest Update: October 7, 2018<br>
By: Can Bekleyici - bekleydata.com<br>

## Summary
For this project, I analyzed the results of an A/B test run by an e-commerce website in order to generate higher conversions. I approached this task by performing a hypothesis test in addition to a logistic regression model using the Python libraries Pandas, NumPy and StatsModels.

## Key Findings
By using a bootstrapping technique to simulate 10.000 random samples of the difference of each website's conversion rate and by calculating the percentage of samples that are below the observed difference in conversion rates, a p-value of of 0.89 could be observed. This p-value is above the previously set threshold of 5%, and suggests not to reject the null hypothesis, which in this case is the old webpage. An additional logistic regression goes even further by suggesting that users on the old page are about 1.015 more likely to convert on average than users on the new page.

## Prerequisite
### Files that are included:
<ul><li><code>ab_test_analysis.html</code> - the complete data analysis report</li>
  <li><code>ab_test_analysis.ipynb</code> - a JSON file, formatted for the usage in Jupyter Notebook</li>
  <li><code>environment.yaml</code> - the environment containing the packages and their versions to be used with Anaconda</li>
  <li><code>requirements.txt</code> - all packages and their versions listed in a txt-file</li>
  <li><code>ab_data.csv</code> - the original dataset file</li>
  <li><code>countries.csv</code> - an additional dataset file</li></ul>

### Installation:
In order to run the project on <code>Anaconda</code>, you will need to download the files <code>ab_test_analysis.ipynb</code>, <code>environment.yaml</code>, <code>ab_data.csv</code>, and <code>countries.csv</code> and save them in the same directory. Next, you will have to navigate the <code>Anaconda Prompt</code> to the directory of the files. Create the environment using <code>conda env create -f environment.yaml</code> and activate it with <code>activate py3</code>. Now you can open the notebook by typing in <code>Jupyter Notebook</code> and run the IPYNB file from there.

### Without Installation:
You can also just view the complete analysis by using the GitHub built-in notebook viewer on <code>ab_test_analysis.ipynb</code> without any prerequisitions.
