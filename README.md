# Wellness Bahamas

###### Code Institute / User-Centric Front-End Development

I did my own project as milestone project 1. My mother is about to start her own business as a plant-based health coach and yoga teacher, so I decided to make a static website for her instead of creating the website for a made up band. 

The typical client is someone who wants a change in their life. It might be because of disease or something else. When the potential client finds the website, he/she should be attracted by the landing page/wellness page. By using less option for the user to interact with the aim is to direct the user towards the courses and coaching section where they can sign up.

The navbar is fixed to the top so it always is reachable. And it is always possible for the user to easily go back to the landing page/wellness page.

The sign up/courses/coaching pages all have a home button for easy access.

## DESIGN

### FRAMEWORK
I have used the Bootstrap framework that we have focused on in the training modules.
### UX DESIGN
This website is for anyone that want to make a change in their life’s towards a healthier plant-based living. The website aims to spark an interest of the user so that they want to learn more and enrol in any one of the courses or coaching program. The user could be a person who is a bit overweight and wants to make a change in their life but doesn't really know how. The courses or coaching program could be the perfect start for this person! 

The website follows the same design but with different large images to distinguish the pages from each other. I have also made the form pages match their parent page, this is intentional since I want to make sure that the user knows what form they are submitting.
The ":hover" effect is used on the buttons and they also change color, all buttons and anchor links all have the same design and hover effect. The Bootstrap Carousel slideshow is used to give the website some more life and movement. 
The sign-in page has a box shadow, I want the sign-in form to stick out from the background.

