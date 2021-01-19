# Virtual Grounds
### Hack The North 2020++
*The all-in-one virtual space with productivity analytics*

![Virtual Grounds logo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/346/472/datas/gallery.jpg)

![Homepage](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/346/678/datas/gallery.jpg)

## Inspiration 
It goes without saying that 2020 presented a multitude of challenges for individuals.

March came by and suddenly we were all in quarantine, trapped at home with nothing to do and nowhere to go.

Some of us found things to do, learned new skills, took up interesting hobbies.

Unfortunately, not everyone was in either a financial situation, mental or emotional state to be able to motivate themselves to do something productive with all their free time.

In addition, we were forced to transition to remote learning and work.

That’s why we came up with the idea of Virtual Grounds.

Virtual Grounds allows users to connect with others in online chat rooms, being automatically placed with those who have similar interests, and are of the same age. Virtual Grounds also provides an online Kanban board, allowing users to keep track of daily, weekly, or monthly tasks. With a single click of a button, users get analytics on their productivity, showing them how many hours they dedicated to each task, as well as the amount of down time they have to try new things out.

## What I did:

 -  Solely designed and created the front-end UI using **React, JavaScript and Bootstrap** to create simplistic yet effective designs


## What it does
Virtual Grounds is a productivity platform that goes beyond simply tracking your daily tasks. We provide the user with all sorts of analytics to help them plan their days and weeks more effectively. Users on our application can easily access their weekly insights to see the hours they slept, the total number of hours spent completing productive tasks, the number of hours dedicated to each category of these tasks, and much more. 

Through analysis of this data, we’re able to calculate the estimated amount of free time the user has each week.  Now, this is where Virtual Grounds finds its niche in the productivity software market. While many platforms aim to increase productivity and reduce idle time, our goal instead is to emphasize the users planning of their own free time. We don’t want our users cycling through the mundane things in life, rather we want to provide them with opportunities to get out and explore new things. Our user analysis software allows us to see what kinds of personalized activities and hobbies the individual may be most interested in. We then present this data to the users, linking them to sites and programs with these activities, and allowing them to custom pick which activities they are interested in and would like to pursue. The user can then enter chats and groups with like-minded people pursuing these same activities, giving them the chance to network and create friends who will motivate the user to stick with the activity they’ve chosen over the long run. The user then provides Virtual Grounds with some more information, such as the date they would like to start, and their expected weekly commitment. Since all these options are up to the user, they’re free to play around with the settings however they’d like. If they’d like to plan out more activities but spend less time with each of them so that they can fit them all into their schedule, it’s completely up to them. Virtual Grounds adapts and schedules however it’s needed. We don’t plan for the user, the user plans with us.

## How we built it
**Frontend**

-   React
    -   UI framework the application was written in
-   JavaScript
    -   Language the frontend was written in
-   Redux
    -   Library used for state management in React
-   Redux-Sagas
    -   Library used for asynchronous requests and complex state management

_**Backend and Frontend connected through REST API as well as Websockets (for chat)**_

**Backend**

-   Django
    -   Backend framework the application was written in
-   Python
    -   Language the backend was written in
-   Django Rest Framework
    -   built in library to connect backend to frontend
-   Django Channels
    -   built in library to build a Websocket ASGI application on your Django server

**Database**

-   CockroachDB
    -   used for data storage of Users, Tasks, Profiles, etc.
    -   distributed transactions allow us to serve two different hosts with ease, using CockroachDB to its full capabilities
    -   Cloud native storage allows for scalibility, as well as uniform data amongst developers, rather than relying on your local machine

## Challenges we ran into
A large challenge that presented itself was hosting an ASGI and WSGI application on the same server.

This was finally accomplished through redis caching, as well as the use of CockroachDB.

## Accomplishments that we're proud of
We are really proud that our group was able to collaborate efficiently and effectively due to this year’s virtual setup. It was definitely a unique experience due to the ongoing pandemic but our group was able to successfully complete our hack.

## What's next for Virtual Grounds
The next step for Virtual Grounds is to market our application towards University of Waterloo students as a test run to see how our application reacts to high traffic. We plan to advertise our additional features such as Discover Mode, Productivity Analytics and much more for those that become invested in our application. Then we plan on targeting individuals across Ontario, and eventually internationally, in order to help them measure and improve their productivity, as well as take up some new hobbies during their quarantine.

For future software developments, we would like to implement ML that can be trained to provide more activity/hobby suggestions to the user based on the tasks they submit into their calendar and the discussions they have in different activity group chats. As well, we'd like to implement a forum where users can share their experiences of taking up some new hobbies. 

## Devpost:
https://devpost.com/software/virtual-grounds-h9ico0



## Created by:

Brandon Goh:

- Linkedin: https://www.linkedin.com/in/brandon-goh/

Sam Eskandar:

- Github: https://github.com/s6eskand

Masih Bouriayee:

- Github: https://github.com/masihbouriayee
