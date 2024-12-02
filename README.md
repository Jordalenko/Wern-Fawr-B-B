[Logo]

[text "Explore what North Wales has to Offer from our lovely manor farm"]

[image from front page]


# Aim of the site

---

This site will introduce visitors to a beautiful 75 acre manor farm B&B in North Wales. The client has requested an update of their 25 year-old site to cater to modern user preferences. This site will display the attractive rental options at the farm, as well as the ameneties on and near the property, employing responsive front-end design and modern layout techniques. The site will simplify the booking process to flow from the hero image atop the home page or the individual rental listings.

Much of the existing client base come from repeat customers. But the site will better attract new business from the prospective clients who find the business through google or referals from, past customers, local businesses and the local community of retired people.

The client hve offered the following guidance for the new site.

1. A simple design that responds to any screen size dynamically.
2. A professional looking colour palette
3. Something that will appeal to the wealthy clientele as well as the weekenders.
4. Feature that they are a dog friendly business.
5. Streamline the booking process
6. Show both the amenities on the property as well as those nearby.

---

## UX:

The company is well established so their main goal is to update the site with modern website design to better meet the modern user's methods to view the site across many different screen sizes. However new customers typically fall within the following categories:

1. Typical client is from the West Midlands, Scotland and Wales
2. They may have friends in the local retirement community.
3. Weekender's with dog(s).
4. Visitors to the nearby Warren Spa

To help modernize the site we will

* Replace large sections that are primarily text walls with a balance of text and images.
* Make the site easy to navigate
* Reminds existing clients why they love both the farm and the area.

---

## Client Stories

"As a visitor to the site I want to see a visual representation of what I love about the property and area."

"As a visitor to the site I want to ensure I feel confident that I will be satisfied with my stay."

"As a visitor to the site I want to be able to easily find available dates to book."

"As a vistor The site needs to confirm my booking has been processed."

---

## Wireframe Mockups

During the design process I drew up the following wireframes using Balsamiq.

## Phone Size

![phone size wireframes](./assets/images/readme/phone_size.webp)

## Tablet Size

![tablet size wireframes](./assets/images/readme/Tablet_.webp)

## Desktop Size

![desktop size wireframes](./assets/images/readme/Desktop_.webp)

---

## Features

### About us

A series of images showing the amenities available both on the property and nearby as well as a button to take visitors to a booking page.

### Rental Properties

A series of clickable cards containing a carousel of images and static text with a basic description of the property. Divided into two categories (Cottages & Rooms). Clicking the cards takes visitors to a new page with larger images of the selected property and a book now button.

### Things To Do

A series of clickable cards containing a carousel of images and static text with a basic description of the amenities. Clicking the cards takes visitors to a new page with larger images of the selected amenity and a detailed description.

### Booking Form

If navigated from the front page the property selector atop the form is set to default. If navigated from the book now button for a specific Cottage or room that selection is displayed. When the date range of the visit is entered prices for the stay with cost details itemized for review. Once the booking is submitted a success page is triggered.

### Success Page

Once a booking is submitted it triggers a success message page. The success page thanks the visitor and offers a button to return to the home page.

### Contact Us

The footer contains contact details and social media links.

---

## Future Goals

* The client would like the booking page to display available dates and prices in the calendar below the date range selector.
* The client would like to be able to receive payment online.
* The client would like the site to update a database and notify them when certain conflicts arise.

---

## Technology Used

/* * HTML & CSS programming languages
* [Bootstrap](https://getbootstrap.com/) - For responsive sizing
* [Google Fonts](https://fonts.google.com/) - aaa
* [Font Awesome](https://fontawesome.com/) - Logos
* [jQuery](https://jquery.com/) - Javascript needed for navbar.
* [Popper.js](https://popper.js.org/) - Javascript needed for navbar.
* [VSCode](https://code.visualstudio.com/) - IDE for local developement
* [GIT](https://git-scm.com/) - Version Control
* [GitHub](https://github.com/) - to host the repositories for this project and the live website preview

*/
---

