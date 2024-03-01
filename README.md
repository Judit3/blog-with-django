# Bread

Bread is a blog website. Users can explore diverse post about bread, share their thoughts through comments and engage with the community by liking or unliking posts.

Bread is powered by Python, using a Django web framework. The user interface is crafted using Boostrap CSS and JavaScript. Furthermore, Bread is deployed on Heroku, a cloud platform.

You can check out the [live-site.](https://blog-with-django-ju-bff470dd15f2.herokuapp.com/)

![Responsive](static/images/readme/responsive.png)

---

## Content

- [User Experience and Workflow](#user-experience-and-workflow)
  * [Target Audience](#target-audience)
  * [User stories](#user-stories)
    + [Workflow](#workflow)
- [Design](#design)
  *  [Colour scheme](#colour-scheme)
  *  [Typography](#typography)
  *  [Imagery](#imagery)
  *  [Wireframes](#wireframes)
    + [Home](#home)
    + [Register](#register)
    + [Login](#login)
- [Features](#features)
  * [Navigation bar in header](#navigation-bar-in-header)
  * [Social media icons in footer](#social-media-icons-in-footer)
  * [Home page](#home-page)
  * [Register page](#register-page)
  * [Login page](#login-page)
  * [Future implementations](#future-implementations)
  * [Accessibility](#accessibility) 

 
- [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks and Libraries Used](#frameworks-libraries-used) 


---

## User Experience and Workflow

### Target Audience

The Bread Blog caters to bread enthusiasts, foodies, home bakers, and anyone with a passion for all things doughy and delicious. Its target audience are seasoned bakers looking for new recipes, a bread lovers eager to explore different types of loaves, or simply someone who appreciates the comforting aroma of freshly baked bread. The community can discover mouthwatering posts, engage with fellow bread aficionados through comments, and indulge in the simple pleasure of a perfectly baked loaf.

### User stories
Features in this project are structured through [user stories](https://github.com/Judit3/blog-with-django/issues).
Each User Story contains:
- **User Objective:** This field outlines the user's goal or objective. It should clearly state what the user wants to achieve or accomplish. The format follows: "As a user, I want to [action], so that [reason or benefit]." With this Objective in mind, User Stories are created to align with the target audience.
- **Acceptance Criteria:** This field specifies the conditions or criteria that must be met for the user story to be considered complete. It helps define the boundaries and expectations for implementing the user story.

#### Workflow
In the development process, a Kanban board in form of a [github project](https://github.com/users/Judit3/projects/3) is used to manage the tasks and track their progress. Initially, all issues are collected and placed in the Todo section.

When working on the tasks begins, the status of the issues is updated to 'In Process'. This signifies that active development is underway. Once the development work is completed, it is considered 'Done' and is moved to the final column on the Kanban board.

![Kanban-Board](static/images/readme/kanban-board.png)

---

## Design
It was used as inspiration the CodeInstitute blog created with Django as it was found user friendly.

These concepts were presented to other people for feedback and evaluation. Their insights and preferences were carefully considered for each design. Its warm colors and easy flair resonated with the audience.

<!-- ![balsamic mockup design idea](link to image in static folder) -->

### Colour scheme

![Colour scheme](static/images/readme/colour-scheme.png) 

The website uses a palette of colours that are fitting the colour palette of the Bread website images. The colour palette was created using the [Coolors](https://coolors.co/) website.

### Typography

Google Fonts was used for the Montserrat, it is used for the entire site. It is a sans-serif font. It was chosen as it looked clean and modern.

![Font](static/images/readme/font.png)

### Imagery

The blog images were taken from [Unsplash](https://unsplash.com). I have credited these in the [Credits](#Credits) section.
All images were compressed through [Fotor foto editor](https://www.fotor.com) and some formats were changed using [Convertio](https://convertio.co)
Chosen images are by random artists and were picked solely based on the style of the business product.

### Wireframes

#### Home

![Wireframe desktop and movile Home](static/images/readme/balsamic.png)

### Features

#### Navigation bar in header

This website is comprised of three pages, all of them are accessible from the navigation menu. The full responsive navigation bar includes links from the name of the web (Bread) to the Home page, and links to each of the three pages, Home, Register and Login, and is identical in each page to allow for easy navigation.

The navigation bar is located in the upper right corner and for smaller screens it is responsive becoming a hamburger menu. 

This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

The inactive page names are faded while the active page name is regular to allow easy understanding of where the user is within the website.

The nav bar addapts if user is logged in or not.

Desktop nav bar:

- Not logged in

<!-- ![Navbar](static/images/readme/navbar.png) -->

- Logged in

<!-- ![Navbar logged in](static/images/readme/navbar-loggedin.png) -->


Mobile hamburger nav bar

<!-- ![Hamburger navbar](static/images/readme/navbar-hamburger.png) -->

#### Social media icons in footer 

The website includes four social media icons for Facebook, X, Instagram and Youtube. The icons were sourced from [Fontawasome](https://fontawesome.com/) and their colour was changed to fit the colour palette of the website.
  
<!-- ![Footer](static/images/readme/footer.png) -->

#### Home page

The home page has a grey background, it presents the post grouped in three per window, with buttons to allow the navigation through the home page, giving the visitor an idea of what they are going to find in the website.

It is set up using Bootstrap cards with three cards per row and three cards per window.

<!-- ![Home page](static/images/readme/home-page.png) -->

#### Register page

The register page allows user to create a profile to be able to interact whit the posts.

<!-- ![Register page](assets/images/readme/about-page.png) -->

#### Login page

The login page allows the users to login to interact with the posts, via comments and/or likes/unlikes, once they are registered.

<!-- ![Login page](assets/images/readme/gallery-page.png) --->

#### Future implementations

<!-- provide ways for the users to comunicate directly with the website owner, 
aloow users to create comments
add to favourites
to provide a more complete experience -->

Overall performance of the website can be improved as some parts of the site are slowing it down. Unfortunately, this type of addition required more technical knowledge.

#### Accessibility

Alt-labels are used for images. Aria-labels for screen readers are implemented at certain places, also semantic elements are used so the page is easy to navigate.


















## Technologies Used

- **GitHub** – storage and deployment
- **Gitpod** - Editor
- **Heroku** - Deployment
- **Cloudinary** - Cloud storage for static images
- **ElephantSQL** - PostgreSQL database
- **Google Fonts** – import font
- **Font Awesome**- import social media and contact icons
- **Favicon Generator Website** – convert logo
<!-- - **Balsamiq** – wireframes design -->
- **Am I Responsive?** – check responsiveness of the website
- **Google Maps** – embed map location
- **Google Chrome** - build and test the website

### Languages Used

- Python
- HTML/CSS
- JavaScript

### Frameworks and Libraries Used

* Git / Github
* Bootstrap
<!-- * [django-allauth](https://docs.allauth.org/en/latest/)
* [django-crispy-forms](https://django-crispy-forms.readthedocs.io/en/latest/)
* [pillow Imaging Library](https://pypi.org/project/pillow/)
* [django-taggit](https://github.com/jazzband/django-taggit)
* [markdown2](https://pypi.org/project/django-markdown2/)
* [django-image-uploader-widget](https://pypi.org/project/django-image-uploader-widget/)
* django-storages and boto3, for r2 bucket storage
* [django-cleanup](https://github.com/un1t/django-cleanup)
* django extensions for exporting DB schema -->