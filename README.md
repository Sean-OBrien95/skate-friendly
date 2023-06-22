# Skate Friendly

Skate Friendly is a site that that is aimed at people who have recently started skating and want to join a community group to skate with, or people who are interested in starting skating based in Dublin, Ireland. This website aims to help them by showing them how to do basic tricks, showing them times and places they can meet other skaters, recommending equipment and safety tips, as well as allowing them to get in contact with the group directly.

Skate Friendly is ultimately a one stop website that will have all the crucial information for beginner skaters to get more comfortable on skates and show them all the crucial information they will need to know such as how to stay safe.

# Features

In this section I will be covering the various features I have implemented, who I had in mind when creating them, and why they are useful. This project will have a total of 6 html sheets, as well as a css sheet. There will be a html for the Home page, the Tricks page, the FAQ page, the Contact page, as well as one Thank You page and 404 Error page.

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Colour Scheme

The colour scheme that I have used for this project is #BDE1EF a pastel blue that I thought fitted the imagery and general skater aesthetic, #999999 a grey colour which I opted for as I thought the black would look too harsh with pastel colours, and a standard white for background. I also chose this scheme as it is clearly readable. In the early stages the highlighted colour was originally green, but decided the light blue fitted the overall design better,

### Navigation Bar

- The navigation bar and logo

* Featured on all six pages, the navigation bar which will always appear at the top of the page features a link to the home page, a link to the tricks page, one to the faq page, and one for the contact page.
* This was created to help the user flow of the website and allow the user to jump between each section at will without having to rely on back commands from the browser. The logo also acts as a home button if the user would like to use that.
* When on a page, the nav bar will have an underline to show the user which specific page they are on. When hovering over a new page the colour will also change to the baby blue contrast colour that matches the pages theme.

![Photo of just the navigation bar](images/nav-bar.png)

### Hero Image and text

- Hero image and text

* The hero image was designed to make the introduction the website instantly recognisable.
* The image is pair of skates with a brief description of what the page is about, so that the user does not question the purpose of the website.
* the image also has a zoom in animation for style.

![Photo of just the landing image and overlay text](images/main-photo-demo.png)

### About Section

- What Skate Friendly is all about

* This is the first piece of information that will be displayed under the landing image. This section is broken up into 3 smaller sections aligned horizontally to that will explain why the group exists, and some of the benefits of skating.
* This clearly shows the user what the group can offer and why they might be interested in joining.

![Photo of just the about section](images/about-image.png)

### Meetup Section

- The meetup section

* This section is intended to show the user the location, times, and days of our meetups.
* They have been designed to have a bakground image that displays the type of environment that they will be skating in. This was chosen as I felt it would be visually appealing and make the design more distinct.

![Photo of just meetup section](images/meetup-demo.png)

### Footer

- Footer section

* The footer section will be appearing on all the pages. This has been designed with a minimal approach, using links that will take you to social media pages. I have not created social media pages for each of these so the link will guide to the home page of each website.

![Photo of just footer section](images/footer-demo.png)

### Tricks Image

- Intro image for Tricks

* The intro to the tricks page is a new image of a pair of skates.
* The zoom effect has also been applied here.

![Photo of tricks main image](images/tricks-demo-image.png)

### Tricks Page Content

- Content for the Tricks page

* The page opens with a styled desription of the page. It is clear what this page is for based on decription.
* Following this are 3 seperate sections describing different trciks as well as having a video underneath them to act as a tutorial.
* None of these videos play automatically and also have a volume control slider.

![Photo of content on tricks page](images/tricks-vids-demo.png)

### FAQ Page Photo

- Main Image on FAQ page

- Similar to the other images, I felt this image captured the energy of the website.
- This also has a zoom effect applied.

![Photo of faq main image](images/faq-demo-image.png)

### FAQ Content

- FAQ section

- This section was designed to answer any questions the user may have when getting into skating.
- It includes plenty of basic information as well as a link to the contact page which keeps you in the same tab.

* In this section there are 3 column sections similar in design to the home page to break up the information in an easy digestible way for the user.

![Photo of faq content](images/faq-content.png)

- Safety

- This section was designed to explain to users best safety practice, along with including a link that open in another page to buy safety gear.

![Photo of safety content](images/safety-content.png)

- Equipment content

- This section goes over the various equipment needs of a new skater such as skates, wheels, and accessories.

![Photo of equipment content](images/equipment-content.png)

### Contact Page

- Main image for page, this image has a smiling woman, I chose this as it is inviting and would suit a contact page. This also features the zoom effect.

![Photo of main contact image](images/contact-demo-photo.png)

- The contact form was designed to take the users name, surname, and email.
- Styling this I decided to use a clear border and have the border be visible through a shadow effect, I chose this as I felt it was a more unique design.
- I then added a radio dial button for users to select their level of experience.
- I then made a submit button, this button was designed with rounded edges and to change colour when hovered over.
- It also gets a cursor when hovered over to let the user know it is able to be clicked.
- All parts of the form are required to be filled before you can submit.

* Once you complete the form and submit, you are redirected to a thank you site.

![Photo of submission form](images/contact-form.png)

### Thank you page

- The thank you page is a redirect from the submission form, it is a simple page displaying a thank you message that will redirect you back tot he home page after 10 seconds.

![Photo of thank you page](images/thank-you.png)

### 404 Error page

- A simple 404 page with basic styling to tells the user they have ended up on a page that doesn't exist. It has an explanation and reedirects back to the home page after 5 seconds.

![Photo of 404 error page](images/404-image.png)

# Testing

- Ran html through W3C validator, have gotten back no errors but have gotten back 'warnings'. These warning are due to use of h1 elements in parts of the page that are not the very top. Due to time constraints, I am not able to change this right away as there is a lot of styling applied. If I were to re do the project, I would keep this in mind for future

* ran through Jigsaw css checker, no issues.

* I have checked screen compatibility for phone and tablet, I have checked tablet by using the inspect tool and shrinking down to size and have tested on my own personal mobile to assure it is responsive.

* A bug I have left uncorrected is on the contact page. The styling shows shadowing on the desktop version but when I checked on the mobile this effect does not appear. I have tried to address this by increasing the shadow effect and this has not worked. Due to time constraints I was not able to find an alternative but I will update in future to something that is compatible with ios

* Another bug left uncorrected was the performance of the hom page on mobile and the performace of trick page on desktop. I researched how to fix this and came across lazy loading. This solution looked like it would fix the issue how ever it would require JavaScript and I wanted to stick to html and css for this project.
