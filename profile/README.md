## Welcome to Ballroom 👋

<h1 align="center">
  <center><img height="512" width="999" src="./profile/logo-black.png" alt="Ballroom Logo"/></center>
</h1>

"Ballroom" – a cutting-edge project evaluation platform that sets a new standard for talent assessment. 

With Ballroom, we sought to create a stage where developers can showcase their skills in building applications that communicate and interact efficiently. From crafting RESTful APIs to handling real-time data exchange with Websockets and managing database connections, our platform provides an arena for participants to dance through a symphony of integration challenges.

Ballroom provides the following core functionalities,
* Comprehensive Integration Projects: Ballroom offers participants the opportunity to engage in complete integration projects, which go beyond simple coding challenges.
* Project Templates and Evaluation Tests: Contest creators can upload project templates along with evaluation tests. This streamlines the submission process for participants and ensures fair assessment through automated evaluation tests.
* Instant Feedback and Continuous Improvement: Upon project submission, participants receive instant scores displayed on the real-time leaderboard.
* Flexible Challenge Types: The ballroom accommodates a variety of challenge types, catering to different industries and skill sets. Whether it's educational assignments, technical interviews, or hackathons, the platform provides a versatile solution.

## Architecture

<h1 align="left">
  <center><img height="512" width="740" src="./profile/ballroom_architecture_diagram.png" alt="Ballroom Architecture Diagram"/></center>
</h1>

"Ballroom" embodies a sophisticated technical architecture designed to foster innovation, scalability, and security. The platform's backend is meticulously modularized into seven autonomous services, empowering enhanced maintainability and scalability.
* Modular Microservices - The platform's backend architecture is structured around seven distinct and independent microservices. This modular approach ensures that each service can be developed, updated, and scaled independently, facilitating streamlined maintenance and future enhancements.
* Containerization with Docker - All seven services are encapsulated within Docker containers. Docker's containerization technology enables consistent and isolated deployment environments
* Robust Security with WAF - Every service is fortified with a Web Application Firewall (WAF) at the front end. This strategic security measure shields the platform against potential application layer attacks
* Data Persistence and Scalability - Data persistence is achieved through an SQL database, offering reliable storage. Furthermore, the architecture employs a message broker to seamlessly transmit submissions to the executor service. This design allows the system to efficiently handle varying submission loads, ensuring optimal performance.
* User Identity Management - Ballroom embraces user identity management through an external CIAM (Customer Identity and Access Management) provider. This integration streamlines authentication and authorization processes, enhancing user experience and security.


## Get started

You can use the resources below to deploy and run the Ballroom platform.

* [Build and deploy the Ballroom backend services](https://github.com/Ballroom-Platform/ballroom-backend/blob/m2/README.md)
* [Build and run the Ballroom frontend webapp](https://github.com/Ballroom-Platform/ballroom-frontend/blob/m2/README.md)

## Contribute to Ballroom

"Ballroom" is an open-source evaluation platform. The ballroom welcomes contributions from the community.

## License

Ballroom code is distributed under the [Apache license 2.0].


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
