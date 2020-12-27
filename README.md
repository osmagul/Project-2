# Project-2

First of all, we import all needed libraries: from numpy zeros, int8 and log; from pylab random function; regular expression function - re; function for returning number of seconds passed since epoch - time; codec registry and base classes - codecs.

After that, we did some preprocessing by removing stopwords from our dataset and creating two dictionaries with corresponding  ids. Moreover, we count the number of times of words showing up in documents. 

Then, we wrote functions for initializing parameters, for Log-likelihood and e/mstep. Finally, we summarize our solution to the result function and call it.

Code.ipynb - main notebook with implementation inside <br/>
dataset.txt - text input <br/>
stopwords.dic - downloaded from web basic stopwords list <br/>
results: dictionary.dic, docTopicDistribution.txt, topicWordDistribution.txt 
