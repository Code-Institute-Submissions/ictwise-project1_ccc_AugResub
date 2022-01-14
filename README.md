<!-- vscode-markdown-toc -->

- 1. [Static responsive website - Stream 1 Project.](#Staticresponsivewebsite-Stream1Project.)
     - 1.1. [Potential new club members](#Potentialnewclubmembers)
     - 1.2. [Existing club members](#Existingclubmembers)
     - 1.3. [General public](#Generalpublic)
     - 1.4. [Public officials](#Publicofficials)
- 2. [Design](#Design)
- 3. [Technologies used](#Technologiesused)
- 4. [Development Process](#DevelopmentProcess)
  - 4.1. [Sprints](#Sprints)
    - 4.1.1. [design](#design)
    - 4.1.2. [create home page, test, retrospective](#createhomepagetestretrospective)
    - 4.1.3. [build responsiveness](#buildresponsiveness)
    - 4.1.4. [create other pages](#createotherpages)
    - 4.1.5. [build contact us](#buildcontactus)
- 5. [Table of contents](#Tableofcontents)
- 6. [**Planning stage**](#Planningstage)
  - 6.1. [**Target Audiences:**](#TargetAudiences:)
    - 6.1.1. [Potential new club members](#Potentialnewclubmembers-1)
    - 6.1.2. [Existing club members](#Existingclubmembers-1)
    - 6.1.3. [General public](#Generalpublic-1)
    - 6.1.4. [Public officials](#Publicofficials-1)
  - 6.2. [**User Stories:**](#UserStories:)
  - 6.3. [**Site Aims:**](#SiteAims:)
  - 6.4. [**How Is This Will Be Achieved:**](#HowIsThisWillBeAchieved:)
  - 6.5. [**Wireframes:**](#Wireframes:)
  - 6.6. [**Color Scheme:**](#ColorScheme:)
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
- 13. [**Deployment**](#Deployment)
- 14. [**Credits**](#Credits)
  - 14.1. [**General reference:**](#Generalreference:)
  - 14.2. [**Content:**](#Content:)
  - 14.3. [**Media:**](#Media:)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## 1. <a name='Staticresponsivewebsite-Stream1Project.'></a>Static responsive website - Stream 1 Project.

I'm a member of Caerphilly Cycling Club. We have a serviceable website, it's static, has not been changed in more than 5 years but generally the content is good. The main failing of the site is that it is not responsive. A sample survey of current members showed that during the last 5 years most users have moved from desktop to mobile devices to view the site.

Any design needs to be mobile first.

# Demo

A live demo of this project can be found [here](https://ictwise.github.io/project1_ccc/).
![Desktop Demo](https://www.caerphillycc.co.uk/wp-content/uploads/2021/05/CCC-Castle-Path-1010x300.jpg "Desktop Demo")

# UX

<!-- ## 1. <a name='Usersstories'>

</a>Users stories

####  1.1. <a name='Potentialnewclubmembers'></a>Potential new club members

Need to find out about the club - rides, how to prepare for a ride, how to join the club, what kind of riders already belong to the club.

####  1.2. <a name='Existingclubmembers'></a>Existing club members

May need to check club rules. See information on club rides. See recent photos. Foster a sense of pride in the club.

####  1.3. <a name='Generalpublic'></a>General public

May want to contact the club to make complaints about club members road use.

####  1.4. <a name='Publicofficials'></a>Public officials

Ask for advice from the club members and committee about policy decisions. -->

## 1. <a name='Design'></a>Design

The club logo and club colours were already set. The culb is often refered to as 'the Green Machine' therfore green and an accent red would always be the colours. To reflect the vibrant nature of the club I wanted to include some animation, video images generally the feeling of movement. The issue with responsiveness had to be addressed, the top navigation bar did not collapse on mobiles and took up most of the real estate on a mobile screen. It was important the new design resolved this.

![image](https://user-images.githubusercontent.com/57628753/146191222-f71e8819-320d-4c06-a901-f10eb82550e3.png)

I created a wireframe for mobile, tablet and desktop. This helped me understand the structure of the site I was creating and focus for the initial design.

## 2. <a name='Technologiesused'></a>Technologies used

1. HTML5
2. CSS
3. Boostrap 4

Pages were built and staged in Visual Studio Code before being commited to Github.

## 3. <a name='DevelopmentProcess'></a>Development Process

Mobile first. Grid system/bootstrap. Visual Studio Code. Correct semantics. This was my primary objective.
I looked at this as an opportunity to practicve my skills specifically those learnt while creating the Code institute 'Love running' site and the Bootstrap resume example.

My first attempt at the index page recreated parts of both (code institute) sites adapting them to new website needs. On creation of the index.html and after discussions with my mentor I was disatisfied with the result. The page was responsive as bootstrap was used for the navigation bar and the footer but the design was - gaudy. I also felt that I had not gained enough practices using HTML and CSS. I wanted a simpler more elegant interface and practice with the DOM for positioning, and understanding margins, borders and padding. I had also many snippets from CSS I'd been trying out. My code was far from beautiful! I was pleased with the footer. Built using Bootstrap the Social media section worked perfectly but the navigation bar although working well, very responsive just looked too bright. Red and green in the shades the club use are intended for cars to see you clearly on the road, on a website they can look very busy.

I researched many alternatives on the web, finally in codepen i found a navigation bar i wanted to adapt and use. <https://codepen.io/nicolettafbr/pen/KKNydVK*/>

to add the map in the joining section i took advantage of <https://google-map-generator.com/>

### 3.1. <a name='Sprints'></a>Sprints

#### 3.1.1. <a name='design'></a>design

Define strategy, build wireframes, finalise fonts/colour schemes/images

#### 3.1.2. <a name='createhomepagetestretrospective'></a>create home page, test, retrospective

Check for look and feel

#### 3.1.3. <a name='buildresponsiveness'></a>build responsiveness

test at different resolutions.

#### 4.1.4. <a name='createotherpages'></a>create other pages

duplicate Header and footer of index, build other pages, test

#### 4.1.5. <a name='buildcontactus'></a>build contact us

Build form
Test entire site at various resolutions and using online testing tools

## 6. <a name='Planningstage'></a>**Planning stage**

### 6.1. <a name='TargetAudiences:'></a>**Target Audiences:**

#### 6.1.1. <a name='Potentialnewclubmembers-1'></a>Potential new club members

Need to find out about the club - rides, how to prepare for a ride, how to join the club, what kind of riders already belong to the club.

#### 6.1.2. <a name='Existingclubmembers-1'></a>Existing club members

May need to check club rules. See information on club rides. See recent photos. Foster a sense of pride in the club.

#### 6.1.3. <a name='Generalpublic-1'></a>General public

May want to contact the club to make complaints about club members road use.

#### 6.1.4. <a name='Publicofficials-1'></a>Public officials

Ask for advice from the club members and committee about policy decisions.

### 6.2. <a name='UserStories:'></a>**User Stories:**

- As a user, I want to find information on the club.
- As a user, I want to navigate the page to find what I require quickly and easily.
- As a user, I want to know how to contact the club.
- As a user, I was to find ride times and locations.
- As a user, I want to understand what is required of riders on a club ride.

### 6.3. <a name='SiteAims:'></a>**Site Aims:**

- To inform users about CCC.
- To educate the user on basic ride etiquette.
- To offer the user a chance to connect with the club.
- Provide the user with the information on club rides.
- Provide a method by which the user can subscribe to a newsletter.

### 6.4. <a name='HowIsThisWillBeAchieved:'></a>**How Is This Will Be Achieved:**

- The home page provides the user with a summary of the club. There is a rides page that gives details of ride time, ride etiquette and links to ride advice. The contacts page has a contact form and a checkbox to sign up for the newsletter.

## <a name='Wireframes:'></a>**Wireframes:**

To organize my thoughts and prevent scope creep, I created wireframes for this project. Below are links to each of the mobile and desktop versions of the four intended pages.

- Wireframes:

There was some deviation from the original wireframes to improve the User Experience (UX). Such variations include: -

## <a name='ColorScheme:'></a>**Color Scheme:**

The club logo and club colours were already set. The culb is often refered to as 'the Green Machine' therfore green and an accent red would always be the colours.

## 7. <a name='CurrentFeaturesCommontoallpages'></a>**Current Features Common to all pages**

### 7.1. <a name='HeaderElement'></a>**Header Element**

The header element is sticky adhering to popular conventions, as the user scrolls the header remains at the top of the page. The header contains the following features:

#### 7.1.1. <a name='Logo:_'></a>_Logo:_

- The logo has the club name embedded into it. I considered adding a title in this area but decided to keep it clean. Also as the site is mobile first just logo and navigation bar works very well.

#### 7.1.2. <a name='NavigationBar:_'></a>_Navigation Bar:_

- The navigation bar appears on all pages.
- It contains links to the home, ride, Join, and contact page to allow easy navigation around the website.
- There is a hover effect for each link which changes the colour and an animated bar pops out.
  _The main reason I chose this design for the navigation bar was that for mobiles the nav bar collapses to a menu button, when clicked a vertical menu swipes out and the hamburger menu animates into a cross. The menu closes whenever a link or cross is selected. I adapted the code for the navbar from <https://codepen.io/nicolettafbr/pen/KKNydVK>_/ . Another reason why I was drawn to this code is that it was HTML and CSS only, which fitted in with my objective of practicing the skills.

---

### 7.2. <a name='HeroImages'></a>**Hero Images**

- I have included a hero image only on the index page, this was a design decision to maximise screen real estate for mobiles .
- The hero image has an animation to grab the attention of the user.

## 8. <a name='Footer'></a>**Footer**

- The footer appears on all pages and includes direct links to all the CCC social media accounts I adapted this from the Code Institute lesson ‘Mini Project with Bootstrap 4’. It is responsive and I felt fitted with the design while giving me chance to practice Bootstrap.

- These icons were imported from font awesome.

## 9. <a name='Typography'></a>**Typography**

- Throughout the page, there are two fonts used:
  - Raleway and Open-sans

## 10. <a name='IndividualPageContentfeatures'></a>**Individual Page Content features**

### 10.1. <a name='HomeAboutPageContent:'></a>**Home/About Page Content:**

- A hero image with a brief introduction to the club. There is a table showing the days and times of the main club rides.

### 10.2. <a name='RidePageContent:'></a>**Ride Page Content:**

- An introduction to the club rides, ride days and times repeated with more information. A description of the types of rides with distance and speed expectations. A map showing the starting point of all rides.

### 10.3. <a name='JoinPageContent:'></a>**Join Page Content:**

### 10.4. <a name='ContactPageContent'></a>**Contact Page Content**

- The user is offered a way to contact me as the site author should they wish to discuss the subject matter further. This section includes a short biography about me and my experience in the NKT.
- Form used has three required fields.
  - The first two are name and email, so I know who has sent the communication and where to respond appropriately.
  - The third required field is the two radio buttons linked via the attribute value name="mailing_list". The user must select one of these options to click submit and cannot choose both.
- An optional text area is between these required fields so the user can choose to send me a message.
- The submit button has a shimmer effect as feedback when the user hovers the pointer over it.

_Note: This form doesn't gather any data; it was created with a GET request to call a feedback page. The submit button then triggers the GET request to load the form feedback page outlined later in the readme. This feature is to simulate a real functional form only._

## 11. <a name='Future-Enhancements'></a>**Future-Enhancements**

\*There are many future enhancements I would make if this were a long term project. They include:
• A members only section with chat room, small ads, upcoming rides, club routes and club kit store.

- I would also make the contact form fully function with a post request and have a database to collate data for the mailing list.

---

## 12. <a name='TestingPhase'></a>**Testing Phase**

I have included details of testing both during development and post development in a separate document called [TESTING.md](TESTING.md).

---

## 13. <a name='Deployment'></a>**Deployment**

I deployed the page on GitHub pages via the following procedure: -

1. From the project's [repository](https://github.com/dnlbowers/modern-buddhism), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.

You can find the live site via the following URL -

---

## 14. <a name='Credits'></a>**Credits**

<https://codepen.io/nicolettafbr/pen/KKNydVK*/> for the NavBar.
The Code Institute – Love Running and Resume.
<https://www.youtube.com/watch?v=r4RQ38EoLds&t> contact form.
<https://github.com/dnlbowers/modern-buddhism> and others on github for ideas on completing the read.me

### 14.1. <a name='Generalreference:'></a>**General reference:**

- I relied upon W3schools, git hub, slack, youtube and stack overflow for general references throughout the project.

### 14.2. <a name='Content:'></a>**Content:**

- Most of the content was provided by CCC.
- All fonts imported from - [Google Fonts](https://fonts.google.com/)

### 14.3. <a name='Media:'></a>**Media:**

- images provided by CCC
