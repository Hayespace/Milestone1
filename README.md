# Ga / LAB.

Ga / LAB. is a showcase of the works of artist and graphic designer, Gaia Dipilato. It has been designed with sleek minimalism and muted tones in mind, in order not to distract from the artworks and information.

The target audience is art collectors, galleries, and people with disposibale income who enjoy high-end art and design.

## Features

### Nav Bar
- The navbar features links to all three pages with the site name in the top left allows the user to link back to the home page.
- When viewed on a mobile device the links convert to a navbar toggler with dropdown button on the right.  Once pressed the menu drops down on the left below the site title. 
- The current page is signalled by a change in text color to black and a period at the end of the word which is in keeping with the branding and style.
- Simple black and muted grey tones have been selected for styling

![Wireframes](/assets/images/readme_images/navbar.png)
![Wireframes](/assets/images/readme_images/navbar_mobile.png)
![Wireframes](/assets/images/readme_images/navbar_toggle.png)

### Logo
- Logo designed and supplied by the artist
- It sits front and center at the top of each page aross all devices as a styling choice
![Wireframes](/assets/images/readme_images/logo.png)
### Carousel
- Three images provided by the artist sit within the carousel with floating text and description
- The images and text offer examples of the differing styles of the artists work.
![Wireframes](/assets/images/readme_images/carousel.png)
### Bio
- Simple design and responsive design offering brief bio provided by the artist.
### Gallery Page
- A nine piece selection of works which showcase the different styles and mediums used by the artist. Opaque overlays have been added with the name of each piece appearing when hovered over.
- The collection has been kept minimal so as not to overhwhelm the user with content but enough to show variety and scope.
![Wireframes](/assets/images/readme_images/gallery.png)
### Contact from
- Simple and elegant floating contact form with light box shadow.  
- The labels sit inside the input boxes but transform to glide upwards and sit just above the box once clicked.
![Wireframes](/assets/images/readme_images/contactform.png)
### Bottom Logo
-  A simple design idea created by the artist to add a touch of colour to the pages
### Footer
- In keeping with the minimal nature of the site, only a single link to instagram has been included with muted copyright information just below.
![Wireframes](/assets/images/readme_images/footer.png)
# Wirefame
The layout of the final site does not differ too much from the planned wireframes.  
I had an initial design meeting with the artist and the structure was mutally agreed upon as was the colour scheme and font choice.


## index.html
![Wireframes](/assets/images/readme_images/wf_index.png)
## works.html
![Wireframes](/assets/images/readme_images/wf_gallery.png)
## contact.html
![Wireframes](/assets/images/readme_images/wf_contact1.png)


# Testing
## Validator Testing

- HTML - No errors were returned when passing through the official W3C validator
- CSS - No errors were found when passing through the official (Jigsaw) validator

## Issues Encountered and Resolved
- ### Gallery - The overlay div was covering the entire screen and causing the screen and individual images to flicker.
    - Fix - I changed the overlay to to 'display : none;' and hover to 'display : inline-block;'

- ### Contact - Message box was single line and text not wrapping within the box.
    - Fix - I used a bootstrap input template and adjusted the styling to match the other input fields on the page.

- ### Gallery - Images provided by the artist were all different sizes
    - Fix - I manually adjusted the size each image in photoshop to match
    

## Unfixed Bugs
- Contact Page - The message box had to be customised in order to create a larger input field and text wrap.  After using a bootstrap template and custom stying the box, I was unable to recreate the same placeholder text transition as the other input fields.  
Due to the expandable nature of the bootstrap template, I was not able to find a work around that would alow for a variable transition based on the size of the expansion.
# Deployment


The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html
# Credits

All images and artworks were designed and provided by the artist.  Bootstrap was used for some design elements as well as a youtube tutorial for the sign up form.

## Content

- Contact Form - The contact form of my site was heavily influenced by the following tutorial https://www.youtube.com/watch?v=s6rF1Josk9M However, I customised some of the styling. In particular, the message box which only allowed for a single line of text and did not text-wrap so this was replaced with my own code.
- Navbar - Navbar is a Bootstrap template with custom css
- Icons - Instagram icon taken from font awesome
- Logo and Artworks - These are original pieces design and provided by the artist, Gaia Dipilato
- Carousel - Bootstrap template with custom media query
- Gallery - Boostrap grid template with custom borders, overlay, shadows and labels
## Media

- Logo, Artworks and Photos - These are original pieces design and provided by the artist, Gaia Dipilato.

