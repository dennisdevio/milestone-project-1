# The Golden Pretzel | Café and Bakery

This is the website for The Golden Pretzel | Café and Bakery. 
The purpose of this website is to increase
The Golden Pretzel's internet presence as part of being a competitive business and provide easily accessible information on their services to both new and regulars customers.

## Showcase
The live website can be found [here](https://tetrapak-dev.github.io/milestone-project-1/)

![desktop_showcase](https://github.com/tetrapak-dev/milestone-project-1/blob/master/assets/images/showcase_laptop.png)

## UX
My goal was to create an appealing website design and make it as accessible as possible by creating a user-friendly design that works smoothly on all device sizes.

### User Stories

#### First Time User Goals
- As a first time user I want to be able to get a great first impression of your business.
- As a first time user I want to find all information on your services easily.
- As a first time user I want to find all information on your services while on the go.
    
#### Returning User Goals
- As a returning user I want to know current special announcements.
- As a returning user I want to know changes to your menu.
- As a returning user I want to know changes to your opening hours.
- As a returning user I want to be able to easily find information on your social media.

### Wireframes
At first I planned on making five wireframes, one for each bootstrap breakpoint but it didn't feel meaningful so I decided to go with three. At first I was going to use Balsamiq for the wireframes but I turned out I couldn't because it's not available on Linux, which I am developing this project on. Therefore I decided to go with InVision instead.

- [InVision](https://www.invisionapp.com/) - The wireframes for this website can be found [here](https://dennischmielewski323696.invisionapp.com/freehand/The-Golden-Pretzel-XozP370FD)

### Structure
The website has one page divided into three distinct sections. The home section has a navigation bar with internal links to all different sections aswell as a clickable logo link. Below the navbar I implemented the Bootstrap carousel for showcasing the cafés images with a announcementb bar just below it. The about section further down provides information on the café itself and their passion for baking. The menu is a two-part menu with foods and drinks further divid into sub-sections. The contact information follows the same structure with the opening hours and address divided into two section aswell. At the bottom there are social media links to their social media pages. The menu collapses into a hamburger-button with fold down links on medium-size and small devices.

### Design
The website consists mainly of white color and a shade of yellow color to go with the name of "The Golden Pretzel". My idea was that the yellow color would draw users attention the most important parts of the page, that is why I have made the announcement bar, just below the pictures and the menu with the color yellow background aswell as the navigation bar and footer in the same color. The café's logo is a drawing of a pretzel to go with the theme, I feelt it was a cute and fun detail. The menu links at the top have a underline on hover, and the social media links at the bottom change color from grey to black on hover. The menus have their static underline respectively to draw the users attention to the menu.

## Features
- On entering the website there's an image carousel on display, showcasing images from the café. 
- A hamburger-button menu displayed on tablet and mobile screens.
- Responsive design between desktop screens and mobile screens.

#### Features Left to Implement
The following features will be implemented on a future release

- Adding an iFrame map to the location of the café.
- Creating a form for larger orders such as birthday parties and weddings.
- Adding another swedish version page to the site with a button to switch between the two.

## Technologies
The technologies utilized to build this website are

- [Gitpod](https://www.gitpod.io/) IDE for all code editing.
- [TinyPNG](https://tinypng.com/) for image compression to decrease load times of the website.
- [Unsplash](unsplash.com/) for all images used in the project. 
- [Google Fonts](https://fonts.google.com/) for all font styles.
- [Font Awesome](https://fontawesome.com/start) for social media icons.

### Languages 
- [HTML5](https://en.wikipedia.org/wiki/HTML5) HTML5 was used for structuring the basis of the website. 
- [CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3) CSS3 was used for the placement and styling of the HTML5 content. 

### Frameworks
- [Bootstrap 4.5.3](https://getbootstrap.com/docs/4.5/getting-started/introduction/) for building a responsive website.

### Libraries 
- [jQuery](https://jquery.com) to simplify DOM manipulation of the Bootstrap Carousel.

## Testing
Testing was done throughout the whole development process. I used Firefox Devtools extensively for debugging errors along the and before implementing new code to the website by using the boxmodel to see what needed to be done. When the website was nearly finished I used devtools to test how it would render on different mobile devices.
There were quite a few bugs along the process but I sorted out the majority of them.

- [Firefox DevTools](https://firefox-dev.tools/)

I used Lighthouse several times during the final stages of the testing process. At first I got results around 80% but I later implemented the changes suggested and got it almost to 100% in all areas. I added meta tags for SEO and improved all the links by adding aria-labels to them for accessibility, as well as improved the logo alt value. The biggest issue from the report was that the images were too big. This also caused problems with the carousel earlier, in retrospect I should have used smaller images for better results.

- [Lighthouse](https://developers.google.com/web/tools/lighthouse/) - results of the final report can be seen below.

![lighthouse_report](https://github.com/tetrapak-dev/milestone-project-1/blob/master/assets/images/Screenshot_2021-04-07%20Lighthouse%20Report%20Viewer.png)

- [W3C HTML Validator](https://validator.w3.org/) - was used two times throughout the process to improve testing results. 
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - was used two times throughout the process to improve testing results.

The website was tested on the following browsers on both latop and mobile devices.
- [Firefox Web Browser](https://www.mozilla.org/en-US/firefox/new/)
- [Chrome Web Browser](https://www.google.com/chrome/)
- [Opera Web Browser](https://www.opera.com/)
- [Edge Web Browser](https://www.microsoft.com/edge)

The website was tested on the following operating systems on laptop and desktop devices.
- [Android](https://www.android.com/)
- [Linux Mint](https://linuxmint.com/)
- [Windows 10](https://www.microsoft.com/software-download/windows10)

The website was manually tested on the following devices.

 - [Fairphone 3](https://www.fairphone.com/en/)
 - [Acer Swift 3 Laptop](https://www.acer.com/ac/en/US/content/series/swift3)
 - [Asus Desktop](https://www.asus.com/)

#### Bugs Fixed
- No hamburger button was showing at first.
- The carousel didn't fit att first.
- The carousel would not change pictures
- The underlines in the contact section was not showing as they do in the menu section so I decided not to go with them due to time constraints (will be implemented on a future release).

#### Bugs Left
- The carousel changes images automatically. I wanted to turn it of to improve user experience but I did not manage to turn it of within the time frame.
- Images files in the carousel were to large, so they are partially cut off on some mobile devices. This was discover through manual user testing on a Fairphone 3.
- Contact heading is not quite centered on all mobile devices. This too was discover during manual user testing on a Fairphone 3.
- Through Firefox Devtools mobile device testingI discovered that the heading in the navbar is cut off on Iphone 5.
- The paragraphs in the contact section are not quite vertically aligned with the menu lists above them larger screens. This was discover during manual testing on a Acer Laptop.

## Deployment

### Hosting Platform
A deployed version of the website is hosted on [GitHub Pages](https://pages.github.com/)

### Repository
This project reposity is hosted on [GitHub](https://github.com/) and can be found [here](https://github.com/tetrapak-dev/milestone-project-1)

## Credits
- [Stack Overflow](https://stackoverflow.com/)
- [W3C Schools](https://www.w3schools.com/)
- [Bootstrap Essentials](https://ajgreaves.github.io/bootstrap-grid-demo/index.html)

### Inspiration
I recieved inspiration for this project from a family member who wishes to one day open a café and bakery of her own.

### Acknowledgements
- Code Institute's Tutor Support and Slack community.
- My mentor [Akshat Garg](https://github.com/akshatnitd) for his advice and support.

#### This project was made as part of Code Institute's Full Stack Software Development Programme. /This is for educational purposes only.      Created by Dennis Chmielewski.