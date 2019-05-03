# First Milestone Project

## Overview

### What is it?

This is a static website for a fictional new album release by a non-fictional British band  [Kasabian](https://en.wikipedia.org/wiki/Kasabian "Kasabian Wiki").

The link to the deployed website is [here](https://kilokilo12.github.io/first-milestone-project/)

### Layout

The website is a single scrolling page, consisting of five separate areas: **Home**, **About**, **Music**, **Tour Dates** and **Contact**. It has navigation links on top of the screen, making it easy to navigate between different parts of the page.


## Features

### Existing Features

* Landing page with a video background that plays automatically and has a poster image for slower or no loading issues.
* Smooth scrolling for better UX
* Responsive navigation bar built using Bootstrap that is fully visible from any part of the web page and collapses into a hamburger on the top right hand side on devices with screen width smaller than 768px. 
* Link to listen to the new songs on main landing page.
* Social links on bottom right of the landing page that lead to the social media accounts of the band.
* About section with short information about the band, band facts and best quotes by two of the band members, also two photos in this section.
* Media section enables users to listen to three songs in full using HTML audio and provides links to songs lyrics, there is also a link to listen to more songs.
* Tour Dates section with built-in widget connecting with bandsintown.
* Fixed background image behind Tour Dates section.
* Flexible Bootstrap 4 contact form that gives user a success message on a separate page after submitting, providing a link to go back to home page.
* Footer with icon links to social media accounts of the band.
* All links open in a new tab, improving user experience.
* Consistent colour scheme was used throughout the page, ensuring better user experience.


### Features yet to implement

* Link to purchase the album
* Possibly sign up to newsletter


## Technologies Used

- HTML5 and CSS3
- Bootstrap 4
- jQuery - for Bootstrap and modal
- Font Awesome - for social media icons and blockquotes
- Google Fonts - used Poppins font
- Visual Studio Code - for IDE and version control

The website was built using HTML5 and CSS3 on a simple framework by Bootstrap 4, using Bootstrap's navbar, grid system, jumbotron and contact form.
Tour Dates section was built using Bootstrap and a widget by bandsintown, allowing users to follow the automatically updated view of upcoming (and previous) tour dates.



## Testing

- Used HP Pavilion Laptop 15-ck0xx for developing and testing. 
- Developer tools were used extensively to test responsiveness of the page and debugging.
- Two different browsers were tested on - Google Chrome and Microsoft Edge.
- For tablet size testing used Samsung...
- For mobile functionality used Pocophone1.
- Also on a numerous devices of friends and family.
- Tested HTML and CSS code with validator.w3.org.
- Tested different devices on responsinator.com.


### Issues found during testing and solutions

During testing found following issues:
- Full screen video background was only showing left top corner on mobile devices. Decided to modify that and replace full screen with fixed width and height.
- The background video was taking too long to load so cropped and compressed it, used black background for smoother transitioning.
- On mobile devices Bootstrap navbar expanded into top left hand side, changed that by adding a media query.
- Also on mobile, navbar items did not disappear when clicked on a link, solution added to the end of script files.
- Fixed background image was cutting off heads on mobile devices, fixed using css.
- Bandsintown widget was overriding the colour scheme of the website, was only able to override this by using !important value.
- Contact form was not giving users any feedback, decided to create a new file ("submit.html") to accommodate this
- Was getting error regarding favicon. Fixed that by adding a link to head.


## User stories

- User 1 - liked the layout but video was loading too slowly
- User 2 - Would like a possibility to sign up for a newsletter in case there are news about the band
- User 3 - Would have loved to find out more about the band but could not find a 'read more' link
- User 4 - Looked at the page on a mobile, loved the colour scheme and usability but found the background video was a bit too small.
- User 5 - I found the page very easy to use and all the links were working, opening in a new tab.
- User 6 - As a fan of the band I enjoyed listening to the songs and used the *Find lyrics* and *Listen to the whole albums* links to listen more and sing along.


## Deployment

* Used Visual Studio Code for writing the master branch and pushed into github pages. To deploy the website master branch was selected on github.
* In order to clone this code and run it locally select the 'Clone or download' link under the repository name.
$ git clone (copied link)
* There are no differences between the deployed version and the development version.


## Resources

### Images
- <https://www.last.fm/>


### Media
- MP3 files purchased from Google Play
- Background video downloaded from <http://converterino.online/>


### Other resources

* Youtube [video](https://youtu.be/V_lAhqLXT9A) by Drew Ryan (Build A Complete HTML & CSS Website with Bootstrap 4)for inspiration
* NME website for [quotes](https://www.nme.com/photos/kasabian-29-of-tom-and-serge-s-most-hilarious-boasts-1411450) and [facts](https://www.nme.com/photos/50-geeky-facts-you-might-not-know-about-kasabian-1404688)
* [Wikipedia](https://en.wikipedia.org/wiki/Kasabian) page for general info


## Acknowledgements