# RockBand 
<img src="http://karolsliwka.abovewave.co.uk/mypage_top.jpg" style="widt:100%;">

> This is a First Milestone Project for [Code Institute](https://codeinstitute.net/) Full Stack Developer Course.</br>
> Website is about the rock band from 1960's. RockBand is playing around 50 years on the rock stage giving theirs fans the best emotions and memories.
> Static website with responsive clear and simply design (front-end only).

## Technologies Used

> Languages

* [HTML](https://en.wikipedia.org/wiki/HTML5)
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

> Frameworks / Libraries
* [jQuery](https://en.wikipedia.org/wiki/JQuery)
* [Bootstrap 3.7](https://getbootstrap.com/docs/3.3/)

## Features

* I have used script to create a 'goToTheTop' button. In my project square with '^' sign represents this button.
```javascript

    //When the user scrolls down 20px from the top of the document, show the button

    window.onscroll = function() { scrollFunction() };

        function scrollFunction() {

            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {

                document.getElementById("myBtn").style.display = "block";

            }

            else {

                document.getElementById("myBtn").style.display = "none";

            }

        }

        // When the user clicks on the button, scroll to the top of the document

        function topFunction() {

            document.body.scrollTop = 0;

            document.documentElement.scrollTop = 0;

        }

```

* Carousel at the top of website was created based on code from - [w3schools](https://www.w3schools.com/bootstrap/bootstrap_ref_js_carousel.asp)
* Menu toggle collapse script from [Codeply](https://www.codeply.com/go/XtiWqN3lGn) used to make the navigation bar simple and easy to use while displayed on small devices.
* Audio and Video files allows users to listen music and watch videos by pressing play button.
* Contact form is making easy way to contact the band by the fans and make all enquiries.





## UX / Design

### Styling
>   Simple and clear one page style, separated sections, colored headers,
contrasting text on dark background.
Smooth website scroll and "goBack" button created to be more user friendly.


### Pages/Sections

> Home
>   - Button/Link to go back to the top of the page. No content in this section.

> News
>   - All the latest news about the RockBand, such as new album/s or song/s,
concert tours and special events.

> About
>   - Short story about RockBand in top part of section.
Team members presented in separated cards with photos, names and roles.

> Music
>   - Section splited for two parts. In left side user can find the audio files to listen, specialy picked songs. Right side of the section was prepared to place the newest video clips to be watched by fans.

> Offer
>   - The best saving offers and deals for upcoming events and concerts, specially prepared for fans.

> Contact
>   - All necessary information about RockBand office, contact form and newsletter subscribe field.

### User stories
The purpose of website is to let old, new fans to hear songs and see videos of RockBand.
RockBand also want to give the fans best offers and make their dreams come true by allow them to contact and make special events for them as Weddings or Christmas parties.

> As a old fan of RockBand I would like to now all the latest news about them.

> I'm a new fan of RockBand and I want to know more about my lovely band and team members.

> As a friend of RockBand fan I want to listen their songs to found out what kind of music they're playing.

> I want to make a surprise for my girdled because she's really big fan of RockBand. I want to check if there are some cheap prices for tickets  or if they're playing near to our town to take her to the concert.

> My whole family is a big fan of RockBand and my brother Mark is getting married next month. I want to contact the band and check if it's possible to arrange the concert on his wedding.

> Our band have a big dream to play as a RockBand support. I would like to call their Manager and ask if it's possible.


## Testing

This website was tested on a Google Chrome browser by using an extension tool - Viewport Resizer.
After website was fully loaded into the Viewport Resizer. I've pressed the Animation button to see how website will react on the viewport changes.
While the width of the website was changing I was scrolling up and scrolling down to see how the images, text and contact form input fields are going to behave and chang the sizes. 
I've used the standard sizes in the Viewport Resizer to see how te website is look like on a different devices, as a tablets and phones.
On each viewport widths I was clicking on all buttons and links to see how they going to react.

By clicking on the links in the navigation bar, the smooth scrollFunction will work correctly on all viewport sizes. No clicking order needed.
Toggle button collapse correctly by clicking on "hamburger button" or by clicking on menu links on all viewport sizes.

Contact form required fields are: Nam and Surname, E-mail Address and Message. The 'required' attribute is added to them so they will not allowed you to submit form before filling them.
When you try to submit the contact form without filling any of input boxes. You will se the message on the top of empty input box says, "! Please fill in this field.".
Mouse cursor will be automatically focus in empty input box.

* When the viewport width is less than 768px aside button 'goToTheTop' is not visible otherwise on larger screen is visible
* Website was tested on iPhone 8. Works and look good in portrait and landscape layout.


Website looks and works good on different browsers and all most common screen sizes.


## Deployment
> This website is hosted and deployed from master branch to GitHub Pages.

* How to deployed website on Github Pages.
>

    - Click on name of repository that you want to deployed.

    - On the top bar click on "Settings".

    - Scroll down to GitHub Pages and from source drop down list choose "Master branch".

    - Create the name for your deployed website and click on "Save" button.



## Credits / Acknowledgement

> Whole website text was created and written by myself (Karol Sliwka).
>
>
> Photos used in this project are from certain pages searched via [GoogleImageSearch](https://www.google.com/advanced_image_search)

* List of all images and url addresses to download/use images
 
> Images

1. Carousel

    - Berlin - [image 1](https://pxhere.com/en/photo/1055770)</br>
    - Spain - [image 2](https://pixabay.com/pl/koncert-t%C5%82um-grupy-odbiorc%C3%B3w-ludzie-768722/)</br>
    - Sweden - [image 3](https://pxhere.com/en/photo/115544)

2. News

    - New CD in Vinyl Release - [image 1](https://www.maxpixel.net/Vintage-Vinyl-Retro-Equipment-Record-Player-761592)</br>
    - Concert With The Orchestra - [image 2](https://pixabay.com/pl/orkiestra-ch%C3%B3r-beethoven-1815716/)</br>
    - Arizona 2019 - [image 3](https://pl.m.wikipedia.org/wiki/Plik:Entering_Arizona_on_I-10_Westbound.jpg)</br>
    - Rock & Roll Picnic - [image 4](https://www.aviano.af.mil/News/Articles/News-Display/Article/1225626/rock-n-roll-wing-picnic/)

3. AboutUs

    - Vocal - [image 1](https://pxhere.com/en/photo/61422)</br>
    - Guitar - [image 2](https://pixabay.com/pl/gitara-gitara-gracz-muzyk-670087/)</br>
    - Bass - [image 3](https://pxhere.com/en/photo/978908)</br>
    - Drums - [image 4](https://www.maxpixel.net/Musician-People-Drums-Set-Concert-Man-Musical-2599508)
 
 
> Audio </br>
* Audio files used in this project are from Code Institute assets for this course

    - [Code Institute Assets](https://github.com/Code-Institute-Org/project-assets) </br>

> Video</br>
* YouTube video ( iframe ) - video used/shared from Foo Fighters YouTube channel.
    - [Foo Fighters YouTube Channel](https://www.youtube.com/channel/UCi2KNss4Yx73NG0JARSFe0A)
    - [Foo Fighters - The Sky Is A Neighborhood (Official Music Video)](https://www.youtube.com/embed/TRqiFPpw2fY")
 
> With reference to the previous Testing section 
    
* Link to GoogleChrome webstore to install ViewportResizer.
    - [ViewportResizer](https://chrome.google.com/webstore/detail/viewport-resizer/kapnjjcfcncngkadhpmijlkblpibdcgm) 

##### *All assets have been used for educational purposes