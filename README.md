<!-- vscode-markdown-toc -->

# Caerphilly Cycling Club (CCC) - Code Institute Project 1

# Table of Contents

- 1. [Design](#Design)
  - 1.1. [Changes to the Original design](#ChangestotheOriginaldesign)
- 2. [Technologies used](#Technologiesused)
- 3. [Development Process](#DevelopmentProcess)
  - 3.1. [Sprints](#Sprints)
    - 3.1.1. [design](#design)
    - 3.1.2. [create home page, test, retrospective](#createhomepagetestretrospective)
    - 3.1.3. [build responsiveness](#buildresponsiveness)
    - 3.1.4. [create other pages](#createotherpages)
    - 3.1.5. [build contact us](#buildcontactus)
- 4. [**Planning stage**](#Planningstage)
  - 4.1. [**Target Audiences:**](#TargetAudiences:)
    - 4.1.1. [Potential new club members](#Potentialnewclubmembers)
    - 4.1.2. [Existing club members](#Existingclubmembers)
    - 4.1.3. [General public](#Generalpublic)
    - 4.1.4. [Public officials](#Publicofficials)
  - 4.2. [**User Stories:**](#UserStories:)
  - 4.3. [**Site Aims:**](#SiteAims:)
  - 4.4. [**How Is This Will Be Achieved:**](#HowIsThisWillBeAchieved:)
- 5. [**Wireframes:**](#Wireframes:)
- 6. [**Color Scheme:**](#ColorScheme:)
- 7. [**Current Features Common to all pages**](#CurrentFeaturesCommontoallpages)
  - 7.1. [**Header Element**](#HeaderElement)
    - 7.1.1. [_Logo:_](#Logo:_)
    - 7.1.2. [_Navigation Bar:_](#NavigationBar:_)
  - 7.2. [**Hero Images**](#HeroImages)
- 8. [**Footer**](#Footer)
- 9. [**Typography**](#Typography)
- 10. [**Individual Page Content features**](#IndividualPageContentfeatures)
  - 10.1. [**Home/About Page Content:**](#HomeAboutPageContent:)
  - 10.2. [**Ride Page Content:**](#RidePageContent:)
  - 10.3. [**Join Page Content:**](#JoinPageContent:)
  - 10.4. [**Contact Page Content**](#ContactPageContent)
- 11. [**Future-Enhancements**](#Future-Enhancements)
- 12. [**Testing Phase**](#TestingPhase)
- 13. [14. Open and Closed Issues](#OpenandClosedIssues)
- 14. [**Deployment**](#Deployment)
- 15. [**Credits**](#Credits)
  - 15.1. [**General reference:**](#Generalreference:)
  - 15.2. [**Content:**](#Content:)
  - 15.3. [**Media:**](#Media:)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc --><!-- vscode-markdown-toc -->

# User Centric Frontend Development Project Resubmition

Based on feedback on my project I have made the following improvements.

### Criterion 1.3 and 1.5

The navigation bar has had a call to action button added to join the club that appears on all pages of the site. Bootstrap is used to position this. The header section has been completely redesigned using images from freepix to give a more professional finish. Bootstap was used to place text above the image to inform the user. Content has been seperated and positioning improved. On the ride page content and layout has been improved and shading added to sections.

### Criterion 2.3 and 2.4

All pages of the site pass validation.
![validation](assets\images\valIndex.png "Desktop Demo")
![validation](assets\images\valRide.png "Desktop Demo")
![validation](assets\images\valJoin.png "Desktop Demo")
![validation](assets\images\valContact.png "Desktop Demo")

All images have been replaced, and optimised.

### Criterion 5.1

Manual testing results are added to the readme.md. User stories are tested. Screenshots for the user stories and tests are listed in this readme.

# <a name='Staticresponsivewebsite-Stream1Project'></a>Static responsive website - Stream 1 Project -Caerphilly Cycling Club (CCC)

I'm a member of Caerphilly Cycling Club. We have a serviceable website, it is static, has not been changed in more than 5 years but generally the content is good. The main failing of the site is that it is not responsive. A sample survey of current members showed that during the last 5 years most users have moved from desktop to mobile devices to view the site.

Any design needs to be mobile first.

# Demo

A live demo of this project can be found [here](https://ictwise.github.io/project1_ccc/).
![Desktop Demo](assets\images\responsiveNew.png "Desktop Demo")

# UX

## 1. <a name='Design'></a>Design

The club logo and club colours were already set. The club is often referred to as 'the Green Machine' therefore green and an accent red would always be the colours. To reflect the vibrant nature of the club I wanted to include some animation, video images generally the feeling of movement. The issue with responsiveness had to be addressed, the top navigation bar did not collapse on mobiles and took up most of the real estate on a mobile screen. It was important the new design resolved this.

![image](https://user-images.githubusercontent.com/57628753/146191222-f71e8819-320d-4c06-a901-f10eb82550e3.png)

I created a [wireframe](assets\doc\wireframe.bmpr) for mobile, tablet and desktop. This helped me understand the structure of the site I was creating and focus for the initial design.

### 1.1. <a name='ChangestotheOriginaldesign'></a>Changes to the Original design

My first attempt at the index page recreated parts of both (code institute) sites adapting them to the CCC website. On creation of the index.html and after discussions with my mentor I was dissatisfied with the result. The page was responsive as bootstrap was used for the navigation bar and the footer, but the design was - gaudy. I also felt that I had not gained enough practice using HTML and CSS. I wanted a simpler more elegant interface and practice with the DOM for positioning, and understanding margins, borders, and padding. I had also many snippets from CSS I had been trying out. My code was far from beautiful! I was pleased with the footer. Built using Bootstrap the Social media section worked perfectly but the navigation bar although working well, very responsive just looked too bright. Red and green in the shades the club use is intended for cars to see you clearly on the road, on a website they can look very busy.

I researched many alternatives on the web, finally in codepen I found a navigation bar I wanted to adapt and use. <https://codepen.io/nicolettafbr/pen/KKNydVK*/>

---

## 2. <a name='Technologiesused'></a>Technologies used

1. HTML5
2. CSS
3. Boostrap 4
4. VS code
5. GitHub
6. Git

---

## 3. <a name='DevelopmentProcess'></a>Development Process

Mobile first. Grid system/bootstrap. Visual Studio Code. Correct semantics. This was my primary objective.
I looked at this as an opportunity to practice my skills specifically those learnt while creating the Code institute 'Love running' site and the Bootstrap resume example.

### 3.1. <a name='Sprints'></a>Sprints

#### 3.1.1. <a name='design'></a>design

Define strategy, build wireframes, finalise fonts/colour schemes/images

#### 3.1.2. <a name='createhomepagetestretrospective'></a>Create home page, test, retrospective

Check for look and feel

#### 3.1.3. <a name='buildresponsiveness'></a>Build responsiveness

Test at different resolutions.

#### 3.1.4. <a name='createotherpages'></a>Create other pages

duplicate Header and footer of index, build other pages, test

#### 3.1.5. <a name='buildcontactus'></a>Build 'contact us'

Build form
Test entire site at various resolutions and using online testing tools

---

## 4. <a name='Planningstage'></a>**Planning stage**

### 4.1. <a name='TargetAudiences:'></a>**Target Audiences:**

#### 4.1.1. <a name='Potentialnewclubmembers'></a>Potential new club members

Need to find out about the club - rides, how to prepare for a ride, how to join the club, what kind of riders already belong to the club.

#### 4.1.2. <a name='Existingclubmembers'></a>Existing club members

May need to check club rules. See information on club rides. See recent photos. Foster a sense of pride in the club.

#### 4.1.3. <a name='Generalpublic'></a>General public

May want to contact the club to make complaints about club members road use.

#### 4.1.4. <a name='Publicofficials'></a>Public officials

Ask for advice from the club members and committee about policy decisions.

### 4.2. <a name='UserStories:'></a>**User Stories:**

- As a user, I want to find information on the club.
- As a user, I want to be able to join the club.
- As a user, I want to navigate the page to find what I require quickly and easily.
- As a user, I want to know how to contact the club.
- As a user, I was to find ride times and locations.
- As a user, I want to understand what is required of riders on a club ride.

### 4.3. <a name='SiteAims:'></a>**Site Aims:**

- To inform users about CCC.
- To educate the user on basic ride etiquette.
- To offer the user a chance to connect with the club.
- Provide the user with the information on club rides.
- Provide a method by which the user can subscribe to a newsletter.

### 4.4. <a name='HowIsThisWillBeAchieved:'></a>**How Is This Will Be Achieved:**

- The home page provides the user with a summary of the club. There is a rides page that gives details of ride time, ride etiquette and links to ride advice. The contacts page has a contact form and a checkbox to sign up for the newsletter.

## 5. <a name='Wireframes:'></a>**Wireframes:**

To organize my thoughts and prevent scope creep, I created wireframes for this project.

- Wireframes:

There was some deviation from the original wireframes to improve the User Experience (UX).
[link to the wireframe file.](assets\doc\wireframe.bmpr)

## 6. <a name='ColorScheme:'></a>**Color Scheme:**

The club logo and club colours were already set. The club is often referred to as 'the Green Machine' therefore green and an accent red would always be the colours.

## 7. <a name='CurrentFeaturesCommontoallpages'></a>**Current Features Common to all pages**

### 7.1. <a name='HeaderElement'></a>**Header Element**

The header element is sticky adhering to popular conventions, as the user scrolls the header remains at the top of the page. The header contains the following features:

#### 7.1.1. <a name='Logo:_'></a>_Logo:_

- The logo has the club’s name embedded into it. I considered adding a title in this area but decided to keep it clean. Also, as the site is mobile first just logo and navigation bar works very well.

#### 7.1.2. <a name='NavigationBar:_'></a>_Navigation Bar:_

- The navigation bar appears on all pages.
- It contains links to the home, ride, Join, and contact page to allow easy navigation around the website.
- There is a hover effect for each link which changes the colour, and an animated bar pops out.
  _The main reason I chose this design for the navigation bar was that for mobiles the nav bar collapses to a menu button, when clicked a vertical menu swipes out and the hamburger menu animates into a cross. The menu closes whenever a link or cross is selected. I adapted the code for the navbar from <https://codepen.io/nicolettafbr/pen/KKNydVK>_/ . Another reason why I was drawn to this code is that it was HTML and CSS only, which fitted in with my objective of practicing the skills.

---

### 7.2. <a name='HeroImages'></a>**Hero Images**

- I have included a hero image only on the index page, this was a design decision to maximise screen real estate for mobiles.
- The hero image has an animation to grab the attention of the user.

---

## 8. <a name='Footer'></a>**Footer**

- The footer appears on all pages and includes direct links to all the CCC social media accounts I adapted this from the Code Institute lesson ‘Mini Project with Bootstrap 4’. It is responsive and I felt fitted with the design while giving me chance to practice Bootstrap.

- These icons were imported from font awesome.

---

## 9. <a name='Typography'></a>**Typography**

- Throughout the page, there are two fonts used:

  - Raleway and Open-sans

  ***

## 10. <a name='IndividualPageContentfeatures'></a>**Individual Page Content features**

### 10.1. <a name='HomeAboutPageContent:'></a>**Home/About Page Content:**

- A hero image with a brief introduction to the club. There is a table showing the days and times of the main club rides.

### 10.2. <a name='RidePageContent:'></a>**Ride Page Content:**

- An introduction to the club rides, ride days and times repeated with more information. A description of the types of rides with distance and speed expectations. A link to the code of conduct pdf. A map showing the starting point of all rides.

### 10.3. <a name='JoinPageContent:'></a>**Join Page Content:**

- A link to the british cycling join page and a link to Strava with instructions how to join.

### 10.4. <a name='ContactPageContent'></a>**Contact Page Content**

- Form used has three required fields.
  - The first two are name and email, so I know who has sent the communication and where to respond appropriately.
  - The third required field is the two radio buttons linked via the attribute value name="mailing_list". The user must select one of these options to click submit and cannot choose both.
- An optional text area is between these required fields so the user can choose to send me a message.
- The submit button has a shimmer effect as feedback when the user hovers the pointer over it.

\_Note: This form gathers data using a third party - formsubmit.co and is only for development purposes.

---

## 11. <a name='Future-Enhancements'></a>**Future-Enhancements**

There are many future enhancements I would make if this were a long-term project. They include:

- A member only section with chat room, small ads, upcoming rides, club routes and club kit store.
- All images need to be optimised for the web.

- I would also make the contact form fully function with a post request and have a database to collate data for the mailing list. The current solution is purely for development and an alternative to a dummy form that doesn't send the data out.

---

## 12. <a name='TestingPhase'></a>**Testing Phase**

Tests using Chrome developer and vs code studio was done at each stage of development.

I used browserstack.com to check how the site looked on the most popular mobile devices and ami.responsiv.is

image.png

the css I ran through http://csslint.net/ no errors were identified.

Parts of my code were tested on codepen.
I used the vs studio code extension Prettier to check and fix my code format.

I used
https://validator.w3.org/nu/?doc=https%3A%2F%2Fictwise.github.io%2Fproject1_ccc%2F
and

https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fictwise.github.io%2Fproject1_ccc%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en
to check my code.

## User Story Testing

| User story                                                                        | Test                                                                                                                                     | Screenshot                                                                         |
| --------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------- |
| As a user, I want to find information on the club.                                | Every page of the site has information on the club, particularly the about section on index.html                                         | <img src="assets\images\aboutSS.png" alt="about screen" style="width:800px;"/>     |
| As a user, I want to be able to join the club.                                    | Every page of the site has a 'Join us' button in the navigation bar                                                                      | <img src="assets\images\joinSS.png" alt="join screen" style="width:800px;"/>       |
| As a user, I want to navigate the page to find what I require quickly and easily. | Every page of the site has a navigation bar/menu that shows all pages of the site                                                        | <img src="assets\images\menuSS.png" alt="menu screen" style="width:800px;"/>       |
| As a user, I want to know how to contact the club.                                | The contact page has a form to contact the club.                                                                                         | <img src="assets\images\contactSS.png" alt="contact screen" style="width:800px;"/> |
| As a user, I was to find ride times and locations.                                | The ride page has all ride times and details, with a location map at the bottom of the screen. Ride times are repeated on the index page | <img src="assets\images\rideSS.png" alt="ride screen" style="width:800px;"/>       |
| As a user, I want to understand what is required of riders on a club ride.        | Ride information is shown on the ride page with a link to a pdf of the club code of conduct.                                             | <img src="assets\images\codSS.png" alt="code of conduct" style="width:800px;"/>    |

## Test Framework

| Test Case                                  |                    |                   |                   |                  |
| ------------------------------------------ | ------------------ | ----------------- | ----------------- | ---------------- |
|                                            | desktop 1600x992px | Laptop 1280x802px | Tablet 768x1024px | Mobile 320x480px |
| index.html                                 |                    |                   |                   |                  |
| Navbar all links work                      | X                  | X                 | X                 | X                |
| Hamburger shows                            |                    |                   | X                 | X                |
| Nav menu opens                             |                    |                   | X                 | X                |
| social media                               |                    |                   |                   |                  |
| hover effect                               | X                  | X                 | X                 | X                |
| links open in new tab to ccc               | X                  | X                 | X                 | X                |
| logos hide                                 |                    |                   | X                 | X                |
| navbar join us link opens in new tab       | X                  | X                 | X                 | X                |
| hero join us link opens in new tab         | X                  | X                 | X                 | X                |
| ride.html                                  |                    |                   |                   |                  |
| Navbar all links work                      | X                  | X                 | X                 | X                |
| Hamburger shows                            |                    |                   | X                 | X                |
| Nav menu opens                             |                    |                   | X                 | X                |
| navbar join us link opens in new tab       | X                  | X                 | X                 | X                |
| social media                               |                    |                   |                   |                  |
| hover effect                               | X                  | X                 | X                 | X                |
| links open in new tab to ccc               | X                  | X                 | X                 | X                |
| logos hide                                 |                    |                   | X                 | X                |
| Code of Conduct opens pdf in new tab       | X                  | X                 | X                 | X                |
| Map shows                                  | X                  | X                 | X                 | X                |
| join.html                                  |                    |                   |                   |                  |
| Navbar all links work                      | X                  | X                 | X                 | X                |
| Hamburger shows                            |                    |                   | X                 | X                |
| navbar join us link opens in new tab       | X                  | X                 | X                 | X                |
| Nav menu opens                             |                    |                   | X                 | X                |
| social media                               |                    |                   |                   |                  |
| hover effect                               | X                  | X                 | X                 | X                |
| links open in new tab to ccc               | X                  | X                 | X                 | X                |
| logos hide                                 |                    |                   | X                 | X                |
| join button opens external link in new tab | X                  | X                 | X                 | X                |
| strava link opens new tab                  | X                  | X                 | X                 | X                |
| contact.html                               |                    |                   |                   |                  |
| Navbar all links work                      | X                  | X                 | X                 | X                |
| Hamburger shows                            |                    |                   | X                 | X                |
| Nav menu opens                             |                    |                   | X                 | X                |
| join button opens external link in new tab | X                  | X                 | X                 | X                |
| social media                               |                    |                   |                   |                  |
| hover effect                               | X                  | X                 | X                 | X                |
| links open in new tab to ccc               | X                  | X                 | X                 | X                |
| logos hide                                 |                    |                   | X                 | X                |
| Submit button sends email                  | X                  | X                 | X                 | X                |

My criteria for error checking and the results can be downloaded [here ](assets/doc/test-cases.xlsx)

## 13. <a name='OpenandClosedIssues'></a> Open and Closed Issues

I fixed many coding errors some problems I had -

- on the contact page there was a shudder when I hovered over the hoverbar, this did not happen on any other page, I deduced it was the form on the page, removing the space-around class from the div fixed this.

- positioning elements on the page, mostly I fixed these using Chrome Developer Tools

- I was disatisfied with the appearance of the first navigation bar I created with bootstrap. I replaced this with an example I adapted from codepen, not realising the code I was using had errors because the output appeared to be good. When running my pages through the w3 validator I found the errors, with the assistance of my mentor I found the fix and then implemented - lesson learnt, when adapting code check the validity of the original first.

Other issues I am aware of but because of time constraints I have not dealt with - although prettier has done a reasonable job of formatting my code I think I could clean it up further.

---

## 14. <a name='Deployment'></a>**Deployment**

I deployed the page on GitHub pages via the following procedure: -

1. From the project's [repository](https://github.com/ictwise/project1_ccc), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.
   You can find the live site [here.](https://ictwise.github.io/project1_ccc/)
   <br>

---

## 15. <a name='Credits'></a>**Credits**

- <https://codepen.io/nicolettafbr/pen/KKNydVK*/> for the NavBar.
  The Code Institute – Love Running and Resume.<br>
- <https://www.youtube.com/watch?v=r4RQ38EoLds&t> contact form.
- <https://github.com/dnlbowers/modern-buddhism> and others on GitHub for ideas on completing the readme
- <https://google-map-generator.com/> was used to create the map on the joining page.

### 15.1. <a name='Generalreference:'></a>**General reference:**

- I relied upon W3schools, git hub, slack, YouTube and stack overflow for general references throughout the project.

### 15.2. <a name='Content:'></a>**Content:**

- Most of the content was provided by CCC.
- All fonts imported from - [Google Fonts](https://fonts.google.com/)

### 15.3. <a name='Media:'></a>**Media:**

- images created by wirestock - www.freepik.com
