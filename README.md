# First Milestone Project

[Website](https://kilokilo12.github.io/first-milestone-project/)

## UX

### What is it?

This is a static website for a fictional new album release by a non-fictional British band [Kasabian](https://en.wikipedia.org/wiki/Kasabian "Kasabian Wiki").

The link to the deployed website is [here](https://kilokilo12.github.io/first-milestone-project/)

### Layout

The website is a single scrolling page, consisting of five separate areas: **Home**, **About**, **Music**, **Tour Dates** and **Contact**. It has navigation links on top of the screen, making it easy to navigate between different parts of the page.

The mock up pages are stored on [Figma](https://www.figma.com/file/IL9Iy0zmTcOyDZGFOj1r6Cdo/Kasabian?node-id=0%3A1)

### User Stories

* As a fan of Kasabian, I want to listen to their music without having to navigate through many links
* As a music lover I want to find relevant info easily
* As a concert-goer I like to find links to upcoming concerts 
* As an artist I like beautiful colour schemes and layouts


## Features

### Existing Features

* Landing page with a video background that plays automatically without sound.
* Smooth scrolling for better UX.
* Responsive navigation bar built using Bootstrap that is fully visible from any part of the web page and collapses into a hamburger on the top right hand side on devices with screen width that is smaller than 768px. 
* Link to listen to the new songs on main landing page.
* Social links on bottom right of the landing page that lead to the social media accounts of the band.
* Back to top button at the bottom right corner of every page, albeit home page.
* About section with short information about the band, band facts and best quotes by two of the band members, also two photos in this section.
* Media section enables users to listen to three songs in full using HTML audio and provides links to songs lyrics, there is also a link to listen to more songs and to purchase albums.
* Tour Dates section with built-in widget connecting with bandsintown website.
* Fixed background image behind Tour Dates section.
* Flexible Bootstrap 4 contact form with data validation that gives user a success message on a separate page after submitting, providing a link to go back to home page.
* Footer with icon links to social media accounts of the band.
* All links open in a new tab, improving user experience.
* Consistent colour scheme was used throughout the page, ensuring better user experience.


### Features yet to implement

* Link to purchase the new album
* Add a collapsible element to song lyrics to include whole songs
* Possibly sign up to newsletter


## Technologies Used

- HTML and CSS
- Bootstrap
- Figma for wireframes
- jQuery - for Bootstrap and modal
- Font Awesome - for social media icons and blockquotes
- Google Fonts - used Poppins font
- Visual Studio Code - for IDE and version control
- GitHub to store the code and GitHub Pages to deploy it
- A small Javascript snippet to enable Back to Top button

The website was built using HTML5 and CSS3 on a simple framework by Bootstrap 4, using Bootstrap's navbar, grid system, jumbotron and contact form.
Tour Dates section was built using Bootstrap and a widget by [bandsintown](https://www.bandsintown.com/), allowing users to follow the automatically updated view of upcoming (and previous) tour dates.


## Testing

- Used HP Pavilion Laptop 15-ck0xx for developing and testing. 
- Developer tools were used extensively to test responsiveness of the page and debugging.
- Two different browsers were tested on - Google Chrome and Microsoft Edge.
- For tablet size testing used Samsung Tab A.
- For mobile functionality used Pocophone1.
- Also on a numerous devices of friends and family.
- Tested HTML and CSS code with validator.w3.org.
- Tested different devices on responsinator.com.

### Issues found during testing and solutions

During testing found following issues:
- Full screen video background was only showing left top corner on mobile devices. Decided to modify that and replace full screen with fixed width and height.
- The background video was taking too long to load, after trying several different options it was cropped and compressed, black background was used for smoother transitioning.
- On mobile devices Bootstrap navbar expanded into top left hand side, changed that by adding a media query.
- Also on mobile devices, navbar items did not disappear when clicked on any link, solution found on this [page](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click) and jQuery script added to the end of script files.
- Fixed background image was cutting off heads on mobile devices, fixed using CSS.
- Bandsintown widget had in-built styling that had to be overridden by using !important values on respective attributes.
- Contact form was not giving users any feedback, decided to create a new file ("submit.html") to accommodate this
- Was getting an error regarding favicon. Fixed that by creating an icon using <https://www.favicon-generator.org/>
- After restructuring the files the fixed background was not loading, fixed this by using relative file path.


## User stories

- User 1 - The video was loading quite slowly but the transition was smooth and looked great
- User 2 - Would like a possibility to sign up for a newsletter for when I can purchase the album
- User 3 - Would have loved to find out more about the band but could not find a 'read more' link, band facts and quotes were entertaining.
- User 4 - Looked at the page on a mobile, loved the colour scheme and usability but found the background video was a bit too small.
- User 5 - I found the page very easy to use and all the links were working, opening in a new tab.
- User 6 - As a fan of the band I enjoyed listening to the songs and used the *Find lyrics* and *Listen to the whole albums* links to listen more and sing along.


## Deployment

* Used Visual Studio Code for writing the code on the master branch, then added files to staging area and committed using VS Code Source Control.
* Created a public repository on GitHub called first-milestone-project and pushed my master branch regularly into the repository. 
* The project’s source file was published from GitHub repository to GitHub Pages using GitHub default settings via the master branch
* In order to clone this code and run it locally select the 'Clone or download' link under the repository name.
$ git clone (copied link)


## Resources

### Images
- All images were downloaded from <https://www.last.fm/>

### Media
- MP3 files purchased from Google Play
- Background video downloaded from <http://www.youtube.com/>


### Other resources

* Youtube [video](https://youtu.be/V_lAhqLXT9A) by Drew Ryan for inspiration
* NME website for [quotes](https://www.nme.com/photos/kasabian-29-of-tom-and-serge-s-most-hilarious-boasts-1411450) and [facts](https://www.nme.com/photos/50-geeky-facts-you-might-not-know-about-kasabian-1404688)
* [Wikipedia](https://en.wikipedia.org/wiki/Kasabian) page for general info in the **About** section
* [W3Schools](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp) for implementing Scroll To Top button
* <https://www.favicon-generator.org/> to create a favicon


## Acknowledgements

- Would like to thank fellow students on Slack for help and advice and my mentor Chris Zielinski for continuous support throughout this project.