## Testing

/* Testing was initial carried out using Chromes developer tools to ensure that the site scaled correctly on each screen size.

I frequently used the below tools to help ensure no issues as i progressed through my build.

- [W3C Markup Validation](https://validator.w3.org/) to validate HTML.

- [W3C CSS validation](https://jigsaw.w3.org/css-validator/) to validate CSS

- [Lighthouse Chrome](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en) to audit best security practice and reduce loading times

- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) to help locate overflow issues

During my mid point review me and my mentor listed bugs that required fixing and features to add. On my mentors advice i produced a list of issues with expected time taken to fix on the following scale

* 1 - Will take a couple of minutes to fix or implement
* 3 - Will take approx 15 minutes to fix or implement
* 5 - Will take approx 1 hour to fix or implement
* 8 - Will take 4 - 8 hours (a working day) to fix or implement

My list is detailed below

<div style="text-align:center">
<img src="" style"max-height:300px;">
</div>

*/

### Issues and resolutions

/* During build the following issues were raised

-Collapse Icon Not Showing On Mobile Devices.

During my build the 'hamburger' icon failed to display when switching to mobile devices, this was resolved by adding the navbar-dark theme to the navbar class allowing me then to edit the perameters.

-Navbar not sticking to the top of the page as expected

This was resolved by removing the nav bar from the container which allowed this to function as expected.

- all text input on forms flagging as needing @ symbol

in the form parameters each was set to "type=email" instead of being "type=text"

- form allowing a blank form to be submitted 

Added required to the input tags to ensure core information has to be inputted.

- Nav menu scrolling to incorrect position

When using the nav menu items scrolling was taking the user to the content of the section instead of the header, this was resolved by moving the section ID to the title of the page instead of the content containers

- Nil links for social media icons opening new tab

As social media pages are not available at the moment clicking the icons opened a new browser with no address when click, this was resolved by removing "target=_blank" from the link code

- Fire & Acoustic Section text too cramped on tablets

Reduced padding from the card tiles to allow the text to have more room to display making this easier to read.

### Known Issues

Below are a list of problems that are known without resolution

- Smooth Scrolling not functioning on Safari or IE:E

This issue is unresolved as this is a browser issue not a site issue.

- Title font contast on white backgrounds doesn't meet readability guidelines

The issue has been raised with the client and a mid ground has been established as the client doesn't want to stray too far away from the logo colour.

*/
---

## Deployment

/* To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/D0nni387/Luxury-Door-Solutions), the following steps were taken: 

1. From the menu items near the top of the page, select **Settings**.
2. Scroll down to the **GitHub Pages** section.
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
5. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 

### How to run this project locally

To clone this project from GitHub:

1. Under the repository name, click "Clone or download".
2. In the Clone with HTTPs section, copy the clone URL for the repository. 
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/D0nni387/Luxury-Door-Solutions.git
```
6. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

*/ 

---

## Credits

### Content

/* All images provided by the client from their existing website & test shots taken on site.

The initial paragraph of text was also reused from the existing site, all other text has been rewritten with the client. 

### Acknowledgements

Last of all i would like to thank my fellow students */

A hero gallery header at the top with text in the lower third of a drone video of the whole property. The video flows into a carousel of images of the amenities both on the property and nearby towns. There is a book now button that links to a calendar page detailing all available rental dates. The main content begins with a features section below the hero gallery with clickable cards containing a picture and descriptive text for each rental space on the property. These links scroll down through images under text for each of the rental spaces to a table of availability and pricing for each rental space. There is an interactive booking calendar that links to the booking form at the bottom of each card. The booking form links to a success page which triggers a confirmation email. The success page has a Thank You! message and a button linking back to the home page. Following the features section is a testimonials section that completes the main content of the home page. Descriptions of the experiences of previous guests are detailed in three cards with links to their google reviews and pics from their stay or their google profile pic. Below the main content in the footer are the social media links and contact details.
