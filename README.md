# First Milestone Project

## Overview

### What is it?

This is a static website for a fictional new album release by a non-fictional British band Kasabian.

### Layout

The website is a single scrolling page, consisting of five separate areas: Home, About, Music, Tour Dates and Contact. It has navigation links on top of the screen, making it easy to navigate between different parts of the page.

## Technologies Used

- HTML5 and CSS3
- Bootstrap 4
- jQuery - for bootsrap and modal
- Font Awesome - for social media and blockquotes
- Google Fonts - used Poppins
- Visual Studio Code - for IDE and version control

The website was built using HTML5 and CSS3 on a simple framework by Bootstrap 4, using their navbar, grid system, jumbotron and contact form.
Tour Dates section was built using Bootstrap and a widget by bandsintown, allowing users to follow the automatically updated view of upcoming (and previous) tour dates.


## Testing

- Used HP Pavilion Laptop 15 for developing and testing. 
- Developer tools were used extensively to test responsiveness of the page and debugging
- Two different browsers were tested on - Google Chrome and Microsoft Edge.
- For tablet size testing used Samsung...
- For mobile functionality used Pocophone1
- Also on a numerous devices of friends and family.
- Tested html and css with validator.w3.org
- Tested different devices on responsinator.com - does not work very well on landscape

### Issues found during testing and solutions
During testing found following issues:
- Full screen video background was only showing left top corner on mobile devices. Decided to modify that.
- On mobile devices Bootstrap navbar expands into top left hand side, changed that
- Same navbar does not disappear when clicked on a link, solution found.
- Fixed background image was cutting off heads on mobile devices.
- Bandsintown widget was overriding the colour scheme of the website, was only able to override this by using !important
- Contact form was not giving users any feedback, decided to create a new file ("submit.html") to accommodate this


### User stories
- User 1 - liked the layout but video was loading too slowly
- User 2 - Would like a possibility to sign up for a newsletter in case there are news about the band
- User 3 - Would have loved to find out more about the band but could not find a 'read more' link
- User 4 - Looked at the page on a mobile, loved the colour scheme and usability but found the background video was a bit too small.

## Features

### Existing Features

* Landing page with full screen video background
* Responsive navigation bar that is fully visible from any part of the web page and collapses on mobile devices.
* Link to listen to the new songs on main landing page
* Social links on bottom right of the landing page that lead to the social media accounts of the band
* About section with short information about the band, band facts and best quotes by two of the band members
* Media section enables to listen to three songs in full and provides links to songs lyrics, also a link to listen to more songs
* Tour Dates section with built-in widget connecting with bandsintown
* Fixed background image behind Tour Dates section
* Flexible Bootstrap 4 contact form that gives user a success message on a separate page after submitting, providing a link to go back to home page
* Footer with icon links to social media accounts of the band


### Features yet to implement
* Link to purchase the album
* Possibly sign up to newsletter
* Override widget colour

## Deployment

* Used Visual Studio Code for writing the master branch and pushed into github pages. To deploy the website master branch was selected on github.
* In order to clone this code and run it locally select Clone or download link under the repository name.
$ git clone (copied link)
* There are no differences between the deployed version and the development version.


## Resources

### Images

### Media

### Other resources

* Youtube video by Drew Ryan (Build A Complete HTML & CSS Website with Bootstrap 4) - link https://youtu.be/V_lAhqLXT9A for inspiration
* NME website for quotes - link https://www.nme.com/photos/kasabian-29-of-tom-and-serge-s-most-hilarious-boasts-1411450
https://www.nme.com/photos/50-geeky-facts-you-might-not-know-about-kasabian-1404688
https://en.wikipedia.org/wiki/Kasabian
