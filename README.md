# MS1 Liz O'Neill - Psychotherapy

The site is aimed at offering psycotherapy services to clients and also provide information for family members/friends looking to get help for loved ones.
There is also some scope to collaborate with similar minded services who's brand is inline with Liz's and also to work with fellow psychotherapists. 
Due to the nature of the topic it is intended to provide information with a relaxed approach, for this reason there will not be a large amount of call to 
action points or direct sales pitches as it's important the client believes Liz is a good match for their needs.

Walking therapy is a fairly new approach to therapy service and encourages a different approach and feeling towards the help people may need, the style of the 
site should reflect this and feel calming and organic. Naturally walking is not for everyone so traditional therapy style services will be offered along with 
online services given the impact of COVID.

## UX

### User stories

* As a potential client, I want to find the information regarding how the therapy works and if it and Liz is a good match for what I'm looking for, if so it then needs 
to be easy to get in contact with Liz.
* As a friend or family member of someone who needs help, I want to see if Liz's services would be a good match for the individual I'm concerned about, I would then want to 
be able to put them intouch with Liz, or share some of her social media with my friend/family member to encourage them to seek help.
* As a potential collaborator, I want to see the style and work done by Liz to see if our brands outlook match one another, if so I need to be able to make contact 
with Liz to start the discussion.
* As a fellow psyhcotherapist, I will be looking to learn how to approach walking therapy as a new style of service that is very uncommon at the moment, I would like to contact 
Liz to either learn from her or to work with her in offering services to a broader geographical range of clients.

### Strategy

My goal in the design is to make a very clean, relaxed site conveying all the information required by all users. There needs to be a simple contact form and also contact details.

### Scope

For clients there needs to be an explanation of the services on offer along with background information on who Liz is. Social media links is a modern approach to offering psycotherapy 
services that is being promoted as a way to make it seam as it should be more socially acceptable and easier to approach the topic.

### Structure

With there being a large amount of information and text inparticularly it's important to break the site into seperate pages allowing clients to jump to what they want to know 
without the need to over scroll. The site will be broken down to Home Page, Types of therapy on offer explained, What to expect/who is Liz, Collaborations and social feeds, contact
page and how to start the process.

### Skeleton

* There are links to the V1 skeletons on Github.
* V2 update removed some image's as there were too many and ammended layouts as needed. Also removed 1 page originally planned.




### Surface

Liz's branding is already working with a color pallet which needs to continue through the site. 

![Kelvington color palate](https://github.com/David-A-Ray/MS1-LizO-Neill-Psychotherapy/blob/master/assets/images/kelvington.jpg "Kelvington color palate")

## Technologies

* HTML5
* CSS3
* Bootstrap V4.5.2
* jquery

## Features

* Links in footer on all pages to "Crisis" help websites and phone numbers for anyone in need of imediate help/suicide prevention.
* Collaboration page uses iframe to embed playable youtube video files linked to social partners.
* Talk page has made use of a submission form for clients to make contact.
* Talk page has made use of a submission form for fellow psychotherapists to make contact.

### Features left to implement

* As Liz builds more social media content the main banner images will be replaced with scrolling images of her content.
* Once more collaborations are established the imbedded youtube content will be expanded.
* A google map range will be added to show where services are available.

## Testing

### Header
* All navbar links work on all pages.
* Navbar active highlight is visible on correct pages.
* On mobile screen size additional page title displays underneith Navbar to help guide users.
* All social icons open websites in new tabs using 'target="_blank"'
* Social icons on "logo-header-bar" aren't visually pleasing on smaller screen sizes as the group with the logo too tightly, so using media queries 
they are now hidden on small screen sizes and displayed on the right handside of the Navbar on the row below.

### footer
* "Crissis" section title link open websites in new tabs using 'target="_blank"'
* BACP logo link opens website in new tabs using 'target="_blank"'
* Bug with BACP logo not showing on mobile screen sizes still to be fixed.

### index.html, types.html, what.html
* All information consice and well structures to assist user stories.
* Information layout responsive and well displayed to suit all screen sizes.
* Some challenges with image display order with two images stacked on small screen sizes so added in media queries to hide image on small screens
and display additional image on large screens.

### collabs.html
* Embedded Youtube files responsive and adjusting well on full range of screen sizes.

### talk.html
* Forms have limited functionality for the time being.
* 
* 
* 

### General Testing
* Site has been tested on multiple service providers (chrome, safari, firefox and internet Explorer).
* Site tested on multiple devices (Large screen desktop, laptop, ipad pro, iphone 6 & XR). Other than the BACP logo in footer display issue
all elements are displayed well.
* [Autoprefixer](https://autoprefixer.github.io/ "Autoprefixer's Homepage") used to ensure all CSS displays on all internet explorers.
* HTML tested using [WC3](https://validator.w3.org/ "WC3's Homepage") and all tests passed with no errors.
* CSS tested using [WC3](https://jigsaw.w3.org/css-validator/ "WC3's Homepage")
* Reponsiveness testing done on [Am I Responsive](http://ami.responsivedesign.is/?url=https://david-a-ray.github.io/MS1-LizO-Neill-Psychotherapy/ "Am I Responsive's Homepage"). 
Click link to view website being displayed.

## Deployment
The site has been deployed using GitHub pages from the masterbranch on GitHub. It is kept upto date with the final GitHub repository automatically
with any Git Commits to the master branch.

You can clone this repository directly into your editor to run it locally by pasting
`git clone` `https://github.com/David-A-Ray/MS1-LizO-Neill-Psychotherapy` into your terminal.

## Credits

### content
All content on Home, Types of therapy, What to expect & FAQ's and Let's talk about it has been written by Liz O'Neill.

Youtube embedded video description has taken some content from the video owners sites to be included in description although it has been altered.

### media
* All images have been taken from [Unsplash](https://unsplash.com/ "Unsplash's Homepage").
* Embedded video files on Collaborations page are from [YouTube](https://youtube.com/ "YouTube's Homepage").
* BACP logo taken from [Step-by-step](https://www.stepbystepcounselling.co.uk/ "Step-by-step's Homepage") and altered to remove registered members number.

* FONT AWESOME AND GOOGLE FONTS NEED ACKNOWLEDGMENT? 

### Acknowledgments
* JQuery used for NavBar dropdown menu taken from Code Institutes Whiskey Drop learning module.
* Social media icons code taken from Code Institutes Resume learning module.
* Box shading on images code taken from Material Design Box Shadows by Samual Thornton.
* Code assistance for images to use `object-fit: cover/contain` from JimLynx_lead on slack who pointed me in the right direction.
* Code assistance with `mx-auto` from Mr_Bim_alumni in the slack thursday evening study group.
* Favicon image was created using [Favicon.io](https://favicon.io/ "Favicon's Homepage"), there code was used in header to load image across all service providers.
* [TinyPNG](https://tinypng.com/ "TinyPNG's Homepage") used to compress all image files except for ldw.jpg which was too large. 