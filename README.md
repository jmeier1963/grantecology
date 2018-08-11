# grantecology
This is a demo of an analysis of funding ecology. The  jupyter notebooks in this repository allow to scrape grants 
from websites and then to represent and analyze the grant ecology as a network. 

An explicit description of the project and the motivation behind it can be found in the 
file "Coordination in complex stakeholder ecology v2.pdf".

This note summarizes an approach where graph theory and big data tools are employed for representation and analysis of 
a network of grants. To that end grants, grantees and funders are represented as nodes in a network or graph where 
edges indicate financial flows or similarities of activities.  
With the help of such network representation and analysis concepts like the centrality of a network can be measured 
to identify partitions or segments of the network. Big data tools and natural language processing are used to identify 
similar grants automatically.

The data used in this paper are descriptions of environmental, conservation and climate change grants that were scraped 
from the websites of the Hewlett Foundation, the Packard Foundation, the Oak Foundation, and 
the Children’s Investment Fund Foundation in July 2018. 
The web scraping resulted in a data set of 3113 grants to 948 with a total funding of $2,625 billion.
