# DJ Tutorial

This project is created to help aspiring DJs to acquire the skills to become a professional DJ. 
With a step by step structured website designed to make it easy to learn and follow along. 

## Showcase
![Showcase-screenshot](assets/images/wireframes/home-page.png)

A deployed version of my website can be found [here.](https://jesperkarlsson500.github.io/DJ-Tutorial-MS1/index.html)

## Navigation

* [UX](#ux)
* [Strategy](#strategy)
    + [User-needs](#user-needs)
    + [Business-vision](#business-vision)
* [Scope](#scope)
* [Structure](#structure)
* [Wireframes](#wireframes)
  + [Changes](#changes-to-wireframes)
* [Features](#features)
    + [Existing-features](#existing-features)
    + [Future-features](#futere-features)
* [Technologies](#technologies)
* [Testing](#testing)
+ [Testing-plan](#testing-plan)
  + [Implementation](#implementation)
  + [Results](#results)
* [Bugs](#bugs)
* [Deployment](#deployment)
* [Credits](#credits)
* [Content](#content)
* [Media](#media)
* [Acknowledgements](#acknowledgements)

## UX
<hr>
The purpose of this website is to create a journey for people that aspire to be a DJ. 
starting with an introduction that will end in a call to action to join the free step by step tutorial.
Users will be able to enjoy the playground were they can listen to my finished mixes.
For those that seek a deeper understanding on how to mix songs 
together can signup for a private lession with a professional DJ.

### UX Stories
 
* As a user I want to learn the basic skills about DJing.
* As a user I want to learn the professional skills about DJ.
* As a user I would like to get inspired in my musical careeer.
* As a user I would to listen to what a DJ can do.
* As a user I want to navigate easily through the content.
* As a user I want to learn in a structured, step by step way.

A user for my website is looking to learn the basics about DJing, through my free step by step totorial.
A user for can also book a private session were they learn the skills to become a professional DJ.

## Strategy
<hr>

#### User Needs
As a user the site needs to work on desktop, tablet and mobile. 
Be user friendly with clear navigation and flow through the whole experience.

#### Business vision
The purpose of this project is to help aspiring DJs. With a free step by step tutorial they will 
learn the basics. If they want to become a professional DJ's they can signup for a private session.
The ultimate goal is to get private session booked with users.

## Scope
I want my user to get excited and inspired as to what you can do with the skills of DJing. 
I want them to find a place were they can learn new skills but also relax and enjoy good music.

## Structure
The project is made up of four pages:
1. Home - The Home page has three secitons ending with a call to action; start tutorial.
2. Tutorial - Ends with a call to action, go to Playground.
3. Playground - Ends with a call to action, go to Signup.
4. Signup - Ends with a call to action, Signup and book a private lesson.

The idea is to create a natural flow for the user through the pages in that order, 
giving them structure on their journey to become a DJ. 

#### Home
On the Home page you are greeted by an image of the workstation of a DJ, turntables and a mixer. 
This image represents the whole purpose of the site. In section two you have a dark purple background contrasting 
the orange horizontal rule and white text, making it easy to read. In section three I yet again show an image of 
turntables and a mixer. This time in brighter colors, with white text glowing pink. 
The bright colors are chosen purposefully to make the user excited for the next step.

#### Tutorial
While speaking to my mentor she recommended me to use a carousel to showcase my 
tutorial, This fit really well with my plan to give the user a step by step experience.

#### Playground
This is were the user comes to listen to the end results of what a DJ can do. At the same time inspire them to
signup for a private lesson.

#### Signup
By signingup the user will be contated through email to book a private DJ sessions.

## Wireframes
<hr>

* My first Wireframes
![Wireframe](assets/images/wireframes/Wireframe-first-edition-one.jpg)
![Wireframe](assets/images/wireframes/Wireframe-first-edition-two.jpg)
![Wireframe](assets/images/wireframes/Wireframe-first-edition-three.jpg)

* My second Wireframes
![Wireframe](assets/images/wireframes/Wireframe-second-edition-one.jpg)
![Wireframe](assets/images/wireframes/Wireframe-second-edition-two.jpg)
![Wireframe](assets/images/wireframes/Wireframe-second-edition-three.jpg)

### Changes to wireframes
I had a hard time keeping to my wireframes, since my skills and the vision for the project 
grew while I was working on it. The second wireframes are the closest to the final build. 
I felt I had no time to make new wireframes, so I used the second wireframes and build on that.
I don't recommend this because I had a lot of trail and error. I think this accually took 
more time then making new wireframes.

## Original ideas
<hr>
The project had three pages full of text and pictures. Mentor Antonija helped me see that 
less is more. She adviced me to create sections on the first page and give the elements some room.

I created a scroll down button on all sections on the Home page to guide the user.
but speaking with my mentor Antonija she asked If that was really necessary. We had a discussion 
and I came to the conclution that you scroll down by instinct when you enter a page, so I took that away.

I wanted to create a decontructed upside down pyramid, created by three 
boxes on the home page. You would have the DJ Tutorial logo on the top box followed by an 
inspirational text and the scroll down text. It would all create the shape of an arrow 
pointing down. The idea was interesting but when i executed it, it dident turn out so good.
It gave a bad impression of the page and I oppted to go with less is more.

Renamed and reworked challenge.html and contact.html to playground.html and signup.html.
Reasoning: Playground and Signup sounds more appealing and intuative, It's a better call to action. 
Moved my two soundcloud link to Playground from Home page to improve load times and performance.

## Features
<hr>

* Responsive Navbar menu collapsing into a hamburger dropdown menu on tablets and phones.
* Easy navigation through the pages using the navbar.
* Homepage with an images of the workstation of a DJ. 
* Soundcloud links were you can play music.
* The tutorial is in a Bootstrap Carousel for easy step by step user experience.
* Signup form to get in contact with a professional DJ.

### Future Features
* Create a multiple choice challenge for the user so they can test their skills learned.

## Technologies
<hr>
This project was build using the following technologies:

* HTML5
* CSS3
* Bootstrap: Carousel
* Google Chrome DevTools: Helped me iterate, debug and profile my site.
* Lighthouse: Helped me improve the websites performance on both desktop and mobile.
* Jigsaw W3C validator: Validated and tested my CSS.
* W3C Markup validator: Validated and tested my HTML.


## Testing
<hr>
I see my users using both desktop and mobile, so I had that in mind when I created my responsive design.

* Markup Validator warning: The document is not mappable to XML 1.0 due to two consecutive hyphens in a comment. 
I was using to many hyphens so I removed the excess ones.

* Markup Validator error: Can't put horizontal rule as a child element of any header element. 
So I move the horizontal rule outside of any header element.

### Testing plan

My goal is to create a site that that works on both desktop and mobile. researching the field I 
found that most professional DJ's use their laptop as a workstation, but being on the road 
they use their phones a lot, also DJ apps are getting more and more popular every day. 
So I had that in mind when I created and tested out my website in devtools. 
I tested on Desktop, Ipad, and Phones. Especially on Iphone 5/SE because it has a unique 
resolution that can cause overflow problems.

### Implementation
My testing was done with Chrome DevTools, Checking through different resolutions and devices.

I used Lighthouse to check the performance on both mobile and desktop and search for errors.


## Results
<hr>


## Bugs
<hr>

I had a problem were my images showed up when I open them in the python3 -m http.server, but not when I open 
my project as a stand alone website. Images dident work because I had a forward slash before my 
assets and then the website searches in the root instead of relative path, which is DJ-Turorial-MS1.




#### Navbar dropdown menu did not work when I click the hamburger icon.
Solution: Added <script src="script.js"></script> in the body

#### class="hide-trance-mix" did not hide the iframe
Solution: Put the closing div after the iframe

#### Chrome devtools problem that img was outside of viewport
Solution: width: 100%; instead of width: 100vw;

## Deployment
<hr>

## Credit
<hr>

## Content
<hr>

## Media
<hr>

## Acknowledgements
<hr> I want to thank my mentor Antonija for helping me and supporting me during this project.

### Existing Features

### Features Left to Implement


## Technologies Used

* Bootstrap
    The project uses bootstrap to make the carousel work in the tutorial page.

### Description/introduction

This is a dj tutorial website designed to teach you how to DJ with a 
step by step dj tutorial and  for those looking for more advanced tips 
a chance to booking private DJ lessons.

It consist of four pages:
index/Home: introduction
Tutorial: Step by step DJ tutorial
Challange: Test your skills and prove that you can DJ
Contact: Sign up with Name, Lastname, Email and write a comment.

DJ tutorial is a website designed to teach everyone the basics on how to DJ. 
With an step by step tutorial and a challange that will test your skills we make sure you know what to do.
Sign up to join the advanced course today.

### Code languages used is the making of this website: HTML, CSS and sript.js.

### Current status of development: 
Home. Page 1 and 2 almost done, page 3 under contruction
Tutorial: Basic design done, needs styling.
Challange: Under construction.
Contact: Under construction.

### Code take from the internet and used in my project.

Navbar taken from https://www.youtube.com/watch?v=At4B7A4GOPg
Carousel taken from https://www.w3schools.com/bootstrap/bootstrap_carousel.asp

### Bug report
#### Navbar dropdown menu does not dropdown when I click the hamburger icon.
Solution: Added <script src="script.js"></script> in the body

#### Carousel doesn't work. 
Solution: fixed carousel problem by changing id="item active" to class="item active
It stopped working because I had a lot of elements 
named by ID and when I changed it to class i forgot to change item active 
to a class too.

#### class="hide-trance-mix" did not hide the iframe
Solution: Put the closing div after the iframe

#### Chrome devtools problem that img was outside of viewport
Solution: set 100% width instead of 100vw

## Project changes during time
28-04-2021: Renamed and reworked challenge and contact to playground and sign up.

Reasoning: Playground and Sign up sounds more appealing and intuative, It's a better call to action. 
Designed so now Playground will hold my two mixes to listen two instead of the front page 
(improving load times and performance, tested in lighthouse) and some questions to test if the 
user has learned whats in the tutorial.



Project creator: Jesper Karlsson

Phone: 0738468666
E-mail: jesper.karlsson500@gmail.com
