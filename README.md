# Together Cycling

Together Cycling is an online platform dedicated to the cycling community, created by and for passionate cyclists. The primary mission is to enhance the cycling experience by organizing and enabling group cycling training rides, and  empower cyclists to connect and embark on exhilarating group training sessions.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/e2f03519-e6b3-4c37-ada3-2ef55049a212)

## Table of contents

- [Together Cycling](#together-cycling)
  - [Table of contents](#table-of-contents)
  - [Purpose and target audience](#purpose-and-target-audience)
    - [User stories](#user-stories)
  - [Design](#design)
    - [Color palette](#color-palette)
    - [Typography](#typography)
    - [Wireframes](#wireframes)
    - [Imagery](#imagery)
    - [Icons](#icons)
  - [Pages and Features](#pages-and-features)
    - [General Features](#general-features)
    - [Pages](#pages)
      - [Home page](#home-page)
      - [Our Rides page](#our-rides-page)
      - [Ride with us page](#ride-with-us-page)
  - [Bug fixes](#bug-fixes)
  - [Technologies](#technologies)
    - [HTML and CSS](#html-and-css)
    - [Imagery](#imagery-1)
    - [Content](#content)
  - [Accessibility](#accessibility)
  - [Deployment](#deployment)
  - [Testing and Validation](#testing-and-validation)
    - [Testing](#testing)
    - [Validation](#validation)
      - [Home page](#home-page-1)
      - [Rides page](#rides-page)
      - [Ride with us page](#ride-with-us-page-1)
  - [Credits](#credits)
    - [Acknowledgement](#acknowledgement)
    - [Code used](#code-used)
    - [Content](#content-1)
    - [Media](#media)

## Purpose and target audience

The Together Cycling website is an online space designed to unite cyclists in the Stockholm (Sweden) area, offering a resource for peloton rides. This site aims to serve the specific needs of individual cyclists who may not be affiliated with any particular cycling club.

The primary objective is to provide regularly updated group training opportunities/peloton rides in the Stockholm area with different starting points and focus. It is a centralized location where you can discover upcoming rides with information on date, time and rides specifics. In addition to this, the aim is also to provide a source of inspiration with a collection of curated maps offering rides suggestions for individual solo rides.

### User stories

- **As the organizer**, I want to establish a cycling community where riders can connect, share their cycling experiences and enjoy group rides together.

- **As an experienced cyclist**, I need easily accessible information on upcoming ton rides in my area, which will enable me to join rides that suit my training goals and skill level.

- **As an experienced cyclist**, I seek an online source that provides a variety of inspiring routes and rides that help me stay motivated and continously challenge myself.

- **As a cyclist new to peloton riding**, I'm eager to learn the ropes of riding in a group and need resources and guidance that help me ride safely and confidently in a peloton.

- **As a prospective member considering joining the group**, I want to learn more about the individuals behind this cycling community. Understanding their vision will help me evaluate if it aligns with my interests.

## Design

### Color palette

[Colormind](http://colormind.io/bootstrap/) have been used to find matching colors.
![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/b3ee9966-1a09-433d-b40c-bd0c5fdbed7b)

- Header and Footer color : #2C4658 (dark greyish blue)
- Text : #F4F4F2 (white)
- Headings :  #5AC4BE (greyish mint) or #F4F4F2 (white)
- Call to action : #2C4658 (dark greyish blue)
- Background colors : #312539 (dark lilac), #B2495E (greyish apricot)

### Typography

The below Google fonts have been used for this site.

- Logo: Bricolage Grotesque, Extra Bold 800

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/bb24a08d-3ac5-4492-922a-96628c16b134)

- Headings & Body: Nunito, Regular 400

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/24116196-3259-4cb4-9f0a-96012a28d324)

- Signature: Give You Glory, Regular 400

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/8064aee0-b7c1-4536-bf34-8b5d69aaf103)

### Wireframes

Wireframes was created using draw.io.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/f35e8bd0-8a2b-44d2-a201-d68fea013542)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/ee639e49-740c-417c-b1b0-549f9c1c3c1d)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/cf233feb-5243-4cbc-9192-5d9ea4da8cff)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/49ec47a5-89cd-4df2-a3a3-83a5c95243d8)

### Imagery

Each of the three pages have a different background image, these were downloaded from [Unsplash](https://unsplash.com) a free stock image site with high-quality photos. For a more dramatic and consequential look a color gradient overlay with #312539 (dark lilac) to #BA567B (greyish pink) has been applied to all. The two colors was picked from the site’s color scheme.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/6dcbc6f1-9a3b-4707-97be-c2ea04e351f2)

### Icons

Icons used come from Font Awesome

- Strava
- Instagram
- YouTube
- Contact/Mail to

Fav icon used for the tab image comes from [Rawpixel](https://www.rawpixel.com/) and was generated through [Favicon](https://favicon.io/) to get all the versions supported by the different browsers.

## Pages and Features

### General Features

- *Together Cycling logo* links back to the home page.

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

#### Home page

The home page (index page), presents the purpose of the page - Coming together on Peloton rides in the Stockholm area. The user can read about the people behind the site and get to know them a bit more. They can also click the links to visit the personal Strava profiles of the two site owners.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/9ed99915-354d-44da-a726-6625be427b6e)
![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/69aadfd7-95ce-4bca-96e5-68fd3d040212)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/abab1114-4aad-4cf0-a090-2b776ad5482b)

#### Our Rides page

The Our Rides page provides information on scheduled rides information on when and where the group rides will take place, what type of ride it is and some information on the focus of the ride so that the user can assess wheather that specific ride is for them or not. The page also provides map to show the route if the user is just out to find inspiration on new rides. The maps are interactive and can be viewed in a larger format by clicking the top right icon in the black bar on top of the map, the maps can also be shared with others from the black top bar.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/3fe7b2f0-0d7e-4862-8ca7-4a5661e69c2b)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/8e92d4b2-007f-4183-b52c-9bf4fc079a71)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/3d4faaa7-1f25-4607-be60-398accef331c)

#### Ride with us page

The Ride with us page contains a form to sign-up for a newsletter with information on scheduled rides and other updates. Together with the sign-up form there is information on the intent with the newsletter for the user to know what they are signing up for (or not). The sign-up form have three required fields to get the basic information about the user, and requires you to fill in an email address in order to submit the form. In the future this could potentially become a members page with a login to add personal information that can be used to present members the same way as the site owners (home page) and connect with eachother.

*For UX reasons* the order of the content will change depending on if the page is viewed using a mobile or a tablet/laptop. On mobiles the sign-up form is prioritized as the most important content while at larger screens where you can overview all content at the same time, the user is presented with the intent information first.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/dc70114f-342b-426d-897a-d6310ccffd4b)
![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/bdbda4f9-5b07-4fa5-a880-3e38398768a5)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/fcf0336e-9c2d-4f0c-8a6d-e0131df4c67e)

## Bug fixes

The content on the Our rides page did not flow as intended, but this was fixed by using the flexbox feature.To be able to adjust the misalignment of the content of the different rides, and to be able to control the responsivity I changed the top container (containing all the rides in one box) to have the display property of flexbox. This solved the issue as I could set the flex-direction to row and let the content wrap to fit the screen size.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/ce2a141f-8f80-4e81-a715-c7d286339b5e)

## Technologies

### HTML and CSS

- GitHub for storing repository
- Codeanywhere for code editing

### Imagery

- Photoshop to convert images to webP files, and resizing.

### Content

- [Font Awesome](https://fontawesome.com/start): to generate icons used on the page.
- [Favicon generator](https://favicon.io/): to generate the fav icon on the tab next to the title.
- [Google Fonts](https://fonts.google.com/): to find the fonts used on the page and to get the code to embed on the page.
- [Google maps/My maps](https://www.google.com/maps/d/): to generate the rides shared on the rides page.

## Accessibility

In order to ensure accessibility for all users, irrespective of their internet connection speed or potential disabilities, the below things have been implemented in the code and design of the web page.

- Structural Elements: I've employed the use of semantic HTML elements such as *header*, *main*, *footer*, and *section* to help organize the content and improve the overall accessibility of the page.

- Alternative Text and ARIA Labels: Throughout the website, I've incorporated descriptive alt-text for images and used ARIA labels to facilitate screen reading, to make the site available for users with visual impairments so they can understand the content and functionality of images and other interactive elements.

Image Optimization: To enhance site performance and accommodate users on slow internet connections, I've converted images to the WebP format, which offers better compression without sacrificing quality. Additionally, I've resized images to their smallest possible dimensions while maintaining their visual integrity. This improves page load times without compromising content quality.

## Deployment

The Together Cycling site was deployed to [GitHub](https://github.com) pages, following these steps:

1. Go to the [Together-Cycling repository](https://github.com/CharlottaG/Together-Cycling)
2. Go to the *Settings* tab (top left in the menu)
3. Go to the left-hand section,under *Code and automation* click **Pages**.
4. Go to *Source* under *Build and deployment* and use the dropdown menu to choose **Deploy from a branch**
5. Under *Branch* use the dropdown menu to select **main** and set the *folder* to **root**.

The live site can be viewed at: [https://charlottag.github.io/Together-Cycling/](https://charlottag.github.io/Together-Cycling)

## Testing and Validation

### Testing

- Testing of the site functionalities was performed on:
  - Laptop: Dell 5430, Windows 10, running Chrome, Edge or Firefox (1920x1080 monitor)
  - iPhone 13, running Safari (6.1" diagonal)
  - Samsung Galaxy S23, Android (6.1" diagonal)
  - iPad 9, running Safari (10.2" diagonal)

- Based on statistics from [Top Browsers Market Share - Most Popular Browsers in July 2023 | Similarweb](https://www.similarweb.com/browsers/) all testing was done using:
	1. Google Chrome
	2. Apple Safari
	3. Microsoft Edge
	4. Mozilla Firefox
	5. Android

- Screen reading was tested using built-in browser functionality in Chrome.

| Feature        | Expected Outcome | Chrome | Edge | Firefox | Safari | Android |
---------------  | ---------------- | ------ | ---- | ------- | ------ | ------- |
| **Navigation bar** |
| Logo link	| Take user to index page | Pass | Pass | Pass | Pass | Pass |
| Home link	| Take user to index page | Pass | Pass | Pass | Pass| Pass |
| Our Rides link | Take user to the Our Rides page | Pass | Pass | Pass | Pass| Pass |
| Ride with us link | Take user to the Ride with us page | Pass | Pass | Pass | Pass| Pass |
| Responsiveness | For screens up to 768px the navigation should be presented in an hamburger menu, while the navigation links should be visible in the header for screens larger than 768px | Pass | Pass | Pass | Pass| Pass |
| **Footer bar** |
| Strava icon | Take user to strava.com | Pass | Pass | Pass | Pass| Pass |
| YouTube icon | Take user to youtube.com | Pass | Pass | Pass | Pass| Pass |
| Instragram icon | Take user to instagram.com | Pass | Pass | Pass | Pass| Pass |
| Contact icon | Open user's email client | Pass | Pass | Pass | Pass| Pass |
| Responsiveness | For screens up to 768px only the social media icons should be visible and the should be centered, while for screens larger than 768px the footer should show copyright information to the left and social media icons to the right| Pass | Pass | Pass | Pass| Pass |
| **Home page** |
| Strava link Jens | Take user to strava.com | Pass | Pass | Pass | Pass| Pass |
| Strava link Joakim | Take user to strava.com | Pass | Pass | Pass | Pass| Pass |
| Image alt text |
| Fallback color | Should show a dark lilac background color if the background image with gradient overlay does not load | Pass | Pass | Pass | Pass|
| Responsiveness |  The page has three content boxes where the second and the third will change depending on the screen size. For screens smaller than 768px the headshot images will be places above the text in the same box and the image size will be 100px, whereas for larger screens the images will be 200px and the text will appear on the right side of the image in the same box. | Pass | Pass | Pass | Pass| Pass |
| **Our Rides page** |
| Google maps | The maps should be interactive and scrollable | Pass | Pass | Pass | Pass| Pass |
| Fallback color | Should show a dark lilac background color if the background image with gradient overlay does not load | Pass | Pass | Pass | Pass | Pass |
| Responsiveness | When viewed on mobile all content should be displayed as one column, whereas it will be two columns, one for the maps and one for the text, on screens larger 550px and for screens larger than that the maps will flow and fit the screen, e.i. as soon as there's room for one more map it will be on the top line. This is to allow for more maps to be added. | Pass | Pass | Pass | Pass| Pass |
| **Ride with us page** |
| Fallback color | Should show a dark lilac background color if the background image with gradient overlay does not load | Pass | Pass | Pass | Pass |Pass |
| Responsiveness | For screens larger than 768px, the signup form will appear to right of the page while the information about the intentions for the newsletter sign-up will appear to the left. For smaller screen the sign-up form will be the first piece of content as this is the most important content on the page, and when you cannot see all content at the same time the focus will be on the purpose of the page, to sign-up.	| Pass | Pass | Pass | Pass |Pass |
| **Sign-up form** |
| First Name | The user should be prompted to enter text | Pass | Pass | Pass | Pass |Pass |
| Last Name	| The user should be prompted to enter text | Pass | Pass | Pass | Pass | Pass |
| Email Address	| The user should be prompted to enter a valid email address | Pass | Pass | Pass | Pass | Pass |
| GDPR checkbox	| User should be prompted to click this| Pass | Pass | Pass | Pass | Pass |
| Radio buttons	| User should be prompted to select one of these | Pass | Pass | Pass | Pass | Pass |
| Submit button	| Should return the collected info from the CI formdump page | Pass | Pass | Pass | Pass | Pass |

### Validation

#### Home page

There was an incorrect use of an aria-label attribute with a link, when that was corrected and two open tags were close the paged passed the validation.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/b21f8bd5-abc9-4a1e-99cb-297b990b14cc)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/880211ac-78bc-44b3-a4d0-14cd515f2517)

<https://wave.webaim.org/report#/https://charlottag.github.io/Together-Cycling/>

#### Rides page

Had issues with the width and height attributes for the iframes, that were initially set to 100%. This had to be change to a numeric value and that caused some errors on the display of the elements. A new media query for smaller screens had to be added to accommodate the display on screens less than 380px.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/7b1dcd3c-4f8c-4e1e-83eb-52e8b014ff8d)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/e8d733f0-c101-4b8d-b7f4-c52f2618768a)

#### Ride with us page

No issues.

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/810660a7-7f30-474a-afd1-77319c147a91)

![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/faef8e2f-c866-48e3-adc0-50b1f60e63ae)

## Credits

### Acknowledgement

I'd like to thank *Luke Buchanan, my mentor at Code Institute*, for invaluable guidance and support as well as insightful constructive feedback throughout the duration of the this project.

### Code used

- Navbar: Inspired by the code used from the CodeInstitute learning project - Love Running project
  
  ![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/34eb255b-66b6-4ead-aa3b-86efd66f89c8)

- Autocomplete feature on the form was inspired by [Mozilla org](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete#values)
  
![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/8ce957af-a320-4990-882f-440875066cb7)

- Using target-blank for the mailto-link to enable web based email clients to open in new window and thus avoid surprises, and using the *noreferrer* for privacy reasons was inspired by [CSS Tricks](https://css-tricks.com/all-about-mailto-links/)
- Gradient color overlay code used from [DEV Community](https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio):
  
![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/8606a4eb-5fed-4d6e-91cc-ba4987ef94be)

- Google maps - used the embed code provided by Google. Example:
  
![image](https://github.com/CharlottaG/Together-Cycling/assets/138576943/a4c72a63-7d30-4e48-a441-f5c9cd27683a)

### Content

The web site copy is my own, but I used [openai](https://openai.com) to add some more flavor and improve it, enhancing its overall quality and engagement.

### Media

- [Rawpixel](https://www.rawpixel.com) was used to find a fav-icon for the tab.
- [Favicon converter](https://favicon.io/favicon-converter/) was used to generate the different files supported by different browsers.
- [Unsplash](https://unsplash.com/)was used to find all other imagery, and Photoshop was used to convert the jpg files to webp files.
- [Colormind](http://colormind.io/bootstrap>) was used to find a color palette with colors for text, headings, background colors and overlays to use on the site.

[EOF]
