# Michael Easton's client base portfolio.
User-Centric FrontEnd Development Project. - 1st Milestone Project.
### The aim of this project is to attract prospective clients interested in getting fit, by taking up sport and new hobbies. His website will be improved in order to bring in more customers.
## Original website
Actual website can be found [here](https://www.backtothefitness.co.uk/).
![Original Website](https://raw.githubusercontent.com/lucas-Joyce/first-milestone-michael/master/assets/images/sketches/backtofitnessfrontpage.png "Original Website")
### I propose a bright, clear and informative layout as well as easy access via mobile to all the contents. Ability to book on demand immediately or at the client's own time would be provided for. 
# UX 
## User Stories
### As a customer, I expect to see infomations of interest for my fitness goals.

![Service showcase](https://raw.githubusercontent.com/lucas-Joyce/first-milestone-michael/master/assets/images/service/serviceinfo.png "Service showcase")
![Experience showcase](https://raw.githubusercontent.com/lucas-Joyce/first-milestone-michael/master/assets/images/experience/experienceinfo.png "Experience showcase" )
### Being Michael, I will have  easy contacts and quick resquests, booking in advance and personal planning. The deposits will be held.


![Booking showcase](https://raw.githubusercontent.com/lucas-Joyce/first-milestone-michael/master/assets/images/booking/bookingform.png "Booking showcase")

## Strategy
My goal in the design was to make it as easy as possible to  navigate and access bookings. A mobile based version would facilitate calender login synchronised between michael and his website clients with an option to contact michael if they choose. 
### Scope
For his clients, Michael intends to provide them with a clear aim for their fitness goals.His expertise and experience will give them a highly personalised programme.
### Structure
In the experience section, I'd like them to see programmes in action showing a variety of imput. Also, in the service section I want them to see exactly what might be involved through visualisation.

### Skeleton
[Index/About Wireframe](https://github.com/lucas-Joyce/first-milestone-michael/master/assets/images/sketches/image0.jpeg)

[Experience Wireframe](https://github.com/lucas-Joyce/first-milestone-michael/blob/master/assets/images/sketches/image4.jpeg)

[Tesimonials Wireframe](https://github.com/lucas-Joyce/first-milestone-michael/blob/master/assets/images/sketches/image3.jpeg)

[service Wireframe](https://github.com/lucas-Joyce/first-milestone-michael/blob/master/assets/images/sketches/image2.jpeg)

[booking Wireframe](https://github.com/lucas-Joyce/first-milestone-michael/blob/master/assets/images/sketches/image1.jpeg)
### Surface
The colour grey was chosen for the background to provide a neutral basis for the contents labels.
Coral orange and pale blue (Michael's favourite colours) are used for the display of buttons and borders making it clear to access the relevant parts.
# Techologies
For this project, as strictly only in
1. HTML
2. CSS
3. Bootstrap (with updated version.)
# Features 
I would like to keep it minimized in mobile media contents, such as carousals that will not be displayed.
On the first Index page, "sign up" was important, to get the clients to add their email address as soon as possible for Michael to acquire new customers.

In the service section, it would be better to minimalise the overloading of infomation so that the icons give an exact indication of the content. 

## Features left to implement 
To have the navigation menu with an extra javascript function added to create a smooth scrolling effect and collapsed menu to stay collapsed.

In the service section I'd like to implement a "Ashion style" box selector in "my portfilo" seen [here](http://www.chitrakootweb.com/template/ashton/home07-light-side-nav.html#portfolio)

In the Booking section, a blue button that shows "Sign in" will only appear at the start, no calendar nor user/setting icons to be shown.
The "sign in" button will also transform into "sign out" when ready, and will have a timer of inactive idle (just above the sign-out button) to countdown and automatically sign out.

Radio buttons, time, and the date, will appear in a coloured ticked icon, once the user has filled in, email and thumb up will also become green when all requirments are met and approved.

I will add further forms for client's details to become a member.
so members able to book a session with Michael, 

I would like a calendar in different booking colors for Michael so he will know which area of sport. Anything that is booked shall be greyed out to members's calendar page and sychonised with Michael's calendar, much of this is related in Javascripts.

## Testing 
 In the about me section, they can read a bit about my background, and if they're viewing on a desktop, and the big screen mobile phone at landscape orientation, the background of this section is a photo of michael. 

In the experience section, the intended outcome is to show that it is more than just skills, hence the title experience. To use the modal form to click on, to illustrate the visual happy pictures, to show postiveness to the potental new customers in all forms of media devices, however i realised not all will work in "Modal" height issue, 
such as  ```max-height:-webkit-fill-available;``` nor ``fit-content``,
and to prevent overflow unwanted scroll, restricted to **90vh** and ```max-width:max-content;```.
See to `modalTest.html`.

If the client is interested in contacting me, they will have to fill out all fields in order for the form to go through.
## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commitments to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.
# Credits
## Content
All contents in the Back to Fitness website is written by Michael and he will update it, in the future.
## Media
All photos were taken by Michael with premission from clients. Some photos are in Modal form and some went into the background Greyscale filter to preserve the blue and coral theme.
### Acknowledgements
- Ashion webpage portfolio.
    - http://www.chitrakootweb.com/template/ashton/home07-light-side-nav.html#portfolio
- Haley Schafer webpage portflio.
    - https://code-institute-solutions.github.io/StudentExampleProjectGradeFive/
- Finding Icons.
    - all on https://www.flaticon.com
    - Climbing Icon  
    - Waist slimming icon
    - Tread mill machine 
    - difficult to find one that's free, but only in SVG, so i add it into HTML.
    - tidy up the svg structure, and changes the color also "fill" to be white from none.
- Carousel effect.
    - Carousel sliding effect, I didn't realise that its involve Javascript, so i have to add the links in order for it to work.
- www.tutorialrepublic.com
- www.w3schools.com
- www.getbootstrap.com
- www.tympanus.net
- https://stackoverflow.com/questions/28791970/how-to-limit-the-height-of-the-modal
- https://return-true.com/demos/popupfooter/
- https://www.flaticon.com/authors/smashicons
- http://jsfiddle.net/tolginho/EBqZv/5/






