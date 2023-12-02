# La Citadelle
---
The website for La Citadelle was created to provide an online presence for a fine dining restaurant.
Users will be able to view La Citadelles opening times, book a table or arrange a private dining/event specific to thier needs. Its intended purpose was to build on a brand and attract and engage customers. The website is compatible on all devices and is easy to navigate with a minimalist approach. In addition they can view the restaurants social media pages and the menus before they visit the restaurant.

As you can see from the image below the website is compatible on all device screen sizes from the Galaxy Fold (280px screen width) and above.
![Amiresponsive image which shows website on different screen sizes](assets/images/readme-images/amiresponsive-image.png)

## Features

### Index.html page features

* **Navigation**
#### Navigation menu on devices with a screen width below 774px width
![Header screenshot showing main header and navigation menu when on mobile](assets/images/readme-images/header-mobile.png)

#### Navigation menu on devices with a screen width above 774px width
![Header screenshot showing main header and navigation menu when on desktop](assets/images/readme-images/header-desktop.png)

 * Featured underneath the main header, the navigation menu includes the following links:

    * **Home**, Which will revert back to the main page (index.html).
    * **About Us**, Which will allow the user to jump to the about us section of the homepage.
    * **Book Now**, wWich will enable the user to go to the bookings page (bookings.html). Here the user can review the events we can offer in additon to making a reservation.
    * **Menu**, Should the user which to view the lunch, dinner, dessert or wine menu they can do so.
    * **Contact**, This will enable the user the view our contact informaton for making a reservation.

* The navigation will respond to the users screen width as shown in the image above three horizontal lines will appear to decrease realestate occupation on the screen.
* The navigation menu lists are easy to understand and allow the user to understand the different sections of the website which allows for a greater user experience.

* **The Header**
* Featured at the top of the page, the header contains the main header on the far left of the screen which allows the user to reverts back to the homepage if clicked and the menu navigation (or menu icon) on the far right.

* **Image Scroller**
* Underneath the header the user can scroll through various images which expand depending on the screen size, this is compatible with touch screens, keyboard and mouse (using the scroller found below the image container).
![Image scroller which allows user to scroll through various images of the chefs, dinner and interior of the restaurant](assets/images/readme-images/image-scroll-container.png)

* **The About Us Section**
* The About us section provides brief but concise details regarding the fine dining restaurant.
![About Us section - which outlines what the restaurant offers](assets/images/readme-images/about-us.png)

* **Contact Us**
* The Contact us section provides an address, email and business telephone number in addition to a anchor/hyper link which directs the user to the reservations form should they wish to make a reservation.
![The Contact Us section which provides contact details and a link to the reservations form](assets/images/readme-images/contact-us.png)
![Anchor link that takes user back to the lunch, dinner, dessert and wine menu navigation](assets/images/readme-images/menu-navigation-anchor.png)

* **Opening Times**
* This provides opening and closing times should the user wish to book a table or visit the restaurant.
![Opening times of the restaurant](assets/images/readme-images/opening-times.png)

* **Social Media Links**
* The links at the bottom of the page direct the user to their chosen link
![Footer image which details address, contact information and links to social media pages](assets/images/readme-images/footer-with-social-media-links.png)

* **Footer Address, Telephone & Email of La Citadelle**
* The footer contains information of the business address including telephone and email details.


### Bookings.html page
* **Events & Private Dining**
* **Reservations Form**

### Menu.html page
    * The Menu page has a quick navigation anchor link for all four sections of the menu including lunch, dinner, dessert and wine menus.
![Lunch, dinner, desserts and wine menu](assets/images/readme-images/menu-navigation-for-menu.png)
    * In addition to the above there is also an anchor element found at the bottom of the lunch, dinner, dessert and wine menu that will allow the user to quickly scroll back up to the menu navigation as the menu is enlongated when on smaller screens.
![Anchor link found at the bottom of each menu to revert back to the menu navigation](assets/images/readme-images/menu-navigation-anchor.png)

* **Lunch Menu**
    * The lunch menu contains starters, mains, three course details in addition to allergy and intolerance advice. Furthermore infromation regarding VAT can be found. Its important to note the allergy and intolerance advice is shown at the bottom of the lunch, dinner and dessert menu. The description of the items are also available.
![Lunch, starters and mains menu](assets/images/readme-images/lunch-menu-starters-and-mains.png)

* **Dinner Menu**
    * The dinner menu contains starters, mains, three course details in addition to allergy and intolerance advice. Furthermore infromation regarding VAT can be found. The description of the items are also available.
![Dinner, starters menu](assets/images/readme-images/dinner-menu-starters-and-mains.png)

* **Dessert Menu**
    * The dessert menu contains starters, mains in addition to allergy and intolerance advice. Furthermore infromation regarding VAT can be found. The description of the items are also available.
![Dessert menu (1 of 2)](assets/images/readme-images/dessert-menu-part-1.png)
![Dessert menu (2 of 2)](assets/images/readme-images/dessert-menu-part-2.png)

