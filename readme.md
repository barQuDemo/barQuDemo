Howdy! Welcome to our MVP, BarQu (name subject to change)

The problem we are trying to solve for people:

We believe in bridging the gap between google places API which only provides historic data and word of mouth from individuals in cities as to what's going on in the evening in terms of "night life." With BarQu, we can finally bridge this gap by creating an application that provides realtime updates as to how many people are frequenting a location with all the added benefits and power of a traditional api to provide information about this location in question. This empowers users with knowledge and helps users make better decisions as to how to optimize their "fun" when considering bars to check out local to Charleston.

===========
===========

How are we planning to solve this? (what does the app do?)
when you log on to the homepage, the homepage will provide a list of bars that we have chosen to work with (fictional or actual) and they will be represented in order from the most foot traffic to the least foot traffic. The bar names can be clickable which will open up a seperate page or popup window with more detailed information and possibly populating via an API to describe location and pertinent information.
There will be a login function for clients to access and perform CRUD functions on their bars "about" section, which will provide a small snapshot of anything special happening at that bar tonight ie. "halloween contest tonight!" There will be a database to manage the data supplied by clients who update their page and ideally keeping track of estimated foot traffic as well.

This app will bubble up to the top the bar with the most foot traffic represented by a progress bar or line that grows with the amount of people in the bar as submitted from the client's page (the page used for updating information on their bar will also serve as a place to update numbers in the bar).

Possible extras we would like to incorporate (for complexity/cool points):

As time and resources permits, we would like to be able to filter by other important categories i.e. do they have live music? Are they dog friendly? etc? There will possibly be a global chat box running off of websocket IO that allows those in the charleston area using the app to comment about rad things happening at these locations/in town i.e. "the band here is so good! aerosmith dream on! woo !" 
The use of emojis similiar to how others use emojis in slack to indicate their interest level in iron pints would be a fun keyboard to integrate in similiar fashion. Possible API integration with reviews of the bar when users click the bar name to show map location or other information. 

===========
===========

The code we are trying to display:
Front-end: React
Back-end: Java with Spring Boot

The front-end will display in function: realtime updates,

The back-end will display in function: CRUD functions, postgreSQL or MongoDB, user authentication, Websockets for chat function in app, bluetooth (potentially), managing routes

===========
===========
User Goals: To view the most popular bar based on foot traffic in real time by opening the app. Single page app usage, designed for quick reference and with simplicity in mind.

===========
===========

Features list and their importance:

1. Update bars by foot traffic in real-time
2. CRUD functions for clients to edit and make changes to their info
3. Database to hold for crud functions
4. Basic Authentication
5. Chat Box (websockets)
6. Possible API integration
6. Emoji's or symbols to share onclick
7. Facebook authentication






