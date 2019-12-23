# Signature Hamburger Bar 

This website is for the Hamburger bar "Signature". It's purpose is to help the visitors find all the information they need in the form of the menu, reservations and contact information, and to drive traffic and reservations for the owners.

## UX

![UX Example] (https://github.com/Lloldrin/Milestone-1/blob/master/assets/README%20images/UXshowcase.png)

### User Stories
 
New Guest: I want to get a feel for the restaurant and see the menu. I also want to make a reservation if it looks good. 

Repeat Guest: I want to be able to quickly make a reservation.

Owner: I want to drive reservations and make sure that people can find information about our food and skills. 

### Strategy
My goal was to make the site feel familiar but daring. Navigation should be intuitive and users should quickly find the information they need.

### Scope
I identified the two most important parts of a restaurant-site. The menu and the reservation form. Along with that you want to get a feel for the restaurant as well as have their contact information and social media links. 

### Structure 


## Skeleton
[Mobile Wireframe] (https://github.com/Lloldrin/Milestone-1/blob/master/assets/wireframes/WireframeMobile.jpg)

[Desktop Wireframe] (https://github.com/Lloldrin/Milestone-1/blob/master/assets/wireframes/WireframeDesktop.jpg)

### Surface
The Black/Orange/White colorscheme was chosen to invoke the feeling of burning coal and flame-grilled burgers. The Navigation is mainly in white to break of from the information. The use of pictures was meant to give the feeling of a hip restaurant that cares about the burgers. 

## Features


### Existing Features

**Navbar:** The navbar is taken from bootstrap and modified to show a hamburger instead of the normal 3 lines. The Logo is visible in the navbar on desktop but hidden on mobile to save screen real estate.

**Hero Image:** Shows a relevant quote and pushes the visitors to place a reservation.

**Menu:** The menu has a hover effect on desktop to highlight whatever menu-item the visitor is reading about.

**Reservation Form:** Styling of the form is made with bootstrap grid. It’s not functional as it’s not connected to a data base.

### Features Left to Implement

**Google Maps:** I wanted to add google maps functionality, but I did not have acces to their API.

## Technologies Used

**HTML**

**CSS** 

**Bootstrap** (https://getbootstrap.com/)
	This project uses bootstrap for styling, navbar and grid system

**JQuery** (https://jquery.com)
	This project uses jQuery as part of the callapse feature in the navigation bar

**Fontawesome** (https://fontawesome.com/)
	This project uses icons from fontawesome in the menu and as social media links

## Testing

The website has been tested by several users who have been given instructions to find errors and try all the links etc on the site. 
The links all either point to ID elements in the site or in the case of the social media links to the respective social media site. The Social media links all use a target=”_blank” to make sure that the user is taken to a new tab. 

The form is nonfunctional but if you try to enter an invalid email adress you will get an error message indicating that the user needs to enter a valid email adress. The other fields all have the ”required” attribute so that the restaurant will have all the neccessary information. When you enter your information and click the submit button the site will reload and your input will be lost.

The site have been tested in Chrome, Firefox and Safari as well as on an Google Pixel (gen1), Samsung (Galaxy S8) and an iPhone 10. 


## Deployment

The site is hosted on GitHub-Pages. It’s deployed using the master branch and will auto update when the site gets a new commit.
 
To run the site locally download the master branch along with the assets and run index.html 

## Credits

### Content

The text for ”Our Promise” and the Menu are originally written by me, Douglas Victor. 

The text for the testimonials are modified versions of reviews on www.yelp.com

### Photos
signatureHero - Photo by John Lorenz Tajonera on Unsplash

signaturePromise - Photo by Pablo Merchán Montes on Unsplash

### Acknowledgements

Getting the transparent overlay of the form background with a linear gradient was taken from : https://css-tricks.com/tinted-images-multiple-backgrounds
