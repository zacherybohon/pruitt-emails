# Pruitt-Emails

Emails released by [CMD about Scott Pruitt](http://www.exposedbycmd.org/Scott-Pruitt-Missing-Emails )

### Questions to Answer:

* Who - who are the people sending these messages? Who is receiving them? Who do they work for?
    * Who are the most common senders or receivers?
    * Social network analysis. Look for measures of centrality.
* What - what words/topics are more common when sent from the AG's office to each recipient? 
* Do the same sender/recipient analysis, but by sending receiving organization. 

### Steps

**1. Data Cleanup**

* Parse the emails into a data frame, with fields for the From, To, Date, Subject, and Message text. Include bate stamps for reference. 
    * This is in [Email Splits](Email%20Splits.ipynb)
* (Nice to have) - an ID / identifier in each email with a link to an HTML page for the original email with its formatting

**2. Analysis and Presentation**

* Start answering the questions above
* Visualize relationships, timelines, and topics. 


### Getting Started

1. Install [Anaconda](https://www.continuum.io/downloads)
2. Open a command line (the Anaconda Command Prompt on Windows, a terminal on OS X or Linux)
3. Navigate to the repo
4. Type 'jupyter notebook' to get started. You can do all the development from a web browser. 


### Misc

* The gold standard for an email dataset is the [Enron corpus](https://www.cs.cmu.edu/~./enron/), but that's the product of years of work. 