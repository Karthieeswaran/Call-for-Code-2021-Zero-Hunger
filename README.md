# Call-for-Code-2021-Zero-Hunger
- [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
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



### The idea

In this we are try to bring the paper ledgers to online and store the data in a cloudant database. Then with this data we can bind the gap between farmers and Co-Ops. After that data will be further analysed to help both farmers and co-ops. With the analysed data a report will be generated with daily price of each crop will be sent to farmers in the SMS. So that farmers can know the current selling value of crops and as an add on feature in the SMS daily wheather report will be sent. We also try to find the solution to reduce the wastage of vegetables and it will be delivered to the one whose in need.



## Built with


- IBM Node Red - This provides a browser-based flow editor that makes it easy to wire together flows using the wide range of nodes in the palette.
- IBM Cloudant - The NoSQL database to store the data.
- Twilio  - The external API to send messages to farmers which will be integrated with in node red using twilio node.
- OpenWheathermap - The external API is used to fetch the wheather report which is integrated in node red using openwheathermap node.
- Node Red UI - The UI will provide an dashboard which is used to display the capacity of the storage space.


## Demo video

[![Watch the video](https://github.com/Call-for-Code/Liquid-Prep/blob/master/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)




## Project 


The project currently does the following things.
1. The farmers with the help of co-ops can register the details of crops in the below UI.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Dail%20Entry.png)



2. Once the farmer is registered the co-ops will send the current value for the crops which they like to sell with co-ops.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Daily_Report.png)



3. Then using the below UI the co-ops can enter the outlet kgs from their storage space.So that the current used storage sapce will be automatically updated in the UI.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Storage_Capacity.png)



4. In need of beneficial to both farmers and customers using below UI the Profit is calculated and these details are stored in the database.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Dashboard/Profit_Dashboard.png)



5. Then an sepaarte UI is created to deliver the vegetables which is going to be waste or someone willing to offer the vegetables to the people whose in need. Beacuse in the farmers end they can't sell the vegetables in the market in some cases. So they became rotten and went to wastage. Inorder to reduce this the unselled vegetables can be shared with whose in need.

![Project](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Website/website.PNG)





## Work flow

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/site.PNG)

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/daily%20entry%20sites.PNG)

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/send%20weather%20via%20sms.PNG)

![Work flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/calculate%20storage%20space.PNG)


## Conclusion

The above API,Workflow,UI was able to integrate successfully solve the above problems. 



## Future Idea
 
 - With help of available data using Machine Learning the selling value of crops can be predicted a day before itself. So that farmer can decide on which day they can sell.
 - The image of an using MMS/SMS crop can be sent directly to the public number. Then the image can be further processed with Machine Learning to predict the better value and then the processed information will be sent to farmer.
 -  Using the stored Profit data the cashback will be given to the farmers with help of bank based on how much they have given profit to the co-ops.
 -  In future the farmer can directly register their details using an common mobile number.






