# Nexpose_Tagging
Automatically tag assets by importing a file using API's - Python 

Description:
Apart from the many features offered by Nexpose/InsightVM, havent you at some point tried to perform a function that seems to take impossible amount of manual work? One of such problems is tagging your assets based on the owner. There might be thousands of assets with a different owner for every few assets. This small program aims at resolving this problem by using the freely available API offered by Rapid7.

Prerequisite:
1. Active Nexpose/InsightVM console
2. Nexpose security console information such as IP address and login credentials
3. Text file with IP address and tag names (this particular one deals with 1 ip for each tag, if you have more than 1 IP per tag, i have another code for you on my other repository)
4. Python 3+
5. Postman (optional - will help with testing the API)

Installation:
Download this code and run in python after changing the required information. 
I have also added a sample text file with IP addresses and tag names in the required format.

I have used the API docuemntation from Rapid7 to build it and check for search criteria etc. If you want to change these, please refer to: https://help.rapid7.com/insightvm/en-us/api/index.html

I am open to all comments, changes, feedback or reccomendations, please do let me know if you have any ideas or additional use cases you would like some answers to. 
