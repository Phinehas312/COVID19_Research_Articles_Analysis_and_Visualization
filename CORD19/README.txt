1. DESCRIPTION

This package provides a dashboard with an automated pipeline that summarized CORD-19 (COVID-19) research data set with Visualization of clusters, citation networks, and Question-Answers.
This software consists of two different programs: server program with Python implementation, Front-end program with React.js implementation.

2. Installation

- 1. server program installation
	1.1. (optional) Create and activate a virtual environment
		$ conda create -n cse6242project python=3.8.3
		$ conda activate cse6242project
	1.2. Create runtime environment
		- Windows
			$ cd server
			$ pip install -r windows.txt
		- Linux & Mac
			$ cd server
			$ pip install -r linux.txt
	1.3. Download data
		- download sample_10k_tsne_clustered_bibs.csv from following link:
		- https://drive.google.com/file/d/1BN8ftjA9hpar9Pns2Hd0uXQnAf0XTZpS/view?usp=sharing

- 2. Frontend program
	2.1. Install Node.js
		-  Download and install Node.js here:
			https://nodejs.org/en/
		- Locate into the folder and install packages
			$ cd ui
			$ npm install


3. EXECUTION
	3.1. Run server program
		$ cd server
		$ python api/server
	3.2. Run frontend program
		$ cd ui
		$ npm start
	3.3. Navigate to the webpage
		- Connect to localhost:3000

4. Demo video
- Link: https://youtu.be/BCeaMXjh1WE