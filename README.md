# **Milestone Project 1 - Joyce Brok - WIP**
## Portfolio Website for a Digital Artist - [View deployed site here.](https://chrotesque.github.io/ci-portfolio-project-1/)

<br>

# Table of Contents

1. [Overview](#overview)
2. [UX](#ux)
    * [Strategy](#strategy)
    * [Scope](#scope)
    * [Structure](#structure)
    * [Skeleton](#skeleton)
        * [Wireframes](#wireframes)
    * [Surface](#surface)
3. [Features](#features)
    * [Current Features](#current-features)
    * [Future Features](#future-features)
4. [Technologies Used](#technologies-used)
5. [Testing](#testing)
6. [Bugs](#bugs)
7. [Validation](#validation)
8. [Deployment](#deployment)
9. [Credits](#credits)
10. [Acknowledgements](#acknowledgements)

<br>

# **Overview** ([^](#table-of-contents))

A website meant for the artist as place to showcase her portfolio as well as providing necessary information for potential new customers while offering a glimpse into the artist herself. While the title states "Digital Artist & Facebook Streamer" the focus is on the aspect of being an artist, with intentional rare mentions of the streaming aspect. It covers a select portfolio, pricing information, process of ordering and receiving work done as well as a bit of information about the artist, including a vast array of methods to establish contact.

<br>

# **UX** ([^](#table-of-contents))

* ## **Strategy**
    ### **Target Audience**
    The target audience of this website are people that are looking to have affordable custom made artwork for various purposes.

    ### **Business Goals**
    - Acquiring new clients to grow in reach ultimately
    - Setting expectations before a client contacts the artist
    - Simplifying the process of contact the artist by offering many options to do so, without automating the entire process to allow the artist to select clients to work with

    ### **User Stories**
    -   First Time Visitor Goals (Visitor stumbles upon the website)
        1. As a first time visitor, I want to quickly understand the purpose of the website
        2. As a first time visitor, I want to find the portfolio of the artist
        3. As a first time visitor, I want to be able to quickly navigate the sites different sections on any device I happen to use at the time

    -   Redirected First Time Visitor Goals (Visitor has an idea what to expect)
        1. As a first time visitor, I want to find the portfolio of the artist
        2. As a first time visitor, I want to find to find information about pricing, commission process as well as contact details 

    -   Returning Visitor Goals
        1. As a returning visitor, I want to be able to review the comission process in case contact is temporarily interrupted (schedules, sleeping rhythms, etc.)
        2. As a returning visitor, I want to be able to find contact information in case it has been lost

<br>

* ## **Scope**
    The website will offer: 
    - a fully responsive design for ease of use on any device
    - a selection of the artist's portfolio
    - information about the comission process including pricing
    - many ways to contact the artist to ease the process of interacting
    - a bit of information about the artist

<br>

* ## **Structure**
    - The contents are segmented into clearly separated logical sections
    - The purpose of the website is briefly explained on the landing / home page
    - The portfolio to show visitors a broad range of the artists work to help with the decision of purchasing art
    - The comissions page is required to offer information about pricing and if the product meets the visitors needs (DPI, file format, file size, etc.)
    - The dedicated contact page offers every imaginable way of contacting the artist (that she's also willing to offer, excluding a phone number as well as physical address) while social links are provided on every single page for ease of use 
    - The about page offers a bit of information about the artist

<br>

* ## **Skeleton**
    ### **Navigation**
    - separates the contents of the page into logical sections to make it obvious what information will and can be accessed and where
    - all parts of the website are available at all times through the navigation
    - navigation is always at the top of the screen to be always accessible

    <br>

    ### **Wireframes**
    <details>
    <summary>Flow with different positions for social icons (click to expand)</summary>

    ![Desktop flow #1 - Socials in footer](assets/images/readme/balsamiq/desktop_flow1.jpg)
    ![Desktop flow #2 - Socials fixed at bottom right side of page](assets/images/readme/balsamiq/desktop_flow2.jpg)

    </details>
    <details>
    <summary>Content wireframes for desktop (click to expand)</summary>

    ![Desktop wireframe for Home page](assets/images/readme/balsamiq/desktop_home.jpg)
    ![Desktop wireframe for Portfolio page](assets/images/readme/balsamiq/desktop_portfolio.jpg)
    ![Desktop wireframe for Comissions page](assets/images/readme/balsamiq/desktop_comissions.jpg)
    ![Desktop wireframe for About page](assets/images/readme/balsamiq/desktop_about.jpg)
    ![Desktop wireframe for Contact page](assets/images/readme/balsamiq/desktop_contact.jpg)

    </details>
    <details>

    <summary>Mobile UI (click to expand)</summary>

    ![Phone UI](assets/images/readme/balsamiq/ui_mobile.jpg)

    </details>

    <br>

    #### **Differences from wireframes to result**
    - During the first mentor session I heard the term "mobile first" and decided to change my approach, the wireframes preceeded that meeting and were not updated to reflect that change in approach which is why the content is sketched out entirely on desktop versions but not for mobile or tablets
    - A secondary top bar holding the sub title "Digital Artist & Facebook Streamer" ultimately complicated the process too much, which is why it was left out
    - The lightbox feature of the gallery was not thought about until my Mentor mentioned it in the 2nd mentor session 

    #### **Limitations**
    - The final implementation of a carousel was born out of the frustration of not understanding keyframes from online examples, it was meant as placeholder and "good enough"-implementation until the very end when I would then decide to either finish the project or leave it be. It turned out better than anticipated and replaced the original carousel 

    <br>

* ## **Surface**
    ### **Navigation**
    - The navigation is consistent between desktop and mobile versions in it's behaviour, as it sticks to the top of the page to always be available.
        - On mobile it uses a standard hamburger menu to reduce space. The hamburger menu then offers all social links as well as internal navigation links. 
        - On the desktop version it separates social links and internal navigation as space is no longer a concern
    - There's an intentional inconsistency:
        - The top left bar featuring the artist's name remains fixed on the top on desktop as it is visually part of the navigation
        - It is not fixed on the mobile version to preserve space and to follow the mantra "mobile first, content first"; as it is part of every page and will be displayed upon loading another page, however as it is not functional nor can be considered "content" which is why I decided to detach it from the navigation

    color scheme: https://coolors.co/9689f6-43405c-c8c5e3-25171a-bbbf99
    https://coolors.co/9689f6-43405c-c8c5e3-25171a-bbbf99

<br>

# Features ([^](#table-of-contents))
## TBD

<br>

# Technologies Used ([^](#table-of-contents))
- Main languages: [HTML5](https://en.wikipedia.org/wiki/HTML5) & [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [Google Fonts](https://fonts.google.com/) used for fonts throughout the whole site
- [Font Awesome](https://fontawesome.com/) used for a few select icons to be able to style them as font/text
- [Git](https://git-scm.com/) used for version control through the Gitpod terminal for deployment onto Github
- [GitHub](https://github.com/) used as host and for deployment of the site
- [Gitpod](http://gitpod.com) used as IDE
- [ClickUp](http://clickup.com) used for project management and to track time used on the project
- [WakaTime](https://wakatime.com) used as time tracking replacement for ClickUp towards the end of the project as per recommendation of my mentor due to it's automated nature
- [Adobe Photoshop 2021](https://www.adobe.com/products/photoshop.html) used for image optimization, saving files in WEBP format as well as creating the collage images used on the front page of this project
- [TinyPNG](https://tinypng.com/) used to optimize JPG and PNG file sizes for this project
- [Lettercounter](https://lettercounter.github.io/) used to keep commit messages below or at 50 characters
- [Am I Responsive?](http://ami.responsivedesign.is/) used to create responsive preview of the site used at the top of this readme
- [Coolors](https://coolors.co/) used to create a color palette for this project
- [Balsamiq](https://balsamiq.com/) used to create the wireframes during the initial design stage
- [Statcounter](https://gs.statcounter.com/screen-resolution-stats) used as resource to optimize website for various commonly used resolutions as a priority

<br>

# Testing ([^](#table-of-contents))
## TBD

<br>

# Bugs ([^](#table-of-contents))
### Existing bugs
- style.css line 226 - without a padding on the bottom, the content reaches the very edge of the screen. With 0.1px it creates the desired gap to the bottom, giving it a bigger value will just make it bigger which is undesired. Marking it as bug as I don't understand the cause, unlikely a real bug but rather a consequence of my html/css choices:
    >   #wrapper { padding-bottom: 0.1px; }


  
### Resolved bugs
- Chromium-specific: Upon opening the hamburger menu 2 sides slide in from the left (30% wide) and right (70% wide) respectively, occasionally (what felt like 40-50% of the time) there would be a 1px wide gap between the two sides
    - Workaround:
        1. initially both sides had 
            > background-color: var(--standard-dark-95);
        2. changed that to right side specific and gave left side 
            > background-color: var(--standard-dark);
        3. to mask the gap if it occurs I added to the left side 
            > border-right: 2px solid var(--standard-dark);
        4. without additional changes, having one side partially transparent and one opaque looked odd, added box-shadow to make it work visually
            > box-shadow: 0 4px 12px #000;
        5. Another gap then appeared on the right side this time, due to previous fix there's extra margin to work with, thus moving it to the right slightly:
            > right: -1px !important;

<br>

# Validation ([^](#table-of-contents))
## TBD

<br>

# Deployment ([^](#table-of-contents))
This project was developed using Gitpod through which it was committed and pushed to the repository on Github as host:
1. Visit [http://github.com](http://github.com) and login
2. Navigate to the respective [repository](https://github.com/Chrotesque/ci-portfolio-project-1)

## Github pages
Github pages were used to deploy the project as follows:
1. Open the **Settings** on the repository specific navigation marked with a gear icon
2. Navigate to the **Pages** subnavigation on the left
3. Select the master branch under **Source** and click **Save**
4. The page refreshes automatically and displays the published site URL at the top next to an exclamation mark
5. It will take a couple of minutes for the site to become available initially

## Making a Local Clone
Once the project has been accessed on Github:
1. Underneath the repository specific navigartion you'll find the button **Code** on the right side above the file listing
2. Upon click, the pop-up will offer the option to copy the repository's git-URL with HTTPS selected at the top within the pop-up
4. Open a Git Bash terminal
5. Change the current working directory to the location where you want the cloned directory to be made
6. Type **git clone**, and then paste the URL you copied in Step 3 and hit Enter; your local clone will now be created

<br>

# Credits ([^](#table-of-contents))
## Media
- All images used on the site were provided to me by the creator Joyce Brok herself

## Content
- All content was written by the developer (exception being the testimonials on the comissions page, as they were written by their respective and named individuals).
- The color palette was created by the developer himself, with some limited input from Joyce Brok for some final touches

## Code
- Hamburger menu was based off of [this Codepen example](https://codepen.io/alvarotrigo/pen/yLzaPVJ), modifications were made to better fit this project  
- Lightbox used in the Portfolio is [CSSBox](https://github.com/TheLastProject/CSSBox), specifically the simplified [v1 Branch version](https://github.com/TheLastProject/CSSBox/tree/v1), modifications were made to better fit this project
- In order to always have the footer at the bottom of a page regardless of content length (necessary for about & contact) I followed a [video tutorial from Dani Krossing](https://www.youtube.com/watch?v=qlCIXXhSX6Y)

## Readme
- I took inspiration from the Table of Contents used in [Github User's taybro23 project](https://github.com/taybro23/AboveBoard_MS4), as well as more general inspiration (and guidance) from [AJGreaves](https://github.com/AJGreaves/portrait-artist) and [the SampleReadme from CI](https://github.com/code-institute-solutions/samplereadme).

<br>

# Acknowledgements ([^](#table-of-contents))
I'd like to thank:
- My Mentor Jack Wachira for our concise and helpful feedback sessions
- My Ex-Colleague and now fellow student [Mycrosys](https://github.com/Mycrosys/) for feedback

https://caniuse.com/?search=var() - 94.27% of all users fully supported