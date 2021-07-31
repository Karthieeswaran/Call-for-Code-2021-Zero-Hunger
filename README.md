# Call-for-Code-2021-Zero-Hunger
- [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [Built with](#built-with)
  - [Demo video](#demo-video)
  - [Long description](#long-description)
  
  - [Authors](#authors)
  - [License](#license)
## Short description

### What's the problem?

Approximately 9 percent of the global population is suffering from hunger. And, much of the world’s food is grown by small-scale, independent farms and distributed through local community cooperatives who sell the surplus produce. The co-ops are a central point for quality control, deliveries, and enabling food commodity markets. However, these co-ops face a myriad of logistical challenges to get the right food to the right places with minimal time and cost.

### How can technology help?

By bringing the paper ledgers of food co-ops online, communities can harness data insights from their environment for better crop resilience and overall yield for sustainable food production systems. More crops mean better access to food for the community.

### The idea

In this we are try to bring the paper ledgers to online and stored everything in a cloudant database.Then with this data we can reduce the gap between farmers and Co-Ops.
A farmer can reach out the co-ops using an public co-ops website with the details of crops.After the request was submitted co-ops can use these data and sms will be sent to farmer with the details of weather, 


## Built with

- IBM Node Red - This provides a browser-based flow editor that makes it easy to wire together flows using the wide range of nodes in the palette.
- IBM Cloudant - The NoSQL database to store the data.
- Twilio  - The external API to send messages to farmers which will be integrated with in node red using twilio node.
- OpenWheathermap - The external API is used to fetch the wheather report which is integrated in node red using openwheathermap node.
- Node Red UI - The UI will provide an dashboard which is used to display the capacity of the storage space.


## Demo video

[![Watch the video](https://github.com/Call-for-Code/Liquid-Prep/blob/master/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)




[![Work Flow](https://github.com/karthi19-DS/Call-for-Code-2021-Zero-Hunger/blob/main/Images/calculate%20storage%20space.PNG)]
## Project roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.

See below for our proposed schedule on next steps after Call for Code 2021 submission.

![Roadmap](./images/roadmap.jpg)

## Getting started

In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

- [sample-react-app](./sample-react-app/)
- [sample-angular-app](./sample-angular-app/)
- [Explore other projects](https://github.com/upkarlidder/ibmhacks)

## Live demo

You can find a running system to test at [callforcode.mybluemix.net](http://callforcode.mybluemix.net/).

## Built with

- [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
- [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - The web framework used
- [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
- [Maven](https://maven.apache.org/) - Dependency management
- [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
