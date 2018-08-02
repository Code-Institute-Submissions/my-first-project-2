The First Milestone Project

Clone:

git clone https://github.com/jstokes1994/my-first-project.git

File structure:

- first-project
    - assets
        - css
            - style.css
        - images
        - videos
    - band.html
    - booking.html
    - index.html
    - videos.html

        

Initial Sructure - Header, footer and section background:

First I created the header and footer which was a constant across each webpage.
The header features the band name at the top of the page, on its own row. I
wanted this to be the first thing I expect the user to see, to keep it in their
mind. 

The header also features links to each webpage present on the site. They utilise
the hover feature which changes the icon and text colour on hover. This was 
based on the links seen in the nav bar of the resume project. I decided against
the white block appearing on hover using just the change of colour. They use 
bootstrap glyphicons.

The footer has three parts: suscribe, question and social media links. The
suscribe feature is a simple form for a user to provide an email to receive 
updates on the band. The question is a tabulated form that receives the name and
email of a user along with the the question. The social links fulfil the project
requirement to increase the band's social media presence. Consistent with the 
navbar in the header the icon and text colour changes from white to black on 
hover.

In terms of the section I wanted a consistent background across each page. I
used a black and white picture of the band and used a linear gradient to fade
it slightly. 

I made use of the 'full background image' code found on CSS tricks to produce
the background image that stretches across the entire section.

Homepage:

Taking inspiration from the 'Whisky Drop' site seen in the course I wanted a
very clean, uncluttered homepage with an initial call-out to interest the user.
The page features a call-out statement and a button to invite the user to read 
more about the page. On clicking the button, I used CSS transitions to reveal a
small piece of writing about the band.

When the viewport is reduced in size the image disappears to allow room for the
text. I had initial issues with the picture and text fitting on a smaller
viewport.

I also featured a button that links to the booking section of the website to
encourage users to book the band from the first page.
I used a black background for the text to make sure the text was clear against
the background image.

The Band page:

This page shows an image of each band member to allow users to familiarise
themselves with the band. Upon hovering over the image, a list of facts about
the member appears to provide information on the individual. This makes use of 
CSS transitions. To fade the image I added opacity to the image on hover.

When the viewport is reduced in size to tablet or mobile the images go from
'col-xs-3' to 'col-md-6' to allow them to seen across platforms. The container
has 'overflow' set to auto which allows it to accomodate the elements.

The Media page:

The page is split between Gallery and Videos.

The biggest challenge was the images to be viewed across viewport sizes.
Each image was within a div with class name 'gallery-container'. At full-size 
the div took up 33.3% of the container, therefore 3 images per row. Using media
queries, when the viewport reached the first breakpoint of 700px, this was
changed to 49.99% to take up half and show 2 images per row. At 500px each image
took up 100%, therefore 1 image per row. On this page I used clearfix so the 
elements would self-clear its children and allow the images to stay within the
container. The responsive aspect of the gallery I learnt from an example found 
on W3Schools.

Beneath the gallery the video was added in the middle of the page.

As a whole the page fulfilled the project requirement to show the band's content
the public.

Booking page:

The booking page features a tabulated form. I found this the best way to line up
the labels and the input fields (since realised I could have simply made use
of bootstrap grid system, but felt this produced the same layout).

As on the homepage the page advertises the band to potential customers for 
events. It requests a variety of data from the user using a range of input
fields. I would like the datepicker to show 'booked' dates, however don't think
this is possible using only HTML/CSS.



