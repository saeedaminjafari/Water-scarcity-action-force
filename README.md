![Image](https://github.com/saeedaminjafari/Water-scarcity-action-force/blob/master/assets/wireframes/screenshot-homepage.png)

# Water Scarcity Action Force - Milestone Project 1

### View the live project [here.](https://saeedaminjafari.github.io/Water-scarcity-action-force/)

## Table of Contents
> - [Overview](#overview)
> - [Description](#description)
> - [Ux](#ux)
> - [Features](#features)
> - [Technologies Used](#technologies-used)
> - [Testing](#testing)
> - [Deployment](#deployment)
> - [Credits](#credits)
> - [Acknowledgments](#Acknowledgements)

## Overview
Although we are living in the 21st century with enormous technological and industrial developments, many people and economies are suffering from a shortage of freshwater. This project aims at addressing the lack of freshwater in vulnerable areas by raising donations, encouraging more academic research in this field, providing policymakers with potential solutions, and absorbing valuable members and volunteers. 
 
## Description
We tried to design this project with concise content and a direct message. The pages are highly responsive and work on different devices.
![Image](https://github.com/saeedaminjafari/Water-scarcity-action-force/blob/master/assets/wireframes/responsive.png)

## UX

 ## Strategy
 
This website belongs to the philanthropic and non-profit organization named WSAF (Water Scarcity Action Force).

### External users’ goal:
The site users are divided into two groups:
-	People who are willing to contribute to combating climate change effects. They reach their goal by donating money or doing volunteering jobs via this website.
-	Researchers, scientists, and job seekers in environmental fields. They achieve their goals by applying for the available positions and vacancies.

### Site owners’ goal:
The WaSAF organization is interested in raising donations and absorbing volunteers and members to carry out their environmental and conservation projects. The final goal is addressing the water scarcity problems.

+ [Wireframes for all pages](https://github.com/saeedaminjafari/Water-scarcity-action-force/blob/master/assets/wireframes/water-scarcity-action-force.pdf)



## Features

### Navigation Bar
All pages have a fixed navigation bar on top of the page that can be accessed throughout the entire page, and users can go to their desired page at any time. The navigation bar collapses on small screen devices (tablets and cell phones) and works as a toggler, and also the logo of the company changes to its acronym. Moreover, by clicking on the name (or logo) of the company, users can navigate to the Home page.
 
### Home Page
- The Home page contains an overlay (blurred) image in its header with the company purposes and slogans sharper on the right side. The company slogans disappear on smaller screens (only on medium and large screens).
- Completed field projects: Photos of the successful projects in Asia and Africa are shown on a section with image captions with brief description.
- Research topics: The pictures and the main topics and a short description of the research conducted in different case studies are shown in the next section.

### vacancies Page
- Vacancies’ announcement: A list of available jobs and volunteering positions and the corresponding application process. We used a table to list the jobs that the color of the rows of the table change by hovering on them.

### Your Contribution (donation) Page
- This page contains different ways that users can donate money to the WSAF.

### Contact Page
- Contact information: Provide users with the WSAF's social media and contact information.
- There is aslo a form that users can directly type there message.

### footer
- Raising money: Adding a “Donation” section that navigate to the Your Contribution page.
- Raising money: Adding a “How to contribute” section that navigate to the Vacancies page.
- The contact info of the WSAF

### Features Left to Implement
- Providing a direct payment terminal
- the form in contact page should include an id to save the messages
- Providing each project with a separate page containing more details
- providing a page for the upcoming projects

## Technologies Used

#### Languages:
- [HTML](https://en.wikipedia.org/wiki/HTML)
- [CSS](https://en.wikipedia.org/wiki/CSS)
- [JS](https://en.wikipedia.org/wiki/JavaScript)

#### Libraries:
- [Bootstrap 4.5](https://getbootstrap.com/) - A mobile-first responsive library used to construct various parts of the project, including the Navbar, Modal Forms, Featurettes and Cards.
- [GoogleFonts](https://fonts.google.com/) - Exo and Robot and Sans-Serif fonts
- [FontAwesome](https://fontawesome.com/) - For Icons
- [Balsamiq](https://balsamiq.com/wireframes/?gclid=EAIaIQobChMIn-_lgbiJ7QIVn4BQBh1X3Av6EAAYASAAEgL1XfD_BwE) - for generating the wireframes
- [ami](http://ami.responsivedesign.is/#) I used this one to check the responsive capability of the website.

#### Version Control:
- [Github](https://github.com/) - To store the code and use of Github Pages to deploy the website. 
- [Gitpod](https://gitpod.io/) - The primary version control IDE for development to further push and commit code to Gihub.

#### Other:
- [Code Institute Course Content](https://courses.codeinstitute.net/) - Some codes copied and modified from the course materials.
- [ChromeDevTools](https://developers.google.com/web/tools/chrome-devtools) - As the primary source of bug and error detection.
- [W3Schools](https://www.w3schools.com/) - I found this website a very helpful tutorial.
- [StackOverFlow](https://stackoverflow.com/) - I found the answers to many of my questins in here and helped me to fix the errors.


## Testing

I mostly checked the functionality of the website with the Chrome inspection tools. I made sure that all links work properly and the external ones open in a new page.

#### Validation

HTML - [W3C](https://validator.w3.org/) - Markup Validation

There was two errors only in Home page:

![Image](https://github.com/saeedaminjafari/Water-scarcity-action-force/blob/master/assets/wireframes/error-1.png)
- I removed h2 and h4 elements from the ul element and put al of them in a div to solve this error

![Image](https://github.com/saeedaminjafari/Water-scarcity-action-force/blob/master/assets/wireframes/error-1(solved).png)

CSS - [W3C](https://jigsaw.w3.org/css-validator/) - CSS Validation

No error found in the css file although There are warnings related to the Mozila browser compatibility:

![Image](https://github.com/saeedaminjafari/Water-scarcity-action-force/blob/master/assets/wireframes/warning.png)

I encountered other errors in the project by using the chrome inspection tool that I tried changing the css properties in a live procedure to fix them. My main issue was related to postioning and display property that the positions of the elements did not fit as I expected. Finally I managed to fix them by trial and error in different screen sizes.

## Deployment

- Since I already had a Github account, I just opened my profile and created a new repository with the Code Institute's [template](https://github.com/Code-Institute-Org/gitpod-full-template).
- I opened my newly created repository in [Gitpod](https://gitpod.io/) as the main IDE that I used to write the codes.
- I add and commit mt repository quite often with these codes ("git add ." and git commit -m message") that all messages and process are tracable in Github because I pushed the repository there every day.
- Then in Github, I put the Master Branch as the source to create a live URL.
- Now the code is accessible through the clone button in Github as a URL or a file.


## Credits

### Repository
- The full repository template of Code Institute was used for the initial wbesite developement: [Gitpod Full Template](https://github.com/Code-Institute-Org/gitpod-full-template)

### Content
- The initial code for the form in the contact page and the social links hover style on the footer were copied and modified from the Code Institute course material.

### Media
- The photos of the projects on the Home page was downloaded from the [Stockholm Resilience Center](https://www.stockholmresilience.org/) which is a research institute belongs to Stockholm University and conducts research in the planet resilience.
- The photo of the Vacancies page was downloaded from [Undraw](https://undraw.co/)
- The photo of the Your Contribution page was downloaded from [this source](https://www.tvo.org/support-us/make-a-donation)
- The photo of the contact page was downloaded from [this source](https://www.activeinternational.co.hu/contact-us)
### Acknowledgements

- I appreciate all of the helps of Nishant Kumar, the Code Institue mentor, that without them I was not able to complete this project.