<!-- omit in toc -->
# Awesome Event-Driven Architecture [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome articles and resources to learn about event-driven architecture. 

<!-- omit in toc -->
## Contents
  
- [📕 Articles](#-articles)
  - [Foundational](#foundational)
  - [Experience Reports And Practicalities](#experience-reports-and-practicalities)
- [📺 Videos](#-videos)
  - [Foundational](#foundational-1)
  - [Experience Reports And Practicalities](#experience-reports-and-practicalities-1)
  
## 📕 Articles

### Foundational

- [Going “Events-First” for Microservices with Event Storming and DDD](https://medium.com/russmiles/going-events-first-for-microservices-with-event-storming-and-ddd-8614437486f0) - By Russ Miles, October 2016. _"It is **not the things** that matter in early stages of design - **it is the things that happen**."_

- [Events As First-Class Citizens](https://hackernoon.com/events-as-first-class-citizens-8633e8479493?gi=5ecff3301dfa) - By Randy Shoup, January 2018. Focusses on the most important part of EDA: The actual events.

- [Why Event-First Programming Changes Everything](https://www.confluent.io/blog/journey-to-event-driven-part-1-why-event-first-thinking-changes-everything/) - By Neil Avery, January 2019. Somewhat lengthy article that's great in painting the "big picture".

- [Introduction to Event-Driven Architecture](https://medium.com/microservicegeeks/introduction-to-event-driven-architecture-e94ef442d824) - By Kacey Bui, February 2021. Good overview of the basics.


### Experience Reports And Practicalities

- [Event Granularity: Modelling events in event driven applications](https://barryosull.com/blog/event-granularity-modelling-events-in-event-driven-applications/) - By Barry O'Sullivan, December 2017. About finding the right granularity for events.
  
- [The different types of events in event-driven systems](https://blog.frankdejonge.nl/the-different-types-of-events-in-event-driven-systems/) - By Frank de Jonge, February 2022. There are different approaches to classifying events - this is a very good one.

- [Reliable event dispatching using a transactional outbox](https://blog.frankdejonge.nl/reliable-event-dispatching-using-a-transactional-outbox/) - By Frank de Jonge, February 2022. Transactional outbox is a crucial pattern for services basing their persistence on CRUD/RDBMS.


- [5 pitfalls to avoid when implementing an Event-Driven Architecture](https://medium.com/@kris_22373/5-pitfalls-to-avoid-when-implementing-an-event-driven-architecture-7fb04d7fa7ca) - By Kris Van Vlaenderen, January 2024. Some good advice here.


## 📺 Videos

### Foundational

- [Core Decisions in Event-Driven Architecture](https://youtu.be/SKXS2h3MdPM?si=LeamTGy93vAy2QYc) - By Duana Stanley, October 2019. Overall a great talk, definitely worth watching. Below are some minor issues I have with it.
    - The advice to use ids in events to refer to other entities is not wrong, but needs deeper discussion. 
    - I don't like the term "command events", something is either a command or an event.
    - In the end she hints at Kafka as an event store, I don't think that's good idea. 
  

- [Event-Driven Architectures Done Right](https://youtu.be/A_mstzRGfIE?si=An0YI1034-PazFc5) - By Tim Berglund, May 2021. Good overview, clear presentation.


- [Shifting Gears: From Events to Event-Driven](https://youtu.be/1dWJO31wpV8?si=ejDZIAWlxTkZENMw) - By Ryan Cormack, May 2024. He tells the story of Motorway's journey to event driven, so it could also be in the "experience reports" section below. But along the way, he really focusses on the foundational aspects. 

### Experience Reports And Practicalities


- [EDA in Practice: Building an eCommerce Platform at Cinch](https://www.youtube.com/watch?v=wM-dTroS0FA&t=493s) - By Toli Apostolidis, September 2022. You can ignore the first 8 minutes and 15 seconds (in fact the link will skip them), they are mostly promotion for AWS. But from there on follows a good talk on real-world experiences with event-driven architecture.



<!-- omit in toc -->
## Contributing

Please note that the list is **highly curated**. The aspiration is to assemble resources that excel in providing clarity around the principles and terminology. As a whole, the collection should provide a comprehensive and consistent overview of the topic. In the spirit of the [Awesome Lists Guidelines](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md): _"Awesome lists are curations of the best, not everything."_


Of course if you think something that belongs in the list is missing, you can suggest its inclusion in an [issue](https://github.com/reactivesystems-eu/awesome-event-driven-architecture/issues) or [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).



<!-- omit in toc -->
## Footnotes

To be updated about changes, follow me on [Mastodon](https://mastodon.social/@lutzhuehnken), [Bluesky](https://bsky.app/profile/lutzh.bsky.social) or [LinkedIn](https://de.linkedin.com/in/lutzh). If you find this interesting, you might also like my [blog](https://www.reactivesystems.eu/).


