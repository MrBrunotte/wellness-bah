# Wellnes Bahamas

###### Code Institute / User-Centric Front-End Development

I did my own project as milestone project 1. My mother is about to start her own business as a plant-based health coach and yoga teacher so I decided to make a static website for her instead of creating the website for a made up band. 

The typical client is someone who wants a change in their life. It might be because of disease or something else. When the potential client finds the website he/she should be attracted by the landingpage/wellness page. By using less option for the user to interact with the aim is to direct the user towards the courses och coaching section where they can sign up.

The navbar is fixed to the top so it always is reachable. And it is always possible for the user to easily go back to the landingpage/wellness page.

The sign up/courses/coaching pages all have a home button for easy access.

## DESIGN

#### FRAMEWORK
I have used the Bootstrap framwork that we have focused on in the training modules.
#### UX DESIGN
I use the `:hover`effect on my buttons and they also change color. I also use the Bootstrap Carousel slideshow to give the website some more life and movement. In the sign in page I have added a box shadow because I want the sign in form to stick out from the background.
##### Wireframe
I used the balsamiq website [balsamiq](https://balsamiq.com/wireframes/) to create my wireframe. <br/>
Take a look at my wireframe: [Wellness-wireframe](https://github.com/MrBrunotte/wellness-bah/blob/master/Wellness%20Bahamas%20wireframe.pdf)

## Features
The sites tree structure can be seen below. The user can choose to scroll through the page from top to bottom or he/she can use the navigation bar on top of the page, which sticks to the top when the page is scrolled down.
I have the navigation bar on every page except the sign in page where I have a Submit button or an anchor link to scroll back to the home page.

###### Page structure
* Wellness (landingpage/homepage)
* My Vision
* Photos & Videos
    * Photos
* Lifestyle
* Coaching
    * Coaching form
* Courses
    * Courses form
* Testimonials
* Sign in
    * Sign in form

The design of the pages have been made to follow the same structure. I also wanted the forms to have the same design but with the corresponding image in the form. 

###### [index.html] (https://mrbrunotte.github.io/wellness-bah/#main)
This is my landing page (home page). My aim with the landing page is to make the user feel interested and to want to explore more. This is done by using a slider carousel that displays plant-based food and some text of what services my mother is offering.
There are three [<btn>] elements, that are designed in CSS so that the user can read more about my mother and hopefully spark some more interest.
The user can also scroll down the page to reach all the other content.
The fixed to the top navbar is a shortcut to all sections if the user does not want to scroll down. All content is reachable from the navbar exept the photos and forms.

###### My vision, Photos & Videos and Lifestyle
These three features are "interest" sparking sections. The aim is to give the user a view of my mothers vision, how healthy she looks from her way of eating and living and the lifestyle she is living as a plant-based food and yoga practitioner. 
When the user clicks on each section the user is able to read a little bit more abut the subject and when the user clicks the photos & video section the user can watch an inspirational yoga video from the Bahamas and some picture of my mother and family.

###### Coaching, Courses and Testimonials
These three sections are displayed in the same way, I have done this to because I wanted to have a consistent theme on the website. 
Each section has has some explanation text and [<btn>] that directs the user to a form where where he/she can contact my mother and get more information.
The testimonial section displays two happy clients that have gone through a course and the coaching program.

###### Sign in
The existing clients log in here.

###### Forms
The coaching and courses forms have the same display as their parent with a navbar on top, I did this because I want to maintain the consistent feel of the website.
The login form is simple and clean.
All forms are validated and the user have to type their name and email correctly before they can proceed.

##### Whish List
Future Implementations:
* Make the site load quicker on mobile.
* Develop the site further with more features and content.

## TECHNOLOGIES
In this project I have used:
* HTML5
    -  Semantic markup language for the site.
* BOOTSTRAP
    -   To make the site responsive
* Google fonts
    -   For my font style.

## TESTING
I have run the code through the HTML and CSS validators

[HTML] (https://validator.w3.org/#validate_by_input)
 *  index.html
 *  courses.html
 *  coaching.html
 *  photos.html
 *  signin.html

I have run all HTML code through the validators and there are no warnings.
    -   Document checking completed. No errors or warnings to show.
(there was one warning about width and height in photo.html, I have ignored this because this was Bootstrap code)
 
[CSS] (https://jigsaw.w3.org/css-validator/#validate_by_input)
*   carousel.css
*   signin.css
*   style.css

I have run all CSS code through the validator and there was only one warning in style.css (same color for [background-color] and [border-color]) which is OK.

I have also tested the sites responsivness on different screen sizes.

## Technologies Used
* Bootstrap
* Fontawsome
* Google fonts
* jQuery

## DEPLOYMENT
 I have deployed the project using GitHub Pages, and my websit is available here: https://mrbrunotte.github.io/wellness-bah/

## CREDITS
### Content
Lorem Ipsum have been used since my mother is not finished with all her text. I have added text (that will be changed in the future) to some parts.
### Media
Images used on this website are personal photos and bought images from Shutterstock.com.
### Acknowledgements
I would really like to thank my mentor from the Code Institute: Maranatha Llesanmi for all his help and guidance in this project!
