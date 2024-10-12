# Vital's portfolio Website -  PP1-HTML-CSS-Vital

![The PP1-HTML-CSS-Vital on a variety of screen sizes](./assets/images/responsiveness-check.png)



Vital's portfolio Website is intended to give important information to professionals and everyone alse who might be interested in hiring Vital as their potential IT project manager or software developer for their Projects.

Users of this website will get most of the information about Vital as their ideal candidate, about me, my crediantials/Portfolio, my contact info, and they can also subscribe to my newsletter if they wish so. Most of the GDPR applies.
Check my website and get opportunity to work with me!

Visit the live site: [The PP1-HTML-CSS-Vital](https://vinsengi.github.io/PP1-HTML-CSS-Vital/)


## Features 

### Site wide
* Navigation Menu
    * Contains links to the Home, About, Customers, Certificates and Contact pages (sections) and will be responsive on all standard devices.
    * This will allow users to easily navigate between the pages within the site on any standard size device. 

![Nav Menu](./assets/images/readme-images/navigation-menu.png)


* Footer
    * This will contain icons as links to social media websites that will open in new tabs. Icons will be accessible to the visually impaired who may be using a screen reader, by the use of aria labels.

    * This will allow the user to follow Vital on various social media where they can get more up to date information that may not be displayed on the website. The contact information will allow the user to contact Vital directly.

![Footer](./assets/images/readme-images/footer.png)



* Favicon
    * A site wide favicon (This is a noraml vital profile picture resized down and rounded to mimik a favicon) will be implemented with vital's profile picture in a form of a circle.
    * This will provide an image in the the tabs header to allow the user to easily identify the website if they have multiple tabs open.

![Favicon](./assets/images/favicon/favicon.png)



* 404 Page
    * A 404 page will be implemented and will display if a user navigates to a broken link.
    * The 404 page will allow the user to easily navigate back to the main website if they direct to a broken link / missing page, without the need  of the browsers back button.

![404](./assets/images/readme-images/404-image.png)

### Landing Page
* Landing page image
    * This will be a collection of favourite images from some of 'Taco's Travels. Images will change on a timer. 
    * This will help to immediately show the user what the website is about and help to animate the page. 

![Landing Page Image](./assets/images/readme-images/landing%20page.png)
* Website information on Vial's website
    * Information about Vital and the websites purpose including an image of Vital.
    * This information lets the user know what the site is about. 

![Bio](./assets/images/readme-images/about-me-section.png)
* This section will provide principal values that Vital believes in especially when it comes to project management profession.


### Customers section
* Customers
    * This section serves as testimonials of other world playrs that Vital has worked with as in to give confidency to the potential customer/business partner.

![Customers](./assets/images/readme-images/customers.png)


### Certificates
* to fullfill all the requirements...
    * This sections containing 3 sample photos from certificates. They aim to give the user another high level overview of proof for my continious learning and growth mindset, learn it all! 
    
![Certificates](./assets/images/readme-images/certificates.png)

### Contact
* Contact form
    * A contact form will be implemented to allow users to contact Vital. The form will consist of the following fields and attributes: 
        *Full Name (required, type=text)
        * Phone number (required, type=text)
        * Email (required, type=email)
        * Message (required, type=textarea)
        * Send Button
    * On successful submission of the contact form, the user will be navigated to contact.html displaying a success message.
    * This will allow user to contact Vital if they have any queiries about him.

![Contact Form](./assets/images/readme-images/contactme-form.png)

![Contact Form](./assets/images/readme-images/contactme-form-filled.png)

![Contact Form Received](./assets/images/readme-images/success-message.png)

![Details Dropdown](docs/readme_images/details_dropdown.JPG)


### Not shown Features on the navigation menu

* Sucess form, not on navigation, it shows up only on successful submission of the contact form
* 404 - Not found form



### Features Left to Implement

* As a future enhancement, the contact form will be updated with javascript to send an email to vital with the contact information.

* Fix the carousel so that its height remains same regardless of image's height.

* A downloadable pdf Resume will be made possile later. As per current deployment, the resume is a simple HTML and CSS webpage.

## Design

### Wireframes
<br>
Home page
<br><br>

![Home Page large screen](docs/readme_images/home_wireframe.JPG)

![Home Page small screen](docs/readme_images/home_mobile_wireframe.JPG)
<br><br>
Contact form successful submission page.
<br><br>
![Contact form submission success](docs/readme_images/contact_wireframe.JPG)

![Contact form submission success](docs/readme_images/contact_mobile_wireframe.JPG)


Adventures page
<br><br>
![Adventures page large screen](docs/readme_images/adventures_wireframe.JPG)

![Adventures page small screen](docs/readme_images/adventures_mobile_wireframe.JPG)

Gallery page
<br><br>
![Gallery page large screen](docs/readme_images/gallery_wireframe.JPG)

![Gallery page small screen](docs/readme_images/gallery_mobile.JPG)

404 page
<br><br>
![Gallery page large screen](docs/readme_images/404_wireframe.JPG)

![Gallery page small screen](docs/readme_images/404_mobile_wireframe.JPG)
<br><br><br><br>


## Technologies

* HTML
    * The structure of the Website was developed using HTML as the main language.
* CSS
    * The Website was styled using custom CSS in an external file.
* Visual Studio Code
    * The website was developed using Gitpod IDE
* GitHub
    * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git 
    * Used to commit and push code during the development opf the Website
* Font Awesome
    * Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section. 
* Tinyjpg
    * https://tinyjpg.com/ was used to reduce the size of the images used throughout the website
* Favicon.io
    * favicon files were created at https://favicon.io/favicon-converter/  and i used some of my own pictured resized down.
* balsamiq
    * wireframes were created using balsamiq from https://balsamiq.com/wireframes/desktop/#


## Testing 

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox and Opera browsers.

Steps to test:

1. Open browser and navigate to [Vital's website](https://vinsengi.github.io/PP1-HTML-CSS-Vital/)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width

Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched.
No horizontal scroll is present.
No elements overlap.

Actual:

Website behaved as expected with the exception of switching to landscape view in Mozilla Firefox. Details can be found in [Unfixed Bugs](#Unfixed-Bugs)

Website was also opened on the following devices and no responsive issues were seen:

- Dell monitor (X-large monitor)
- Lenovo Thinkpas x1 yoga (large screen)
- iPhone 13 pro max (small screen)
- ipad 12 pro (Medium screen)

### Accessibility

[Wave Accessibility](https://wave.webaim.org/) tool was used throughout development and for final testing of the deployed website to check for any aid accessibility testing.

Testing was focused to ensure the following criteria were met:

- All forms have associated labels or aria-labels so that this is read out on a screen reader to users who tab to form inputs
- Color contrasts meet a minimum ratio as specified in [WCAG 2.1 Contrast Guidelines](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)
- Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user
- All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
- All not textual content had alternative text or titles so descriptions are read out to screen readers
- HTML page lang attribute has been set
- Aria properties have been implemented correctly
- WCAG 2.1 Coding best practices being followed

Manual tests were also performed to ensure the website was accessible as possible and an accessibility issue was identified.

Issue #1: Use of hidden check boxes and labels for the gallery filter and accordion on the gallery page were not accessible via the keyboard due to the property display: none;

Fix: I could not find a way to fix this issue with html and css alone so a tabindex of 0 was added to allow the label to be tabbed to and an onkeypress event to target and click the correct checkbox was implemented. Javascript code was taken from this [Mozilla Doc](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/click)

Issue #2: After keyboard controls were implemented, while testing the site with windows 'Narrator' screenreader, it was not clearly known what the purpose of the labels/checkboxes were. An aria-label label was added to the labels for screen readers to alert them that the labels were clickable and what their purpose was.

### Lighthouse Testing

![Home](docs/testing/index_lighthouse.JPG)

![Gallery](docs/testing/gallery_lighthouse.JPG)

![Adventures](docs/testing/adventures_lighthouse.JPG)

### Functional Testing

**Navigation Links**

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

| Navigation Link | Page to Load    |
| --------------- | --------------- |
| Home            | index.html      |
| Aventures       | adventures.html |
| Gallery         | gallery.html    |

Links on all pages navigated to the correct pages as exptected.

**Form Testing**

The form on the home page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following test scenarios were covered:

_Scenario One - Correct Inputs_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name: John
   - Last Name: Doe
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit
4. User should be redirected to contact.html confirmation page

Expected:

Form submits with no warnings or errors and user is redirected to contact.html confirmation page.

Actual:

Website behaved as expected with no errors or warnings and redirected to contact.html.

_Scenario Two - Missing Required Field First Name_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:
   - Last Name: Doe
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Three - Missing Required Field Last Name_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:John
   - Last Name:
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Four - Missing Required Field Email_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:John
   - Last Name: Doe
   - Email:
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Six - Incorrect email format_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:John
   - Last Name: Doe
   - Email: doe.johntest.com
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that a valid email is required and the format it should be in.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

**Footer Social Media Icons / Links**

Testing was performed on the Font Awesome Social Media icons in the footer to ensure that each one opened in a new tab and that each one had a hover affect of the orange branding color.

Each item opened a new tab when clicked as expected and correct hover color was present.

**Footer Contact Information**

Testing was performed on the phone number in the contact information section of the footer to ensure behaviour was as expected.

_Steps to test Telephone Number_

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Click the phone number in the footer (01 123 456 789)

Expected:

A window is opened asking which device you would like to call from.

Actual:

Behavior was as expected and the window presented me with the following option to call:

- Oukitel Mobile Phone

_Steps to test Email Link_

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Click the email address in the footer (taco@gmail.com)

Expected:

A windows popup is displayed asking what application you would like to send a mail from or your default email application is opened.

Actual:

Behavior was as expected and my outlook application was opened ready to send an email to the target address.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org)

![Contact HTML Validator Results](docs/testing/contact_validator.JPG)

![Avdentures HTML Validator Results](docs/testing/adventures_validator.JPG)

![Home HTML Validator Results](docs/testing/home_validator.JPG)

![Gallery HTML Validator Results](docs/testing/gallery_validator.JPG)

![404 HTML Validator Results](docs/testing/404_validator.JPG)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org)

![CSS Validator Results](docs/testing/css_validator.JPG)

### Unfixed Bugs
Responsiveness of the website worked on all devices, screen sizes and orientation with the exception of landscape orientation on mozilla firefox. I was unable to resolve this bug on time but will address in a future release.

## Deployment

### Version Control

The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘tacos-travels’.

The following git commands were used throughout development to push code to the remote repo:

```git add <file>``` - This command was used to add the file(s) to the staging area before they are committed.

```git commit -m “commit message”``` - This command was used to commit changes to the local repository queue ready for the final step.

```git push``` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the menu on left select 'Pages'
  - From the source section drop-down menu, select the Branch: main
  - Click 'Save'
  - A live link will be displayed in a green banner when published successfully. 

The live link can be found here - https://gareth-mcgirr.github.io/tacos-travels/ 

### Clone the Repository Code Locally

Navigate to the GitHub Repository you want to clone to use locally:

- Click on the code drop down button
- Click on HTTPS
- Copy the repository link to the clipboard
- Open your IDE of choice (git must be installed for the next steps)
- Type git clone copied-git-url into the IDE terminal

The project will now of been cloned on your local machine for use.

## Credits 

* [Accordion without javascript](https://supfort.com/pure-css-accordion-without-javascript)
    * Code was used from this site to create the accordian effect on the adventures page sections for the hidden sections for each days travels. Styles were changed to suit styling on my Website.
* [Youtube Gallery Filter Tutorial](https://www.youtube.com/watch?v=U-CujW5OlW0)
    * Gallery page was created with inspiration from this video. I adapted code to use flexbox rather than css grid to make the page responsive on every device. 


### Content 

All content with the exception of those listed in the Media section of this document was owned by Hair O'The Dog club members Rocket and Taco. Permission was granted from Rocket to use the images.

### Media

Website Logo was created by my wife [Daisy McGirr](https://github.com/Daisy-McG) using Canva.

Maps on the adventure page were from google maps timeline.










## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)
  * [Features](#features)
    * [The Home Page](#the-home-page)
    * [The Game Page](#the-game-page)
    * [The High Scores Page](#the-high-scores-page)
    * [The 404 Error Page](#the-404-error-page)
    * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  * [Solved Bugs](#solved-bugs)
  * [Known Bugs](#known-bugs)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

- - -
![The PP1-HTML-CSS-Vital Banner](documentation/the-quiz-arms-banner.png)

## User Experience (UX)

### User Stories

#### First Time Visitor Goals

* I want to take part in a pub quiz online and improve my general knowledge. I want to be able to play at any time, anywhere.
* I want the site to be responsive to my device.
* I want the site to be easy to navigate.

#### Returning Visitor Goals

* I want to be able to choose a level of difficulty that I feel is appropriate for me, based on my experience from my first visit to the site.

#### Frequent Visitor Goals

* I want to be able to adjust the difficulty level to keep improving my knowledge.
* I want to be able to log my high scores to see how I am performing.

- - -

## Design

### Colour Scheme

As the pages of the site have a background image, I wanted to keep the colour scheme used on the site quite small so as to not overwhelm users. Red and green  are very typical colours in traditional British public houses, with the red & green used for upholstery.

In my css file I have used variables to declare colours, and then used these throughout the css file. I was recently introduced to this method during a hackathon - it is a useful convention to use as it allows you to alter the colour throughout the website if you decide to update a colour, by changing the colour once in the variable.

* I have used `#f5f5f5` & `#000000` as the primary and secondary colours used for the sites text.
* I have used `#292929` as the overlay used over the sites background image.
* I have used `#a50c3c` for the border of the modal and to display the wrong answers.
* I have used `#047638` to display the correct answer.

  ![The PP1-HTML-CSS-Vital
 Color Scheme](documentation/color-scheme.webp)

### Typography

Google Fonts was used to import the chosen fonts for use in the site.

* For the Page Title I have used the google font [Almendra](https://fonts.google.com/specimen/Almendra?preview.text=The%20Quiz%20Arms%20THE%20QUIZ%20ARMS&preview.text_type=custom&query=almendra). Almendra is based on a calligraphy style and I have chosen it as it looks like the type of font you would see on a pubs name sign, slightly medieval looking and grand.

![Almendra Font Example](documentation/almendra.webp)

* For the body of the page I have used the google font [Quicksand](https://fonts.google.com/specimen/Quicksand?preview.text=The%20Quiz%20Arms%20THE%20QUIZ%20ARMS&preview.text_type=custom&query=quicksand). QuickSand is a sans-serif font which has lovely clean lines. I have chosen to use a sans-serif font for the body of the page as studies have found that sans-serif fonts are generally more legible to read on a screen.

![Quicksand Font Example](documentation/quicksand.webp)

### Imagery

As the website is called The PP1-HTML-CSS-Vital, I wanted to use an image for the page background of a pub to give the user the feeling that they are participating in a pub quiz.

### Wireframes

Wireframes were created for mobile, tablet and desktop using balsamiq.

![Home Page](documentation/wireframes/homewireframe.webp)
![Difficulty Page](documentation/wireframes/difficultywireframe.webp)
![Game Page](documentation/wireframes/gamewireframe.webp)
![High Scores Page](documentation/wireframes/highscorewireframe.webp)

### Features

The website is comprised of a home page, a games page, a high scores page, a 404 error page & a 500 error page.

All Pages on the website are responsive and have:

* A favicon in the browser tab.

  ![favicon](documentation/favicon-image.webp)

* The title of the site at the top of every page. This title also acts as a link back to the home page.
  ![The PP1-HTML-CSS-Vital
 Title](documentation/the-quiz-arms-banner.png)

* Every page will display a custom cursor when on a button. This feature is not available on mobile touch devices.

![Custom Cursor](documentation/features/custom-cursor.gif)

#### The Home Page

The home page of The PP1-HTML-CSS-Vital displays the sites name as a title and then a container which holds some welcome text, including alerting the users that they can navigate back to the home page at any time by clicking on the page name. Below this are three buttons, how to play, play and high scores.

![Home page image](documentation/features/index.png)

The how to play  button opens a modal showing the user how to play the game. The modal contains a close button which will close the modal, and show the home page again.

![Modal open image](documentation/features/modal.png)

The play button will redirect the user to the game page to select the difficulty of their quiz and the high Scores button redirects the user to the high scores page.

#### The Game Page

The game page displays the sites name as a title. This also acts as a link back to the home page. Initially on the game page you will be shown a container with three buttons to select the difficulty of the quiz the user can choose from.

![Image of the game page difficulty selection buttons](documentation/features/difficulty.png)

Once the user has selected their difficulty they will then be shown the quiz area. The quiz area contains the question and the 4  answer choices.

when a user selects an answer, they will then be prevented from selecting any more answers. The quiz area border and the button selected will change styles depending on whether the answer selected was correct or incorrect. If the answer selected was correct, the score counter will add 10 to the score total. When the user clicks the next button the question no counter will increase by 1. If the user selects the wrong answer, the button selected will display red, and the correct answer will display as green.

![Image of quiz area](documentation/features/quiz.png)

Once a user has answered the 15 questions they will be taken to the end of the game which will allow them to enter their team name and submit it to be entered onto the high scores page if it is in the top 10 scores. The submit button is disabled by default to prevent the user from submitting without a team name. This is made clear to the user as the cursor will show not allowed when hovered over the submit button.

![End of game](documentation/features/end.png)

#### The High Scores Page

The high scores page displays the sites name as a title. This also acts as a link back to the home page. The page then displays the high scores recorded - showing the team name a user chooses and their score. The high scores page will list the top ten scores recorded. Underneath the high scores are two buttons to allow the user to play again or be redirected to the home page.

![High Scores Page Image](documentation/features/highscores.png)

#### The 404 Error Page

The 404 error page displays the sites name as a title. This also acts as a link back to the home page. Within the page container there is a sorry message explaining to the user that there has been an error directing them to the page they were looking for. The user is then given a choice of three buttons to redirect them to other pages on the site, the home page, the games page and the high scores page.

![Error page image](documentation/features/404.png)

#### The 500 Error Page

The 500 error page displays the sites names as a title, which also acts as a link back to the home page. Within the container is an error message that tells the user sorry there seems to be an issue retrieving the quiz data. Two buttons for the home page and the high scores page are below. I did not add the play game button here, as a user will been directed to this page if there is an error calling the API.

![500 Error Page](documentation/features/500.png)

#### Future Implementations

In future implementations I would like to:

1. Give users the option to select the amount of questions in their quiz.
2. Look into making the quiz a multiplayer game, so that it could be played by teams, which would make the quiz even more like a pub quiz.
3. Create a back end database to enable me to store scores which would then allow you to see how you scored against other players.
4. Look further into the accessibility for people with colour blindness, perhaps by adding symbols such as a tick or cross next to the answer when they are checked.

### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. This has been have achieved by:

* Using semantic HTML.
* Using a hover state on all buttons on the site to make it clear to the user if they are hovering over a button.
* Choosing a sans serif font for the site - these fonts are suitable for people with dyslexia.
* Ensuring that there is a sufficient colour contrast throughout the site.

![contrast button](documentation/contrast-btn.png) ![Contrast button hover](documentation/contrast-btn-hover.png) ![contrast text](documentation/contrast-text.png)

As the site relies on colour to display to the user whether an answer is correct or incorrect, I was interested to see what this would look like for someone with red/green colour blindness. I used the chrome extension [Web Disability Simulator](https://chrome.google.com/webstore/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) to be able to see what someone with red/green colour blindness would see.

In a future implementation I think it would be a great accessibility feature to also add a symbol such as a tick or cross on the answer button to enable people who are colour blind to also be able to access the quiz easier. Each of the images below have whether they are correct/incorrect in the name. Can you tell which one is which?

![Colour blindness (red/green) correct answer](documentation/rg-colour-blind-correct.png)
![Colour blindness (red/green) incorrect answer](documentation/rg-colour-blind-incorrect.png)

- - -

## Technologies Used

### Languages Used

HTML, CSS, Javascript

### Frameworks, Libraries & Programs Used

* [Balsamiq](https://balsamiq.com/) - Used to create wireframes.

* [Git](https://git-scm.com/) - For version control.

* [Github](https://github.com/) - To save and store the files for the website.

* [GitPod](https://gitpod.io/) - IDE used to create the site.

* [Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.

* [jQuery](https://jquery.com/) - A JavaScript library.

* [Google Developer Tools](https://developers.google.com/web/tools) - To troubleshoot and test features, solve issues with responsiveness and styling.

* [TinyPNG](https://tinypng.com/) To compress images

* [Birme](https://www.birme.net/) To resize images and convert to webp format.

* [Favicon.io](https://favicon.io/) To create favicon.

* [Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

* [Shields.io](https://shields.io/) To add badges to the README

* [Open Trivia DataBase](https://opentdb.com/) - API used for the trivia questions.

* [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) - a google chrome extension to enable you to view JSON as raw data or parsed.

* [Web Disability Simulator](https://chrome.google.com/webstore/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) - a google chrome extension that allows you to view your site as people with accessibility needs would see it.

* [Webpage Spell-Check](https://chrome.google.com/webstore/detail/webpage-spell-check/mgdhaoimpabdhmacaclbbjddhngchjik/related) - a google chrome extension that allows you to spell check your webpage. Used to check the site and the readme for spelling errors.

- - -

## Deployment & Local Development

### Deployment

The site is deployed using GitHub Pages - [The PP1-HTML-CSS-Vital](https://kera-cudmore.github.io/TheQuizArms/).

To Deploy the site using GitHub Pages:

1. Login (or signup) to Github.
2. Go to the repository for this project, [kera-cudmore/TheQuizArms](https://github.com/kera-cudmore/TheQuizArms).
3. Click the settings button.
4. Select pages in the left hand navigation menu.
5. From the source dropdown select main branch and press save.
6. The site has now been deployed, please note that this process may take a few minutes before the site goes live.

### Local Development

#### How to Fork

To fork the repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, [kera-cudmore/TheQuizArms](https://github.com/kera-cudmore/TheQuizArms)
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, [kera-cudmore/TheQuizArms](https://github.com/kera-cudmore/TheQuizArms)
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Testing

Please refer to [TESTING.md](TESTING.md) file for all testing carried out.

### Solved Bugs

| No | Bug | How I solved the issue |
| :--- | :--- | :--- |
| 1 | An error was displaying in the console when next was clicked after the first question, stating that results wasn't defined. | Data was defined in the callApi(), so couldn't be accessed as it was in local scope rather than global scope. By defining data globally and then passing the data as a parameter into the getQuestion() in the nextQuestion() solved this. |
| 2 | The Questions being pulled in from the JSON have HTML entity characters that are not escaped and therefore display incorrectly with symbols in place of the correct characters. ![Characters not escaping correctly in the JSON data](documentation/characters-not-escaped.webp) | After a lot of research into escaping characters, I came across a post on slack that mentioned using innerHTML rather than innerText. Once I changed the answers to innerHTML the characters are now displaying correctly. |
| 3 | I have the local storage set up to save the final score as mostRecentScore. However when completing a game and submitting the team name the score added to the high scores section would be the previous score and not the most recent score. | After a lot of research to try and find out why this was happening I went over the code again and decided to see if I changed mostRecentScore in the scoreLog to score it would make a difference. By changing this, I have solved the issue and it now pulls the most recent score achieved. |
| 4 | Players were able to select an answer which would then display whether correct or incorrect. However they could still click on the answers which meant they could click all the answers to receive the points.| I researched a way to disable the buttons and initially found that I could use answer1.disabled = true; This worked, however it added quite a bit of code, as I had to add this for each button. Further research led me to find [this article](https://blog.revillweb.com/jquery-disable-button-disabling-and-enabling-buttons-with-jquery-5e3ffe669ece) which showed how to use jQuery and the class on the buttons to enable and disable them all at the same time. This then allows me to enable the buttons when a new question has been populated and once a selection has been made, the answer buttons are disabled until the user clicks next to advance onto the next question. |
| 5 | There was an issue with the data-correct not always being removed correctly from questions, which meant that incorrect answers were displaying as correct | I changed the way the data-correct attribute was removed from the answers, by using the same a for loop similar to what was used to add the data-correct attribute. I also changed the for innerText in the for loop to be innerHTML so that it was correctly reading the same as what was displayed on the button. |
| 6 | If a user selected an incorrect answer and the correct answer contained HTML entity characters (such as /&#(\d+);/g) the correct button styling would not be applied to the displayCorrectAnswer variable and a error would display in the console. This would then prevent the user from progressing in the quiz as the next button would not display for them to move on.![Bug 6](documentation/bug-6.png) | I adjusted line 161 to use innerHTML rather than innerText, however the issue persisted. I looked for an answer online but struggled to find anything that would help. I then reached out to Bim Williams on Slack who is an alumni on the course and asked to run the problem past him. He suggested adding a function that would decode the HTML entity and then apply that function within line 161. The function takes the HTML entity characters and replaces them with the correct characters. I will be researching this topic further in my spare time to gain a deeper understanding of it. |

### Known Bugs

* When viewing on screens that use touch rather than a cursor, the colour change for the answer button selected is not immediately obvious as the hover state remains on the button. If the user clicks away from the button the colour can then been seen.

  ![Touch Button Colour](documentation/touch-button-colour.gif)

* There is a a warning displaying in the console on the live page. This error seems to be because GitHub hosted pages disable googles 3rd party cookie alternative FLoC, which then throws this error. The error doesn't affect the site in any way.

  ![Console warning](documentation/interest-cohort-error.png)

* When friends tested the site they found that very rarely a game will get stuck on a question, and it will not populate a new question but the question no counter continues to increase. This issue only seems to be if a large number of games are played consecutively, possibly using up the questions in the API. I have not been able to replicate this issue to troubleshoot further.
  ![Question overloaded](documentation/questions-depleted.gif)

- - -

## Credits

### Code Used

* I used [this You Tube tutorial](https://www.youtube.com/watch?v=XH5OW46yO8I) to learn how to create a modal for the how to play section.

* As the API I used for the questions declared the correct answer and then had an array of incorrect answers, I had to find a way to shuffle the answers together so that the correct answer wouldn't always appear on the same button. Research led me to the Fisher-Yates Shuffle. Other methods of shuffling can favour some items in the array more than others, however the Fisher Yates Shuffle allows for a more even spread of probability of the answer being placed on each button. I used the following [YouTube tutorial](https://www.youtube.com/watch?v=eATLMjs7y4s&list=PL5egNEXQTWmFHAoWFVRLNAvD-9zzyWVxA&index=3) to further adapt the shuffle I had researched on W3Schools to work with the data I had.

As the JavaScript modules of the Code Institute Diploma did not cover local storage, I had to do a bit of research into this topic myself in order to set up the high scores section of my site.

* I used this [video tutorial](https://www.youtube.com/watch?v=DFhmNLKwwGw&list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx&index=9) on YouTube by [James Q Quick](https://www.youtube.com/channel/UC-T8W79DN6PBnzomelvqJYw) which taught me to save the team name and score to an object, that would then be saved into an array in local storage. It also explained how to sort the items in the array into descending score order, and then to splice the array, I have used the MAX_HIGH_SCORES as my point to splice.

* I used this [video tutorial](https://www.youtube.com/watch?v=jfOv18lCMmw&list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx&index=10) on YouTube by [James Q Quick](https://www.youtube.com/channel/UC-T8W79DN6PBnzomelvqJYw) to learn how to insert the local storage into the high scores page.

### Content

All questions for my site were pulled from [The Open Trivia Database](https://opentdb.com/) using their API.

All other content for the site, such as introduction messages and instructions were written by myself.

### Media

[Page background image of a pub](https://pixabay.com/photos/bar-pub-cafe-establishment-stools-2209813/)

### Acknowledgments

I would like to acknowledge the following people:

* Adegbenga  Adeye - My Code Institute Mentor.

* Bim Williams - For being a great sounding board for me when I faced issues with moving onto the next question in the quiz, and for helping solve the issue faced with the HTML entity characters in the answer buttons.

* [Dave Horrocks](https://github.com/daveyjh) - For taking the time to walk through my code with me when I was struggling with adding event listeners.

* [Emanuel Silva](https://github.com/manni8436) - For cheering me on when I was struggling with the JavaScript, and for testing the site.

* [Abi Harrison](https://github.com/Abibubble) - For being a great rubber duck and helping debug, helping to test the site and for sharing her knowledge on accessibility.

* The Code Institute Slack channel Peer Code Review - Thank you to everyone who took the time to play the quiz and look over the code.