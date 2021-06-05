# Something-Awesome
This repository is created towards the Security Project

# Project Name:
A network intrusion detection system leveraging Statistical Machine Learning.

# Why ?
As the bad actors become more sophisticated with the attack models or threats being employed, we have to use the existing data and draw more efficient conclusions and moreover
learn from that to develop efficient systems.

# Description:
Our digital plane is hyper-connected which results in a plethora of network activity, going beyond the scope that anyone could have imagined when ARPANET was formed.
Now in order to protect aginst the bad actors the traditional setups involve using a network firewall and then a complex analysis of network ports/ priveleged access.

But, often even then there are situations where in a network breach happens sometimes over these so called secured ports, other times it is an internal threat.

This project aims to demonstrate the ability of machine learning approaches by detecting the threats over analyzation of network packets.

Now this approach itself, poses yet another challenge which is : 
* The communication over the internet is secured via HTTPS.
* So if we can't access the packet data, how to check for the bad actors.

UNSW Prof. Noor Mustapha in his paper -> https://www.tandfonline.com/doi/full/10.1080/19393555.2015.1125974
Shares the idea where in the analyis is done via doing an analysis of the packet size and then about a possiblity of checking whether intrusion if found or not ?

# Dataset
The dataset being used is UNSW NB15 and the credit goes to Prof Mustapha, https://www.tandfonline.com/doi/full/10.1080/19393555.2015.1125974

# Description of the Dataset
The dataset is good for supervised learning models and involves examples of a huge sets of types of attacks that the bad actors have leveraged.

# Models being implemented on the dataset
* Descision Tree
* Logistic Regression
* Random Forest Classifier
* MLP Classifier
* Gaussian Naive Bayes
* Gradient Boosting Classifier

# Conclusion
This demonstration sucessfully demonstrates that machine learning can be used using the packet size analysis for prediction of the network intrusion detection.

