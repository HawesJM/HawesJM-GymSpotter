![alt text](assets/images/gym-spotter-logo.jpg)

# Gym Spotter
### Introduction
Gym Spotter is a web application designed to aid the individual user to develop and maintain a desired exercise routine in order to set and achieve specific fitness aims and life goals. To do this it aims to help users assess their body type, set realistic fitness targets with this in mind, and plan accordingly with the most efficient strategy and techniques for them. Gym Spotter also aims to support the user by introducing the concept of a community of individuals with shared goals, as sharing their progress within a likeminded peer group of individuals with similar time constrains or struggles helps build accountability and maintain motivation. Gym Spotter also aims to underpin this heightened knowledge and sharpened motivation by providing users with a wealth of tips and external resources to find the best workout regime for them. In so doing Gym Spotter aims to be a focal point of a conscientious and content fitness and lifestyle minded community that firstly offers advice and resources tailored to the individual, and secondly never loses sight of the sense fun and camaraderie offered by sports and exercise that keeps people engaged and motivated in their workouts.

The concept was developed for the purpose of completing the first Milestone Project for the Code Institute's Full Stack Developer course. It was built to express the knowledge and skills gained from the HTML, CSS and User Centric Design modules.

The live website can be found here https://hawesjm.github.io/GymSpotter/

### Structure
##### Archetecture
Gym Spotter is built using pure HTML5 and CSS according to the principles of creating a responsive and accessible static front-end user-centric website. Bootstrap and media queries were also used to ensure responsive design.

![alt text](assets/images/mock-up-image.png)

##### User Experience Design
For fist time visitors I imagined the user first of all wanting to know the best way to get started working out in an appropriate way, and quickly access a starting framework for sustainable progress and remaining motivated. For returning users I wanted to begin developing a framework where they can continually assess their progress according to an easily defined roadmap and measure their achievements against certain external standards. In both cases I wanted clear and easily navigable content on desktop, tablet and also mobile device so users can effectively achieve their goals while working out or while taking some rest in their downtime.
##### Navigation
All Pages will contain a Navigation menu at the top of the Webpage that directs them to a new Page to easily allow users to Navigate the site easily. The Nav Menu will be collapsible on a Mobile device to make use of space on smaller devices. The homepage will give a brief introduction to the purpose of the site itself. "Plans and Goals" will provide users with the basic information to get started. "Contact and Social" will help users to stay on track through positive engagement and accountability. "External Resources" will provide paths for users to enhance and develop their workout plans and lifestyle according to the principles introduced in previous sections.

Across all devices and screen sizes the layout will remain clean and the flow of information will progress logically, enhanced at certain points by CTAs. All pages will contain a footer with social media contact links for further engagement. Certain elements on each page will respond interactively to help users move through the information flow of the site.

### Design
##### Colour Scheme
The main background colour is Grey ![alt text] (assets/images/43464b.jpg), with a darker shade for certain areas of focus or calls to action. This aims to echo the industrial colour scheme popular with a lot of urban gyms. The main accent colour is Orange ![alt text] (assets/images/ED6B47.jpg) which provides excellent contrast and elevates the Grey tones with an energetic, modern feel. Occasionally a light Blue is used to further this.
##### Typography
The main font used is Teko to enhance the modern industrial feel of the website with provision for using Roboto when this is necessary for further clarity.
##### Imagery
The Gym Spotter logo is displayed in the header and footer of all pages, and on all devices and screensizes. The exact placement, positioning and sizing of the logo will change depending on the screen size. The website also displays images for general motivation or to help clarify specific sections of information.
##### Wireframes
###### Homepage
![alt text](assets/images/homepage-wireframe.png)
###### Plans and Goals
![alt text](assets/images/plans-wireframe.png)
###### Contact and Social
![alt text](assets/images/contact-wireframe.png)
###### Partners and External Resources
![alt text](assets/images/resources-wireframe.png)
###### Differences
Needed more space appropriate descriptive elements on Plans and Goals page for mobile. Slight changes to logo position for different screen sizes.
### Limitations
Due to no JavaScript functionality, apart from Bootstraps(JS/JQuery) there is no contact form that will store data or send email requests. Also for this reason the intended individual workout plans cannot be created.

### Features
##### Existing Features
- CTA button on home page
- Responsive table with workout plans
- Responsive contact form with fields and slider
- Responsive Google maps iframe
- Responsive testimonials carousel

##### To Be Added
- Member login area and forum
- Form clearing function

### Technologies
- **HTML**
This project uses HTML as the main language used to complete the structure of the Website.
- **CSS**
This project uses custom written CSS to style the Website.
- **Bootstrap**
The Bootstrap framework is used throughout this website for layouts and styling.
This has also been used to import JavaScript/Query where necessary
- **Font Awesome**
Font awesome Icons are used in the Body of the site and for the Social media links contained in the Footer section of the website.
- **Google Fonts**
Google fonts are used throughout the project to import the Teko and Roboto fonts
- **Code Anywhere**
The IDE for writing the code, using CI approved template
- **GitHub**
GithHub is the hosting site used to store the source code for the Website and Git Pages is used for the deployment of the live site.
- **Google Chrome Developer Tools**
Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
- **Balsamiq Wireframes**
This was used to create wireframes for 'The Skeleton Plane' stage of UX design.
 - **place-hold.it**
place-hold.it was used to display the colours shown in the Color Scheme section.

### Testing

##### Strategy
As this project is static and contains no back-end functionality, the testing performed will be on the visual effects and layout of the Website including navbars, buttons and links.

No elements should overlap another container div. All elements should remain on the screen at all sizes above 300px. All carousel items should be controllable with the mouse as well as sliding on a timer.

All nav links should direct to the correct html pages as per their names. The Home page is the exception, this one will redirect to index.html.

All links to external websites must open in a new browser.

Testing of form validation will also be required to ensure the correct inputs are taken and that all fields are required.

##### Initial Bugs
Index html columns not centered. Solved with media query and margin left.
Text size for columns wont increase for larger screen sizes, too small. Solved with media query.
Hamburger menu not working on mobile, due to bootstrap class error, wrong target property.
Form columns bootstrap – changed div class from “form-row” to “row”. Alignment issue solved with margin auto.
Testimonial text size for mobile – solved by media query.

All other bugs related to positioning and sizing of flexbox elements or bootrstrap columns, e.g. with the Google Maps iframe as below eventually solved by giving parent div fixed height and width properties before styling accordingly.

![alt text](testing/map-padding-bug.png)

##### Testing Methodology

##### Testing Report
![alt text](testing/testingreport.png)
Full testing results can be found here testing/gym-spotter-testing.xlsx
Please note these results are a .xlsx file and will require excel, google docs or compatiable program to open the file.
Additionally, all pages were run through the W3C HTML Validator.
### Deployment & Usage


