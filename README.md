<![endif]-->
# Welcome


## Purpose and target audience

The Together Cycling website is an online space designed to unite cyclists in the Stockholm (Sweden) area, offering a resource for peloton rides. This site aims to serve the specific needs of individual cyclists who may not be affiliated with any particular cycling club.

The primary objective is to provide regularly updated group training opportunities/peloton rides in the Stockholm area with different starting points and focus. It is a centralized location where you can discover upcoming rides with information on date, time and rides specifics. In addition to this, the aim is also to provide a source of inspiration with a collection of curated maps offering rides suggestions for individual solo rides.

### User stories

- As the organizer, I want to establish a cycling community where riders can connect, share their cycling experiences and enjoy group rides together.

- As an experienced cyclist, I need easily accessible information on upcoming peleton rides in my area, which will enable me to join rides that suit my training goals and skill level.

- As an experienced cyclist, I seek an online source that provides a variety of inspiring routes and rides that help me stay motivated and continously challenge myself.

- As a cyclist new to peloton riding, I'm eager to learn the ropes of riding in a group and need resources and guidance that help me ride safely and confidently in a peloton.

- As a prospective member considering joining the group, I want to learn more about the individuals behind this cycling community. Understanding their vision will help me evaluate if it aligns with my interests.

## Design

### Color palette

Colormind have been used to find matching colors.

- Header and Footer color : #2C4658 (dark greyish blue)
- Text : #F4F4F2 (white)
- Headings :  #4EABA5 (greyish mint) or #F4F4F2 (white)
- Call to action : #2C4658 (dark greyish blue)
- Background colors : #312539 (dark lilac), #B2495E (greyish apricot)

<http://colormind.io/bootstrap/>

### Typography

Google fonts have been used for this site.

- Logo: Bricolage Grotesque, Extra Bold 800

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/bb24a08d-3ac5-4492-922a-96628c16b134)

- Headings & Body: Nunito, Regular 400

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/24116196-3259-4cb4-9f0a-96012a28d324)

- Signature: Give You Glory, Regular 400

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/8064aee0-b7c1-4536-bf34-8b5d69aaf103)

### Wireframes

xxxx

### Imagery

Each of the three pages have a different background image, seen below in their original state. For a more dramatic and consequential look a color gradient overlay with #312539 (dark lilac) to #BA567B (greyish pink) has been applied to all. The two colors was picked from the site’s color scheme.

Image source: [https://unsplash.com/s/photos/](https://unsplash.com/s/photos/)

### Icons

Icons used come from Font Awesome

- Strava
- Instagram
- YouTube
- Contact/Mail to

Fav icon used for the tab image comes from rawpixel and was generated through favicon.io to get all the versions supported by the different browsers.
<https://favicon.io/>

## Pages & Features

### General Features

* *Together Cycling logo* links back to the home page.

- **Navigation bar** : Upper right corner on screens above 768px and hamburger menu on smaller screens:
  - *Home* goes to the index page with information about the purpose of the site and information on the people behind it.
  - *Rides* takes the user to a page with maps and information on upcoming rides.
  - *Ride with us* links to a sign up form to get news on upcoming rides

- **Footer** : The copyright information is only shown on screens larger than 768px, while the social media icons and the contact/mail to icon are visible on all screen sizes.
  - Strava icon:
	 links to Strava, should link to the group page if there were one.
  - YouTube icon:
	links to YouTube, should link to the group page if there were one.
  - Instagram icon:
	links to Instagram, should link to the group page if there were one.
  - At-icon:
	is a mailto-link to together@together-cycling.com. It opens in a new tab if the user uses a browser email client.

### Pages

- Home page:
On the home page which is the index page, the user gets a clear understanding of what the site is about, the purpose and who is behind it.

- Rides page:
This page contains information on scheduled rides with ride specifics and maps showing the route, which enables the cyclists to evaluate the planned rides to see if they match their needs and wants.

- Ride with us page:
Ride with us has a form to sign-up for a newsletter with information on scheduled rides and other updates. In the future this could potentially become a members page with a login to add personal information and order cycling clothes with the Together Cycling team logo.

## Technologies

**HTML, CSS and Git commands**
- GitHub for storing repository
- Codeanywhere for code editing

**Imagery**
*Photoshop to convert images to webP files, and resizing.

**Content**
- Font Awesome: to generate icons used on the page.
- Favicon generator: to generate the fav icon on the tab next to the title.
- Google Fonts: to find the fonts used on the page and to get the code to embed on the page.
- Google maps/My maps: to generate the rides shared on the rides page.

## Accessibility

I have used header, main and footer elements, as well as section elements to make the page accessible and easy to consume for people with disabilities or slow internet connections. Aria-labels and alt-text on images have been used consistently for screen reading or in the case of images not loading properly. Images have been converted to webP to improve site performance, as well as resizing the images to the smallest possible size with kept quality.

## Deployment

xxx

## Testing & Validation

### Testing

Testing of the site functionalities was performed on:

- Laptop: Dell 5430
- iPhone 13
- iPad 9

Based on statistics from [Top Browsers Market Share - Most Popular Browsers in July 2023 | Similarweb](https://www.similarweb.com/browsers/) all testing was done using:

- Google Chrome
- Safari
- Microsoft Edge
- Mozilla Firefox

Screen reading was tested using built-in browser functionality in Chrome.

### Validation

**Home page:**
There was an incorrect use of an aria-label attribute with a link, when that was corrected and two open tags were close the paged passed the validation.

- <https://jigsaw.w3.org/css-validator/>
- <https://validator.w3.org/>
- <https://wave.webaim.org/report#/https://charlottag.github.io/Together-Cycling/>
- <https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fcharlottag.github.io%2FTogether-Cycling%2Frides.html&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext>

**Rides page:**
Had issues with the width and height attributes for the iframes, that were initially set to 100%. This had to be change to a numeric value and that caused some errors on the display of the elements. A new media query for smaller screens had to be added to accommodate the display on screens less than 380px.

The google maps cause the page to perform bad.

**Ride with us page:**
No issues.

## Credits

### Acknowledgement

xxx

### Code used

* Navbar: Code used from the CodeInstitute learning project - Love Running
- Autocomplete feature on the form was inspired by: <https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete#values>
- Tricks for the mailto-link to use target-blank feature for web based email clients to open in new window to avoid surprises, and using the noreferrer for privacy reasons. [https://css-tricks.com/all-about-mailto-links/](https://css-tricks.com/all-about-mailto-links/)

### Content

Copy is my own with help from open.ai to flesh out the text on the Ride with us sign-up page.

### Media

- Rawpixel was used to find a fav-icon for the tab. (<https://www.rawpixel.com>)
- Favicon converter was used to generate the different files supported by different browsers. (<https://favicon.io/favicon-converter/>)
- Unsplash was used to find all other imagery, and Photoshop was used to convert the jpg files to webp files.
- Colormind was used to find a color palette with colors for text, headings, background colors and overlays to use on the site. (<http://colormind.io/bootstrap/#>)

- [EOF]
