
# Enron Email Network Analysis

The dataset can be found at : https://www.kaggle.com/datasets/wcukierski/enron-email-dataset

## Requirements

Python 3 and Gephi (https://gephi.org/)

## Conclusion

To summarize my findings, I discovered clusters that could be used to identify departments within the organization. Using text-based analysis methods on the email text, I was able to identify targeted personnel.

Using my explanatory analysis, I identified key members in our network. This gave me a starting point for my investigation. I used this information to do some research, which gave me a general understanding of the company.

I identified node-based clusters in our network by setting the modularity to 2. I also used betweenness centrality to identify prominent members in these networks. It’s worth noting that these members corresponded to the members I identified in our explanatory analysis.

I investigated email traffic in our subnetwork. I used a variety of graph-based analytics to determine which employees sent and received the most emails. Using centrality metrics, I also identified employees with the highest betweenness and closeness.

In the final part of our analysis I conducted a text based analysis where I used certain keywords to filter the email text and recognise the employees associated with that email. I could successfully identify employees directed related to the high attrition rate in the organization. I could also single out employees who overlooked financial matters of the company and were aware about the debts and losses the company was suffering from.
