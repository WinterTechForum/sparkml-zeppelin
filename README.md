Spark ML Zeppelin
=================

1. Install Python 2.7.x (The one that comes with MacOS/Linux is probably fine).

2. Install and initialize nltk:

  1. Install library using pip: `pip install nltk`

  2. Download nltk data

           import nltk
           nltk.download()

       (Details: http://www.nltk.org/data.html)

3. Download and install Zeppelin 0.7.0:

  1. Download from https://zeppelin.apache.org/download.html

  2. Unzip the downloaded file.

  3. Run: `(zeppelin home)/bin/zeppelin-daemon.sh start`

4. Clone this project.

5. Configure Zeppelin to use this project's `notebook` directory:

  1. Open the notebook repos page: http://localhost:8080/#/notebookRepos

  2. Change the "Notebook Path" to `.../sparkml-zeppelin/notebook`

6. Load the Zeppelin note: http://localhost:8080/#/notebook/2CBEJDES5 
