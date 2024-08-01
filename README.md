  <h1 align="center">Awesome Event-Driven Architecture</h1>
<p align="center">
    <a href="https://github.com/sindresorhus/awesome" ><img alt="awesome" src="https://awesome.re/badge-flat2.svg?style=flat-square" /></a>
    <a href="https://github.com/mehdihadeli/awesome-software-architecture/blob/main/LICENSE" ><img alt="license" src="https://img.shields.io/badge/License-CC0_1.0-E91E63.svg?style=flat-square" /></a>
</p>

A list of awesome articles and resources to learn about event-driven architecture. 




## 📕 Articles

### Fundamentals

- [Going “Events-First” for Microservices with Event Storming and DDD](https://medium.com/russmiles/going-events-first-for-microservices-with-event-storming-and-ddd-8614437486f0) by Russ Miles, October 2016. _"It is **not the things** that matter in early stages of design - **it is the things that happen**."_

- [Events As First-Class Citizens](https://hackernoon.com/events-as-first-class-citizens-8633e8479493?gi=5ecff3301dfa) by Randy Shoup, January 2018.

- [Why Event-First Programming Changes Everything](https://www.confluent.io/blog/journey-to-event-driven-part-1-why-event-first-thinking-changes-everything/) by Neil Avery, January 2019.

- [Introduction to Event-Driven Architecture](https://medium.com/microservicegeeks/introduction-to-event-driven-architecture-e94ef442d824) by Kacey Bui, February 2021.


### Experience Reports And Practicalities

- [The different types of events in event-driven systems](https://blog.frankdejonge.nl/the-different-types-of-events-in-event-driven-systems/) and [Reliable event dispatching using a transactional outbox](https://blog.frankdejonge.nl/reliable-event-dispatching-using-a-transactional-outbox/) by Frank de Jonge, February 2022

- [5 pitfalls to avoid when implementing an Event-Driven Architecture](https://medium.com/@kris_22373/5-pitfalls-to-avoid-when-implementing-an-event-driven-architecture-7fb04d7fa7ca) by Kris Van Vlaenderen, January 2024



## 📺 Videos

### Fundamentals

- [Core Decisions in Event-Driven Architecture](https://youtu.be/SKXS2h3MdPM?si=LeamTGy93vAy2QYc) by Duana Stanley, October 2019. Overall a great talk, definitely worth watching. Some minor issues:
    - The advice to use ids in events to refer to other entities is not wrong, but needs deeper discussion. 
    - I don't like the term "command events", something is either a command or an event.
    - In the end she hints at Kafka as an event store, I don't think that's good idea. 

- [Event-Driven Architectures Done Right](https://youtu.be/A_mstzRGfIE?si=An0YI1034-PazFc5) by Tim Berglund, May 2021.



### Experience Reports And Practicalities


- [EDA in Practice: Building an eCommerce Platform at Cinch](https://www.youtube.com/watch?v=wM-dTroS0FA&t=493s) by Toli Apostolidis, September 2022. You can ignore the first 8 minutes and 15 seconds (in fact the link will skip them), they are mostly promotion for AWS. But from there on follows a good talk on real-world experiences with event-driven architecture.




## Addendum

Please note that the list is **highly curated**. The aspiration is to assemble resources that excel in providing clarity around the principles and terminology. As a whole, the collection should provide a comprehensive and consistent overview of the topic. In the spirit of the [Awesome Lists Guidelines](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md): _"Awesome lists are curations of the best, not everything."_


Of course if you think something that belongs in the list is missing, you can suggest its inclusion in an [issue](https://github.com/reactivesystems-eu/awesome-event-driven-architecture/issues) or [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).


To be updated about changes, follow me on <a href="https://mastodon.social/@lutzhuehnken" rel="me">Mastodon</a>, <a href="https://bsky.app/profile/lutzh.bsky.social">Bluesky</a> or <a href="https://de.linkedin.com/in/lutzh">LinkedIn</a>. If you find this interesting, you might also like my <a href="https://www.reactivesystems.eu/">blog</a>.


