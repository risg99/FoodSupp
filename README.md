# FoodSupp
Food Supply Chain Using Blockchain

# Implementation
The system tracks a particular product right from its raw material ( eg: Tomato ) from farm to the processed product (eg : Tomato sauce) in the retailer store up for sale.
The system includes the following functionalities:
1. An end to end marketplace for all the stakeholders, especially for farmers to sell their produce at a better rate.
2. The quality reports of a lot (part of harvest) are stored in a blockchain network. The processors can use these reports as a metric to evaluate the quality of raw materials.
3. The processor (after receiving raw materials) and retailer (after receiving processed products) adds the respective reports(along with timestamp) to a blockchain network.
4. The customer can analyse all the reports from retailer to farmer (quality reports -> processor report -> retailer report) before buying a product.
5. The system is entirely transparent. Any forgery or other fraudulent activities (hoarding) can be traced as the timestamp is noted at every step.


# Ppt link 
https://docs.google.com/presentation/d/12nV76cK7YiDq3pBJMG4s6rc43g09HuKsHTnrOwjBuYE/edit?usp=sharing

# Demo link
https://drive.google.com/open?id=1Qcu7o6hqE7lXYvSeIBtloQWHxpkNFMmB

# Dependencies:
* Ganache(install from "https://www.trufflesuite.com/ganache")
* Remix Console (https://remix.ethereum.org/)
* Django Framework (pip3 install django)

# Steps To Test
For testing:
1. Deploy Contracts on Ganache
* Connect Ganache to Remix IDE.
* Deploy the contract() in the Contracts folder after compiling.
* Copy the contract addresses and assign them to contract variables in user/views.py. (Line 31).
2. Change Path of SVG files (Present in "user/views.py" at line number --) to Systems directory(Ex: "C://Your path/FoodSupp/user/static/Images/QRfiles/").
3. Run server a. Run the "python manage.py runserver" command after changing the root directory as "FoodSupp".
