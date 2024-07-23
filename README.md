  <h1 align="center">Awesome Event-Driven Architecture</h1>
<p align="center">
    <a href="https://github.com/sindresorhus/awesome" ><img alt="awesome" src="https://awesome.re/badge-flat2.svg?style=flat-square" /></a>
    <a href="https://github.com/mehdihadeli/awesome-software-architecture/blob/main/LICENSE" ><img alt="license" src="https://img.shields.io/badge/License-CC0_1.0-E91E63.svg?style=flat-square" /></a>
</p>

A list of awesome articles and resources to learn about event-driven architecture. Please note that the list is **highly curated**. The aspiration is to assemble those resources that the curator fully endorses and recommends, not as many as possible. In the spirit of the [Awesome Lists Guidelines](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md): _"Awesome lists are curations of the best, not everything."_


Of course if you think something awesome is missing from the list, you can suggest its inclusion by creating a PR.


## 📕 Articles

- [Going “Events-First” for Microservices with Event Storming and DDD](https://medium.com/russmiles/going-events-first-for-microservices-with-event-storming-and-ddd-8614437486f0) by Russ Miles - _"It is **not the things** that matter in early stages of design - **it is the things that happen**."_


## 📺 Videos

### Fundamentals

- [Core Decisions in Event-Driven Architecture](https://youtu.be/SKXS2h3MdPM?si=LeamTGy93vAy2QYc) by Duana Stanley, October 2019. Overall a great talk, definitely worth watching. Some minor issues:
    - The advice to use ids in events to refer to other entities is not wrong, but needs deeper discussion. 
    - I don't like the term "command events", something is either a command or an event.
    - In the end she hints at Kafka as an event store, I don't think that's good idea. 
- [Event-Driven Architectures Done Right](https://youtu.be/A_mstzRGfIE?si=An0YI1034-PazFc5) by Tim Berglund, May 2021.



### Experience Reports


- [EDA in Practice: Building an eCommerce Platform at Cinch](https://www.youtube.com/watch?v=wM-dTroS0FA&t=493s) by Toli Apostolidis, September 2022. You can ignore the first 8 minutes and 15 seconds (in fact the link will skip them), they are mostly promotion for AWS. But from there on follows a good talk on real-world experiences with event-driven architecture.



