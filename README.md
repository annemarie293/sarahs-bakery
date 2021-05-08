# Sarah's Bakery

View the deployed site [here](https://annemarie293.github.io/sarahs-bakery/ "Sarah's Bakery")

## Project Introduction
Sarah recently lost her job due to the Covid-19 lockdown and has decided to take this as an opportunity to pursue her passion for baking into a career. She has been selling her baked goods at some local markets and created social media accounts to connect with her customers. She feels a website is now necessary to help grow her business, creating a branded image and attracting new customers. The website would provide a full list of all her available cakes and pastries, as well as information on which markets she will be selling at. She would use the website as a way to take custom orders and increase her sales.7

![image of site mock-ups on various screen sizes](https://github.com/annemarie293/sarahs-bakery/blob/3eba9aac62830f705c58d3d37bbb403a0611bf2f/assets/images/readme-images/screens-mockup.jpeg "Mock Up")
___

## **User Experience (UX)**

###  STRATEGY
 - **Customer Stories**

   - New Customer
     1. As a new customer, I want to easily find about Sarah and her bakery
     2. As a new customer, I want to see what cakes Sarah has for Sale
     3. As a new customer, I want to find out where I can buy the cakes

   - Existing customer
     1. As an existing customer, I want to keep checking on the latest weekly menu
     2. As an existing customer, I want to place a custom order for an occasion cake


### DESIGN


 - **Colour Scheme**

   - The site uses complementary shades of golden orange, green and off-white, these are natural earth tones to reflect fresh homemade baking and not overpower the images which should stand out. Color palette inspiration take from this [image](https://i.pinimg.com/originals/5c/e5/21/5ce52102a139487bf5c0549da681688c.jpg) 
  The navbar and footer are in green with off-white font, and each section is plotted in different colour combinations to differentiate them.


 - **Font**

   - An elegant classic type front, Cormorant Garamond from google fonts has been used for this site, and sans serif is the backup font.


- **Images**

  - All images taken from open source sites. The large hero image was chosen to complement the colour scheme of the site and act as a bright invitation to keep scrolling and learn more.


### WIREFRAMES


  - [Wireframe for home page](https://github.com/annemarie293/sarahs-bakery/blob/master/assets/images/wireframes/Wireframe-home.png)

  - [Wireframe for Cakes menu page](https://github.com/annemarie293/sarahs-bakery/blob/master/assets/images/wireframes/Wireframe-our%20cakes.png)

  - [Wireframe for custom order page](https://github.com/annemarie293/sarahs-bakery/blob/master/assets/images/wireframes/Wireframe-custom%20orders.png)

  - [Wireframe for location page](https://github.com/annemarie293/sarahs-bakery/blob/master/assets/images/wireframes/Wireframe-find%20us.png)

    - The wireframes were a rough mock-up to kick off the project, and some small design elements changed as the project progressed and following discussions with my mentor.
    - The main change was to have all the different sections included in one single scrolling page rather than a separate page for each section.

___

## **Features**

###  CURRENT FEATURES

 - Single scrolling page to allow for a single loading time when opening the page, and geared towards improved mobile user experience (no need to switch pages or tabs)
 - Full width header containing navbar links to all sections of the page. This is fixed to the top of the page so it is always possible to navigate to another section from any position on the page.
 - Responsive navbar which collapses to hamburger icon with dropdown menu for smaller screen sizes
 - Large full width, viewport height hero image of Sarah’s cakes to introduce the user to her products.
 - Listing of all the available cakes in a responsive grid format for all screen sizes
 - Order form which can be submitted to request a custom cake order
 - Listing of all market locations in a responsive grid format for all screen sizes, and links to google map locations of each market.
 - Footer with contact info and links to social media sites.
 - Site is fully responsive (using bootstrap) to adapt to all display sizes - mobile tablets and large monitors/laptop screens.


### FUTURE FEATURES TO INCLUDE

 - Adapt the cakes menu into an ecommerce section allowing customers to order all cakes online

 ____

 ## **Technologies Used**

 ### LANGUAGES

  - [Html5](https://en.wikipedia.org/wiki/HTML5)
  - [CSS3](https://en.wikipedia.org/wiki/CSS)

 ### FRAMEWORKS, LIBRARIES AND TOOLS USED

  - [Bootstrap v4.6.0](https://getbootstrap.com/)
    - Bootstrap was used for navbar, grid layout, card layout,form structure responsive layout, margins, padding etc on all screen sizes.

  - [JQuery](https://jquery.com/)
    - The project uses JQuery script to add active class to the nav-links when the target is on the same page.

  - [Gitpod](https://www.gitpod.io/)
    - Code was written in Gitpod, and version control was managed by commit and push to GitHub.

  - [GitHub](https://github.com/)
    - Used to store the project repository and deploy the final website.

  - [Font Awesome](https://fontawesome.com/)
    - Used to display social media and map location icons.

  - [Google Fonts](https://fonts.google.com/)
    - Used to import the Cormorant Garamond font used throughout the site.

  - [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
    - Used for testing code output, especially to view various display sizes during the site creation.

  - [Balsamiq](https://balsamiq.com/)
    - Wireframes were created using the balsamiq app.

  - [JPEGmini Pro](https://www.jpegmini.com/)
    - Used to reduce file size of images while preserving quality, to improve page loading times.         

  - [Wix Logo Maker](https://www.wix.com/logo/maker)
    - Used to create the logo for Sarah’s bakery.

   ___

## **Testing**

#### VALIDATION

W3C Markup Validator and W3C CSS Validator tools were used to check all code written for this project and validate that there were no syntax errors

 - [W3C Markup Validator](https://validator.w3.org/) : [View Results](https://github.com/annemarie293/sarahs-bakery/blob/3eba9aac62830f705c58d3d37bbb403a0611bf2f/assets/images/readme-images/css-validation.jpg)
 - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) : [View Results](https://github.com/annemarie293/sarahs-bakery/blob/3eba9aac62830f705c58d3d37bbb403a0611bf2f/assets/images/readme-images/css-validation.jpg)



 ### USER STORIES

 - New Customer
     1. As a new customer, I want to easily find about Sarah and her bakery

         1. On the first visit to the site, users are greeted by a large clear banner containing the logo and name of the bakery and the navigation bar at the top of the page (or dropdown menu log on mobile/tablets). A large hero image fills the viewport, showing the cakes made by Sarah and inviting the user to discover more.
         2. The user can then either scroll down to view the next section introducing Sarah and her company, or click the “About” link in the navbar to get to the same section.
         3. From here the user can choose to continue to scroll down through the sections showing Sarahs cakes, ordering info and Market locations, or they can jump to a preferred section from the navbar.
         4. The navbar always remains fixed at the top of the screen so that the user can jump around to their preferred section from any location on the page. The current section will be highlighted in the navbar


     2. As a new customer, I want to see what cakes Sarah has for Sale
          1. On visiting the site, the user can immediately jump to the “cakes” section from the navbar, or scroll down the page until they reach the cakes section.
          2. The cakes menu is displayed in a grid format, with a separate card for each cake containing a picture, cake name and description for each.
          3. The grid is displayed single stacked for mobile users (8x1 cards), 2 card width for tablets (4*2 cards) and 4 cards wide for laptops and larger screens (2*4 cards)
          4. On laptop/computer devices, each card changes to green to highlight the content while the mouse pointer hovers over it. The same effect is achieved on mobile/tablet screens by tapping the card.

     3. As a new customer, I want to find out where I can buy Sarah's cakes
         1. On visiting the site, the user can immediately jump to the “markets” section from the navbar, or scroll down the page until they reach the Markets section.
         2. The market info is displayed in a grid format, with a separate card for each market day, containing a market location and time for each.
         3. The grid is displayed single stacked for mobile users (4x1 cards), 2 card width for tablets (2x2 cards) and 4 cards wide for laptops and larger screens (1*4 cards)
         4. The market location changes color when hovered over to highlight the link, and the user can click this link to open google maps in a new tab showing the market location.
         5. For mobile/tablet users without hover capability, the map location icon helps to show that this is a link, and clicking on it will open the google maps app to show the market location.


 - Existing customer
     1. As an existing customer, I want to keep checking on the latest weekly menu
         1. On visiting the site, the user can immediately jump to the “cakes” section from the navbar, or scroll down the page until they reach the cakes section.
         2. The cakes menu is displayed in a grid format, with a separate card for each cake containing a picture, cake name and description for each.
         3. The grid is displayed single stacked for mobile users (8x1 cards), 2 card width for tablets (4*2 cards) and 4 cards wide for laptops and larger screens (2*4 cards)
         4. On laptop/computer devices, each card changes to green to highlight the content while the mouse pointer hovers over it. The same effect is achieved on mobile/tablet screens by tapping the card


     2. As an existing customer, I want to place a custom order for an occasion cake 
         1. On visiting the site, the user can immediately jump to the “order” section from the navbar, or scroll down the page until they reach the order section.
         2. The user can see a collage of some samples of Sarahs special occasion cakes and read about how to order.
         3. The user can complete the form with contact details and details on the occasion and type of cake required.
         4. The user will not be able to submit the form until all fields (except for additional information textbox) are completed.

___

## **Deployment**

#### Deployed using GitHub pages

- **Instructions**
  1. Open the [repository](https://github.com/annemarie293/sarahs-bakery)
  2. Click on “settings” on the repository menu across the top of the page
  3. Scroll down until you find the “pages” button on the left hand menu
  4. Under the “Source” section, click the dropdown currently showing “None” and choose “master branch”, then save.
  5. The page will refresh and an alert is seen informing that the page is ready to be published along with a link to the site.


#### FORKING THE REPOSITORY

- **Instructions**
  1. Open the [repository](https://github.com/annemarie293/sarahs-bakery)
  2. Click on the “fork” button at the top right hand side of the page, just below the navbar.
  3. A copy of the original repository will be created to your own GitHub account.


#### CLONING THE REPOSITORY

- **Instructions**
  1. Open the [repository](https://github.com/annemarie293/sarahs-bakery)
  2. Click on the “code” button to the left of the green “Gitpod” button.
  3. To clone the repository using HTTPS, under "Clone with HTTPS", click the clipboard icon. 
  4. To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click the clipboard icon . 
  5. To clone a repository using GitHub CLI, click Use GitHub CLI, then click the clipboard icon.
  6. Open Git Bash.
  7. Change the current working directory to the location where you want the cloned directory.
  8. Type `git clone`, and then paste the URL you copied earlier.

   ```
   $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
   ```

  9. Press Enter to create your local clone.

  ```
  $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
  > Cloning into `Spoon-Knife`...
  > remote: Counting objects: 10, done.
  > remote: Compressing objects: 100% (8/8), done.
  > remove: Total 10 (delta 1), reused 10 (delta 1)
  > Unpacking objects: 100% (10/10), done.
  ```
  10. For more detailed info on this process please click [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

___

## **Credits**

#### CONTENT
  - The text content for this site was all written by myself, Anne Marie Murphy.


#### MEDIA
- **The photos used in this site were obtained from below free image sites:**
    - [Hero Image](https://www.pexels.com/photo/baked-cake-with-candies-on-top-709841/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)
    - ["Sarah" Picture](https://www.pexels.com/photo/content-housewife-cutting-delicious-pie-in-garden-6210835/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)
    - [Lemon Cake](https://unsplash.com/photos/-Qe0rpF2ThY)
    - [Lemon Tart](https://unsplash.com/photos/lD0JFJDXBfQ)
    - [Carrot Cake](https://unsplash.com/photos/OXQALgjpwkc)
    - [Cheesecake](https://www.pexels.com/photo/white-cake-with-sliced-strawberries-and-blueberries-on-top-3791088/)
    - [Brownies](https://www.pexels.com/photo/close-up-photo-of-stacked-brownies-on-chopping-board-2067396/)
    - [Fruit Cake](https://www.pexels.com/photo/white-icing-covered-cake-in-bokeh-photography-1721932/)
    - [Chocolate Cake](https://www.rawpixel.com/image/415801/homemade-chocolate-cake)
    - [Cupcakes](https://www.pexels.com/photo/cupcakes-with-white-icing-on-top-4099124/)
    - [PicsArt collage](https://picsart.com/u/otqm0n99q_rxk3j2cs0x)


#### ACKNOWLEDGEMENTS

   - I received inspiration for this project from our course material, and help with issues from the below resources:
     - [W3schools](https://www.w3schools.com/)
     - [Stackoverlfow](https://stackoverflow.com/)
     - [CSS-Tricks](https://css-tricks.com/)
     - [Mozilla developper](https://developer.mozilla.org/en-US/) 
     - Code Institute slack channel

   - Thanks also to my mentor Rahul Lakhanpal for all his help and support throughout this project. 
 