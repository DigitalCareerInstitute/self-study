**Set of projects and self-study prompts for students that have finished the course, but don't yet have an internship or job.**


## HTML/CSS projects

### Project 1: *Music Festival*

**Goal:** create a website for a music festival, with calendar, concerts list, bands list...

**Description:** go wild with the design and colors; create an audiovisual experience with music and animations

**Must include:**

  - band listing page with 5 bands per day and YouTube music examples for each band)
  - 2 day schedule page and a page for festival info including instructions for arriving by car.

**Time:** 5 days

**Tech Stack**:

- Use only HTML, SCSS and JS.
- Do not use any JS framework.


### Project 2: *Interactive Tour*

**Goal:** create a website for a music festival, with calendar, concerts list, bands list...

**Description:** create a family friendly and engaging experience. Something like [this](https://notenspur-leipzig.de/notenrouten/notenspur/karte-stationen/), but maybe using [WebGL Overlay View](https://developers.google.com/codelabs/maps-platform/webgl#0) or a similar library.

**Must include:**

 - general information about this route or place
  - map (can be an image) with landmarks and points of interest that display further information and / or link to a site with further information
  - book tour site
  - 
**Time:** 5 days
  
**Tech Stack:**
- Use only HTML, SCSS and JS.
- Do not use any JS framework.


### Project 3: *Media Player*

**Goal:** create a minimalistic user friendly media player.

**Description:**

**Must include:**

  - a search functionality (musician / band / song / album) 
  - media player controls
  - track information

**Time:** 5 days
 
**Tech Stack:**

- Use only HTML, SCSS and JS.
- Do not use any JS framework.

 *Bonus points* a wave representation like [this](https://www.google.com/imgres?imgurl=https%3A%2F%2Fimg.freepik.com%2Fpremium-vector%2Fsound-wave-with-imitation-sound-audio-identification-technology_106065-64.jpg%3Fw%3D2000&imgrefurl=https%3A%2F%2Fwww.freepik.com%2Fpremium-vector%2Fsound-wave-with-imitation-sound-audio-identification-technology_4476394.htm&tbnid=6gCxrhBizPWGOM&vet=12ahUKEwjJhP2jp_36AhUFiv0HHQPvBnAQMygDegUIARDeAQ..i&docid=vhHBjaNrQUicvM&w=2000&h=1124&q=wave%20sound&client=firefox-b-d&ved=2ahUKEwjJhP2jp_36AhUFiv0HHQPvBnAQMygDegUIARDeAQ), [this](https://www.google.com/imgres?imgurl=https%3A%2F%2Fmedia.istockphoto.com%2Fvectors%2Fsound-waves-motion-sound-wave-abstract-background-vector-id1176100626%3Fk%3D20%26m%3D1176100626%26s%3D612x612%26w%3D0%26h%3Dvl-hfVdQnFD-rEmRvTUI8f_QC0WGek3JXZPCJLAkow8%3D&imgrefurl=https%3A%2F%2Fwww.istockphoto.com%2Fphotos%2Fvoice-waves&tbnid=R5KG9o2_CBhFwM&vet=12ahUKEwjJhP2jp_36AhUFiv0HHQPvBnAQMygOegUIARD2AQ..i&docid=gkj39ZpYk799WM&w=612&h=349&q=wave%20sound&client=firefox-b-d&ved=2ahUKEwjJhP2jp_36AhUFiv0HHQPvBnAQMygOegUIARD2AQ) or [this](https://www.google.com/imgres?imgurl=https%3A%2F%2Fcdn3.vectorstock.com%2Fi%2F1000x1000%2F52%2F07%2Fneon-wave-sound-background-music-soundwave-vector-24515207.jpg&imgrefurl=https%3A%2F%2Fwww.vectorstock.com%2Froyalty-free-vector%2Fneon-wave-sound-background-music-soundwave-vector-24515207&tbnid=tS83ALlgosmYhM&vet=12ahUKEwjJhP2jp_36AhUFiv0HHQPvBnAQMyg2egQIARBS..i&docid=9qO3ZcDX8vxy7M&w=1000&h=780&q=wave%20sound&client=firefox-b-d&ved=2ahUKEwjJhP2jp_36AhUFiv0HHQPvBnAQMyg2egQIARBS)
   
### Project 4: *Tetris clone*

**Goal:** make a clone tetris with a twist. Don't do a copy! Let's get creative with colors, shapes and game dynamics.

**Time:** 5 days
**Tech Stack:**

- use only HTML, CSS and JS


### Project 5 : *Quiz game*


**Goal:** let's build a quiz game

**Description:** it can be as simple as questions with multiple answers and as complex as a 3D trivial pursuit.
**Time:**
**Tech Stack:**

 - use only HTML, CSS and JS (eventually a JS library like [phaser](https://phaser.io/), [melon](https://melonjs.org/) or [gdevelop](https://gdevelop.io/) for a more "gamy" UI
 - you can make your own questions and answers or use an API like the [trivia API](https://the-trivia-api.com/) 

### Project 6 : *React Calendar*

**Goal:** make your own react calendar package, that gives the developer the option to display date in multiple ways 
**Description:** this project is mainly about making a package that works good in react, but it's about publishing a npm package as well.

**Must include:**
- a package that offers components to be used by the developer in a react app, which displays date
- the components must offer a way to be stilised by the developer according to her/his tech stack

**Time:** 7 days

**Tech Stack:**
- on top of react you'll need a JS bundler like [rollup](https://rollupjs.org/guide/en/), [webpack](https://webpack.js.org/) or [parcel](https://parceljs.org/), and of course learn [how to create and publish in npm](https://docs.npmjs.com/creating-and-publishing-scoped-public-packages)


### Project 7 : *Chat bot*

**Goal:** create a chat bot that addresses the most common questions and complains from the customers of a given business. 

**Description:** since some companies are relative big and complex, every day more business introduce a chat bot on the website to answer the most common questions, or to connect the customer with the needed professional.

**Must include:**
  - implement a field where the customer can input a question / complain.
  - interpret the customer's input (=> translate the customer's input to the options we have and implement a default option in case of no available answer)
  - write an answer tree, giving  one or multiple options for the customer for a giving sentence
  - you'll need a simple UI for the interaction with the user. Keep it simple and clean.
 
 * bonus points:* animate an image (robot, cartoon, …) so it looks like it saying the answer. For that you can use vanilla JS animations or use a library [phaser](https://phaser.io/), [melon](https://melonjs.org/) or [gdevelop](https://gdevelop.io/), depending on the animation's complexity

**Time:** 7 days
**Tech Stack:**
  - use HTML, CSS and JS only
  - for the chatbot function you can use vanilla JS or a framework like [botui](https://docs.botui.org/) or [intelligo](https://intelligo.js.org/)



## Backend projects

### Project 1: *Build a CMS*


**Goal:** Build a Content Management System (CMS) for a little NGO (3-15)

**Description:** the core this project is to create the connection between an admin UI and the NGO website. Therefore an Admin-UI is needed, but not the focus.

**Must include:**
  - a simple and clean UI for the administrator
  - a connection to the DB of your choice, where you can edit (create, edit, delete):
    -   the blog
    -   the "we are" (meaning: manage associated profile's)
    -   read and answer blog comments
 
**Time:** 7 days

**Tech Stack:** - Use the tech stack you think is better for the job (CSS and JS frameworks included)


### Project 2: *Messaging app*

**Goal:** Build your own messaging app!

**Must include:**
- An UI will be needed, but it should be kept  simple, since it's not the core aspect this project
- The app should send, store and deliver messages between users. Which kind of messages (only txt, emojis, voice, files, videocall...) is up to you.
- Users should be logged in in order to use the app.
- 
**Time:** 7 days

**Tech Stack:**
 on top of the front- and back-end you'll probably need some tech like socket.ir, Memcached, RabbitMQ or Reddis
 

### Project 3: *Music Life Api*

**Goal:** write an API that manages musicians, bands, venus(concert locations), and concerts

**Description:** the point of that API is create a dense related database, where every group is related to the others (a musician could play in many bands, has multiple concerts in different venues and so on). 

**Must include:**

**Time:**

**Tech Stack:**
- use JS and Node.js.
- you can use this project to learn more about relations in a no-SQL Db or to learn a SQL Db.
- make a little testing db. You can use a fake data generator like [mockaroo](https://www.mockaroo.com/).   










## Fullstack projects


### Project 1: *Restaurant with reservation functionality*

**Goal**: build the website for a restaurant, in which the user can not only discover the restaurant, but make a reservation as well, like by [this restaurant](https://www.nu-eat.de/)

**Description:**

**Must include:**

  - Landing Page
  - Menu
  - Reservation, where the customer can book a table for a speciffic day and time
  - Contact
  - Another site, where the owner can manage the bookings

**Time**: 10 days

**Tech Stack:**

- Use the tech stack you think is better for the job (CSS and JS frameworks included)

### Project 2: *Art Marketplace*
  
  **Goal:** Build an Art Marketplace to train usefull skills.
 
  **Description:** a marketplace is a different kind of online shop. It's usually a mixture of showcase, auction house (where you can bid, not buy, and only if you logged in), stock exchange and blog. So it offers place for different types of contents and skills, as well as a big space for creativity and design (for instance: protect displayed images from being downloaded).
  
  *Examples* [artsy](https://www.artsy.net/), [artstation](https://www.artstation.com), [masterworks](https://www.masterworks.com/)
  
  **Must include:**
    - Landing Page
    - Registration / Login
    - Art and artist list
    - Top Tier List to see the "most wanted ones"
  **Time:** 10 days
  **Tech Stack:**  
  
- Use the tech stack you think is better for the job

### Project 3 : *Community Manager Assistant*

**Goal:** is to manage post on a social media app by uploading and scheduling content as well as interacting with the community

**Description:** there's already some platforms that offers this service, like [hootsuite](https://www.hootsuite.com/en-gb) and [buffer](https://buffer.com/) or [youtube studio](https://studio.youtube.com) *this link is different for every user and will lead to your youtube's account youtube studio* . Take inspiration from then and make your own version of it!
This could be a way to collaborate with the OM department. Don't miss the chance to talk to them. I'm sure there's many people who would love some missing feature in the mentioned apps!

**Must include:**
- connection with at least one social media platform (twitter, instagram, facebook, pinterest...). Look their respective API.
- the option to upload and schedule content to this platforms (display a calendar, post preview, in case of instagram feed preview, ...)
- read and write comments
- make UI clean, simple. Be aware of color selection, then you probably want to be differenciated from an specific brand.

**Time:** 10 days

**Tech Stack:** use the tech stack you find more suitable for the project

### Project 3 : *Project assistant*

**Goal:** is to have an app that helps with project management. 

**Description:** there's plenty of project management apps out there. Most of them are mainly focused on team work. Interesting extra-features could be offering automate certain processes (ie automating reactions => "when become input A do B"), scheduling certain apps processes, or become regular previously programmed notifications.

**Must include:**
- open a new document (project) with different sections (goals, timing, processes, ...)
- "to do list" (a project manager is a more complete and complexe to do list)
- back-end to store every document
- an UI to manage this content

**Time:** 10 days

**Tech Stack:**
- use the tech stack you find more useful for the project

### Project 3 : *New social media*

**Goal:** create a new social media for a very concrete niche.
**Must include:**
- user profile (sign up and login)
- post (which kind of content is up to you and it depends on which kind of social media you are making)
- feed
- follow user
- messaging user

**Time:** 10 days
**Tech Stack:**
- use the tech stack you find more usefull for the project

### Project 4 : *Meal + groceries manager*

**Goal:** build an application that assist the user with meal planning and groceries

**Description:** the application must offer the user a variety of recipes according to the user preferences. Every X days the user will get a meals list to pick from and will order the groceries accordingly. This should help with accomplish diet goals, releaving the grocery buying stress as well as to people with reduced movility, or even to help managing catering services.

**Must include:**
provides a meals list for a period of time (a week), filtered from the user suggestions (“anything”, “vegetarian”, “vegan”, “glutenfree”,...). The user can edit this list by editing every recipe and discarding unwanted meals (and then getting a new suggestion. The unwanted recipe can be stored in a “unwanted meals list”)
once the user agrees to a meal selection, the backend “translates” it into a grocery list
then orders the grocery list. Some german supermarkets has API
the user can input “what's in the pantry”, which the backend takes into consideration to form the next meals list
You can use a recipe / meal planner API like 

**Time:** 10 days
**Tech Stack: **
This is a full stack application mainly focused on the back-end side.
For the front-end: use React, SCSS and a CSS framework
For the back-end you'll need the techs learned during the 1-year-course (Mongo Db, Express, mongoose, …), as well as some API:
for recipe suggestions: [suggestic](https://docs.suggestic.com/graphql/), [spoonocular](https://spoonacular.com/food-api) or [nutrixionix](https://www.nutritionix.com/)
to order groceries: some german supermarkets like [Kaufland](https://www.kaufland.de/api/v1/) has an API. Maybe it's worth take a look into [Open Food Facts](https://de.openfoodfacts.org/data), [Zinc](https://zincapi.com/) or [Amazon](https://developer-docs.amazon.com/sp-api/). Web scraping could be an alternative. If you do it through a good SaaS provider you safe yourself work and potential trouble. [Smartproxy](https://smartproxy.com/scraping/ecommerce)

## Let's get cloning! 

Clone a website is always a good learning experience, either for the front and for the back end. Opening the dev tools is a great way to see what the industry standards and the real world practices are. Don't hesitate and burn this F12!

When cloning an UI is important to be as closer to pixel perfect as possible (sometimes it's not exactly the same but close enough. For instance: [Deutsche Bahn](https://www.bahn.de/) has their own typeface.

Some websites that you can find interesting to copy:

  
## Self-study prompts

