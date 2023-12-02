# ELION GYM
This is a simple website designed with responsive functionality as a central priority. The goal is to give visitors a good browsing experience on a variety of devices and help the owner to get new customers.

![Project-image](documentation/pp1-responsive.png)

[View the Elion Gym website here](https://emilionr.github.io/portfolio-project-1/)
For educational purposes only, NOT a real gym. I made this as my first portfolio project for Code Institute.

## Contents

* [User Experience (UX)](#User-Experience-(UX))
  * [Initial Discussion](#Initial-Discussion)
  * [User Stories](#User-Stories)

* [Design](#Design)
  * [Colour Scheme](#Colour-Scheme)
  * [Typography](#Typography)
  * [Images](#Images)
  * [Wireframe](#Wireframes)
  * [Features](#Features)
  * [Accessibility](#Accessibility)

* [Technologies Used](#Technologies-Used)
  * [Languages Used](#Languages-Used)
  * [Frameworks, Libraries & Programs Used](#Frameworks,-Libraries-&-Programs-Used)

* [Deployment & Local Development](#Deployment-&-Local-Development)
  * [Deployment](#Deployment)
  * [Local Development](#Local-Development)

* [Testing](#Testing)
  * [W3C Validator](#W3C-Validator)
  * [Solved Bugs](#Solved-Bugs)
  * [Known Bugs](#Known-Bugs)
  * [Testing User Stories](#Testing-User-Stories)
  * [Lighthouse](#Lighthouse)
    * [Index Page](#Index-Page)
    * [Join Page](#Join-Page)
    * [Features Page](#Features-Page)
    * [Confirmation Page](#Confirmation-Page)
  * [Full Testing](#Full-Testing)
  
* [Credits](#Credits)
  * [Code Used](#Code-Used)
  * [Content](#Content)
  * [Media](#Media)
  * [Acknowledgments](#Acknowledgments)

## User Experience (UX)

### Initial Discussion

Elion Gym is a medium-size gym in a fairly big city. Due to the stiff competition with other gyms, the owner wants to communicate better what sets his gym apart and draw more new members to the gym.

__Key information for the site__

*When the gym is open.
*Membership pricing.
*What equipment exists at the gym.
*Events taking place at the gym.
*How to become a member.

### User stories

__Client goals__

*Make it easy for visitors to see what the gym can offer.
*Make it easy for potential customers to sign up for membership.
*Provide all relevant contact information and social media channels.
*Reach the audience regardless of device used to view the site.

__First-time visitor goals__

*I want to get all the info about this gym, its equipment and open hours.
*I want to navigate the site with ease on any device.
*I want to find any relevant social media channels.
*I want to sign up for membership if I like the gym.

__Returning visitor goals__

*I want to know what's happening at the gym.
*I want an easy way to contact the gym.

## Design

### Color palette

![Color Palette](documentation/color-palette.png)

For this site, I wanted a strong, striking impression and found inspiration from the packaging of popular workout supplements. I wanted mostly grayscale with a single sharp red or orange color. After some initial testing, I chose orange due to better contrast.

### Typography

I used Google Fonts for these fonts:

Kdam Thmor Pro for all headings and some emphasized text. It's a bold sans-serif font.

### Images

I used a combination of royalty-free pictures from Unsplash and Pexels, along with one AI-generated portrait.
Credits for photos are found in the Credits section.

### Wireframe

I made wireframes for mobile and desktop versions of each page. I had a firm plan and stayed mostly true to the wireframe. However, I had to make some slight changes to the positioning of banner contents, as well as the list containers on the features page.

[Wireframe](documentation/pp1-wireframe.png)

### Features

The site has four main pages accessible via the navigation menu, plus one confirmation page for signing up. The latter is only accessible by filling out the sign-up form and can not be reached via the navigation menu.

* All pages on the website have:
  * A header with a navigation menu, containing links to each of the four pages. The current page lights up in the menu. Navigation is always visible in a horizontal strip on bigger screens. On smaller screens, it turns into a dropdown menu which is hidden until opened by a traditional burger toggle. This is meant to avoid clutter and make navigation intuitive regardless of screen size.
  * A footer with another home link, a set of contact details, links to social media pages, and copyright information. The links are inside icons to reduce clutter and to let the viewer know instantly what they are.
* Home Page:
  * Four panels of information such as business hours and selling points, giving the brief and snappy version of what sets the gym apart.
  * A message from the owner, to provide the viewer a face and a feel for the vibe of the gym.
* Join Page:
  * Information about the costs of joining the gym and what's included in the price.
  * A form for signing a new membership.
  * A panel with the rules of the gym.
* Features Page:
  * Three panels listing the diverse excercise equipment found inside the gym.
  * A list of products sold at the gym and their prices.
* Events Page:
  * Two panels about upcoming events.
  * An information panel about scheduled events.
* Confirmation Page:
  * A message thanking the user for signing up and informing them about the next steps to take.
  * A button for returning to the home page.
* Future Implementations:
  * Install a carousel for user testimonials/reviews.
  * A page about the staff
  * A blog page for news and content marketing purposes.

### Accessibility

I designed this website with accessibility in mind, using the following procedures:

Using semantic HTML.
Using descriptive alt attributes on images.
Giving screen readers information about sections, buttons, and link icons.
Using aria-current and aria-label to help screen readers know where the user is.
Ensuring a sufficient colour contrast for viewers with visual impairments such as color-blindness.

## Technologies Used

### Languages Used

This website was made with HTML and CSS, with no additional libraries.

### Frameworks, Libraries, & Programs used

VSCode - Used for all the coding.

Git - For version control.

GitHub - To store files and provide a live site.

Google Fonts - For stylish headings.

Font Awesome - For icons used throughout the site.

Google Dev Tools - For debugging and trying out design improvements on the fly.

GNU Image Manipulation Program - Cropping and scaling images for faster load times.

Cloud Convert - For compressing images to webp for even faster page loading.

Favicon.io - I used this to make the page favicon.

Am I Responsive - For testing how the site looks on different devices.

WAVE Evaluation Tool - To check accessibility.

Web Disability Simulator - To check accessibility.

Shields.io - For the badges in the ReadMe.

## Deployment & Local Development

### Deployment

The page was deployed using GitHub Pages.

### Local Development

## Testing

I frequently tested all pages throughout the development process. Most of this testing was done with the dev tools in my browser. Throughout development, I would resize the viewports and try to abuse the pages to see if something would break the layout and whether the site was responsive enough.

Mentor input:
* s
* s

Peer review input:
* s
* s

### W3C Validator

Index
Join
Features
Events
Thanks
Style.css

### Solved Bugs

1. An interaction between the header and main section would cause the body to either overflow out the bottom past the footer, or cut the footer in half on mobile devices. This was fixed by adjusting the height of the main section and the overflow of the header.
2. Header images would cut out or cause horizontal overflows making the whole page scroll to the side with nothing but empty space outside the main design. This happened because I used the overflow settings on the header instead of the image container inside the header. Designing the image slider with pure CSS requires some strange workarounds, as it is usually done with Javascript.
3. Text lines would break in bad places or extend outside panels when sizing down between tablet and phone screen sizes. I solved this by adjusting the padding and flex properties of the elements containing the affected text.
4. Footer contents would scramble and end up in the wrong order on small screen sizes. I solved this by arranging contents in separate dividers for rows and creating a reusable line-break element for flex layouts.
5. Header contents would move out of position and fight for space at certain screen sizes. This was solved when I changed the margins and paddings from percentages to specific numbers.

### Known Bugs

There are no known bugs as of now.

### Testing User Stories

### Lighthouse

### Full Testing

## Credits



### Code Used

While I did not directly copy any code, I took a lot of inspiration from [Theodore Coding's image slider video](https://www.youtube.com/watch?v=Ll5JIjdwQEM) when making my header image slides.

### Content

All content is original.

### Media

**Images used**

"empty-gym" [Photo by Jelmer Assink](https://unsplash.com/@jelmerassink?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Jelmer Assink</a> on <a href="https://unsplash.com/photos/barbell-on-rack-gzeTjGu3b_k?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
"weight-rack" [Photo by Ivan Samkov](https://www.pexels.com/sv-se/foto/gym-utrustning-hantlar-hantel-4162451/)
"ropes" [Photo by Chase Kinney](https://unsplash.com/@chasekinney?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Chase Kinney</a> on <a href="https://unsplash.com/photos/person-holding-black-exercise-rope-FMQBLyhD2HU?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
"group-training" [Photo by Victor Freitas](https://unsplash.com/@victorfreitas?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Victor Freitas</a> on <a href="https://unsplash.com/photos/person-about-to-lift-the-weight-plate-Btl6ZNdIfdQ?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
"lifting-comp" [Photo by](https://unsplash.com/@victorfreitas?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Victor Freitas</a> on <a href="https://unsplash.com/photos/a-man-lifting-a-barbell-in-a-gym-71T4vSUphQI?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
"dumbbells" [Photo by Samuel Girven](https://unsplash.com/@samuelgirven?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Samuel Girven</a> on <a href="https://unsplash.com/photos/dumbbells-on-floor-VJ2s0c20qCo?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
"owner" Image generated with [Picsart](https://picsart.com/)

### Acknowledgements

The Code Institute team.
