# Call-for-Code-2021-Zero-Hunger
- [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [our idea](#our-idea)
    
  - [The Architecture](#the-architecture)
  - [Built with](#built-with)
  - [Demo video](#demo-video)
  - [Project](#Project)
  - [Work flow](#work-flow)
  - [Conclusion](#Conclusion)
  - [Future Idea](#future-idea)
  
  
## Short description

### What's the problem?

Approximately 9 percent of the global population is suffering from hunger. And, much of the world’s food is grown by small-scale, independent farms and distributed through local community cooperatives who sell the surplus produce. The co-ops are a central point for quality control, deliveries, and enabling food commodity markets. However, these co-ops face a myriad of logistical challenges to get the right food to the right places with minimal time and cost.

### How can technology help?

By bringing the paper ledgers of food co-ops online, communities can harness data insights from their environment for better crop resilience and overall yield for sustainable food production systems. More crops mean better access to food for the community.



### Our idea

In digitized and enhanced co-operative solution, we will try to  minimize the wastage of foods including crops and vegetables, recycle of wastage to promote organic farming and will also provide access to digital wallet through sms. This solution will be reachable to remote or village areas where farmers do not have smart system like smartphone, digital camera etc. Farmers just need basic mobile phones. To achieve this idea we will implement voice/text based bots to communicate with farmers for subscription and accessibility to Co-Ops, digital wallet. We will adapt blockchain to track transactions. Kindly note this idea will also be considered as an improvement/enhancement of solution starter kit followed by provided format:

```diff
! Who?- Bots
+ What will they do?-Will interact with farmers through voice call/sms
- To achieve this measurable outcome (wow!): In order to ensure higher food security
```
### The Architecture

![image](https://user-images.githubusercontent.com/88243059/127747294-37f36563-adfc-46c5-b8a0-067c4695df44.png)


1. The farmers will interact with digitized Co-ops system through text/caller bots.
2. The SMS/Call will be done through Twilio or Telestra(Australia users).
3. Programmable Messaging service will forward the message to  Node-RED app i.e hosted on IBM Cloud.
4. This Node-RED app interacts with the IBM Cloud Pak for Data AI/ML service to get the response.
5. IBM Cloud Pak service will do the necessary computations and returns the response.
6. The Node-RED app processes the response, converts it to a user-readable format, and forwards it to the digital co-operative management system app UI and also to farmers through SMS/voice through Programmable Messaging service.CoOp admin will be able to view the response via the digital co-operative management system app UI.
7. CoOp admin can also manually enter data in the system app ui as per the need ans Node-RED app helps to deliver this entries to farmers.
8. CoOps will also communicate with local agencies/Volunteers for getting the surplus delivered at right place on right time.
9. CoOp admin will enter data for profit made on selling surplus in local markets and this will be stored in different U/I which can help Govt/Bank Authorities to process cashbak in farmer's wallet.This separte U/I will interact with Node-RED app to get the response from Cloud Pak for data AI/ML service for further analysis.

## Built with


- IBM Node Red - This provides a browser-based flow editor that makes it easy to wire together flows using the wide range of nodes in the palette.
- IBM Cloudant - The NoSQL database to store the data.
- Twilio  - The external API to send messages to farmers which will be integrated with in node red using twilio node.
- OpenWheathermap - The external API is used to fetch the wheather report which is integrated in node red using openwheathermap node.
- Node Red UI - The UI will provide an dashboard which is used to display the capacity of the storage space.


## Demo video

[![Watch the video](https://github.com/Karthieeswaran/Call-for-Code-2021-Zero-Hunger/blob/main/Images/youtube.PNG)](https://www.youtube.com/watch?v=8621HT7mjpY)




## Project 


Currently,this project does the following things:
1. Subscription for farmers to get daily updates on market prices of crops/vegetables.
2. The Co-ops can register the details of crops in the below UI.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Dail%20Entry.png)



2. Once the farmer gets registered, the co-ops will send the current value for the crops which they like to sell in local market.(This will be automated in future #Phonebots)

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Daily_Report.png)



3. Then using the below UI the co-ops can enter the outlet kgs from their storage space.So that the current used storage sapce will be automatically updated in the UI.This information will be used for storing surpluses incase any challanges observed in transportation or consumser availability.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Storage_Capacity.png)



4. If selling of surplus amount will be successful then  below UI will be used to calculate profit margins for independent farmers.This information will be handy to investors like Govt/Bank authorities. They will add cashback to farmer's wallet so that they can use this profit amount for their own need.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Profit_Dashboard.png)



5. This sepaarte UI has been created to deliver the extra surplus amount which was failed to sell in the market due to certain reason. Coops will help to share with other locality farmers or food processing industries.Incase Coops fail to sell then the surplus will be used for organic farming to make compost or animal food.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Website/website.PNG)





## Work flow

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/site.PNG)

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/daily%20entry%20sites.PNG)

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/send%20weather%20via%20sms.PNG)

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/calculate%20storage%20space.PNG)


## Conclusion

The above API,Workflow,UI was able to integrate successfully solve the above problems. 



## Future Idea
 
 -  Using Machine Learning the weather data, selling proce of crops/vegetables can be predicted earlier.It will help farmers to make better plans.
 -  Using the stored Profit data the cashback will be given to the farmer's digital wallet from Govt/Bank authorities.
 -  The whole solution will be integrated with distributed ledger like blockchain to secure the transactions.






