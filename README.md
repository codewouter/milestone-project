# README.md

## The 1975 Website
My project focuses on the popular rock band, The 1975. This website is for fans of theirs who like to keep up with their tour dates, latest music and easy access to their social medias. The website also caters to companies and venues who would like to see where they are touring and possibly book them. 

My project has its opening page where it briefly describes the bands history and what they are all about, while also showing the members of the band. This is crucial as visually seeing who you will be engaging with is very important and brings it to a personal level. The second menu item brings fans and potential bookers to the touring timeline of the 1975, which enables them to see when and where the band will be playing for the foreseeable future. I have also enabled a feature to allow fans to be directed to the ticket selling websites for each arena so they can purchase tickets to see the band live. The following menu item allows for individuals to listen to some of the bands popular hits and see photos of them live in action. The last menu item allows for companies and venues to contact the band for bookings and shows. 

## UX
This website is for individuals interested in, are fans of and who want to know more about the 1975. This website allows these individuals to see what dates and where the band is touring, as well as links to buy tickets to these events. The website also provides popular songs, photos of the band, direct links to their verified social media links and a contact page. The contact page is more for companies and venues who would like to book The 1975 to play. The website caters to these individuals as well because it allows the companies and venues to see who is in the band, information about them and music for them to sample.  

- As a new fan I want to see photos of the band members and see who plays what position to know more about them 
- As a new fan I want to read about the band so that I am knowledgeable about them
- As a possible employer I want to read about the band and see who it is composed of so that I know more about them when I decide to book them 
- As a fan I want to know when they are touring and where they will be so that I can book tickets 
- As a possible employer I would like to see when they are touring and where they will be so that I can book them to play at my venue
- As a new fan I want to listen to their popular songs and watch videos on them to learn more about them and their style
- As a possible employer I want to listen to the genre of music they produce so that I can potentially book them for my venue
- As a fan I want to know what their social media pages are so that I can follow their live updates and tag them in photos I take when I attend their concerts

### Mockups
- Please find paper and pen mockup for the original first design [Here](Mockups/first-design.pdf)
- Please find paper and pen mock up for the second and final design (explained in acknowledgements) [Here](Mockups/final-design.pdf)

## Features

### Existing Features

#### index.html
- Eye catching front page
    - Music video and photos of the band members for users to view in case they are not familiar with the band or type of music
- Information on the band
    - Information about the band readily accessible
- Photos of band members
    - Allows users to see who they are listening to and connect more deeply with the band
- A music video
    - Allows users to listen to the music of the band by pressing play

#### tourdates.html
- Organised tour dates
    - Tour dates orgainsed on a timeline for pleasant user experience so that fans and potential bookers can see when and where the band is playing
- Ticket buying
    - A section to buy tickets next to the tour dates of the band so that people can go straight from the website and not look it up separately

#### gallery.html
- Audio song clips
    - Allows users to listen to popular songs of the band
- Photo gallery
    - Allows users to view photos of the band live in action on stage

#### contact.html
- Contact form
    - Contact form for companies and venues to get in touch with the band for bookings
    - Required input fields

### Features to be Implemented in the Future
- Javascript
    - To link up the contact form for it to work correctly once I have learnt it
    - To have an alert that says "thank you for submitting your form" without over writing the 'required fields' popup
    - To create a lightbox for the photos on the gallery.html page

### Features Left to Implement
- None

## Tech Used
- HTML
    - This was used to make the base language to create the website
- CSS
    - milestone-project/assets/css/styles.css
        - This was used to style the elements of the HTML code
- Bootstrap 
    - https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css   
        - This was used to help style the website and with the grid layout of it
- Font Awesome
    - https://fonts.googleapis.com/css?family=Roboto:400,400i,700,700i
    - https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css
        - This was used to create a universal font for the website
- Hover
    - https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css
        - This was used to have the hover styles run smoothly
