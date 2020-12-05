# Eleventh Embodiment

Main purpose of this project was to build a website for my First Milestone Project as a part of Full Stack Web Developer Diploma course, using knowldge of HTML and CSS only.
I have decided to build a website for a friend of mine who is a yoga teacher and an alternative healer. Idea was to create a place where people can learn about different types of yoga, 
different healing techniques, and to be able to book yoga or healing sessions, workshop and retreats.
Website owner's goal is to attract more visitiors to the website wich will result in a bigger community, larger following on social media, and ultimately more people booking her classes, healing seassions or retreats.  

# UX
 
Idea was to create a website that will be easy to navigate and to encourage the user to explore all the pages to learn all about site owner's skills and experience. 
The site should be simple but elegant and bright wich should be accomplished white, gold and grey colors.

# User Stories

#### As a first time user,
  As a first time user,
* I want to be able to  navigate through the site easily to find information and services available
* I want to learn more about the site owner and their skills 
* I want to be able to see this website clearly on my mobile device
* I want to find ways to follow the owner on social media platforms


#### Returning User
  As a returning user,
* I want to check if there are any new classes and/or retreats 
* I want to book online classes and/or retreats 
* I want to contact the owner to find out more information about their services

#### Frequent User
  As a Frequent user,
* I want to see if there are any new upcoming events
* I want to sign up to the newsletter to get latest news and offers/discounts
---

#### Structure

- Each page will contain the navigation bar at the top of the page so that user can easily navigate the site and
know which site they are on at all times.\
    Purpose is to fulfill the user story - I want to be able to  navigate through the site easily to find information and services available
- Home page will contain information about the owner and their experience in the industry\
   Purpose is to fulfill the user story - I want to learn more about the site owner and their skills.
- At the bottom of the home page user will have the option to view the upcoming events.\
    Purpose is to fulfill the user story - I want to check if there are any new classes and/or retreats
- Footer will remain the same across all pages and will contain contact information as well as social media links so user can easily contact or connect with the site owner.\
    Purpose is to fulfill the user stories:\
    I want to find ways to follow the owner on social media platforms and \
    I want to contact the owner to find out more information about their services
- "What I do" page will contain details about each of the yoga styles and healing techniques site owner is providing and teaching. 
   Purpose is to fulfill the user story - I want to learn more about the site owner and their skills.
- Site will be made responsive using Bootstrap grid and media queries to fulfill the user story\
    I want to be able to see this website clearly on my mobile device

## Design 

 #### Typogroaphy 
 Google font Lato was used trought the website to achieve the elegantand clean look

#### Colors
  An off white shade #fafafa  was used for the text to contrast the gold #c4881be3 backgrounds.
  Same gold color was used for borders and titles as site owner wanted this to be main color.
  For the text, the grey hsla(38, 38%, 25%, 0.89) color was used for easier reading as a lot of backgrounds are white
  There was a need to use grey text shadow rgba(0, 0, 0, 0.281) on some titles and navigation menu for easier reading of gold letters.

## Wireframes 

[Home Page](https://github.com/TanYa-Go/eleventh-embodiment/tree/master/assets/wireframes)\
[About Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/about.pdf)\
[What I Do Page]\
[Gallery Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/gallery.pdf)\
[Events Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/events.pdf)\
[Contact Page](https://github.com/TanYa-Go/eleventh-embodiment/blob/master/assets/wireframes/contact.pdf)

## Features
- 
- Option to see upcoming events on home page - "See Events" button leads to a separate Events page where all events are listed
- Option to book an online class on "What I do" page - "Book" button opens a modal where user can open account and book a class
- Option to contact the site owner through the form located on "Contact" page or links in the footer
- Video on events page that shows previous retreat, user needs to click to play, it is not set to autoplay

 
### Features Left to Implement
- Currently the forms do not send any information, we would like to implement this option in the future
- Plan is also to implement a payment system where a user can register and pay for a workshope or a retreat

## Technologies Used

1. [HTML](https://en.wikipedia.org/wiki/HTML#:~:text=Hypertext%20Markup%20Language%20(HTML)%20is,scripting%20languages%20such%20as%20JavaScript.)

1. [CSS](https://en.wikipedia.org/wiki/CSS)

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.
1. [TinyPNG](https://tinypng.com/)
    - TinyPNG was used to reduce the overall total image size

## Testing



## Deployment


## Credits

### Code

#### Code Institute
- Navbar menu items "active" effect borrowed from Love Running challenge
- Code for hero image and animation borrowed from the Love Running challenge and adapted to suit my project
- Code for the form on the contact page is a combination of the forms from Love Running and Resume projects
- Code for social media icons borrowed from Love Running challenge then adapted to suit my project 

#### Other Sources
- "Grow hover" effect on navbar menu items borrowed from this post from [Travis Media](https://travis.media/how-to-make-an-item-grow-on-hover-with-css/) 
- Idea on how to insert a video borrowed from this [W3 Schools](https://www.w3schools.com/html/html5_video.asp) post
- Idea for making images responsive borrowed from [W3 Schools](https://www.w3schools.com/howto/howto_css_image_responsive.asp) and [Bootstrap](https://bootstrapcreative.com/make-image-responsive-bootstrap-4/#:~:text=In%20Bootstrap%204%20you%20would,than%20the%20image%20pixel%20width.)
- Code for modal borrowed from [Bootstrap](https://getbootstrap.com/docs/4.5/components/modal/) and adapted to suit the desegn of my website
- Code for linkable button borrowed from this [Stackoverflow](https://stackoverflow.com/questions/2906582/how-to-create-an-html-button-that-acts-like-a-link#:~:text=The%20plain%20HTML%20way%20is,URL%20in%20the%20action%20attribute.&text=If%20necessary%2C%20set%20CSS%20display,type%3D%22submit%22%3E%20) post

### Content
- All content was provided by the site owner 

### Media

- For idea on how to insert a favicon I used this [YouTube video](https://www.youtube.com/watch?v=kEf1xSwX5D8)
- Images on home page in the "Methods I use in my practice" section are from Unsplash - <span>Photo by <a href="https://unsplash.com/@sonniehiles?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Sonnie Hiles</a> on <a href="https://unsplash.com/s/photos/yoga?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
- The other images are  all from the private collection of the site owner Ana Trajko herself
- Video on the events page is also provided by the site owner

### Acknowledgements

I'd like to thank 
- My mentor Ignatius Ukwuama for guidance and advice
- Anna and Jim from Code Institute for amazing tutorials on how to prepare the MS1
- All the CI tutors and Slack students
- My paretns for minding my son while I work on my project
- And of course my friend and site owner Ana Trajko for trusting me to build the website and for her ideas and suggestions to make it better


