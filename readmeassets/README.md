# **Bujinkan Club Finder**

### 2nd Milestone Project - Interactive Frontend Development - Code Institute - Tadhg Nolan.

The owner requires a website show users Bujinkan club locations within their proximity.

The purpose is to direct customers towards aforementioned clubs.

---

### Showcase

A deployed link to the website can be found [here](https://tadhgnolan.github.io/MilestoneProject2)
![Preview](https://github.com/tadhgnolan/MilestoneProject2/blob/master/readmeassets/landingsample.PNG)

### UX

End users will be those looking for martial arts classes. This encompasses an age range from 18 to 60 (essentially working age and beyond). The technological approach is mobile first

- As a user I would like the club locations to be visible with minimal clicks.

- As a user I would like the map & markers to be clearly visible, but leave room on mobile to allow scrolling to other parts of the page.

- As a user I would like to a description of what Bujinkan is.

- As a user I would like to have a way to contact the site with any further questions I may have.

- As a user I would like to have access to social media links to what the creator is working on & media that interests them or is related to the sites content.

**Wireframe Mockups**

Click [here](https://github.com/tadhgnolan/MilestoneProject2/blob/master/readmeassets/bujinkanclubfindermockup.pdf) to see wireframe concept mockups for the website

### Features

Home/landing area - This area should be an image related to the subject matter & direct me towards the information I require.

Navbar - Hamburger menu for easy access on mobile devices.

Go to map - Links directly to the map & club locations.

What is Bujinkan - Links directly to the section describing Bujinkan.

Any questions - Links to the contact form.

Footer - Social media links if users wish to contact or follow the site owner.

### Existing Features

Navbar - allows users to quickly access all content from one place & will collapse as soon as link is pressed.

Find button - allows users to go directly to map & view nearby club locations.

Any questions - Users can fill out their email address and contact the site owner with any further questions they may hive. (Form is currently non-functional as it is beyond the scope of this assignment and my current abilities). "Send it" button highlights when hovered over or pressed to alert user.

Footer - Social media links can be accessed here and will open a new browser window.

### Future Features

Use JavaScript & Google Maps JS API to display individual club websites and images in a modal. Attempted to do this with a pop out panel, but was unsuccessful, possibly due to conflicts with Bootstrap.

Set up a mail server, currently website is static as per project outline.

Aim for higher lighthouse scores for greater efficiency.

### Optimisation

Followed as many recomedations as possible, within my ability, suggested by Lighthouse testing.

Added smooth scrolling in css for better UX.

---

### Testing

All testing performed before and after each commit.

Repeated real world testing performed with Google Pixel 3aXL (2160 × 1080px), Nokia 3 (720 x 1280), Asus Nexus 7 (1920 x 1200px) & Desktop PC (1920 x 1080px) representing a mixture of age plus hardware capability & were readily available.

In Lighthouse (Chrome Dev Tools) Samsung Galaxy S5, Google Pixel 2, Pixel 2 XL, Apple iPhone 5/SE, iPhone 6,7 + 8, 6, 7 + 8 Plus, iPhone X, iPad, iPad Pro as well as all available responsive presets from Mobile S-320px to 4K-2560px were tested repeatedly.

This functionality testing involved:

- Verifying all navbar & other links functioned as expected.

- Using Chrome Dev Tools Elements tab to test out small styling changes before adding.

- Checking that fonts scaled correctly for each display size.

- Checking for overflow.

Tested initial html layout with https://validator.w3.org
Found error with initial commit. Removed <button> tag & replaced with <a> link styled to look like button with CSS.

Tested navbar using server and https://validator.w3.org.

Found no issues with markdown validator.

Tested main body sections-containers-rows in Chrome Dev Tools with all available phone & tablet presets as well as pc. Functioned normally on each.

Tested html code for social media icons and About text at https://validator.w3.org.

Tested css at https://validator.w3.org. No error found.

Html & css passed validators on https://validator.w3.org.

Tested form & page with all device presets in Chrome dev tools. Initital form alignment was not ideal. Tried correcting with Bootstrap with no success. Corrected with custom css & was successful.

Had repeated discussions over zoom & review over Google hangouts with family member who has worked as a dev. Had intitial project meeting and halfway meeting & final meeting with mentor over Skype.

Added theme-color meta tag after reviewing Lighthouse score in Chrome Dev Tools & following suggestions.

---

Project proposal meeting, midway review and final review by mentor, followed by action on any identified issues.

### Remaining Bugs

Unknown Javascript issue which I was unable to clearly identify. This did not manifest in any clearly visible way in the finished site, but did reduce the final Lighthouse score and possibly increased loading times.

Unable to get Google maps pop-out panel to function. Commented out code & will attempt to resolve at a later date.

**Deployment**
_On GitHub:_ Checked that branch was present in repository. Navigated to site repository on GitHub. Clicked settings under repository name. Selected master branch for GitHub Pages under source drop-down menu.

_If you wish to run this project locally:_

```
1. Click clone / download
2. Choose your preffered method (Zip or github desktop)
3. Open in your preffered IDE
4. Run on local server
```

### Technologies Used

- [HTML5](https://html.spec.whatwg.org/multipage/)
- CSS3
- JavaScript (https://www.javascript.com/)
- Bootstrap 4.4.1 - The project uses **Bootstrap** for additional styling.

* [JQuery](https://jquery.com)
  - The project uses **JQuery** to simplify DOM manipulation.
* [Visual Studio Code](https://code.visualstudio.com/) - IDE used to write and deploy code.

### Credits

**Navbar** https://mdbootstrap.com/snippets/jquery/mdbootstrap/102551

https://www.udemy.com/course/bootstrap-4-from-scratch-with-5-projects
(Course Resources Section 3: CSS Components - Navbar & Navs. Brad Traversy)

**Hero Image**
http://bujinkanshinkendojo.blogspot.com/2017/01/las-escuelas-de-la-bujinkan-dojo.html

**Footer**
https://mdbootstrap.com/docs/jquery/navigation/footer/

**Fonts**

https://kit.fontawesome.com/668eef35c0.js

https://fonts.googleapis.com/css?family=Baloo+Bhaina+2|Open+Sans+Condensed:300|Roboto+Condensed&display=swap

**Favicon**
https://cdn1.iconfinder.com/data/icons/love-for-books/154/reading-book-512.png

**Websites Referenced**

https://color.adobe.com/create/image

https://www.w3schools.com/

https://getbootstrap.com/docs/4.4/

https://stackoverflow.com/questions/4758878/how-to-increase-the-font-size-of-one-word-only-in-the-line

https://stackoverflow.com/questions/10041706/applying-a-single-font-to-an-entire-website-with-css

https://web.dev/themed-omnibox/?utm_source=lighthouse&utm_medium=devtools

https://stackoverflow.com/questions/710089/how-do-i-make-an-html-link-look-like-a-button

https://stackoverflow.com/questions/11151089/position-one-element-relative-to-another-in-css

https://codelabs.developers.google.com/codelabs/google-maps-nearby-search-js

https://www.w3schools.com/howto/howto_css_hero_image.asp

https://developers.google.com/maps/documentation/javascript

### Content

All written content was created by the site owner.

### Acknowledgements

- Many thanks go out to Cormac Nolan who provided lots of advice and feedback over Zoom throughout the project. This was greatly appreciated.

- I would also like to give my thanks to Aaron Sinnott for mentoring me through the process. His advice and feedback was of great help in achieving the finished site.

### Created by Tadhg Nolan
