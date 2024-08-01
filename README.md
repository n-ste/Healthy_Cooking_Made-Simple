# Healthy Cooking Made Simple!

## Contents

* [User Experience](#user-experience)

* [Design](#design)
  * [Typography](#typography)
  * [Colour Scheme](#colour-scheme)
  * [Wireframes](#wireframes)
  * [Imagery](#imagery)
  * [Features](#features)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Frameworks and Libraries](#frameworks-and-libraries)

* [Deployment and Local Environment](#deployment-and-local-environment)
  * [Deployment](#deployment)
  * [Local Environment](#local-environment)

* [Testing](#testing)
  * [HTML Validation](#html-validation)
  * [CSS Validation](#css-validation)
  * [Bugs](#bugs)
  * [Resolutions](#resolutions)
  * [Known Bugs](#known-bugs)
  * [Home Page](#home-page)
  * [Breakfast Recipes Page](#breakfast-recipes-page)
  * [Lunch Recipes Page](#lunch-recipes-page)
  * [Dinner Recipes Page](#dinner-recipes-page)

* [Credits](#credits)
  * [Code](#code)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgements](#acknowledgements)

- - -

## User Experience

* In this project I've created a recipe website, this purpose is for users to be able to make healthy meals cooked from the comfort of their home without having to decipher difficult recipes.

* I've created four pages, on the home page the user will find a summary of what the website is for with a few tips and an optional newsletter they can sign up to so they can remain up to date on the latest recipes.

- - -

## Design

## Typography

I carefully chose two fonts for this project as I didn't want to use too many and make the project look cluttered, I imported these to my CSS file from Google Fonts.

* For the title, headings and expand/hide buttons for the recipe instructions and newsletter I used the font Kanit, in weight 700.

![Kanit 700](docs/fonts/kanit-700.jpg)

* For the main body paragraphs and navigation links I used Montserrat, in its standard weight of 400.

![Montserrat 400](docs/fonts/montserrat-400.jpg)

## Colour Scheme

Like with the fonts I didn't want to have too many colours in my project as I thought this could be quite distracting with the amount of images I've got displayed on the web page. I chose to use 5 different colours for separate sections of the page.

* For the header and footer I decided to use #B1CC74 to stand out against the other colours selected and be one of the first things the user sees.

* When it came to the background colour for the body element I wanted to use a colour to compliment the footer but not be too similar and I settled on #E8FCC2 which came out as a lighter green but not too similar to that of the header and footer section.

* As for the background colours for the paragraph sections in the page I chose to use a darker colour of #829399 to make it really stand out again the white font colour I chose, and further complimented this by added another even darker colour of #545F66 for the background of their respective headings.

* I opted to have a white font colour as I found this provided a great contrast to the header, footer and paragraph section background colours.

* The final colour I selected was always going to be a light blue which I only used to provide a border to the bottom of the header, and paragraph sections and the top of the footer for for this I chose #D0F4EA.
![Website Colour Scheme](docs/color-scheme/colour-scheme.jpg)

## Wireframes

* To give myself an idea of how I'd like the website to look I produced wireframes through the use of [Balsamiq](https://www.balsamiq.com), this allowed me to visualise what I wanted the website to look like before it was created and prompted me to style it accordingly.

* [Mobile Webpages](https://github.com/n-ste/Healthy_Cooking_Made-Simple/blob/main/docs/wireframes/mobile-wireframes.png)
* [Tablet Webpages](https://github.com/n-ste/Healthy_Cooking_Made-Simple/blob/main/docs/wireframes/tablet-wireframes.png)
* [Laptop Webpages](https://github.com/n-ste/Healthy_Cooking_Made-Simple/blob/main/docs/wireframes/laptop-wireframes.png)
* [Desktop Webpages](https://github.com/n-ste/Healthy_Cooking_Made-Simple/blob/main/docs/wireframes/desktop-wireframes.png)

### Imagery

* All images on my website including hero images and recipe images have been taken from [BBC Food](https://www.bbc.co.uk/food), individual images will be referenced in the credits section.

### Features

* Navigation Menu

  * When I started working on this project I knew that I wanted to create several different pages opposed to using a single-scrolling page.

  * Every page will have the same format and I started this by incorporating a navigation menu which will include the links to the other pages in my project.

* [Navigation Menu for Mobiles - Image](docs/navigation/mobile-nav.png)

  * For the navigation menu I decided to make this as responsive as I could due to the limited screen size and to prevent things from looking too cluttered. I started doing this by including a hamburger dropdown menu for smaller devices and positioning it on the far right of the screen.

    * This was done by using a checkbox and label, then in CSS I was able to hide the checkbox and make it so when you clicked it would display and hide the navigation menu.

  * Another choice I made when it came to the navigation menu was to have an active class on the page the user was currently visiting.

    * I did this by styling this class on CSS to have inverted colours and display it as a button.

  * I also adding some styling to the links for when they're hovered over, this was only a simple change and I did this by providing a bottom border to the link the user was hovering over in a contrasting white colour.

* [Navigation Menu for Tablets - Image](docs/navigation/tablet-nav.png)

* [Navigation Menu for Laptops - Image](docs/navigation/laptop-nav.png)

* When it came to the styling for the navigation menu on tablet and laptop size screens I decided to remove the hamburger icon and display the page links as we've got more space on these displays.

  * This was done by displaying the navigation toggle on the tablet breakpoint as 'none'.

* [Navigation Menu for Desktops - Image](docs/navigation/desktop-nav.png)

* For styling the navigation menu for desktop screens I decided to have this displayed on the left hand side of the screen so it could easily be differentiated from the way it was displayed on tablets and laptops.

* Footer
  * When it came to creating the footer I wanted this to appear the same on all devices, the only change that I made was adjusting the height depending on the screen size.

  * The only information provided on the footer is the links to our social media pages and I added these through the use of an unordered list.

  * [Mobile Footer - Image](docs/footer/mobile-footer.png)
  * [Tablet Footer - Image](docs/footer/tablet%20-%20footer.png)
  * [Laptop Footer - Image](docs/footer/laptop-footer.png)
  * [Desktop Footer - Image](docs/footer/desktop-footer.png)

* Page Layout
  * The layout of the page depends on the screen size you're viewing it on. Because I wanted to make the site as adaptable as possible I made it so the layout would change for each device type you view it on.
  
  * For mobiles I made the content display vertically to avoid the user having to scroll from left to right to view all the content on the screen.

  * But when it came to creating the design for bigger devices I wanted to display the content on the screen differently and I decided to do this by using a flexbox model so the items would display differently depending on the screen size. Instead of the sections displaying above eachother, they would display to the side.

  * I also adjusted the margin and padding size on the different breakpoints so that there would be more free space depending on the device the user was viewing the website on.

  * [Page Layout for Mobile - Image](docs/layout/mobile-layout.png)
  * [Page Layout for Tablet - Image](docs/layout/tablet-layout.png)
  * [Page Layout for Laptop - Image](docs/layout/laptop-layout.png)
  * [Page Layout for Desktop - Image](docs/layout/desktop-layout.png)

* Home
* Breakfast Recipe Page
* Lunch Recipe Page
* Dinner Recipe Page

### Accessibility

## Technologies Used

### Languages

This website was built using HTML and styled with CSS.

### Frameworks and Libraries

* Gitpod
* Github - Used to store and build my repository and to deploy my website.
* Google Developer Tools - To allow me to find out what might be preventing the bugs in my code.
* Google Fonts - I used the fonts 'Kanit', and 'Montserrat'.
* Balsamiq - I used Balsamiq to produce wideframes for my website and give me an idea of what might work and what might not.
* Font Awesome - Font Awesome was used to download the icons for my navigation and social media links.

## Deployment and Local Environment

### Deployment

### Local Environment

## Testing

### HTML Validation

### CSS Validation

### Bugs

### Resolutions

### Known Bugs

### Home Page

### Breakfast Recipes Page

### Lunch Recipes Page

### Dinner Recipes Page

## Credits

### Code

### Content

### Media

### Acknowledgements