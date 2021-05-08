# Sarah's Bakery

View the deployed site [here](https://annemarie293.github.io/sarahs-bakery/ "Sarah's Bakery")

## Project Introduction
Sarah recently lost her job due to the Covid-19 lockdown and has decided to take this as an opportunity to pursue her passion for baking into a career. She has been selling her baked goods at some local markets and created social media accounts to connect with her customers. She feels a website is now necessary to help grow her business, creating a branded image and attracting new customers. The website would provide a full list of all her available cakes and pastries, as well as information on which markets she will be selling at. She would use the website as a way to take custom orders and increase her sales.7

![image of site mock-ups on various screen sizes](/assets/images/readme-images/screens-mockup.jpeg "Mock Up")
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
 - Responsive and interactive navbar which collapses to hamburger menu with dropdown menu for smaller screen sizes
 - Large full width, viewport height hero image of Sarah’s cakes to introduce the user to her products.
 - Bio section with a picture of Sarah and information to introduce her and her business to customers.
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

### VALIDATION

W3C Markup Validator and W3C CSS Validator tools were used to check all code written for this project and validate that there were no syntax errors

 - [W3C Markup Validator](https://validator.w3.org/) : [View Results](https://github.com/annemarie293/sarahs-bakery/blob/3eba9aac62830f705c58d3d37bbb403a0611bf2f/assets/images/readme-images/css-validation.jpg)
 - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) : [View Results](https://github.com/annemarie293/sarahs-bakery/blob/3eba9aac62830f705c58d3d37bbb403a0611bf2f/assets/images/readme-images/css-validation.jpg)



 ### USER STORIES

 - **New Customer**

     1. As a new customer, I want to easily find about Sarah and her bakery

         1. On the first visit to the site, users are greeted by a large clear banner containing the logo and name of the bakery and the navigation bar at the top of the page (or dropdown menu log on mobile/tablets). A large hero image fills the viewport, showing the cakes made by Sarah and inviting the user to discover more.
         2. The user can then either scroll down to view the next section introducing Sarah and her company, or click the “About” link in the navbar to get to the same section.
         3. From here the user can choose to continue to scroll down through the sections showing Sarahs cakes, ordering info and Market locations, or they can jump to a preferred section from the navbar.
         4. The navbar always remains fixed at the top of the screen so that the user can jump around to their preferred section from any location on the page. The current section will be highlighted in the navbar


     2. As a new customer, I want to see what cakes Sarah has for Sale
          1. On visiting the site, the user can immediately jump to the “cakes” section from the navbar, or scroll down the page until they reach the cakes section.
          2. The cakes menu is displayed in a grid format, with a separate card for each cake containing a picture, cake name and description for each.
          3. The grid is displayed single stacked for mobile users (8*1 cards), 2 card width for tablets (4*2 cards) and 4 cards wide for laptops and larger screens (2*4 cards)
          4. On laptop/computer devices, each card changes to green to highlight the content while the mouse pointer hovers over it. The same effect is achieved on mobile/tablet screens by tapping the card.

     3. As a new customer, I want to find out where I can buy Sarah's cakes
         1. On visiting the site, the user can immediately jump to the “markets” section from the navbar, or scroll down the page until they reach the Markets section.
         2. The market info is displayed in a grid format, with a separate card for each market day, containing a market location and time for each.
         3. The grid is displayed single stacked for mobile users (4x1 cards), 2 card width for tablets (2x2 cards) and 4 cards wide for laptops and larger screens (1*4 cards)
         4. The market location changes color when hovered over to highlight the link, and the user can click this link to open google maps in a new tab showing the market location.
         5. For mobile/tablet users without hover capability, the map location icon helps to show that this is a link, and clicking on it will open the google maps app to show the market location.


 - **Existing customer**

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


### MANUAL TESTING OF ALL ELEMENTS

Testing was carried out by myself using Chrome DevTools while writing the code, and once deployed, friends and family helped to test the site on various screen sizes and web browsers.

#### Navbar

  - **Tests**

    1. Check that logo and "Sarahs Bakery" text are visible on all screen sizes, and resized accordingly.
       - **_Verified_**
    2. Check that navbar links are collapsed to hamburger menu for tablet and mobile screens.
       - **_Verified_**
    3. Check that dropdown menu of links is shown when hamburger menu is clicked on mobile and tablet.
       - **_Verified_**
    4. Check that the links change colour when hovered on all screen sizes.
       - **_Verified_**
    5. Click on each link to ensure the link goes to the correct section of the page.
       - **_Verified_**
    6. Check that navbar is fixed to the top of the screen on all screen sizes and devices.
       - **_Verified_**

  - **Bugs found during testing**

    1. The anchor link brought the user to the correct section, but the section heading text was covered by the Navbar.
       - **_Fix:_** I did not want to add a huge padding-top to each section on the page to always be visible, so solution was found on stack-overflow to use padding and negative margin along with :target pseudo class so that the padding would only be applied when clicking on the link. Note, this was not applied to #markets section as this section height was too small for the section heading to be ata the top od the page, so fix was not necessary.
       - **_Result:_** Section headings are clearly visibile beneath the navbar when clicked.

    2. The "Home" link was always highlighted in the active class as all links were targetted on the same page.
       - **_Fix:_** A simple JQUERY script was found on stackoverflow which changed each link to the active class when it was clicked.
       - **_Result:_** Each link changes to the highlighted active class when clicked.
       

#### Hero Image Section

  - **Tests**
     1. Hero Image is visible on all screen sizes, and covers the full width and height.
        - **_Verified_**
     2. Hero Image text section is visible on all screen sizes, located to the top left.
        - **_Verified_**

  - **Bugs found during testing**
     1. Friends and family testing the site following deployment noticed that the image was not the full height on all devices.
       - **_Fix:_** CSS img sizing was updated to 100 vh.
       - **_Result:_** Hero image displays full height on first visit to the page across all devices.   


#### About Section

  - **Tests**
     1. Check that section heading is visible at the top on all screensizes.
        - **_Verified_**
     2. On mobile and tablets, check that the bootstrap grid cols are stacked full width.
        - **_Verified_** 
     3. On mobile and tablets, check that the image is displayed above the text.
        - **_Verified_**  
     4. On large screens, check that the bootstrap grid cols are displayed side by side (text 2/3 width, img 1/3 width)
        - **_Verified_**
     5. On large screens, check that img is displayed to the right of the text.
        - **_Verified_** 

  - **Bugs found during testing**
    - No issues found.


#### Cakes Menu Section

  - **Tests**
     1. Check that section heading is visible at the top on all screensizes.
        - **_Verified_**
     2. Check that on mobile screens, the cake menu cards are displayed stacked full-width, 1*8 grid.
        - **_Verified_**
     3. Check that on tablets, the cake menu cards are displayed side by side, half width each, 2*4 grid.
        - **_Verified_** 
     4. Check that on large screens, the cake menu cards are displayed 4 across, 1/4 width each, 4*2 grid.
        - **_Verified_** 
     5. Check that on computer screens, the highlight effect is working, card changes to green with white text on hover.
        - **_Verified_**
     6. Check that on mobile and tablet screens, the highlight effect is working, card changes to green with white text on tap.
        - **_Verified_**  

  - **Bugs found during testing**

    1. The card deck was not responsive on tablet sizes. Cards showed single stacked on miobile devices, but then showed as 4 cards in each row for both mobile and larger screens.
       - **_Fix:_** Bootstrap "card" class was added directly to each column. This seemed to prevent the responsive grid from working properly. The "card" class was removed from the columns, and instead added to a new div nested in each column.
       - **_Result:_** The card grid is now showing fully responsive on all screen sizes as intended.

    2. When the card div was added to the column as in above fix, the cards were no longer the same height and were resposive to their content
       - **_Fix:_** The Bootstrap "h-100" class was added to each card to keep them all uniform height.
       - **_Result:_** Each card is now showing the same height, regardless of the amount of text contained inside.


#### Order Section

  - **Tests**

    Order Intro Section

     1. Check that section heading is visible at the top on all screensizes.
        - **_Verified_**
     2. On mobile and tablets, check that the bootstrap grid cols are stacked full width.
        - **_Verified_** 
     3. On mobile and tablets, check that the image is displayed above the text.
        - **_Verified_**  
     4. On large screens, check that the bootstrap grid cols are displayed side by side (text 2/3 width, img 1/3 width)
        - **_Verified_**
     5. On large screens, check that img is displayed to the left of the text.
        - **_Verified_** 

    Order Form Section
     1. Check that form displays full width on mobile devices.
        - **_Verified_**
     2. Check that form is displayed in center screen with intended offset cols on tablet and large screens.
        - **_Verified_** 
     3. Check that all placeholder text is diplaying correctly and clearly visible.
        - **_Verified_** 
     4. Check that required fields must be completed before form can be submitted (first name, last name, phone, email, occasion, cake type and date)
        - **_Verified_**    
     5. Check that all fields are mapped to the correct name when form is submitted.
        - **_Verified_** (Code institute formdump action used for this, results [here](/assets/images/readme-images/formdump-test.jfif). Form action has been removed for the final deploy as there is no current target for this info)

  - **Bugs found during testing**
     - No issues found


#### Markets Section

  - **Tests**
     1. Check that section heading is visbile at top on all screensizes.
        - **_Verified_**
     2. Check that on mobile screens, the market cards are displayed stacked full-width, 1*4 grid.
        - **_Verified_**
     3. Check that on tablets, the market cards are displayed side by side, half width each, 2*2 grid.
        - **_Verified_** 
     4. Check that on large screens, the market cards are displayed 4 across, 1/4 width each, 4*1 grid.
        - **_Verified_** 
     5. Check that the hover effect is working for the market location link - text changes to orange.
        - **_Verified_** 
     6. Check that the link for each market opens to a new tab on computer screens.
        - **_Verified_** 
     7. Check that the link for each market opens to the google maps app for mobiles and tablets.
        - **_Verified_** 
     8. Check that the link for each market opens to the relevant location in google maps.
        - **_Verified_** 


  - **Bugs found during testing**
     - No issues found


#### Footer

  - **Tests**
    1. Check that footer is visible at the bottom of the page.
        - **_Verified_** 
    2. Check that the logo and "Sarahs Bakery" text is visible on the left hand side and has responsive sizing on all screen sizes.
        - **_Verified_** 
    3. Check that the contact information below the logo section is clearly visible on all screen sizes.
        - **_Verified_** 
    4. Check that the social media icon links are visible on all screen sizes, and positioned to the right of the footer.
        - **_Verified_** 
    5. Check that the hover class is working on computer screens - icon should change to orange.
        - **_Verified_** 
    6. Check that the social media links open in a new tab.
        - **_Verified_** 
    7. Check that the social media links open to the correct site.
        - **_Verified_** 

  - **Bugs found during testing**
        - No issues found.

 
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

#### CODE

All code written by myself with the exception of:
 - [JQUERY script to change the current section link to active when the link target is on the same page](https://stackoverflow.com/a/23921579)
 - [CSS code so that padding is applied to top of sections when the link is clicked, allowing the section heading to be visible below the header](https://stackoverflow.com/a/51071591)
 - Bootstrap used for the collapsible navbar element, grid layout, card structure and form elements.


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
 