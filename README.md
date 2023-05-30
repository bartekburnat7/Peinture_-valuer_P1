# __Peinture Évaluer__

https://bartekburnat7.github.io/Peinture_Evaluer_P1/

### __Target Audience__
Peinture Évaluer is a website made for collectors that are looking to evaluate their artwork so that they get an accurate price of their collection or a piece of artwork they are trying to sell.

### __Approach__
I decieded to make the website a one page layout to make it as basic and simple to use as possible, as most artwork collectors are older folk and arent as tech savy as the younger population. This also creates a fast and enjoyable UI expiernce and increases the chances of the user comming back.

On the website the user will be able to find out about the business's history and have the option to choose between the three services provided in the "Pricing" section. There is a large contact section where you will be able to type in your personal details and select what type of item is in question and book a time to discuss the deal.

![Am I Responsive Test](/assets/images/WebsiteForProjectamiresponsive.JPG)

## __Features__

- __Navigation__
    - The navigation bar at the top of the page has two sections, the title which brings you to the top of the page when clicked and the menu with buttons that you can jump to each section of the website.
    - The navigation bar follows the user when they scroll so that it is easy to jump to each section from any part of the website.
    - New users that never used the website can use the navigation bar to easily find the section of interest easily without scrolling through the page.
    ![Navigation Bar](/assets/images/navbar.PNG)

- __Heading__
    - The main hero area has a large image of a painting to signify that the webiste and company does indeed specialise in artwork and can catch the eye of new users looking for this specific service.
    - The container on top of the image tells the user what the company specialises in, the box also contains a button that links to the contact section so that new user can quickly skip to the contact section and quickly get in touch with the business rasing the chances of closing a deal with a client.
    ![Hero Image](/assets/images/READMEheroimage.JPG)

- __About Us__
    - The "About Us" section explains the business's history and what country and city they are based in. It informs the user about who runs the company and what qualities the company can bring to the client, which helps new users decide on which service to use.
    ![About Us](/assets/images/aboutus.PNG)

- __Pricing__
    - The Pricing section displays all the options that the company provides.
    - Each option has a list of features that come with the given service and displays the greyed out features that are not included in that option, this gives a user a choice if they would rather not go for the most expensive option.
    - The business option has a purple gradient in the background to attract clients attention and make the top option stand out.
    ![Pricing](/assets/images/pricing.JPG)

- __Contact Us__
    - The contact section is where the user can contact the company throught the website to book a consultation or discuss
    what service the client should opt for.
    - The form validates if all fields are filled out or selected and checks if the right email format was used and all areas are filled in, otherwise the form will inform the user what the error is and wont send the form.
    - Each field when selected will be highlighted, this is implemented so that users can clearly see what input area they are currently typing into and makes the process easier.
    ![Contact](/assets/images/contactus.JPG)

- __Footer__
    - The footer contains "Quick Links" if the user decides they would like to go back to any section of the page they have passed, this makes finding any part of the website effortless and creates an enjoyable user experience. 
    - Extra contact information like phone number or direct email address are also included, as some users may prefer to get in touch directly with the company staff, instead of using the "Contact Us" section.
    ![Am I Responsive Test](/assets/images/footer.PNG)

- ## __Testing__
    - I tested and made sure that hte website is compatible on different browsers(Chrome, safari, Internet Explorer, Microsoft edge) and phone devices(Iphone) so that the user experience is seamless accross the different platforms.
    - I made sure that all the links are working and are linked to the right part of the website.
    - The website is responsive on tablets and phone devices.
    - I made sure that the website is well structured, readable and easy to follow.

### __Bugs__
- Image wasnt loading on Github Pages after deployment due to wrong method of linking the image:

    -   /assets/images/heroimage.JPG
- Fix
    -   ../images/heroimage.JPG


### __Validator Testing__
- __HTML__
    - The index.html file passed the w3c validation test with no errors
    ![HTML Validation](/assets/images/htmlvalidation.JPG)
- __CSS__
    - The style.css file passed the w3c CSS validation  test with no errors
    ![CSS Validation](/assets/images/cssvalidation.JPG)
- __Lighthouse Accessibility Score__

    ![Lighthouse Score](/assets/images/lighthousetest.JPG)

- ## __Deployment__
    - The website was deployed on the Github Pages. Here are the steps I took:
        1. Go to the Github repository of choice, then click on settings.
        2. Click the "Pages" tab from the list on the left.
        3. In the "Branch" Section, click on the dropdown and select main
        4. Hit save and the website will be deployed to the github pages.

## __Credits__

- I used stack overflow to find a way to display a defualt value in the "input select"  inside the form so that its shows "Choose Here" https://stackoverflow.com/questions/3518002/how-can-i-set-the-default-value-for-an-html-select-element.

### __Content__

- I used a website named https://cssgradient.io/ to create the gradient in css for my footer and pricing page.

### __Media__

- The background photo for the Hero Image area was taken form this link: https://pixabay.com/photos/generated-piet-mondrian-mondrian-7687508/
- The background image for the About Us section was taken from this link: https://pixabay.com/photos/robert-duncanson-landscape-art-84959/