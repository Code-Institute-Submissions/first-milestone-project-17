# First Milestone Project


[Website](https://kilokilo12.github.io/first-milestone-project/)



## UX


### What is it?

This is a static website for a fictional new album release by a non-fictional British band [Kasabian](https://en.wikipedia.org/wiki/Kasabian "Kasabian Wiki"). It is created for fans of the band and all music lovers to enable them to listen to music, find information and upcoming tour dates on one page.

The link to the deployed website is [here](https://kilokilo12.github.io/first-milestone-project/)

### User Stories

* As a fan of Kasabian, I want to listen to their music without having to navigate through many links
* As a music lover I want to find relevant info easily
* As a concert-goer I like to find links to upcoming concerts 
* As an artist I like beautiful colour schemes and layouts


### Layout

The website is a single scrolling page, consisting of five separate areas: **Home**, **About**, **Music**, **Tour Dates** and **Contact**. It has fixed navigation links on top of the screen, making it easy to navigate between different parts of the page.

The wireframes for this website are stored on [Figma](https://www.figma.com/file/IL9Iy0zmTcOyDZGFOj1r6Cdo/Kasabian?node-id=0%3A1)



## Features


### Existing Features


* Landing page with a video background that plays automatically without sound, clearly visible button to go to music section to listen to the songs.
* Responsive navigation bar built using Bootstrap that is fully visible from any part of the web page and collapses into a hamburger on the top right hand side on devices with screen width that is smaller than 768px. 
* Social links on bottom right of the landing page that lead to the social media accounts of the band.
* *Back to top* button at the bottom right corner of every page, albeit home page, enabling users to easily go back to the landing page.
* **About** section with short information about the band, band facts and best quotes by two of the band members, there are also two photos in this section.
* **Media** section enables users to listen to three songs in full using HTML audio and provides links to songs lyrics, there is also a link to listen to more songs and to purchase albums.
* **Tour Dates** section with built-in widget connecting with bandsintown website and fixed background image behind Tour Dates section.
* Flexible Bootstrap 4 contact form in **Contact** section with data validation that gives user a success message on a separate page after submitting, providing a link to go back to home page.
* Footer with icon links to social media accounts of the band.
* All links open in a new tab, improving user experience.
* Smooth scrolling for better UX.
* Consistent colour scheme was used throughout the page, ensuring better user experience.


### Features yet to implement

* Link to purchase the new album
* Add a collapsible element to song lyrics to include whole songs
* Possibly sign up to newsletter



## Technologies Used

- [Bootstrap](https://getbootstrap.com/) - used to simplify code
- [Figma](https://www.figma.com/) - was used to create wireframes
- [jQuery](https://jquery.com/) - for Bootstrap and modal
- [Font Awesome](https://fontawesome.com/) - for social media icons and blockquotes
- [Google Fonts](https://fonts.google.com/) - used Poppins font
- [Visual Studio Code](https://code.visualstudio.com/) - for IDE and version control
- [GitHub](https://github.com/) to store the code and GitHub Pages to deploy it


### Languages
- [HTML](https://html.com/)
- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- A small [Javascript](https://www.javascript.com/) snippet to enable Back to Top button

The website was built using HTML5 and CSS3 with a simple framework by Bootstrap 4, using Bootstrap classes for [navbar](https://getbootstrap.com/docs/4.3/components/navbar/), [grid system](https://getbootstrap.com/docs/4.3/layout/grid/), [jumbotron](https://getbootstrap.com/docs/4.3/components/jumbotron/) and [contact form](https://getbootstrap.com/docs/4.3/components/forms/).

Tour Dates section was built using Bootstrap and a widget by [bandsintown](https://www.bandsintown.com/), allowing users to follow the automatically updated view of upcoming (and previous) tour dates.



## Testing

- Used HP Pavilion Laptop 15-ck0xx for developing and testing. 
- Developer tools were used extensively to test responsiveness of the page and debugging.
- Two different browsers were tested on - Google Chrome and Microsoft Edge.
- For tablet size testing used Samsung Tab A.
- For mobile functionality used Pocophone 1.
- Also on a numerous devices of friends and family.
- Tested HTML and CSS code with <https://validator.w3.org> and <http://www.css-validator.org/>.
- Tested different devices on <https://www.responsinator.com/>.


### Issues found during testing and solutions

During testing found following issues:
- Full screen video background was only showing left top corner on mobile devices. Decided to modify that and replace full screen with fixed width and height.
- The background video was taking quite long to load, after trying several different options it was cropped and compressed, black background was used for smoother transitioning.
- On mobile devices Bootstrap navbar expanded into top left hand side, changed that by adding a media query.
- Also on mobile devices, navbar items did not disappear when clicked on any link, solution found on this [page](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click) and jQuery script added to the end of script files.
- Fixed background image was cutting off heads on mobile devices, fixed using CSS.
- Bandsintown widget had in-built styling that had to be overridden by using `!important` values on respective attributes.
- Contact form was not giving users any feedback, decided to create a new file ["submit.html"](https://kilokilo12.github.io/first-milestone-project/submit.html) to accommodate this
- Was getting an error regarding favicon. Fixed that by creating an icon using <https://www.favicon-generator.org/>
- After restructuring the files the fixed background was not loading, fixed this by using relative file path.


### User stories

- User 1 - Used desktop site, all links were working.
- User 2 - Used the form in **Contact** section, tried to leave a field empty but received an error message. When all fields filled, was taken to a new page with 'Thank you for your message' on it.
- User 3 - As a fan of Kasabian found that the band facts and quotes in **About** section were entertaining, also the background video looked great once it loaded.
- User 4 - Looked at the page on a mobile, loved the colour scheme and usability but found the background video was a bit too small. Tried to send a message using contact form without a valid email address but received an error message. Form worked after email address was amended.
- User 5 - Found the page very easy to use on a mobile and all the links were working, opening in a new tab.
- User 6 - As a fan of the band I enjoyed listening to the songs and used the *Find lyrics* and *Listen to the whole albums* links to listen more and sing along. Would have liked to see the whole lyrics on the page.
- User 7 - used the **Tour Dates** section to check previous concert dates and navigated to [bandsintown](www.bandsintown.com) website to see more information about tour dates.



## Deployment

* Used Visual Studio Code for writing the code on the master branch, then added files to staging area and committed using VS Code Source Control.
* Created a public repository on GitHub and pushed my master branch regularly into the repository. 
* The project’s source file was published from GitHub repository to GitHub Pages using GitHub default settings via the master branch.
To do this:
 ..1. Go to <https://github.com/kilokilo12/first-milestone-project>
 ..2. Click Settings
 ..3. Under GitHub Pages select master branch in Source section as your publishing source
 ..4. Click Save

* In order to clone this code and run it locally:
..1. Select the 'Clone or download' link under the repository name.
..2. Copy the 'Clone with HTTPS' link
..3. In your IDE go to the location you want the cloned directory to be created 
..4. In the terminal of your IDE type `git clone https://github.com/kilokilo12/first-milestone-project.git`
To remove this GitHub repository, type `git remote rm origin` into your terminal.

Only master branch was used to develop this website.



## Credits


### Media

- All images were downloaded from <https://www.last.fm/>
- MP3 files purchased from [Google Play](https://play.google.com/store)
- Background video downloaded from <http://www.youtube.com/>


### Acknowledgements

* Youtube [video](https://youtu.be/V_lAhqLXT9A) by Drew Ryan for inspiration
* NME website for [quotes](https://www.nme.com/photos/kasabian-29-of-tom-and-serge-s-most-hilarious-boasts-1411450) and [facts](https://www.nme.com/photos/50-geeky-facts-you-might-not-know-about-kasabian-1404688)
* [Wikipedia](https://en.wikipedia.org/wiki/Kasabian) page for general info in the **About** section
* [W3Schools](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp) for implementing *Scroll To Top* button
* <https://www.favicon-generator.org/> to create a favicon

This website is for educational purpose.