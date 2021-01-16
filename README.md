<p align="center">

</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	
</p>

<h1> Introduction</h1> 


<h2 id="task"> Module 3 Task Overview </h2>
Display data visually for traders.
Use Perspective to create the chart for the trader’s dashboard.

<b>Aim:</b> Use Perspective to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy. Basically, you have to modify the existing live chart to be able to (1) track and display the ratio between the two stock prices (2) show the historical upper and lower bounds of the stocks' ratio (3) and finally, show 'alerts'  whenever these bounds are crossed by the ratio.


<h2 id="installation" >Setup / Installation</h2>
<p>In order to get the server and client application code working on your machine, </p>



<h2>How to Run</h2>
<p>Similar to Task 2, start the data feed server by running the python server</p>
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code>python datafeed/server3.py</code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

<h2>Known Issues</h2>
Some users seem to be having trouble with the unzipped version of the node_modules back up for windows. 
This is the alternative unzipped version:
https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz

Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.

<h2>How to fix the code to meet the objectives</h2>
<p>To make the changes necessary to complete the objectives of this task, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m3_v2.pdf">follow this guide</a>.</p>

<h2>How to submit your work</h2>
<p>A patch file is what is required from you to submit. To create a patch file, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf">follow this guide</a>. Then submit the patch file in the <a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/EbtbrgmwKbgqcXyGt">JPM Module 3 Page</a>.</p>
