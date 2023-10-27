---
{"dg-publish":true,"permalink":"/blog/graph-ql-summit-keynote/"}
---

# Why do we need a Supergraph?

Users have come to expect great experiences everywhere. Not just web and mobile, but voice, kiosk, IoT, wearables, AI and more. But the systems that power those experiences are becoming more divergent, with 100s of different software and hardware systems from modern micro services through to mainframes or legacy data bases. Systems that were not necessarily designed to fulfil todays requirements. 

![Screenshot 2023-10-26 at 10.52.22.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2010.52.22.png)

All these systems have to be brought together, mostly to enable and deliver 3 primary capabilities.

![Screenshot 2023-10-26 at 11.00.31.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2011.00.31.png)

- Clear understanding of services and data.
- To ship more, quickly and more efficiently. 
- Delightful and consistent experience across all touch points.

These requirements have driven adoption of new platforms and technologies on both the front end and back end.

![Screenshot 2023-10-26 at 13.08.26.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2013.08.26.png)
![Screenshot 2023-10-26 at 13.09.23.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2013.09.23.png)


Platforms are replacing much of the software we used to write with re-usable, configurable and composable building blocks, and have accelerated adoption of the numerous tools and technologies we have to work with when delivering applications and services.

And the result?

![Screenshot 2023-10-26 at 13.11.36.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2013.11.36.png)

An absolute mess, the worst of all worlds. A plethora of single use connections between applications and services. The opposite of what platform adoption is meant to deliver. So why are we still investing in the platform?

![Screenshot 2023-10-26 at 13.16.45.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2013.16.45.png)

Because we understand that with hand-written solutions there is an "entanglement tax" on everything that came before us. The platform offers re-usable building blocks that both save time and add value. So we have conflicting needs. We want the re-usability and efficiency offered by the platform. We also want a single, coherent source of truth, to have high developer velocity and the also ability to deliver great user experiences.

The Supergraph is a way to meet these conflicting requirements.

![Screenshot 2023-10-26 at 13.42.56.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2013.42.56.png)
The Supergraph is a self-service platform layer that sits between the Service APIs and the Applications. It makes it easier to build a platform with characteristics that are essential to success. 

The characteristics of a "good" platform are:
![Screenshot 2023-10-26 at 14.03.13.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2014.03.13.png)

But if the Supergraph is so powerful why do so many advocates and adopters struggle to get full buy in and adoption within their organisations? The wall many have hit is the need to build a marketplace.

![Screenshot 2023-10-26 at 14.18.24.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2014.18.24.png)

We can think of the supergraph as a special kind of platform that brings different kind of users together with complimentary needs. Adopters must understand the key characteristics that make marketplaces successful.

- Supply and Demand: API owners bring supply, App developers bring demand. The market therefor has to appeal to both parties.
- Bootstrapping: API owners must take the hit of the stage early work without the benefit of early success.
- Minimum viability: A market needs to be boot strapped until it reaches the size at which it can grow organically.
- Growth Wins: In the early phase of adoption, growth to achieve minimum viability is more important than correctness.

Considering these key marketplace characteristics can be critical to achieving a level of adoption needed to release value, stimulate organic growth, and ultimately drive organisation wide adoption of the Supergraph.

### So you want to build a Supergraph?
A Supergraph is built from 1 or more sub graphs which follow GraphQL federation open specification, and are composed into a single API - the Supergraph. 

![Screenshot 2023-10-26 at 15.31.32.png|undefined](/img/user/References/Screenshot%202023-10-26%20at%2015.31.32.png)

GraphQL federation is an open standard so you are free to implement a supergraph yourself. Alternatively you can use Apollo Router - the de factor runtime for a Supergraph. Check out [the Federation quickstart](https://www.apollographql.com/docs/federation/quickstart/setup/) to learn more. 