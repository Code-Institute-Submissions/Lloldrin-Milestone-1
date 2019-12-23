# Signature Hamburger Bar 

This website is for the Hamburger bar "Signature". It's purpose is to help the visitors find all the information they need in the form of the menu, reservations and contact information, and to drive traffic and reservations for the owners.

## UX

![UX Example](https://github.com/Lloldrin/Milestone-1/blob/master/assets/README%20images/UXshowcase.png)

### User Stories
 
* New Guest: I want to get a feel for the restaurant and see the menu. I also want to make a reservation if it looks good. 

* Repeat Guest: I want to be able to quickly make a reservation.

* Owner: I want to drive reservations and make sure that people can find information about our food and skills. 

### Strategy
My goal was to make the site feel familiar but daring. Navigation should be intuitive and users should quickly find the information they need. 

### Scope
I identified the two most important parts of a restaurant-site. The menu and the reservation form. Along with that you want to get a feel for the restaurant as well as have their contact information and social media links. 

This satisfies the needs of guests as well as the owner in a simple and clear manner.

### Structure 

To simplify navigation I kept the site as a single page. All of the information fit together and it made sense to have it gathered. I wanted to make it easy to reach the reservation form by having navigation options there directly. But I also wanted to make sure that customers would see the story of the restaurant by having it right after the hero image. 

## Skeleton
[Mobile Wireframe](https://github.com/Lloldrin/Milestone-1/blob/master/assets/wireframes/WireframeMobile.jpg)

[Desktop Wireframe](https://github.com/Lloldrin/Milestone-1/blob/master/assets/wireframes/WireframeDesktop.jpg)

### Surface
The Black/Orange/White colorscheme was chosen to invoke the feeling of burning coal and flame-grilled burgers. The Navigation is mainly in white to break of from the information. The use of pictures was meant to give the feeling of a hip restaurant that cares about the burgers. 

## Features

### Existing Features

* **Tab Icon:** On desktop the browser tab-icon will be the same as the hamburger menu icon.
* **Navbar:** The navbar is taken from bootstrap and modified to show a hamburger instead of the normal 3 lines. 
    * The Logo is visible in the navbar on desktop but hidden on mobile to save screen real estate.

* **Hero Image:** Shows a relevant quote and pushes the visitors to place a reservation.

* **Menu:** The menu has a hover effect on desktop to highlight whatever menu-item the visitor is reading about.

* **Reservation Form:** Styling of the form is made with bootstrap grid. It’s not functional as it’s not connected to a data base. 
    * The Reservation form will open a modal to verify that the reservation has gone through.

### Features Left to Implement

* **Google Maps:** I wanted to add google maps functionality, but I did not have acces to their API.

* **Add functionality to the form:** make sure that the reservation form acually works.
    * Add a database to the form to make sure that only available dates/times are shown.

## Technologies Used
 
* **HTML**
* **CSS** 
* **[Bootstrap](https://getbootstrap.com/)**
	* This project uses bootstrap for styling, navbar and grid system
* **[jQuery](https://jquery.com)** 
	* This project uses jQuery as part of the collapse feature in the navigation bar
* **[Fontawesome](https://fontawesome.com/)** 
	* This project uses icons from fontawesome in the menu and as social media links
* **Visual Studio Code** main IDE used for the site
* **[ami.responsivedesign.is](http://ami.responsivedesign.is/)**
    * To create the UX example for the readme and to test the responsiveness of the design
	

## Testing

* The website has been tested by several users who have been given instructions to find errors and try all the links etc on the site. 
   * The links all either point to ID elements in the site or in the case of the social media links to the respective social media site. 
   * The Social media links all use a target=”_blank” to make sure that the user is taken to a new tab. 
   
   
* The form is nonfunctional. 
    * If you try to enter an invalid email adress you will get an error message indicating that the user needs to enter a valid email adress. 
    * The phone field is set to type="numbers" and will only accept numbers as input. I did look into using a type="tel" with a required pattern, but this introduced unnessesary complications for the users and led to a bad user experience. 
    * First name, last name, phone and email all have the ”required” attribute so that the restaurant will have all the neccessary information. 
    * When you enter your information and click the submit a modal will open to confirm that your reservation has been accepted.

### Browsers 
The site have been tested in:
* Desktop
    *  Chrome 
    * Firefox 
    * Safari
* Mobile
    * Google Pixel gen1
        * Chrome
        * DuckDuckGo
    * Samsung Galaxy S8 
        * Chrome
    * iPhone 10 
        * Safari    


## Deployment

The site is hosted on GitHub-Pages. 

* To deploy the site a GitHub repository was created [here](https://github.com/Lloldrin/Milestone-1)
* GitHub pages was used to deploy the site. 
    * A guide on how this is done can be accessed [here](https://pages.github.com/)
* The site uses the Master branch of the repository
    * It will update automatically with new commits to the master branch
* To ensure that GitHub pages will read the fire correctly the main page must be named index.html 
 
To run the site locally
1. In your terminal, go to a folder you want to save the project in.
2. Make sure you have git installed and then, to download the project, in the terminal run: 
     `git clone https://github.com/Lloldrin/Milestone-1.git` 
3. The index.html file and README.md files are in the main project folder, the assets are in their respective folders.
4. To run the site open the index.html in a browser to view the site locally, or open it in an IDE to edit the code. 

## Credits

### Content

### Text
The text for ”Our Promise” and the Menu are originally written by me, Douglas Victor. 

The text for the testimonials are modified versions of reviews on www.yelp.com

### Photos
signatureHero - Photo by John Lorenz Tajonera on [Unsplash](https://unsplash.com/)

signaturePromise - Photo by Pablo Merchán Montes on [Unsplash](https://unsplash.com/)

### Acknowledgements
Getting the transparent overlay of the form background with a linear gradient was taken from: https://css-tricks.com/tinted-images-multiple-backgrounds
