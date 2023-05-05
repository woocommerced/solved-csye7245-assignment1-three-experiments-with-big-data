Download Link: https://assignmentchef.com/product/solved-csye7245-assignment1-three-experiments-with-big-data
<br>
In this assignment, you will develop a data pipeline to ingest, process, store it so you can access it through different means.

<strong>Preparation: </strong>

<ul>

 <li>Review the tutorials we discussed in class on Snowflake, Apache Beam, Dataflow, Accessing Amazon S3 buckets, Sevir etc.</li>

 <li>Review:</li>

</ul>

<a href="https://nbviewer.jupyter.org/github/MIT-AI-Accelerator/eie-sevir/blob/master/examples/SEVIR_Tutorial.ipynb">https://nbviewer.jupyter.org/github/MIT-AI-Accelerator/eie-sevir/blob/master/examples/SE </a><a href="https://nbviewer.jupyter.org/github/MIT-AI-Accelerator/eie-sevir/blob/master/examples/SEVIR_Tutorial.ipynb">VIR_Tutorial.ipynb</a>

<ul>

 <li><a href="https://www.ncdc.noaa.gov/stormevents/ftp.jsp">https://www.ncdc.noaa.gov/stormevents/ftp.jsp</a></li>

</ul>

<strong>Case: </strong>

<strong>You are a freshly minted data scientist engineer at WeSpace Inc. which leverages space and weather data to build forecasting systems! It is exciting and you just bought your first Tesla to celebrate. Post Covid, you drive to your office and your manager is kind enough to offer the corner office with the view of the ocean on one side and mountains on the other. She checks in to make sure you don’t miss the freshly baked cookies that are at the kitchen. During group lunch, the team is engrossed in a fresh challenge. They plan to build a nowcasting system leveraging satellite data and weather datasets but everyone in the team wants to build models!  </strong>

<strong>Where is the data ? You ask. Everybody stares at you and pretend it isn’t a problem and continues the conversation about Deep Learning and other problems. Your manager </strong>

<strong>interjects and asks your question to the group again. “That is an important question! Where is the data?”. </strong>

<strong>Some team members say it is all on AWS and in csv files and ​</strong><strong>HDF5 format.  </strong>

<strong>“How do we plan to access it?” You ask! </strong>

<strong>“Well, we will get there when we get there!”, a team member says! </strong>

<strong>Your manager in your 1:1, commends you for asking the hard questions and gives you your first assignment! First, we need to try out how to access the data. She suggests 3 architectures and asks you to experiment and provide your recommendations.  </strong>

<strong>———– </strong>

<strong>Here is the dataset catalog: </strong>

<a href="https://github.com/MIT-AI-Accelerator/eie-sevir/blob/master/CATALOG.csv"><strong>https://github.com/MIT-AI-Accelerator/eie-sevir/blob/master/CATALOG.csv</strong></a>

<ul>

 <li><a href="https://nbviewer.jupyter.org/github/MIT-AI-Accelerator/eie-sevir/blob/master/examples/SEVIR_Tutorial.ipynb">https://nbviewer.jupyter.org/github/MIT-AI-Accelerator/eie-sevir/blob/master/examples/SE </a><a href="https://nbviewer.jupyter.org/github/MIT-AI-Accelerator/eie-sevir/blob/master/examples/SEVIR_Tutorial.ipynb">ipynb</a></li>

 <li><a href="https://www.ncdc.noaa.gov/stormevents/ftp.jsp">https://www.ncdc.noaa.gov/stormevents/ftp.jsp</a></li>

 <li><a href="https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/Storm-Data-Export-Format.pdf">https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/Storm-Data-Export-Form </a><a href="https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/Storm-Data-Export-Format.pdf">pdf</a></li>

</ul>

Gives you information on the datasets we need for the project.

<strong>Experiments needed: </strong>

<h2>1. AWS S3</h2>

<ul>

 <li><strong>Leave the data here where it is: ​</strong><a href="https://registry.opendata.aws/sevir/"><strong>https://registry.opendata.aws/sevir/</strong></a></li>

 <li><strong>Upload a sample of data to Amazon S3 </strong></li>

 <li><strong>Experiment with Amazon Glue and build a pipeline. </strong></li>

 <li><strong>Show how to use Amazon Quicksight to query and sample datasets </strong></li>

</ul>

<strong> </strong>

<h2>2. Google</h2>

<ul>

 <li><strong>Download sample datasets and move it to Google storage buckets </strong></li>

 <li><strong>Experiment with Google Dataflow and build a pipeline </strong></li>

 <li><strong>Show how Google Bigquery and Data studio to query and sample datasets. (​</strong><a href="https://cloud.google.com/bigquery/docs/visualize-data-studio"><strong>https://cloud.google.com/bigquery/docs/visualize-data-studio</strong></a><strong>​) </strong></li>

 <li></li>

</ul>

<h2>3. Snowflake</h2>

<ul>

 <li><strong>Download sample datasets and move it to Snowflake </strong></li>

 <li><strong>Use Sql-alchemy and Apache Superset to query and sample datasets.https://superset.apache.org/docs/databases/snowflake </strong></li>

</ul>

<strong>Questions to answer: </strong>

<ol>

 <li><strong>How can you combine satellite data + storm data? </strong></li>

 <li><strong>Which architecture would you recommend for machine learning purposes? </strong></li>

 <li><strong>What are the challenges working with different architectures? </strong></li>

 <li><strong>Do a cost/benefit analysis for each architecture </strong></li>

</ol>