### Wireframe
I used the balsamiq website [balsamiq](https://balsamiq.com/wireframes/) to create my wireframe. <br/>
Here is the wireframe, take a look: [Wellness-wireframe](https://github.com/MrBrunotte/wellness-bah/blob/master/Wellness%20Bahamas%20wireframe.pdf)

### Features
The sites tree structure can be seen below. The user can choose to scroll through the page from top to bottom or he/she can use the navigation bar on top of the page, which sticks to the top when the page is scrolled down.
I have the navigation bar on every page except the sign in page where I have a Submit button or an anchor link to scroll back to the home page.

#### Page structure
* [Wellness](https://mrbrunotte.github.io/wellness-bah/)
* [My-Vision](https://mrbrunotte.github.io/wellness-bah/#myvision)
* [Photos&Videos](https://mrbrunotte.github.io/wellness-bah/#photos)
    * [Photos](https://mrbrunotte.github.io/wellness-bah/photos.html)
* [Lifestyle](https://mrbrunotte.github.io/wellness-bah/index.html#lifestyle)
* [Coaching](https://mrbrunotte.github.io/wellness-bah/index.html#coaching)
    * [Coaching-form](https://mrbrunotte.github.io/wellness-bah/coaching.html)
* [Courses](https://mrbrunotte.github.io/wellness-bah/index.html#courses)
    * [Courses-form](https://mrbrunotte.github.io/wellness-bah/courses.html)
* [Testimonials](https://mrbrunotte.github.io/wellness-bah/index.html#testimonials)
* [Sign-in](https://mrbrunotte.github.io/wellness-bah/signin.html)

The design of the pages has been made to follow the same structure. I also wanted the forms to have the same design but with the corresponding image in the form. 

##### [Wellness](https://mrbrunotte.github.io/wellness-bah/#main)
This is my landing page (home page). My aim with the landing page is to make the user feel interested and want to explore more. This is done by using a slider carousel that displays plant-based food and some headers of what services my mother is offering.
There are three [<btn>] elements, that are designed in CSS so that the user can read more about my mother and hopefully spark some more interest.
The user can also scroll down the page to reach all the other content.
The fixed-to-the-top navbar is a shortcut to all sections if the user does not want to scroll down. All content is reachable from the navbar except the photos and coaching and courses form.

##### My Vision, Photos & Videos and Lifestyle
These three features are "interest" sparking sections. The aim is to give the user a view of my mother’s vision, how healthy she looks from her way of eating and living and the lifestyle she is living as a plant-based food and yoga practitioner. 

###### My Vision
The user is met by a picture of my mother and some text about what her goal is with the website and how this can help the user. 

###### Photos & Videos
When the user clicks on this feature the user is met by a inspirational yoga video from the Bahamas (Ruth’s daughter), she also tell the user about her yoga and what she offers if the user is in the Bahamas. 
The user can also click to see more photos of Ruth and her family and surrounding and the lifestyle she is living.

###### Lifestyle
In this section the user can read more about Ruth’s lifestyle, how she lives her life and prepares her food.

##### Coaching, Courses
These two sections are displayed in the same way, this is intentional because I wanted to have a consistent theme on the website. 
Each section has some explanation text and [<btn>] that directs the user to a form where he/she can contact Ruth and get more information.

##### Testimonials
The testimonial section is designed in the same way as the coaching and courses sections. The testimonials show two happy clients that have gone through a course and the coaching program.

##### Sign in
The sign-in anchor link is where the existing customer signs in. The user is taken to a sign-in form that is plain and simple to not confuse the user. There is a welcome back greeting and two fields of required input from the user. The email and password must be typed in the correct way for the user to be able to continue.
There is a "forgot password" link and a "Back to Wellness" link if the user needs these options.

##### Forms
The coaching and courses forms have the same display as their parent with a navbar on top, so that the user can reach all other sections of the website if they want.
The user is asked to check the boxes of what coaching or course they are interested in, they can make multiple choices.
The first name, last name and email are required fields and the user is not able to submit until these three fields are typed correctly (Name: [a-ö], [A-Ö] 2-63 characters and Email: [^]+@[^]+[.][a-z] 2-63 characters).

The sign-in form is clean and simple and both input fields are required (Email: [^]+@[^]+[.][a-z] 2-63 characters and password has to have a minimum of 8 characters).

##### Whish List
Future Implementations:
* Make the site load quicker on mobile.
* Develop the site further with more text (the lorem ipsum needs to be changed).
* The text needs to be changed, added and worked on so that there is valid content in the page.
* More photos and videos should be added to that section.

## TECHNOLOGIES
In this project I have used:
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
    -   Semantic mark-up language for the site.
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    -   I have done my own CSS code, overwritten some of the Bootstrap CSS code.
* [BOOTSTRAP](https://getbootstrap.com/docs/4.2/getting-started/introduction/)
    -   To make the site responsive
* [GOOGLE-FONTS](https://fonts.google.com/)
    -   For my font style.

## TESTING
I have tested the website manually and all the links work as intended, I have not found any bugs when navigation around on the website.

#### Navbar
##### Wellness, Coaching, Courses and Testimonials
I followed the link to the form page, on every step I tested if I could go to all other pages from where I was. The path from the navbar to the form and back all work and all other parts are also reachable at every stage when the link is clicked.
##### Photos & Video
I made sure that the video was not on auto play, the user has to manually play the video.
###### Photos
I tested if the navbar with all links worked correctly from the Photo section, which it did.
I tested the "back to top" link and the "Back to Wellness" link, they both worked as they were intended to.
#### Forms
I tested all fields in the form and made sure that all required fields are working. I tested if there was any way of not submitting any data and all forms worked as the should - all required data had to be correctly submitted and when not doing this a "hint" message appears in each "wrong" input field. 
The user is not able to proceed forward until everything is filled in correctly.
#### Sign in
The sign-in form was tested in the same way as the forms. The difference was that the password needs a minimum of 8 characters to let the user proceed. I tested if this worked for different scenarios.

#### HTML & CSS validation
[HTML](https://validator.w3.org/#validate_by_input)
 *  index.html
 *  courses.html
 *  coaching.html
 *  photos.html
 *  signin.html

I have run all HTML code through the validators and there are no warnings.
    -   Document checking completed. No errors or warnings to show.
(there was one warning about width and height in the photo.html file but I have ignored this because this was a setting from Bootstrap CSS code)
 
[CSS](https://jigsaw.w3.org/css-validator/#validate_by_input)
*   carousel.css
*   signin.css
*   style.css

I have run all CSS code through the validator and there was only one warning in style.css (same color for [background-color] and [border-color]) which is OK.

#### Responsiveness
I have also tested the sites responsiveness on different screen sizes. All pages are responsive and change according to the change of screen size.

## DEPLOYMENT
 I have deployed the project using GitHub Pages, and my website is available here: https://mrbrunotte.github.io/wellness-bah/

## CREDITS
### Content
Lorem Ipsum have been used since my mother is not finished with all her text. I have added text (that will be changed in the future) to some parts.
### Media
Images used on this website are personal photos and bought images from Shutterstock.com.
### Acknowledgements
I would really like to thank my mentor from the Code Institute: Maranatha Llesanmi for all his help and guidance in this project!
