# Self-study

This is a list of projects and self-study prompts for students that have finished the DCI Web Dev course, but don't yet have an internship or job.

- Table of contents
    - [Frontend focus](#frontend-focus)
    - [Backend focus](#backend-focus)
    - [Fullstack](#fullstack)
    - [Clone](#clone)
    - [Self-study prompts](#self-study)

## Frontend focus

### *Music Festival*

Create a website for a music festival!

- Simulate a client deadline: try limiting your available time to 5 days
- Add a calendar, concerts list, bands list...
- Go wild with the design and colors
- Create an audiovisual experience: music and animations
- Add band listing page with 5 bands per day and YouTube links for each band
- Add a festival schedule page
- Add a page for festival info; e.g. instructions for arriving by car
- Try to use only HTML, SCSS and vanilla JS (do not use any JS framework)

### *Interactive Tour*

Create a family friendly and engaging tour of a city/hike/route/area/museum. Something like [this](https://notenspur-leipzig.de/notenrouten/notenspur/karte-stationen/).

**Pointers**

- Simulate a client deadline: try limiting your available time to 5 days
- Add general information page about this tour
- Add a map (can be an image) with points of interest to display further information 
- Create pages for each point of interest for further information
- Add a form to book a tour on site
- For an extra challenge try using [WebGL Overlay View](https://developers.google.com/codelabs/maps-platform/webgl#0) or a similar visual library

### *Media Player*

Vreate a minimalistic user friendly media player.

- Simulate a client deadline: try limiting your available time to 3-5 days
- Use hardcoded data
- Add a search functionality (musician / band / song / album)
- Add Media player controls
- Add current track information
- **Extra challenge**: add a [waveform](https://duckduckgo.com/waveform?iax=images&ia=images) of the currently playing audio

### *Tetris clone*

Make a tetris clone!

- Get creative with colors and shapes
- For an even greater challenge, invent your twist, your own game meachanics 
- To make it very interesting, actually draw the graphics by using `<canvas>` OR...
- ...research (a JS library like [phaser](https://phaser.io/), [melon](https://melonjs.org/) or [gdevelop](https://gdevelop.io/)

### *React Calendar*

Make your own react calendar package, that gives the developer the option to display date in multiple ways. This project is mainly about making a package that works good in react, but it's about publishing a npm package as well.

- Simulate a client deadline: try limiting your available time to 7 days
- Should be used by the developer in a react app, which displays date
- The components must offer a way to be stilised by the developer according to her/his tech stack
- Create a demo page
- On top of React you'll need a JS bundler like [rollup](https://rollupjs.org/guide/en/), [webpack](https://webpack.js.org/) or [parcel](https://parceljs.org/), and of course learn [how to create and publish in npm](https://docs.npmjs.com/creating-and-publishing-scoped-public-packages)

## Backend focus

### *Headless CMS*

Build a Content Management System (CMS) for a little NGO (3-15). The core this project is to create the connection between the backend and two *separate* frontends: an admin website and the NGO website. The frontends are not the focus, they can be extremely small proof of concepts.

- Limit your available time to 7 days (simulating a client project!)
- Research: what does "Headless CMS" mean
- The CMS should manage content types of: User, Project and Article
- Create a simple admin website: login, add/delete/update project, add/delete/update article
- Create a simple website: load projects, load articles
- For an extra challenge use PostgreSQL (find an ORM!)

### *Messaging backend*

Build your own messaging app! Users open the chat app page with their browser, enter a nickname and they will instantly join a chatroom and instantly see as new messages are written. Users already in the room should also see when a new user is added to the room.

- This project should be implemented with https://socket.io/
- An simple UI will be needed, but it's not the core aspect this project
- The app should send, store and deliver messages between users
- Start with only text messaging
- **Bonus**: research into `Redis` and `RabbitMQ` and think how they might be useful in messaging apps
 
## Fullstack

### *Restaurant with reservation functionality*

Build the website for a restaurant, in which the user can discover the restaurant and also make a reservation as well, like by [this restaurant](https://www.nu-eat.de/)

- This is a (fake) customer project! You have 10 days to work.
- Create
    - Landing page
    - Menu page
    - Contact us form
    - Reservation (book a table for a specific day and time)
    - Another separate site, where the owner can manage the bookings

### *Art Marketplace*

Build an Art Marketplace to train usefull skills. A marketplace is a different kind of online shop. It's usually a mixture of showcase, auction house (where you can bid, not buy, and only if you logged in), stock exchange and blog. So it offers place for different types of contents and skills, as well as a big space for creativity and design (for instance: protect displayed images from being downloaded).

*Examples* 
- [artsy](https://www.artsy.net/)
- [artstation](https://www.artstation.com)
- [masterworks](https://www.masterworks.com/)

### *Community Manager Assistant*

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


### *New social media*

Find a niche and create a focused new social media platform. A niche could be something like Immigant dungeons and dragons players in Berlin, guerilla gardeners, spraypainting scene...

- user profile (sign up and login)
- post (which kind of content is up to you and it depends on which kind of social media you are making)
- feed of posts
- follow user
- messaging user

### *Meal + groceries manager*

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

## Clone 

Clone a website is always a good learning experience, either for the front and for the back end. Opening the dev tools is a great way to see what the industry standards and the real world practices are. Don't hesitate and burn this F12!

When cloning an UI is important to be as closer to pixel perfect as possible (sometimes it's not exactly the same but close enough. For instance: [Deutsche Bahn](https://www.bahn.de/) has their own typeface.

## Focused self-study prompts

Research some of the following topics:

- CSS Glassmorphism and Neumorphism
- CSS Parallax effects
- CSS Masonry layout
- Brutalist Web Design
- Clipboard management (manage Copy/Paste with JavaScript)
- Image editing with JavaScript (meme generator)
- Creating a PDF with JavaScript
- Read the text from an uploaded PDF in the backend
- Read the text from an uploaded image in the backend (OCR)
- Webcam mirror page (bonus: facial expression recoginition)
- What is Redis and how do I use it?
- What is PostgreSQL and how do I use it?