- Box Shadow Generator
    - A [box shadow generator](https://cssmatic.com/box-shadow) to create the shadowing behind the images on gallery.html
- Validators
    - An HTML [validator](https://validator.w3.org/) was used to check the code
    - A CSS [checker](http://csslint.net/) was used to check the stylings
- Formatter 
    - An HTML [formatter](https://www.freeformatter.com/html-formatter.html) was used

## Testing

#### Overall
- I tested out some designs in a workspace that I cloned from this milestone project and ended up copying and pasting some of that code over for some aspects of my submitted project. [This repository can be found here](https://github.com/ananyasitlani/milestone-project-cloned)

#### index.html
- Video
    - Go to Home page
    - Click play on video and wait for it to load
    - Repeat this on different browser

#### tourdates.html
- Buying tickets
    - Go to Tour Dates page
    - Click through each ticket buying option
    - Make sure they open in another page due to the target="_blank"
    - Make sure each link correlates to the correct website
    - Get friend to also check for you

#### gallery.html
- Audio Clips
    - Go to Gallery page
    - Click through each audio clip
    - Make sure each song plays aloud
    - Get friend to also check for you

#### contact.html
- Contact Form
    - Go to Contact page
    - Try submit form with nothing filled out, this should bring up a "required field" alert
    - Try fill out form but leave one input field blank to make sure the "required field" alert pops up
    - Try to submit form with all input fields filled out and the page should reload

#### Navigation and Footer
- Navigation
    - Open each menu item on each page respectively 
    - Make sure they lead to the correct place and can easily find your way back to starting point
    - Have friend also test this out for you
- Footer
    - Book Us Now
        - Click "Book Us Now" link on each page and make sure it leads to contact.html 
        - Make sure you can get other places easily from that page
    - Social Media Links
        - Click each link to make sure they open in another page due to the target="_blank"
        - Make sure each link correlates to the correct social media platform

#### Mobile Responsive 
- Each page was checked through the live preview by inspecting it in dev tools and choosing different screen sizes
- Throughout project code was put through an HTML validator to make sure there were no open elemets or such that was preventing the code to run smoothly
- Towards the end of the design it was figured out that the navigation bar was preventing all the pages to fill out the screen as a white space was running down the right side
    - This was fixed by looking in the dev tools and altering the CSS

### Bugs/Problems Encountered
- Contact form
    - When adding in an alert to say "thank you for submitting your form", the code would overwrite the required fields of the form
    - In the end I had to remove the alert and will work on it when I learn Javascript
- Mobile responsive was not working at first when viewing in ‘inspect’ and on the different devices
    - First I ran my code through an HTML validator which fixed the tourdates.html page in mobile responsive 
    - Second I discovered the video element and audio elements were preventing the mobile responsive to work. To fix this I resized and repositioned the video and audio elements which fixed the problem and the mobile responsive worked smoothly after this
- Footer code would not collapse in my cloud9 workspace
    - To fix this I ran the footer code through an HTML validator and corrected the problems which worked to then collapse my footer code
- My mentor pointed out that the code for my navigation bar was not formatted correctly with the Bootstrap divs and rows
    - To fix this I re watched some videos and took in what my mentor said to make my code my cleans and work more effectively
- Creating a timeline for the tour dates on tourdates.html
    - This was difficult for me as when I created it the first time it did not go as smoothly as I would have liked it to. To correct this, I re watched the lesson on it and understood more of what I had to do as I was leaving out some key CSS styles 

## Deployment

## Credits

### Content

#### index.html
- The information used in index.html paragraph one was obtained and rewritten by me from [Wikapedia article The 1975](https://en.wikipedia.org/wiki/The_1975)
- The information used in index.html paragraph two was copy and pasted from the fourth paragraph from [Wikapedia article The 1975](https://en.wikipedia.org/wiki/The_1975)

#### tourdates.html
- The information used for the tour dates timeline in tourdates.html was found from [The 1975 Official Website](https://the1975.com/)
- The information used for buying tickets on tourdates.html were from the following 
    - [Belfast SSE Arena](https://www.ssearenabelfast.com/whats-on)
    - [Dublin Arena](http://3arena.ie/)
    - [Glasgow SSE Hydro](https://www.thessehydro.com/)
    - [Cardiff Motorpoint Arena](https://motorpointarenacardiff.co.uk/)
    - [Brighton the Centre](https://brightoncentre.co.uk/)
    - [London the O2](https://www.theo2.co.uk/events/venue/the-o2-arena)
    - [Exeter Westpoint](http://westpointexeter.co.uk/whats-on)
    - [Birmingham Arena](http://www.arenabham.co.uk/)
    - [Manchester Arena](http://www.manchester-arena.com/)
    - [Sheffield Flydsa Arena](http://www.flydsaarena.co.uk/home)
    - [Reading Festival](https://www.readingfestival.com/tickets)
    - [Leeds Festival](https://www.leedsfestival.com/tickets)

### Media

#### Header
- The photo used in the navigation bar was obtained from [Nodaway Broadcasting](https://nodawaybroadcasting.com/event/the-1975/)
- The photo used as a background in all files was obtained from [Pixabay](https://pixabay.com/en/wear-retro-people-abandoned-3289266/)

#### index.html
- The photos used in index.html were obtained from [The Billboard Photos From The 1975 Cover Shoot](https://www.billboard.com/photos/8468106/the-1975-photos-billboard-cover-shoot)
- The video used in index.html was obtained from downloading the video from [The 1975’s Youtube Channel](https://www.youtube.com/watch?v=CHk5SWVO4p8)

#### gallery.html
- The photos used in gallery.html were obtained from [Getty Images of The 1975](https://www.gettyimages.co.uk/photos/the-1975-band?sort=mostpopular&mediatype=photography&phrase=the%201975%20band)
- The audio clips used in gallery.html were obtained by downloading songs from the following youtube channels
    - The 1975 [Somebody Else](https://www.youtube.com/watch?v=NzjzBsgZH2w)
    - Bestfiend Lyrics [The Sound](https://www.youtube.com/watch?v=Oc5GRjZvffo)
    - The 1975 [Paris](https://www.youtube.com/watch?v=xxaPbsT0ixk)
    - The 1975 [If I Believe You](https://www.youtube.com/watch?v=_o0_q89IqVc)

### Acknowledgements
- Thank you to the tutors for helping me through the parts I needed assistance with
- Thank you to my first mentor, Yoni Lavi, who gave me confidence in my first website design
- Thank you to my new mentor, Antonija Simic, who showed me and went through with me how a modern day website should look like and giving me the confidence to re deisign and shape my website
    - Half way through my project I gained a new mentor due to my original mentor changing roles within The Code Institute
    - My new mentor talked through the design and we decided that I would make the website more modern looking
    - Therefore I would like to say thank you to Antonija Simic for inspriring my website design 
- I received inspiration for the original top of the website design from the blog [Poppy Loves](http://www.poppyloves.co.uk/)