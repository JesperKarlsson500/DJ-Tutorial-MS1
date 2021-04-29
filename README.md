# DJ Tutorial

Project creator: Jesper Karlsson

Phone: 0738468666
E-mail: jesper.karlsson500@gmail.com

# UX
A user for my website is looking to learn the basics about DJing through my step by step totorial
or book a private lesson with me teaching them in depth on how to DJ.

* As a user I will experience a clean first page with call to action. An orange bordered button letting 
me know that I need to scroll down if I want to know more. 

* As a user I want to know where I can learn how to become a DJ. The information is given 
to me by following the orange call to action button and scrolling down on the page.

* As a user I want to learn this information in a bite sized order so it's easier to take in.
With the step by step carousel experience it lets me take in information in a 
easy to read enviroment and at my own pace.

* As a user I want to practice what I have learned and test my skills. 
I can do that by clicking the Challange link in the Navbar and take the test 
and see how many points I get.

* If I want to dive deeper and learn more about DJing I can navigate to the contact page and book a 
one on one lesson with a professional DJ for a small hourly fee.

# Features

## Existing Features

## Features Left to Implement


# Technologies Used

* Bootstrap
    The project uses bootstrap to make the carousel work in the tutorial page.

## Description/introduction

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

## Code languages used is the making of this website: HTML, CSS and sript.js.

## Current status of development: 
Home. Page 1 and 2 almost done, page 3 under contruction
Tutorial: Basic design done, needs styling.
Challange: Under construction.
Contact: Under construction.

## Code take from the internet and used in my project.

Navbar taken from https://www.youtube.com/watch?v=At4B7A4GOPg
Carousel taken from https://www.w3schools.com/bootstrap/bootstrap_carousel.asp

## Bug report
### Navbar dropdown menu does not dropdown when I click the hamburger icon.
Solution: Added <script src="script.js"></script> in the body

### Carousel doesn't work. 
Solution: fixed carousel problem by changing id="item active" to class="item active
It stopped working because I had a lot of elements 
named by ID and when I changed it to class i forgot to change item active 
to a class too.

### class="hide-trance-mix" did not hide the iframe
Solution: Put the closing div after the iframe

### Chrome devtools problem that img was outside of viewport
Solution: set 100% width instead of 100vw

# Project changes during time
28-04-2021: Renamed and reworked challenge and contact to playground and sign up.

Reasoning: Playground and Sign up sounds more appealing and intuative, It's a better call to action. 
Designed so now Playground will hold my two mixes to listen two instead of the front page 
(improving load times and performance, tested in lighthouse) and some questions to test if the 
user has learned whats in the tutorial.



