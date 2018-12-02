# README.md

## The 1975 Website
My project focuses on the popular rock band, The 1975. This website is for fans of theirs who like to keep up with their tour dates, latest music and easy access to their social medias. The website also caters to companies and venues who would like to see where they are touring and possibly book them. 

My project has its opening page where it briefly describes the bands history and what they are all about, while also showing the members of the band. This is crucial as visually seeing who you will be engaging with is very important and brings it to a personal level. The second menu item brings fans and potential bookers to the touring timeline of the 1975, which enables them to see when and where the band will be playing for the foreseeable future. I have also enabled a feature to allow fans to be directed to the ticket selling websites for each arena so they can purchase tickets to see the band live. The following menu item allows for individuals to listen to some of the bands popular hits and see photos of them live in action. The last menu item allows for companies and venues to contact the band for bookings and shows. It also has a section for fans, allowing them to have easy access to the bands verified username on their social medias and subsequently, links to the bands direct social media pages. 

## UX
This website is for individuals interested in, are fans of and who want to know more about the 1975. This website allows these individuals to see what dates and where the band is touring, as well as links to buy tickets to these events. The website also provides popular songs, photos of the band, direct links to their verified social media links and a contact page. The contact page is more for companies and venues who would like to book The 1975 to play. The website caters to these individuals as well because it allows the companies and venues to see who is in the band, information about them and music for them to sample.  

- As a new fan I want to see photos of the band members and see who plays what position to know more about them 
- As a new fan I want to read about the band so that I am knowledgeable about them
- As a possible employer I want to read about the band and see who it is composed of so that I know more about them when I decide to book them 
- As a fan I want to know when they are touring and where they will be so that I can book tickets 
- As a possible employer I would like to see when they are touring and where they will be so that I can book them to play at my venue
- As a new fan I want to listen to their popular songs and watch videos on them to learn more about them and their style
- As a possible employer I want to listen to the genre of music they produce so that I can potentially book them for my venue
- As a fan I want to know what their real social media pages are so that I can follow their live updates and tag them in photos I take when I attend their concerts

## Features

### Existing Features

#### index.html
- Eye catching front page
    - Music video and photos of the band members for users to view in case they are not familiar with the band or type of music
- Information on the band
    - Information about the band readily accessible
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
    - Required input fields and a submit button that acknowledges submission
- Social media links
    - Direct links and username provided to the bands verified social media pages

### Features to be Implemented in the Future
- Javascript
    - To link up the contact form for it to work correctly once I have learnt it
    - To have an alert that says "thank you for submitting your form" without over writing the required fields

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
    - https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css
    - This was used to help style the website and with the grid layout of it
- Font Awesome
    - https://fonts.googleapis.com/css?family=Roboto:400,400i,700,700i
    - This was used to create a universal font for the website
- Hover
    - https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css
    - This was used to have the hover styles run smoothly

## Testing
- .html files
    - An HTML [validator](https://validator.w3.org/) was used to check the code
    - An HTML [formatter](https://www.freeformatter.com/html-formatter.html) was used
- .css file
    - A CSS validator was used to check the stylings
- Overall
    - I tested out some designs in a workspace that I cloned from this milstone project and ended up copying and pasting some of that code over for some aspects of my submitted project. [This repository can be found here]()


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

#### index.html
- The photos used in index.html were obtained from [The Billboard Photos From the Billboard Cover Shoot](https://www.billboard.com/photos/8468106/the-1975-photos-billboard-cover-shoot)
- The video used in index.html was obtained from downloading the video from [The 1975’s Youtube Channel](https://www.youtube.com/watch?v=CHk5SWVO4p8)

#### gallery.html
- The photos used in gallery.html were obtained from [Getty Images of The 1975](https://www.gettyimages.co.uk/photos/the-1975-band?sort=mostpopular&mediatype=photography&phrase=the%201975%20band)
- The audio clips used in gallery.html were obtained by downloading songs from the following youtube channels
    - The 1975 [Somebody Else](https://www.youtube.com/watch?v=NzjzBsgZH2w)
    - Bestfiend Lyrics [The Sound](https://www.youtube.com/watch?v=Oc5GRjZvffo)
    - The 1975 [Paris](https://www.youtube.com/watch?v=xxaPbsT0ixk)
    - The 1975 [If I Believe You](https://www.youtube.com/watch?v=_o0_q89IqVc)

### Acknowledgements
- I received inspiration for the top of the website design from the blog [Poppy Loves](http://www.poppyloves.co.uk/)