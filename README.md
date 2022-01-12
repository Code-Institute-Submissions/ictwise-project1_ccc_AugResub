# project1_ccc

# Caerphilly Cycling Club

Static responsive website - Stream 1 Project.

I'm a member of Caerphilly Cycling Club. We have a serviceable website, it's static, has not been changed in more than 5 years but generally the content is good. The main failing of the site is that it is not responsive. A sample survey of current members showed that during the last 5 years most users have moved from desktop to mobile devices to view the site.

Any design needs to be mobile first.

# Demo

A live demo of this project can be found [here](https://ictwise.github.io/project1_ccc/).
![Desktop Demo](https://www.caerphillycc.co.uk/wp-content/uploads/2021/05/CCC-Castle-Path-1010x300.jpg "Desktop Demo")

# UX

## Users stories

#### Potential new club members

Need to find out about the club - rides, how to prepare for a ride, how to join the club, what kind of riders already belong to the club.

#### Existing club members

May need to check club rules. See information on club rides. See recent photos. Foster a sense of pride in the club.

#### General public

May want to contact the club to make complaints about club members road use.

#### Public officials

Ask for advice from the club members and committee about policy decisions.

## Design

The club logo and club colours were already set. The culb is often refered to as 'the Green Machine' therfore green and an accent red would always be the colours. To reflect the vibrant nature of the club I wanted to include some animation, video images generally the feeling of movement. The issue with responsiveness had to be addressed, the top navigation bar did not collapse on mobiles and took up most of the real estate on a mobile screen. It was important the new design resolved this.

![image](https://user-images.githubusercontent.com/57628753/146191222-f71e8819-320d-4c06-a901-f10eb82550e3.png)

I created a wireframe for mobile, tablet and desktop. This helped me understand the structure of the site I was creating and focus for the initial design.

## Technologies used

1. HTML5
2. CSS
3. Boostrap 4

Pages were built and staged in Visual Studio Code before being commited to Github.

## Development Process

Mobile first. Grid system/bootstrap. Visual Studio Code. Correct semantics. This was my primary objective.
I looked at this as an opportunity to practicve my skills specifically those learnt while creating the Code institute 'Love running' site and the Bootstrap resume example.

My first attempt at the index page recreated parts of both (code institute) sites adapting them to new website needs. On creation of the index.html and after discussions with my mentor I was disatisfied with the result. The page was responsive as bootstrap was used for the navigation bar and the footer but the design was - gaudy. I also felt that I had not gained enough practices using HTML and CSS. I wanted a simpler more elegant interface and practice with the DOM for positioning, and understanding margins, borders and padding. I had also many snippets from CSS I'd been trying out. My code was far from beautiful! I was pleased with the footer. Built using Bootstrap the Social media section worked perfectly but the navigation bar although working well, very responsive just looked too bright. Red and green in the shades the club use are intended for cars to see you clearly on the road, on a website they can look very busy.

I researched many alternatives on the web, finally in codepen i found a navigation bar i wanted to adapt and use. https://codepen.io/nicolettafbr/pen/KKNydVK*/

to add the map in the joining section i took advantage of https://google-map-generator.com/

### Sprints:

#### design

Define strategy, build wireframes, finalise fonts/colour schemes/images

#### create home page, test, retrospective

Check for look and feel

#### build responsiveness

test at different resolutions.

#### create other pages

duplicate Header and footer of index, build other pages, test

#### build contact us

Build form
Test entire site at various resolutions and using online testing tools

# Demo

A live demo of this project can be found [here](https://ictwise.github.io/project1_ccc/).
![Desktop Demo](https://www.caerphillycc.co.uk/wp-content/uploads/2021/05/CCC-Castle-Path-1010x300.jpg "Desktop Demo")

## Table of contents:

1. [**Site Overview**](#site-overview)
1. [**Planning stage**](#planning-stage)
   - [**_Target Audiences_**](#target-audiences)
   - [**_User Stories_**](#user-stories)
   - [**_Site Aims_**](#site-aims)
   - [**_How Is This Will Be Achieved:_**](#how-is-this-will-be-achieved)
   - [**_Wireframes_**](#wireframes)
   - [**_Color Scheme_**](#color-scheme)
1. [**Current Features Common to all pages**](#current-features-common-to-all-pages)
   - [**_Header Element:_**](#header-element)
     - [_Logo_](#logos)
     - [_Navigation Bar_](#navigation-bar)
   - [**Hero Images:**](#hero-images)
     - [**_About Page_**:](#about-page)
       - [_Hero-Image_](#hero-image)
       - [_Quote_](#quote)
     - [**_Teachings page_**:](#teachings-page)
       - [_Hero-Image_](#hero-image-1)
       - [_Quote_](#quote-1)
     - [**_Community page:_**](#community-page)
       - [_Hero-Image_](#hero-image-2)
       - [_Quote_](#quote-2)
     - [**_Contact and Form-Feedback pages:_**](#contact-and-form-feedback-pages)
       - [_Hero-Image_](#hero-image-3)
       - [_Quote_](#quote-3)
   - [**Anchor Tags Within all Pages Main Content**](#anchor-tags-within-all-pages-main-content)
   - [**Footer**](#footer)
   - [**Typography**](#typography)
1. [**Individual Page Content features**](#individual-page-content-features)
   - [**About Page Content**](#about-page-content)
   - [**Teachings Page Content**](#teachings-page-content)
   - [**Community Page Content**](#community-page-content)
   - [**Contact Page Content**](#contact-page-content)
   - [**Form Feedback Page Content**](#form-feedback-page-content)
1. [**Future-Enhancements**](#future-enhancements)
1. [**Testing Phase**](#testing-phase)
1. [**Deployment**](#deployment)
1. [**Credits**](#credits)
   - [**Honorable mentions**](#honorable-mentions)
   - [**General reference**](#general-reference)
   - [**Content**](#content)
   - [**Media**](#media)

## **Planning stage**

### **Target Audiences:**

#### Potential new club members

Need to find out about the club - rides, how to prepare for a ride, how to join the club, what kind of riders already belong to the club.

#### Existing club members

May need to check club rules. See information on club rides. See recent photos. Foster a sense of pride in the club.

#### General public

May want to contact the club to make complaints about club members road use.

#### Public officials

Ask for advice from the club members and committee about policy decisions.

### **User Stories:**

- As a user, I want to find information on the club.
- As a user, I want to navigate the page to find what I require quickly and easily.
- As a user, I want to know how to contact the club.
- As a user, I was to find ride times and locations.
- As a user, I want to understand what is required of riders on a club ride.

### **Site Aims:**

- To inform users about CCC.
- To educate the user on basic ride etiquette.
- To offer the user a chance to connect with the club.
- Provide the user with the information on club rides.
- Provide a method by which the user can subscribe to a newsletter.

### **How Is This Will Be Achieved:**

- The home page provides the user with a summary of the club. There is a rides page that gives details of ride time, ride etiquette and links to ride advice. The contacts page has a contact form and a checkbox to sign up for the newsletter.

### **Wireframes:**

To organize my thoughts and prevent scope creep, I created wireframes for this project. Below are links to each of the mobile and desktop versions of the four intended pages.

- Wireframes:

There was some deviation from the original wireframes to improve the User Experience (UX). Such variations include: -

### **Color Scheme:**

The club logo and club colours were already set. The culb is often refered to as 'the Green Machine' therfore green and an accent red would always be the colours.

## **Current Features Common to all pages**

### **Header Element**

The header element is sticky adhering to popular conventions, as the user scrolls the header remains at the top of the page. The header contains the following features:

#### _Logo:_

- The logo has the club name embedded into it. I considered adding a title in this area but decided to keep it clean. Also as the site is mobile first just logo and navigation bar works very well.

#### _Navigation Bar:_

- The navigation bar appears on all pages.
- It contains links to the home, ride, Join, and contact page to allow easy navigation around the website.
- There is a hover effect for each link which changes the colour and an animated bar pops out.
  _The main reason I chose this design for the navigation bar was that for mobiles the nav bar collapses to a menu button, when clicked a vertical menu swipes out and the hamburger menu animates into a cross. The menu closes whenever a link or cross is selected. I adapted the code for the navbar from https://codepen.io/nicolettafbr/pen/KKNydVK_/ . Another reason why I was drawn to this code is that it was HTML and CSS only, which fitted in with my objective of practicing the skills.

---

### **Hero Images**

- I have included a hero image only on the index page, this was a design decision to maximise screen real estate for mobiles .
- The hero image has an animation to grab the attention of the user.

## **Footer**

- The footer includes direct links to all the CCC social media accounts I adapted this from the Code Institute lesson ‘Mini Project with Bootstrap 4’. It is responsive and I felt fitted with the design while giving me chance to practice Bootstrap.

- These icons were imported from font awesome.

## **Typography**

- Throughout the page, there are two fonts used:
  - Raleway and Open-sans

## **Individual Page Content features**

### **Home/About Page Content:**

### **Ride Page Content:**

### **Join Page Content:**

\*xxxxxxxx

### **Contact Page Content**

- The user is offered a way to contact me as the site author should they wish to discuss the subject matter further. This section includes a short biography about me and my experience in the NKT.
- Form used has three required fields.
  - The first two are name and email, so I know who has sent the communication and where to respond appropriately.
  - The third required field is the two radio buttons linked via the attribute value name="mailing_list". The user must select one of these options to click submit and cannot choose both.
- An optional text area is between these required fields so the user can choose to send me a message.
- The submit button has a shimmer effect as feedback when the user hovers the pointer over it.

_Note: This form doesn't gather any data; it was created with a GET request to call a feedback page. The submit button then triggers the GET request to load the form feedback page outlined later in the readme. This feature is to simulate a real functional form only._

## **Future-Enhancements**

\*There are many future enhancements I would make if this were a long term project. They include:
• A members only section with chat room, small ads, upcoming rides, club routes and club kit store.

- I would also make the contact form fully function with a post request and have a database to collate data for the mailing list.

---

## **Testing Phase**

I have included details of testing both during development and post development in a separate document called [TESTING.md](TESTING.md).

---

## **Deployment**

I deployed the page on GitHub pages via the following procedure: -

1. From the project's [repository](https://github.com/dnlbowers/modern-buddhism), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.

You can find the live site via the following URL -

---

## **Credits**

https://codepen.io/nicolettafbr/pen/KKNydVK*/ for the NavBar.
The Code Institute – Love Running and Resume.
https://www.youtube.com/watch?v=r4RQ38EoLds&t contact form.
https://github.com/dnlbowers/modern-buddhism and others on github for ideas on completing the read.me

### **General reference:**

- I relied upon W3schools, git hub, slack, youtube and stack overflow for general references throughout the project.

### **Content:**

- Most of the content was provided by CCC.
- All fonts imported from - [Google Fonts](https://fonts.google.com/)

### **Media:**

- images provided by CCC