* **Wine Menu**
    * The wine menu showcases all the wines available to compliment the customers meals, ranging from white, red, Italian and Spanish including the origin of some but more importantly the price. The description of the items are also available.
![Wine menu - White wines](assets/images/readme-images/wine-menu-white-wine.png)
![Wine menu - Red wines](assets/images/readme-images/wine-menu-red-wine.png)
![Wine menu - Italian wines](assets/images/readme-images/wine-menu-italian-wine.png)
![Wine menu - Spanish wines](assets/images/readme-images/wine-menu-spanish-wine.png)  

*Below is a table showing various actions performed on the website including the expected/desired outcome with the result on the final column.
### Testing
| Action                                                                                    |Expected                                                                                           | Result                                                 |
| :---------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------ | :----------------------------------------------------- |
| Load index.html page                                                                      | The Homepage should load                                                                          | Homepage loaded                                        |
| Load menu-html page                                                                       | The Menu page should load                                                                         | Menu page loaded                                       |
| Load bookins.html                                                                         | The Book now page should load                                                                     | Book now page loaded                                   |
| Click on the h1 logo                                                                      | The page should refresh if currently on the home page or divert user to the homepage if not       | Home page loaded                                       |
| Click on menu icon (hamburg) when on screens less than 774px width                        | The nav drop down menu should reveal all the nav options Home, About Us, Book Now, Menu, Contact  | Navigation menu dropped                                |
| Scroll images on scroll.container found underneath the header                             | The imagess move left to right with touch, keyboard or using scroller                             | Images scrolled - left to right                        |
| Click the CLICK HERE on the contact us section of the homepage                            | The bookings page should load where the user can complete the reservations form                   | Bookings page loaded                                   |
| Click the Facebook social media link found in the footer at the bottom of all html pages  | Facebook site should load                                                                         | Facebook loaded                                        |
| Click the X (formally known as Twitter) social media link found in the footer             | Twitter (X) site should load                                                                      | Twitter (X) loaded                                     |
| Click the Youtube social media link found in the footer at the bottom of all html pages   | Youtube site should load                                                                          | Youtube loaded                                         |
| Click the Instagram social media link found in the footer at the bottom of all html pages | Instagram siteshould load                                                                         | Instragram loaded                                      |
| Click About Us on the header (both desktop and mobile device)                             | The user should be directed to the About us section found on the homepage                         | Page scrolled to About us section                      |
| Click Book Now on the header (both desktop and mobile device)                             | The user should be directed to the Book Now page (bookings.html)                                  | Book now page loaded                                   |
| Click Menu on the header (both desktop and mobile device)                                 | The user should be directed to the Menu page (menu.html)                                          | Menu page loaded                                       |
| Click Contact on the header (both desktop and mobile device)                              | The user should be directed to the Contact us section found on the homepage                       | Page scrolled to Contact us section                    |
| Fill in the reservations form on the bookings.html                                        | The user will receive a confirmation of receipt and the details inputted                          | Received confirmation of receipt with details          |
| Fill in the reservations form on the bookings.html with invalid input                     | The user will receive a pop up notification to confirm error with input                           | Pop up message shown with prompt                       |
| Click the Lunch anchor at the top of the menu.html page                                   | The user will be redirected to the top of the Lunch Menu                                          | Redirected to Lunch menu                               |
| Click the Dinner anchor at the top of the menu.html page                                  | The user will be redirected to the top of the Dinner Menu                                         | Redirected to dinner menu                              |
| Click the Desserts anchor at the top of the menu.html page                                | The user will be redirected to the top of the Desserts Menu                                       | Redirected to dessert menu                             |
| Click the Wine anchor at the top of the menu.html page                                    | The user will be redirected to the top of the Wine Menu                                           | Redirected to wine menu                                |
| Click the BACK TO TOP anchor at the bottom of the lunch menu                              | The user should be directed to the top of the menu back to the menu navigation                    | Scrolled back up to menu navigation on top of the menu |
| Click the BACK TO TOP anchor at the bottom of the dinner menu                             | The user should be directed to the top of the menu back to the menu navigation                    | Scrolled back up to menu navigation on top of the menu |
| Click the BACK TO TOP anchor at the bottom of the desserts menu                           | The user should be directed to the top of the menu back to the menu navigation                    | Scrolled back up to menu navigation on top of the menu |
| Click the BACK TO TOP anchor at the bottom of the wine menu                               | The user should be directed to the top of the menu back to the menu navigation                    | Scrolled back up to menu navigation on top of the menu |
| Expand screen size bookings page                                                          | The background image should be revealed                                                           | Background image revealed                              |
| Expand screen size menu page                                                              | The background images should be revealed (1 for each menu - four in total                         | Background image revealed                              |


## Bugs

## Unfixed Bugs

## Validator Testing

## Deployment

## Credits
    * Used the footer seagment from Code Institute from the Love Running project - credits provided here and within the pages.

### Content
    *

### Media
    *

## 5trategy Plane
    Aiming to achieve and for whom?

## Scope Plane
    Features

## Structure Plane
How is the information structured and how is it loigcally grouped

## Skeleton Plane
    How will our information be presented and how will the information be featured

## Surface Plane
    What will the finished product look like


<!-- Images to add -->
<!-- index.html hompage -->


<!-- bookings.html page -->
![Events and private dining section which details various events that the restaurant can accommodate including customized menus and special occassions](assets/images/readme-images/reservations-section-events-and-private-dining.png)
![The reservation form allows user to book a table or an event](assets/images/readme-images/book-now-reservations-form-desktop-view.png)

<!-- menu.html page -->


<!-- testing -->
![Screenshot to illustrate a successful reservations form submission](assets/images/readme-images/form-submission.png)
![Screenshot showing html validator for the index.html page - no errors found](assets/images/readme-images/html-validator-index.html.png)
![Screenshot showing html validator for the menu.html page - no errors found](assets/images/readme-images/html-validator-menu.html.png)
![Screenshot showing html validator for the bookings.html page - no errors found](assets/images/readme-images/html-validator-bookings.html.png)
![Screenshot showing css validator for the style.css page - no errors found](assets/images/readme-images/css-validator-style.css.png)

![Screenshot from lighthouse report using developer tools for desktop version of index.html](assets/images/readme-images/lighthouse-index.html-desktop.png)
![Screenshot from lighthouse report using developer tools for mobile version of index.html](assets/images/readme-images/lighthouse-index.html-mobile.png)

![Screenshot from lighthouse report using developer tools for mobile version of menu.html](assets/images/readme-images/lighthouse-menu.html-mobile.png)
![Screenshot from lighthouse report using developer tools for desktop version of menu.html](assets/images/readme-images/lighthouse-menu.html-desktop.png)

![Screenshot from lighthouse report using developer tools for mobile version of bookings.html](assets/images/readme-images/lighthouse-bookings.html-mobile.png)
![Screenshot from lighthouse report using developer tools for desktop version of bookings.html](assets/images/readme-images/lighthouse-bookings.html-desktop.png)




<h2>Table of Contents</h2>

<ol>
<li>Introduction</li>
<li>About La Citadelle</li>
<li>Getting Started</li>
<li>Features</li>
<li>Menu</li>
<li>Reservations</li>
<li>Contact Information</li>
<li>Feedback and Support</li>
<li>Legal Information</li>
</ol>

<h3>1. Introduction</h3>

Welcome to La Citadelle Fine Dining Restaurant in London! This readme file provides essential information about our establishment, making reservations, and accessing our menu.

<h3>2. About La Citadelle</h3>

La Citadelle is a prestigious fine dining restaurant located in the heart of London. We are committed to delivering an exquisite culinary experience in an opulent and inviting setting. Our menu showcases a wide array of the finest dishes, skillfully prepared by our world-class chefs using the freshest, locally-sourced ingredients.

<h3>3. Getting Started</h3>

To start your journey with La Citadelle, you have several options:
Visit us: We are conveniently located at [Carlos Pl, London W1K 2AL].
Visit our website: LaCitadelle.co.uk
Make reservations: Contact us by phone at: [+44 20 4513 5208]

<h3>5. Features</h3>

La Citadelle offers an array of features and services, including:

<h3>Elegant dining rooms with a refined atmosphere</h3>

An extensive wine list curated by expert sommeliers
A private dining area for special occasions and events
Attentive and knowledgeable staff to cater to your needs
An array of delectable desserts and aperitifs
Seasonal and special tasting menus

<h3>5. Menu</h3>

Our ever-evolving menu is available on our website. It is regularly updated to reflect seasonal and chef's special creations. Whether you have a penchant for seafood or are a vegetarian, our menu caters to every palate, promising a memorable dining experience.

<h3>6. Reservations</h3>

We highly recommend making reservations in advance to secure your table at La Citadelle. You can reserve a table through the following channels:
<ul>
<li>Online reservation system on our website</li>
<li>By phone at [+44 20 4513 5208]</li>
<li>In person at our restaurant</li>
</ul>
  
<h3>7. Contact Information</h3>

For any inquiries or further information, please do not hesitate to get in touch with us:
<ul>
<li>Address: Carlos Pl, London W1K 2AL</li>
<li>Phone: +44 20 4513 5208</li>
<li>Email: Reservations@LaCitadelle.co.uk</li>
</ul>
  
<h3>8. Feedback and Support</h3>

We genuinely value your feedback and are dedicated to providing you with an exceptional dining experience. If you have any comments, suggestions, or require support, please feel free to reach out to us via email at Reservations@LaCitadelle.co.uk. Your input is invaluable, and we are committed to continuously enhancing our services.

<h3>9. Legal Information</h3>

Terms of Service: Please refer to our terms of service on our website.
Privacy Policy: For insights into our privacy practices, consult our privacy policy on our website.
Thank you for selecting La Citadelle Fine Dining Restaurant in London. We eagerly await the opportunity to serve you and create a memorable dining experience!
