# Portfolio Project 1 - HTML/CSS Essentials

Another incompleted project. For the purpose of my course, this site was too time consuming with the layout and menu structure. As my knowledge of other languages is increasing, I have realised there are many other ways to achieve my original concept and so this project will remain here as is. It has some far better aspects than previous incompleted projects, but the ARIA of the site was too difficult to correct with my, at the time, limited knowledge.  A real case of biting off more than I could chew!

## Table of Contents
- [Objective](#Objective)
- [Brief](#Brief)
- [UX &#8722; User Experience Design](#UX-&#8722;-User-Experience-Design)
- [Initial Concept](#Initial-Concept)
    - [Wireframes](#Wireframes)
        - [All Wireframes - Separate Document](/wireframes.md)
    - [Colour Scheme](#Colour-Scheme)
- [Features](#Features)
    - [Existing Features](#Existing-Features)
    - [Features Left to Implement](#Features-Left-to-Implement)
- [Technologies Used](#Technologies-Used)
- [Testing](#Testing)
    - [Bugs](#Bugs)
- [Deployment](#Deployment)
- [Credits](#Credits)
    - [Content](#Content)
    - [Media](#Media)
    - [Acknowledgements](#Acknowledgements)
- [Downloads](#Downloads)
***
## Objective
In this project I intend to provide a portfolio style website for my sister's wildlife photography.  The main objective is to demonstrate competency in HTML and CSS.  I hope to provide an emotive, static front end application which is easy to navigate and has a clear purpose.
***
## Brief
### **Katie Horrocks - Wildlife Photography**
<!-- link to site here -->
The goal of this website is to promote Katie Horrocks' photography.  The client would like to have:
- a brief introduction, who she is and what she does
- the client intends to display a few small galleries
- a contact form
- links to her social media sites

*She may, at a later date, add a blog to the site so that element should be considered during the design of the application*
***
## UX &#8722; User Experience Design
### User Requirements
Some example user stories which will effect the design
 
- *"As a first time visitor, I want to know what this site is about. I may use a number of different devices (mobile/tablet etc.) to view the site. I would like to be able to navigate easily"*
- *"As a returning visitor, I want to take a look at some different galleries and possibly some social media links. I am interested in learning a little more about Katie, but I really do like the photographs"*
- *"As a potential client, I would like to see some of Katie's work. I care about presentation and the overall design may impact my decisions. I want to be able to send my enquiries directly to Katie"*

### Initial Concept
With photographic images featuring as a really important aspect of the site, I  hope to keep the design fairly free from other distractions. I anticipate using a fairly neutral colour scheme as I feel this will allow the content images to stand out more from the design aspects. The application is to be designed with 'mobile first' in mind.
#### Wireframes
*See [here](/wireframes.md#Wireframes) for other device types*
##### Home Page
![Home Page Wireframe](/assets/images/readme-content/mob-home.png)

#### Colour Scheme
A neutral color scheme created using [coolors.co](https://coolors.co)
![Colour Scheme](/assets/images/readme-content/scheme-a.png)
![Colours Applied](/assets/images/readme-content/mob-col-1.png)
***
## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
<!-- - Feature 1 - allows users X to achieve Y, by having them fill out Z -->

1. The header will be visible on all pages and have a maintained style throughout
>*"As a visitor ... **I would like to be able to navigate easily**"*
- *the nav menu is accessible through the header and is easily recognised by the metaphorical menu icon*

2. The title is brief and informative and accompanied by a pleasant image
>*"As a first time visitor...**I want to know what this site is about**"*
- *the tag line under the name gives an immediate indication to what the site is connected to, the small image is relevant and emotive*

3. The home page has a large image showing animal photography
>*"As a first time visitor...**I want to know what this site is about**"*
>*"As a returning visitor...**I really do like the photographs**"*
- *the hero image shows off the type of photography included in the website*

4. The footer element has accessible icons which link to social media platforms
>*"As a returning visitor...**some social media links**"*
- *the social media links will be available on all pages*
***
The footer element contains a link to my github and linked in profiles
>BONUS
- *the design of the footer allows for discrete links to me, should any visitor wish to know more*

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea
***
## Technologies Used

<!-- In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation. -->

- [FontAwesome](https://fontawesome.com/)
    - The project uses icons from Font Awesome version 5

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Bugs
1. The h2 element, "wildlife photography" is visible over the "main-hero" div. This appears to only present a problem with small phones screens such as the iphone 4.  I have added a background colour with some opacity as a simple work-around for now.  I do not feel the bug will effect a large audience and is of a minor nature

*style.css line - 219*
~~~
    opacity: 0.75;
    background-color: #E4DAE7;
    border-radius: 0.8rem;
~~~
*I believe I could move the h2 element into the main section, rather than the header. This would allow it to flow with the content, but will require some repositioning of items*

2. The entire title-container div acts as the anchor for the home page. This could lead to a user performing an accidental click on this anchor instead of the nav menu. This issue should be addressed, likely by moving the anchor element to parent only the h1 element.  I could have a second anchor on the h2 but do not feel that is necessary.  Some CSS will need to be checked and changed at the same time
## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The main structure for the nav-menu is based on some tips from [CSS Tricks](https://css-tricks.com/solved-with-css-dropdown-menus/)

### Media
- The photos being used in the site are currently from [Unsplash](https://unsplash.com) but will be updated with photographs from Katie's albums as soon as she has chosen them

### Acknowledgements

- I received inspiration for this project from X

## Downloads
