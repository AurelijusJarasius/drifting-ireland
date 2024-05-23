# Drifting Ireland
## A website built to highlight the popularity of drifting in Ireland, history, events and driver information.
### Aurelijus Jarasius

![am I responsive screenshot](assets/images/responsive-screenshot.webp)

## **[Live site](https://aurelijusjarasius.github.io/drifting-ireland/)**

## **[Repository](https://github.com/AurelijusJarasius/drifting-ireland/)**

## Table of Contents

 1. [ UX ](#ux)
 2. [ Features ](#features)  
 3. [ Future Features ](#future)  
 4. [ Technology used ](#tech) 
 5. [ Testing ](#testing)  
 6. [ Bugs ](#bugs)  
 7. [ Deployment](#deployment)
 8. [ Credits](#credits)
 9. [ Content](#content)  
 10. [ Acknowledgements](#acknowledgements) 

## UX

<a name="ux"></a>
### Pre-project planning
When choosing a project I thought of things that I am interested in and passionate about. This has led be to drifting as there aren't a lot of websites like this for Irish drifting specifically.

I then researched different websites which contain information on Irish drifting, events and drivers:
- https://www.irishdriftchampionship.com/
- https://dm.gp/
- https://shop.driftgames.life/ 
- https://www.lzworldtour.com/ 
- https://www.juiceboxforyou.com/

This has led me to the conclusion that while there is a lot of information out there, it takes some time to scroll through all the websites and find the information you're after. Therefore I decided to build a website which hosts all relevant information in one place.

## UX Design

### To identify the best way forward for my project, I started looking at the user and business requirements for this type of website

## User Stories
> As a new user I want to learn what is drifting

> As a user I want to find event calendar

> As a user I want to learn about drivers

> As a user I want to be able to get newsletters

## Owner
> As an owner I want to inform about drifting

> As an owner I want to share event details

> As an owner I want to share driver bio

> As an owner I want to share updates about events and drivers

## Scope Plane
> Website should have consistent navigation pane across all devices

> Website should have a hero message so the users understand what the website is about

> Website should detail information about drifting, it's origins and drifting in Ireland

> Website should contain event calendar

> Website should contain Irish driver details

> Website should contain newsletter sign up option

## Structure Plane
> Website will contain 4 pages: Home, Events, Drivers, Sign Up

### Home Page
> Navigation with links

> Hero message

> Origins of drifting and images of fathers of drifting

> Technicalities of drifting & a video explaining it

> Roots of drifting in Ireland and when did it become popular

> Call to action to sign up to a newsletter

### Events Page

> Irish Drift Championship calendar

> Drift Masters European Championship calendar

> LZ World Tour calendar

### Drivers Page

> James Deane high level bio

> Jack Shanahan high level bio

> Conor Shanahan high level bio

> Duane Mckeever high level bio

### Sign Up Page

> Form to sign up for a newsletter

## Skeleton Pane

### Home Page
![Homepage desktop frame](assets/images/Home-page.webp)

### Events Page
![Events page desktop frame](assets/images/Home-page.webp)

### Drivers Page
![Drivers page desktop frame](assets/images/Drivers-page.webp)

### Signup Page
![Signup page desktop frame](assets/images/signup-page.webp)

> Design of the website is meant to be simple and provide relevant information without any clutter. As I worked through the project, I had to change the design as it did not look how I wanted. I had to change the background and reorder the content.

> Initially I chose an image of a car as a background, however the image was bright in color which made it difficult to read text. When added in shading around text, the website did not look right. I opted for a dark charcoal color background with colours coming in from logo and images.

### Colours
> I decided that the best way forward will be to keep colours of text and background plain and simple with images providing colour.

> This also meant that with a dark background images had much more visual impact to the end user

#### Fonts

- Briem Hand
- Open Sans

#### Colours

> Text colour kept to a single colour. Logo and box shading colours used where taken from the logo colours to keep colouring to a minimum

- #FFFFFF
- #FF883E
- #DFE6E6
- #169B62

# Features

<a name="features"></a>

### index.html

#### Navigation Bar
![Navigation Bar](assets/images/navigation-bar.png)
> Navigation bar consists of 4 links in the center of the page

![Navigation Bar Mobile](assets/images/navigation-mobile.png)

> For mobile use navigation bar shrinks to burger icon

#### Hero Section
![Hero-image](assets/images/hero.png)

> Image with a flex box overlay. This section is intended to draw attention the image as not many people are familiar with what drifting is. It serves the purpose of both image content and explanation on what drifting is.

#### Origins Section
![origins-text-images](assets/images/origins.png)

> Text explaining origins and a slideshow containing images of the mentioned drivers. This section is intended to give a brief history lesson on where drifting comes from. Images in the slideshow give an impact to how far drifting dates back to.

#### Technical Bit Section
![Technical-text-video](assets/images/technical.png)

> Text explaining technical (boring) bit of drifting and an iframe video to youtube. Intention here is to explain how drifting works in theory. It is not the most exciting part so a video accompanies the text to make it more interesting.

#### Roots in Ireland Section
![Roots-section](assets/images/Roots.png)

> Text explaining roots of drifting in Ireland with an image underneath. The intention of this section is to showcase when drifting has become popular in Ireland.

#### Call to signup Section
![Call-to-action](assets/images/call-to-action.png)

> Bar across the page with a call to action. This links to the sign up page. The intention is to get people to sign up and build a database for potential future features.

#### Footer with social media links
![Footer](assets/images/social-media.png)

> Footer used to showcase social media icons. Clicking on the icons will redirect to external pages in a new tab.

### events.html

#### Event Calendar
![Event-calendar](assets/images/event-calendar.png)

> Images of the competition logos

> Event calendar under each competition logo

### drivers.html

#### Irish Drivers
![Driver-info](assets/images/drivers.png)

> Picture of 4 most famous drivers in Ireland. Basic bio information. Age, place of Birth and winnings to date.

### sign-up.html

#### Sign Up form
![Signup-form](assets/images/Signup.png)

> Basic sign up form with email validation. Name, Last Name & email address.

<a name="Future"></a>
# Future Features
### Home Page
> Additional section with videos from main figures in drifting community

> Additional section with ways on how to get involved

### Events Page

> Embed google maps to each event location

> Add sections for upcoming and past events

> Add an option to purchase tickets direct from the website for upcoming events

### Drivers Page

> Add links to drivers social media platforms

> Add more information about drivers, including videos of highlight reels

> Add links to drivers merch shops

### NEW Page - Community

> Add sections for various communities around Ireland

### Sign Up Page

> Add more detail to the form, to gather more data and customize newsletters
- Competition Preference
- Driver Preference
- Competitor or Spectator

<a name="testing"></a>
# Testing
> Majority of the testing has been conducted manually by myself and a few relatives to ensure the site is useable, responsive and it's easy to navigate

### Testing Phase
#### Testing for links and form
| Test | Expectation | Result |
|--|--|--|
All links on navigation bar | 1. Logo = Redirect to index.html 2. Home = Redirect to index.html 3. Events = Redirect to events.html 4. Drivers = Redirect to drivers.html 5. Signup = Redirect to sign-up.html | Pass |
Sign up to our newsletter banner on the bottom of the page | Redirect to sign-up.html | Pass |
Footer social media links (external links) | 1. Facebook Icon = New tab, redirect to facebook 2. Instagram Icon = New tab, redirect to instagram 3. X Icon = New tab, redirect to X 4. Youtube Icon = New tab, redirect to youtube | Pass |
Sign up form | User prevented from entering email address without @ | Pass |
Image links on events page (external links) | 1. IDC logo = Redirect to IDC page 2. DMEC logo = Redirect to DMEC page 3. LZWT Logo = Redirect to LZWT page | Pass |

#### Testing for responsiveness
| Test | Result |
|--|--|
Home page, about, portfolio, contact us displays correctly on screens less than 769px | Pass |
Home page, about, portfolio, contact us displays correctly on screens larger than 992px | Pass |

#### User Testing
| Test | Result |
|--|--|
Navigate to to sign up to our newsletter and sign up to the newsletter | Pass |
Navigate to the bottom of the page and navigate to facebook | Pass |
Find how many winnings does Conor Shanahan have | Pass |
Find when is the next Drift Masters event in Ireland | Pass |

### Browser Testing
| Browser | Test | Expectation | Result |
|--|--|--|--|
Chrome | Browse through all website | Content displayed correctly, all links work as expected | Pass |
Edge | Browse through all website | Content displayed correctly, all links work as expected | Pass |
Firefox  | Browse through all website | Content displayed correctly, all links work as expected | Pass |
Opera  | Browse through all website | Content displayed correctly, all links work as expected | Pass |
Safari  | Browse through all website | Content displayed correctly, all links work as expected | Pass |

> Safari: light variation in colors/fonts

## Mobile/Tablet Testing
| Device | Test | Expectation | Result |
|--|--|--|--|
OnePlus Nord 2 | Browse through all website | Content displayed correctly, all links work as expected | Pass |
Samsung Galaxy A22 | Browse through all website | Content displayed correctly, all links work as expected | Pass |
OnePlus Pad | Browse through all website | Content displayed correctly, all links work as expected | Pass |
iPhone 15 Pro | Browse through all website | Content displayed correctly, all links work as expected | Pass |
iPhone 12 Pro | Browse through all website | Content displayed correctly, all links work as expected | Pass |
Huawei P30 Pro | Browse through all website | Content displayed correctly, all links work as expected | Pass |



## Google Lightouse Testing

### index.html
![Google Lightouse index.html](assets/images/Homepage-test.png)

### events.html
![Google Lightouse events.html](assets/images/Events-page-test.png)

### drivers.html
![Google Lightouse drivers.html](assets/images/drivers-page-test.png)

### sign-up.html
![Google Lightouse sign-up.html](assets/images/signup-page-test.png)

## HTML Validation

### index.html
![html validation index.html](assets/images/html-validation-index.png)

### events.html
![html validation events.html](assets/images/html-validation-events.png)

### drivers.html
![html validation drivers.html](assets/images/html-validation-drivers.png)

### sign-up.html
![html validation sign-up.html](assets/images/html-validation-sign-up.png)

## CSS Validation
![css validation](assets/images/css-validation.png)

<a name="bugs"></a>
## Bugs
> Issues with youtube video refusing to connect. **Fixed**
![youtube bug 1](assets/images/youtube-bug1.png)

> Original background did not look well with content, made it difficult to read. **Fixed**

> Contrast issue with nav drop down on mobile, hard to see navigation links **Fixed**
![nav bug](assets/images/nav-bug.png)

> Video and images not positioning correctly on larger screens 992px and up **Fixed**

> On the drivers page, not all driver name centred **Known**

<a name="deployment"></a>
## Deployment

> To deploy the project I followed these steps starting from the main project repository [here](https://github.com/AurelijusJarasius/drifting-ireland).

 1. Clicked on `Settings` on the navigation menu in the repository
 2. I then selected the `Pages` menu on the side bar.
 3. In the first dropdown menu labelled `Source` I selected the branch of the name `main` from the dropdown.
 4. In the next dropdown labelled `/root` I left as the default option.
 5. Selected Save
 
> I then received a notification from GitHub that my project is being deployed and after about 1 minute & a couple of refreshes of the page it was ready and live.

<a name="credits"></a>
## Credits

> Background image : https://www.freepik.com/free-photo/dark-grunge-texture_982950.htm#query=charcoal%20background&position=3&from_view=keyword&track=ais_user&uuid=3f6db062-0537-4c12-b059-b0e75ee6c038 

> What is drifting content: https://en.wikipedia.org/wiki/Drifting_(motorsport)

> Drifting Roots in Ireland content: https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+3/courseware/e805068059af42af87681032aa64053f/92a91cf7fcee4361a2af651b7827a341/  

> Youtube video: https://www.youtube.com/watch?v=2GhYuKIbYGk&t=94s 

> Iframe style: Course content - https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+HE101+2/courseware/fcc67a894619420399970ae84fc4802f/13db720675f94dbca6b0fe79467628ca/ 

> Newsletter call to action banner: https://www.scaler.com/topics/how-to-redirect-from-one-page-to-another-in-html-on-button-click/  

> Hero Image - Photo by IDC: https://www.facebook.com/BurkeLubricants/photos/t.100071575119290/1387911637976706/?type=3  

> Tazio Nuvolari image - Photo by Central Press // Getty Images : https://www.roadandtrack.com/motorsports/a29267/the-legend-of-tazio-nuvolari/  

> Sir Stirling Moss image - Photo by Reuters  : https://s7757.pcdn.co/wp-content/uploads/2020/04/200412Moss-8.jpg  

> Japan drift image - Photo by  : https://scontent.fdub1-3.fna.fbcdn.net/v/t39.30808-6/369784580_805524438240846_4785509070831530953_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=5f2048&_nc_ohc=0VJbcI2pgMkQ7kNvgH2LObZ&_nc_ht=scontent.fdub1-3.fna&oh=00_AYBxsFY-AsWQgc95jSIs9j8WgkqlM-1rKj3mqVDVO6aNGw&oe=665124DC  

> Origins slideshow code : https://www.w3schools.com/howto/howto_js_slideshow.asp 

> Bottom Image - Photo By IDC : https://scontent.fdub1-4.fna.fbcdn.net/v/t31.18172-8/14500194_867154456719096_8167580349029681826_o.jpg?_nc_cat=106&ccb=1-7&_nc_sid=5f2048&_nc_ohc=QVIJNXpwyocQ7kNvgErrTy_&_nc_ht=scontent.fdub1-4.fna&oh=00_AYAuOsHStWRrUTkGefwwZQiYs2De-jUvI7JFQL2BkmVzCQ&oe=6672B7B1 

> Events page - IDC Logo : https://www.irishdriftchampionship.com/ 

> Events page - DMEC Logo : https://static.wixstatic.com/media/8b596f_3756347a31b44ddcaa288deef727f1c0~mv2.jpg/v1/fill/w_979,h_552,fp_0.50_0.50,q_85,usm_0.66_1.00_0.01,enc_auto/8b596f_3756347a31b44ddcaa288deef727f1c0~mv2.jpg 

> Events page - LZWT Logo : https://www.lzworldtour.com/

> Drivers page - James Deane image - Photo by Drift.News : https://drift.news/drivers-profile/james-deane-dmec/ 

> Drivers page - Jack Shanahan image - Photo by Drift.News : https://drift.news/drivers-profile/jack-shanahan/ 

> Drivers page - Conor Shanahan image - Photo by Drift.News : https://drift.news/drivers-profile/conor-shanahan-fd/ 

> Drivers page - Duane Mckeever image - Photo by Drift.News : https://drift.news/drivers-profile/duane-mckeever/ 

> Drivers page - Driver image styling : https://www.w3schools.com/css/css3_images.asp 

> Sign up form code - course content/Love Running : https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+3/courseware/e805068059af42af87681032aa64053f/fc8bba87c52a4d91b32d1c7c28b1d79b/

> Sign Up page - Regex code: https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_input_pattern

<a name="content"></a>
## Content & Resources

### Code Institute

> Project created inline with project 1 scope

> Certain aspects of the site follow course content and Love Running project

### w3 schools

> Used for general look up for HTML and CSS syntax

### htmlcolors.com
> Used for colour codes

<a name="acknowledgements"></a>
## Acknowledgements

### Alan Bushell

> My mentor who has provided tips, tools, tricks, encouragement and aleviated fears to get this project completed 

### Lewis Dillon

> My Course Facilitator who has shared advised and lend a helping hand where needed to troubleshoot




