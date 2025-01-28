# Queen Nefertiti

# Overview

The Queen Nefertiti History Website is an engaging, user-friendly platform that provides an in-depth look into the life, reign, and legacy of Queen Nefertiti, one of ancient Egypt's most iconic figures. Designed for casual learners, history enthusiasts, educators, and researchers, the website aims to make historical learning accessible and visually captivating.

The interface complements the theme of ancient Egypt, utilizing a color scheme inspired by artifacts and a design that balances historical accuracy with modern usability.

![Am I Responsive Screenshot](assets/images/am-i-responsive.png)

## Key Features

### Home Page
* Fixed header for easy navigation that is responsive to mobile, tablet and larger screens.
* Full width landing hero image with overlayed text letting the useer know exactly what the website is for
![Home Page Landing image](assets/images/hero-landing.png)

* An introduction section with a call to action button linking to the Timeline of Events.
![Introduction section image](assets/images/introduction-section.png)

* A small preview of the Artifacts Gallery on the home page for easy navigation and exploration of the other pages relating to the artifacts.
![Artifact call to action section image](assets/images/artifacts-cta.png)

### Timeline of Events
* A Timeline of Events explaining significant moments in Queen Nefertiti's life.
![Timeline of events image](assets/images/timeline.png)
* A supporting video for a more dynamic, multimedia learning experience.
![Timeline video image](assets/images/timeline-video.png)

### Artifact Gallery
* An Artifact Gallery featuring detailed information on items linked to Nefertiti's era.

* The Artifact Gallery cards are clickable links that open a more detailed section on the artifacts
![Artifacts gallery image](assets/images/artifact-gallery.png)
* This page includes a link back to the gallery for easy navigation.

### Did You Know?
* A Did You Know? section for users seeking fast facts about the Queen and her era.
![Did You Know? facts image](assets/images/did-you-know-facts.png)

### Newsletter Signup
* A newsletter signup form that appears on all pages.
![Alt](assets/images/)

### Related Content
* A related content section with links to the other pages
![Related Content image](assets/images/related-content.png) 

### Footer
![Footer image](assets/images/footer.png)

* The footer includes information about this website.
* Secondary navigation links
* Links to sources used for the content for this website.
* Links to external websites open in a seperate tab
* Copyright information

### Features Left to Implement
* 3D model of Nefertiti Bust
* Interactive Map of ancient Egypt

## Testing

### Navigation
* I have tested all links and buttons to ensure they work and are linked to the correct section/page.
* I have tested all of the links to external websites in the footer

### Responsiveness
* I have tested the website across multiple screens to ensure the layout responds well and is as intended.

### Media Functionality
* I have tested that the video plays as intended and does not autoplay
* All images display and loads as expected

### Content Accuracy
* I have checked for grammatical errors and proper display of the text

### Loading Speed
* I have tested the website loading speed to ensure there are no delays

### Broken Links
* I have tested that any broken links are now working as intended.

### Accessibility
* I have tested my web pages using Lighthouse in Dev Tools and fixed any issues, keeping a high score.

## Validator Testing

### HTML

Bugs
* ul not allowed as child element of ul - I removed and used another element.
* h3 not allowed as child of ul - I placed it outside of the ul element.
* Button not allowed as a child of the anchor tag. - I removed the button and styled the anchor tag as a button.
* A stray </a> was found. I removed it
 

### CSS

Bugs 
* Value Error: removed display: hidden on hr element.
* Removed invalid values from .link-container
* Missing value on padding. -fixed.


### Bugs

### Deployment

* I went to the 'Settings' tab of my GitHub repository.
* On the left-hand sidebar, in the Code and automation section, I selected 'Pages'.
* I set 'Source' to 'Deploy from Branch'
* I selected 'Main Branch'
* I set 'Folder' to /(root).
* I clicked save
* I went back to the 'Code' tab and refreshed after a couple minutes.
* On the right sidebar, I went to deployments and viewed my deployed website.

* Live link here: https://francisjxmes.github.io/queen-nefertiti/index.html

## Credits

- Header and responsive nav bar credit to: [Coding2go](https://www.youtube.com/watch?v=8eFeIFKAKHw&list=PLx7XtnNwKaYwtHlY0UNAkb9QiWvXiKtNt&index=2)
- Guidance on Flex Box system credits to: [Coding2go](https://www.youtube.com/watch?v=8eFeIFKAKHw&list=PLx7XtnNwKaYwtHlY0UNAkb9QiWvXiKtNt&index=2)
- Button styling and hovering effects tutorial credits to: [SuperSimpleDev](https://www.youtube.com/watch?v=G3e-cpL7ofc&list=PLx7XtnNwKaYwtHlY0UNAkb9QiWvXiKtNt&index=1)
- Steps to embedding a video from youtube into HTML credit to: [Web Dev Tutorials](https://www.youtube.com/watch?v=ly36kn0ug4k&list=PLx7XtnNwKaYwtHlY0UNAkb9QiWvXiKtNt&index=3)
- The arrow icons on the buttons taken from [Font Awesome](https://fontawesome.com/icons)

### Content

- The text in the introduction section was taken from [history.com](https://www.history.com/topics/ancient-egypt/nefertiti)
- The content for Timeline of Events was researched on [history.com](https://www.history.com/topics/ancient-egypt/nefertiti) and [britannica.com](https://www.britannica.com/biography/Nefertiti)
- The text on the Artifact Cards and in the detailed artifacts information page was taken from [metmuseum.org](https://www.metmuseum.org/search-results?q=nefertiti+amarna+period&searchFacet=Art)
- The content for the Bust of Nefertiti on the artifacts gallery was taken from [smb.museum](https://www.smb.museum/en/museums-institutions/aegyptisches-museum-und-papyrussammlung/collection-research/bust-of-nefertiti/the-bust/)
- The Did You Know facts was taken from [history.com](https://www.history.com/topics/ancient-egypt/nefertiti), [britannica.com](https://www.britannica.com/biography/Nefertiti) and [factinate.com](https://www.factinate.com/people/facts-nefertiti)

### Media

- The Nefertiti bust images on the artifacts gallery was taken from [smb.museum](https://www.smb.museum/en/museums-institutions/aegyptisches-museum-und-papyrussammlung/collection-research/bust-of-nefertiti/the-bust/)
- The artifacts images on the gallery page was taken from [metmuseum.org](https://www.metmuseum.org/search-results?q=nefertiti+amarna+period&searchFacet=Art)
- The video on the Timeline of Events page was taken from [National Geographic Youtube Channel](https://www.youtube.com/channel/UCpVm7bg6pXKo1Pr6k5kxG9A)




example: 
* The text for the Home page was taken from Wikipedia Article A

* Instructions on how to implement form validation on the Sign Up page was taken from Specific YouTube Tutorial

* The icons in the footer were taken from Font Awesome

example:
* The photos used on the home and sign up page are from This Open Source site

* The images used for the gallery page were taken from this other open source site

Congratulations on completing your Readme, you have made another big stride in the direction of being a developer!
