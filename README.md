# Rick Russell Ceramic Tiler - User Centric Frontend Milestone Project
<https://harclemadscam.github.io/first-milestone-project/>
## Overview
As part of the Code Institute Full Stack Web Developer course, I was tasked with building a mobile-first responsive website for my first project. 
I decided to create a website for an experienced, self-employed ceramic tiler called Rick Russell. 
It not only provides him with an online presence where potential customers can contact him for work, but also promotes his services and encourages potential customers to request a quote. 
The website is a single page starting with a landing page, and scrolling down the page will take you to Testimonials, an About Rick section, a photo Gallery, and finally a Contact Rick form. 
There is also a footer with social media links.

The website utilises the frontend skills I have learnt in the first two modules of the course. 
It is responsive across different devices, with some extra content appearing on larger resolutions. 
These include extra testimonials, customer photographs, extra text in the About Rick section, and a larger selection of images in the gallery. 
At the top of the page is a fixed navigation bar, that allows the user to navigate to the different sections of the page with a click. 
On mobile resolutions the bar collapses to a "burger menu" button.

## UX
My full UX documentation can be found in the ux-design folder, which can be found [here](ux-design).
This includes documents detailing my thoughts on the strategy and scope planes of this project, plus the basic structure and my skeleton wireframes.

### User Stories

* As a potential customer of Rick Russell, I want to be able to contact him so that I can request his services and/or a quote.
* As a potential customer who yet to be convinced, I want to read what other customers have to say about his services so that I can make up my mind.
* As someone looking to have their bathroom tiled, I want to be able to view images of bathrooms Rick has tiled to assess the quality and come up with ideas.
* As a business owner, I want to be able to find out more about Rick Russell before I consider hiring him for a job, as I want to know that he is someone I can trust.

## Features
### Existing Features

* The navigation bar allows users to navigate to the different sections of the page by clicking or tapping the appropriate heading. Clicking or tapping the brand name furthest to the left will reload the page.
* The landing page features a button that will navigate to the contact form.
* The Testimonials and About Rick sections use responsive Bootstrap grids to present text and images. There are links to social media and other sections of the page in the About Rick section.
* The Gallery section uses Bootstrap Cards to create a responsive Pinterest-style image gallery.
* The Contact form allows users to input data into the appropriate fields and submit that data with a button click.
* The footer includes icons that can be clicked or tapped to open up social media pages in a new tab.

### Future Features

* The gallery could be expanded to feature more images while taking up the same amount of space on the page, possibly with the use of a carousel or images that can be hidden. These images could also be enlarged with a click.
* An additional script could allow the navbar links could cause the page to scroll to the relevant section rather than immediately snap to it.
* The input validation of the contact form could be improved. A captcha could be added to prevent bot spam.

## Technologies Used
* [HTML5](https://www.w3.org/TR/2017/REC-html52-20171214/)

  * A fundamental requirement. Used to create the index file, providing the structure of the page.

* [CSS3](https://www.w3.org/Style/CSS/)

  * The other fundamental requirement. Used to add custom styling to the HTML - including fonts, layout and colours.

* [Bootstrap](https://getbootstrap.com/)

  * An open source framework focused on responsive, mobile-first development. Used to create a number of components and features on the page, 
  including the navigation bar, landing page jumbotron, responsive grids, and the image gallery.

* [Git](https://git-scm.com/)

  * Used for version control and committing changes to GitHub.

* [GitHub](https://github.com/)

  * Used to host and publish my project files.

* [Google Chrome/Developer Tools](https://www.google.com/chrome/)

  * My internet browser. 
  The Developer Tools were used to troubleshoot, edit the layout, and preview changes, as well as test the responsiveness of the page.

* [GitPod IDE](https://gitpod.io/)

  * The application I used to develop the project.

* [Font Awesome](https://fontawesome.com/)

  * Used to source the social media icons on the footer.

* [jQuery](https://jquery.com/)

  * Used briefly in a script that collapses the navbar dropdown when a link is tapped in a mobile view. See the acknowledgements below for the source of this solution.

* [Google Fonts](https://fonts.google.com/)
  
  * Used to provide the Noto Serif font.

## Testing
All actions have been tested in the following browsers: Google Chrome, Opera, Mozilla Firefox, Internet Explorer 11.

1. Basic testing
   1. When the page is loaded, all images load properly and appear as they should. The landing page image is large and takes half a second to load on most browsers.
   2. All sections load and display as they should, including text and the contact form. The exception is the image gallery in Internet Explorer, which has a minor visual bug in displaying an empty white box underneath one of the images.
   3. The colours appear normally in all but one browser. Internet Explorer does not display the hyperlinks in the About Rick section in the custom colour.
   4. The font Noto Serif displays correctly.

2. Navigation Bar and Landing Page
    1. The navbar bar is visible and stays fixed to the top of the screen.
    2. All navbar links can be clicked and the link works properly, moving to the appropriate section.
    3. Clicking the brand "Rick Russell" reloads the index file.
    4. All hover styling effects work properly when the cursor hovers over them.
    5. The navbar options collapse to a "burger menu" icon when viewed on a mobile resolution. 
    This has been tested using the browser developer tools and on an Android phone using the Opera Touch browser.
    6. The collapsed burger menu can be toggled with a tap to show the links and hide them.
    7. All navbar links in the mobile view are working and move to the appropriate section when tapped. In addition, the menu is hidden when a link is tapped.
    8. The "Get a quote" call to action button on the landing page can be clicked or tapped and navigates to the contact form as expected.

3. About Rick section
   1. The links within the About Rick section are working properly and navigate to the correct section. For external links, the correct page loads in a new tab.
   2. The hover styling effect of the links is working properly when the cursor hovers over them.

4. Responsive design
   1. Using the browser developer tools, several different device resolutions have been tested.
   2. On the mobile views, the page displays with a more compact view. The Testimonials section lists three quotes one on top of the other and does not feature photos. 
   The About Rick section features four paragraphs and the photo below the text. The gallery features four photos, one on top of the other. 
   As mentioned in the navbar section above, there is a burger menu for the nav links. This is working as intended.
   3. On the smaller tablet views, the page is less compact. The Testimonials are still displayed one on top of the other, but instead have photos and there is an additional quote. 
   The About Rick section includes two additional paragraphs. The gallery now features eight photos in a grid. The burger menu is replaced with links across the navbar. This is working as intended.
   4. On the larger tablet views, the page features more space but is mostly the same. 
   The most significant difference is that the Testimonials are now arranged in a two by three grid of six quotes with photos. This is working as intended.
   5. On the desktop view, the layout is similar to the larger tablet view. The About Rick section now has the photo sat beside the text and the contact form is more central.

5. Contact form
   1. 

## Deployment
Used master branch
used git
selected master branch on github

## Credits
### Content
All text content was created by myself.
### Media
Images were sourced from: 

<https://www.pexels.com/>

<https://unsplash.com/>

<https://images.google.co.uk/> (with usage rights set to labelled for reuse)

### Acknowledgements
My design was inspired by the Whiskey Drop miniproject that was demonstrated as part of the course, as well as the Haley Schafer sample project.

The jQuery script that I used to collapse the navbar dropdown when links were tapped was found in this [stackoverflow thread](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click).

