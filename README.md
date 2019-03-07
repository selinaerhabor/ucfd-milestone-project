# UCFD Milestone Project: The Kinks' Website

This is a website created for the 1960s Rock Band called The Kinks to showcase their work and music influence. Formed in Muswell Hill, London, 
UK in 1963, The Kinks are believed to be one of the most influential rock bands of the 1960s.

A live demo of The Kinks’ website can be viewed [here]

Main Website Pages: [Home], [About], [Music], [Photos], [Events] and [Store].

## 1. User Experience Design (UX)
The primary target audience of this website are fans and potential fans of the rock band who are interested in viewing clips of the band and the band’s work.

The Kinks' Main Requirements for the Site: 
* Photos of the band members
* A video clip
* Audio clips
* Showcase their music and increase awareness of their availability to perform at events
* Provide links to their social media pages to improve their social media presence


## 1.1 User Stories
Firstly, I gathered users’ opinions on what they feel a 1960s band website should showcase. From the ease of navigation to the band’s merchandise to old fashioned photos, I collected several user stories discussing potential features that should be included on the website... 
> "Simple and easy access through navigation across the website"

> "Old fashioned photos – black and white style"

> "1960s Culture/dressing/outfit/wears"

> "Seeing obsolete/old musical instruments and equipment"

> "Seeing how the band relates to audience, introduction speeches/stage performances"

> "Ease to buy The Kinks’ merchandise"

> "Ease to send requests for booking to perform at weddings/other parties"

> "Ease of using website on mobile phones as well as desktops or other devices"

I created sketches of different website layouts and design ideas that would be suitable for the band’s website (see Initial Ideas-Wireframes folder). These sketches were based on meeting the project requirements and the needs of users. The sketches were then developed further to produce wireframes focusing on the different pages/sections of the website to give an idea of the key features that should be included in the website and their layout.

## 2. Features
My project focused on meeting the needs of users’ for the website, so the user stories were taken into account during building the features and 
components of the website.

## 2.1 Existing Features

### 2.1.1 [Home] Page and Standard Features:
*	**Navigation Bar** - allows users to navigate through the website. This navigation bar is available on all the pages of the website and also on all forms of screen sizes. On smaller screen sizes the navigation bar is collapsed/minimised to save space on smaller screen sizes. When clicked, the burger icon on the right top end of the screen will then expand the list of the different pages of the website vertically downwards. 
*	**Subscribe Features** - users are welcomed to subscribe to The Kinks' Newsletter if they would like to. Clicking the "Subscribe" button opens up a form which allows users to fill in their details (email, first name and last name) on the website. Users are redirected to "Thanks for Subscribing" page upon successful completion. When user hovers the cursor over the "Subscribe" button, it changes gradually from light orange background with grey text to a red background with white text and returns back to the original state when cursor is removed from button. On smaller screens the Subscribe text on button changes to the Pen Square Font Awesome icon.
*	**Footer** - consists of links to The Kinks’ social media channels (Facebook, Twitter and YouTube) and legal documentation on privacy policy, terms & conditions for website usage and Frequently Asked Questions for Store help. When user hovers the cursor over the social media channel icons, the icons gradually increase in size to 45px from medium blue to a light blue colour and returns back to its original state when the cursor is removed from the button. Similarly, when the user hovers the cursor over the footer text links such as Privacy Policy, the link changes from medium blue to a lighter blue colour, but no size change and returns to original state when cursor is removed. The hover effects have been achieved using `:hover` extension for styling the buttons in style.css.
*   **Website Icon** - the chosen website icon is a guitar, because The Kinks influenced 1960s rock music greatly through their guitar sounds.
*   **Font** - The font style [Fjalla One], makes letters appear tall and thin especially when in uppercase. This font style works well with The Kinks' brand and has been used as the chosen font to maintain the style of the brand across the website.

### 2.1.2 [About] Section:
*	**Embedded Video** - A YouTube embedded video, visible and responsive across all screen sizes and is the only video present on this website. The video gives an overview on the biography of The Kinks including interview with some of the band members and their team. The length of the video is approximately just under nine minutes.
*	**Summary Text** - The text below the video summarises how The Kinks were formed and different band members.
*   **Thumbnail Layout Arrangement** - Each thumbnail presented brief information for each member of the band. The thumbnail arrangement has been organised in a pyramid style effect, with the main/long-serving members positioned at the top of the hierachy. This layout is visible on desktop screen sizes (screen widths of 1200px or larger).
*	**Blockquote style** - The Blockquote style displays the band members in order of service with the main/long-serving members at the top. Visible only on small screen sizes (screen widths less than 1200px).

### 2.1.3 [Music] Section:
*	**Audio Bar** - equipped with play button, pause button, progress slider, volume control and download options. Allows the user to play the audio files.
*	**Blockquote style** - Visible only on small screen sizes (screen widths less than 1200px). Displays song title, track cover and audio bar for each song using the blockquote style.
*	**Song Title becomes link on smaller screens** - On smaller screen sizes, users can click on the song title to open up an enlarged image of the music cover (in a new tab) as the image has been downsized to save space on smaller screens.
*	**More Music Feature** - redirects users to Apple itunes store where they can browse more on The Kinks' music and possibly make purchases. When user hovers the cursor over the "More Music?" button, it changes gradually from white background with blue text to a darker grey background with light blue text and returns back to the original state when cursor is removed from button.

### 2.1.4 [Photos] Section:
*	**Every Photo is a hyperlink** - All photos when clicked reveal an enlarged version of itself in a new tab so that the user can keep track of where they are on the website. This was done by using  `target="_blank"` inside the `img` tags.
*	**Three Columns Layout** - Photos have been organised into sections (1960s & 1970s, 1980s & 1990s, 2000-Present). When viewing the Photos section on desktops (i.e. devices with screen widths of 1200px or larger), the photos are arranged in three columns. When viewing on smaller screen sizes, the photos are arranged in one column but their sections are still separating them as user scrolls through. 

### 2.1.5 [Events] Section:
*	**Upcoming Tours** - Displays six upcoming tour dates Dave Davies or Kast off Kinks will be performing across US and UK. 
*	**Buy Tickets Button** - Users are redirected to where they can purchase their tickets via "Buy Tickets" button. When user hovers the cursor over the button, it changes gradually from white to an orange colour and returns back to white when cursor is removed from button.
*	**Events Form** - Users can fill in details of the event they would like The Kinks to perform at.
*	**Submit Button** -  Users are redirected to "Thanks for completing our Events Form" page when they successfully submit the Events form. When user hovers the cursor over the Submit button, it changes gradually from a lighter green to a darker green colour and returns back to the original state when cursor is removed from button.

### 2.1.6 [Store] Section:
*   **Store Tab** - includes a trolley cart icon to signal to users that the Store tab is where they can find The Kinks merchandise to buy.
*	**Thumbnail Layout Arrangement** - The Kinks' merchandise are organised in terms of their item type (CDs, T-Shirts, Tote Bag, Mugs and Accessories). This layout is visible on both large and smaller screen sizes and number of items displayed on one row decreases to two items per row and then one item per row on a smaller screen size (sm) or extra small screen (xs) respectively.
*	**Buy Now Button** -  Users are redirected to merchandise page to purchase sellected item. When the user hovers the cursor over the button, it changes gradually from white to a lighter green colour and returns back to the original state when cursor is removed from button.

## 2.2 Potential Features to implement in the future:
*	**News Feed** - Recent news feed on The Kinks could also be added to appear on one side of the website's home page to give users the opportunity to view information posted on their social media in real time.


## 3. Technologies Used
*   [Cloud 9] - The Integrated Development Enviroment (IDE) for building the website.
*	[HTML] - Used for the structure and format of the entire website.
*	[CSS] - For styling the website and maintaining its responsiveness across various screen sizes.
*	[Bootstrap (3.3.7)] - Used for grid form and assistance in styling.
*	[JQuery] - Used to ensure modal forms appear on the screen when the specified button is clicked by the user.
*	[Tube2mp3] - Used for converting YouTube videos into MP3 audio files which were easily imported into the website.
*	[Font Awesome] - Used for displaying the social logos and vector icons present on the website.
*	[Browsershots.org] - For checking browser compatibility and cross platform browser testing.



## 4. Testing
This section discusses the results from testing the website and its features. Tests were carried out on key components of the website and on various device screen sizes and browsers.

## 4.1 Feature Testing Process:
**Navigation Bar**
> "Simple and easy access through navigation across the website"

* Website default page - [Home]
* Clicked the "About" tab and it changed from a dark grey colour to a white underlined text
* Redirected to the [About] page
* Process was repeated for all the pages on the website
* All navigation tabs are working correctly.

**Subscribe Form**
* On [Home] page clicked "Subscribe" button
* Clicked the "Submit" button without filling in any data and an error message about the required fields appears (Required fields: Email, First Name, Last Name, Privacy Policy checkbox)
* Submitted the form with an invalid email address and error message appears prompting user to amend details provided for email
* Submitted the form with all valid inputs in the required fields and ["Thanks for Subscribing"] page.

**Subscribe Button (Mobile View)**
* On [Home] page "Subscribe" button changes from the text "Subscribe" to an icon successfully.

**Social Media Channels**
* At the "Footer" of the website there are links to The Kinks' social media channels are present
* Clicked on the "Facebook" icon and a new tab opens loading the official Facebook page of The Kinks
* Process was repeated for "Twitter" and "YouTube" icons at website footer

**Footer Text Links**
* At the "Footer" of the website there are text links with information on Privacy Policy, Terms & Conditions and Store Help
* Clicked on the "Privacy Policy" link and the information appears in a modal form in the centre of the screen 
* Process was repeated for "Terms & Conditions" and "Store Help" icons

**Events Request Form**
> "Ease to send requests for booking to perform at weddings/other parties"

* On [Events] page scrolled down to "Want the Kinks at your Event?" section
* Clicked the "Submit" button without filling in any data and an error message about the required fields appears (Required fields: First Name, Last Name, Phone Number, Email Address, Country and Privacy Policy checkbox)
* Submitted the form with an invalid email address and error message appears prompting user to amend details provided for email 
* Selected from the dropdown menu my event type, venue capacity and event duration
* Submitted the form with all valid inputs in the required fields and redirected to the ["Thanks for completing our Events form"] page.

**Video**
> "Seeing how the band relates to audience, introduction speeches/stage performances"

* On [About] Page, click play button on video
* Video begins to play whilst on the page 
* Video quality is clear and showcases some members of The Kinks' and their performances.

**Photos**
> "Old fashioned photos – black and white style"
> "1960s Culture/dressing/outfit/wears"
> "Seeing obsolete/old musical instruments and equipment"

* On [Photos] Page, click on a picture
* Page loads bigger size of picture in a new tab 
* Picture quality is clear and showcases The Kinks' outfits, musical instruments and photo styles over the years.

**Buy Now Buttons**
> "Ease to buy The Kinks’ merchandise"

* On [Store] Page, place cursor over "Buy Now" button
* Button hover style comes into effect - changing the button to a light green background
* Clicked "Buy Now" button and redirected to where I can actually purchase the item.

## 4.2 Device Screen Size and Browser Compatibility Test Results:
The website has been tested on various browsers including Internet Explorer, Safari, Firefox and Google Chrome at the various screen sizes using [Browsershots.org]. This website allowed me to test each page of The Kinks' website on Linux, Windows and Mac operating systems.

> "Ease of using website on mobile phones as well as desktops or other devices"

* The below screen size tests were carried out assessing performance of all pages of the website using Google Chrome 72.0 (Windows):

Device | Screen Size (Weight x Height) | Responsiveness 
------ | ------ | ------
Galaxy S5 | 360 x 640 | ✓
Pixel 2 | 411 x 731 | ✓
Pixel 2 XL | 411 x 823 | ✓
iPhone 5 SE | 320 x 568 | ✓
iPhone 6/7/8 | 375 x 667 | ✓
iPhone 6/7/8 Plus | 414 x 736 | ✓
iPhone X | 375 x 812 | ✓
iPad | 768 x 1024 | ✓
iPad Pro | 1024 x 1366 | ✓

* Below are the test results of the website deployed on GitHub pages when tested on Browsershots.org on various browsers. Key screenshots of the `Browser Test` results can be found in a folder called Browser Tests under the assets folder.
* Key: ✓ - Website loads successfully

Operating System | Browser | Home | About | Music |Photos| Events| Store
---- | ---- | ---- | ---- | ---- | ---- | ---- | ----  
Linux | Chrome 71.0 | ✓ |  ✓  |  ✓   |   ✓  |  ✓   |   ✓  |
Linux | Firefox 3.0 |  ✓   |  ✓   |  ✓  |  ✓ |   ✓ |   ✓ |
Linux | Firefox 61.0 | ✓    |   ✓  |  ✓   |  ✓   |    ✓ |    ✓ | 
Windows | Firefox 64.0 | ✓    | ✓    |  ✓   |  ✓   |  ✓   |   ✓  | 
Windows | Internet Explorer 11 |  ✓  |   ✓ |    ✓|   ✓ |    ✓|    ✓|
Mac | Chrome 48.0 | ✓    |  ✓   |  ✓   |   ✓  |   ✓  |    ✓ | 
Mac | Safari 9.1 |  ✓   |  ✓   |   ✓  |   ✓  |    ✓ |    ✓ |

The results of the tests above show that the website works well across key operating system browsers and various screen sizes with column arrangement adjusting correctly. The website should therefore be reliable and easy for users to explore. Things to note: In Internet Explorer 11, the audio bar appears as black coloured, but the style of the audio controls border radius is still maintained.

## 4.3 Interesting bugs or problems discovered during testing:
* Placeholders for the input forms and required input error messages were not appearing when viewing the website using Internet Explorer 11, so I had to state the color of the placeholder on the main browser types in the style.css file.
```sh
:-webkit-input-placeholder {color: #4a4a4a; }
:-moz-placeholder {color: #4a4a4a; }
:-o-placeholder {color: #4a4a4a;}
:-ms-input-placeholder {color: #4a4a4a; }
```
* Initially, I had planned to include the font awesome "fas fa-user" icon with the dropdown options for venue capacity. I tried using the `i` tags and then unicode in the code, but the icons still were not appearing. I have added the text "people" to give a sense of the size measurement for venue capacity and removed the code for the icon.

* Centering of the Store Item's price and "Buy Now" buttons in store.html were initially slightly tricky as the details of each store item differed in length. The Store item's price and the Buy Now buttons are inside a `div` with the class `order-item`. In order to center the features despite the length of the text above it, I set the position to absolute and declared ppropriate sizes for bottom and width in the style.css file.
```sh
.order-item {
    position: absolute;
    bottom: 50px;
    width: 65%;
}
```
* During the testing of the website on different browsers, the footer social media icons were not loading on Firefox or Safari browsers. In order to ensure that the social media icons appear on other types of browsers I changed the Font Awesome link in the `<head>` to the most updated version of font-awesome - Version 5.7.2 and amended the classes of the social media icons in my code. For example, the code for the subscribe icon that appears on smaller screens `<i class="fa fa-pencil-square-o"></i>` has now been changed to `<i class="fas fa-pen"></i>`. The icons used across the website are now appearing correctly for various browser types.

* In Internet Explorer 11, the audio bar style for the audio files in the Music section was bigger in size than on other browsers such as Chrome. As a result, the audio bars were overlapping and had no border radius. In order to fix this issue, I specified the width to 250px and border radius to 50px for the `musicAudio` audio controls class.
```sh
.musicAudio {
   margin-bottom: 60px;
   align-items: center;
   text-align: center;
   cursor: pointer;
   width: 250px;
   border-radius: 50px;
}
```


## 5. Deployment
The hosting platform for The Kinks’ website is GitHub Pages, which publishes the master branch containing the most updated version of code for the website.
To deploy the website to GitHub pages, I amended my GitHub Repository settings for this website by changing the source under GitHub pages from `None` to `master branch` to allow the `git push` command in my IDE (Cloud 9) terminal to deploy the website successfully to GitHub pages.
This project has two branches which have been merged as the Wireframes were initially uploaded directly to GitHub, but a folder called `Initial Ideas - Wireframes` has now been created and is stored under the assets folder.

The repository for this website can be cloned using the command below in terminal:
```sh
$ git clone https://selinaerhabor.github.io/ucfd-milestone-project/
```


## 6. Credits

#### Software Developer: Selina Erhabor

## 6.1 Content:
An appropriate range of sources have been used in order to publish some factual information about the 1960s Rock Band, The Kinks.

### Events - Tours
**Sources**: 
* https://www.ents24.com/uk/tour-dates/the-kast-off-kinks
* https://kindakinks.net/tourdates.php
* https://fanart.tv/artist/17b53d9f-5c63-4a09-a593-dde4608e0db9/kinks-the/

### Footer
**Sources**:
* The links to social media channels redirect users to The Kinks' Official [YouTube], [Twitter] and [Facebook] accounts. 
* The information in the Privacy Policy and Terms & Conditions links in the footer were tailored from [Sunny Afternoon The Musical] 
* Information in the Store Help link in the footer was tailored from [Official Merchandise Store].


## 6.2 Media:

### About
**Sources**:
* The video used in the About section is available on YouTube: https://www.youtube.com/embed/5FhaF0I3gv0
* https://www.allmusic.com/artist/the-kinks-mn0000100160/biography
* http://www.keno.org/classic_rock/kinks_bio.htm
* http://kastoffkinks.co.uk/

### Music
**Sources**: 
* http://sixtiesnumberones.blogspot.com/2010/11/1964-kinks-you-really-got-me.html
* https://www.youtube.com/user/TheKinksOfficial
* https://itunes.apple.com/ca/artist/the-kinks/1179227

The audio clips of The Kinks' top tracks in the Music section were sourced from their Official [YouTube] channel and those YouTube videos 
were converted into mp3 files which have been included in the audio folder under assets.

### Photos
**Sources**: 
* https://fanart.tv/artist/17b53d9f-5c63-4a09-a593-dde4608e0db9/kinks-the/#
* https://www.allmusic.com/artist/the-kinks-mn0000100160/biography
* https://www.facebook.com/TheKinksOfficial
* https://twitter.com/TheKinks

### Store
**Sources**: 
* https://thekinks.backstreetmerch.com/
* https://www.amazon.co.uk/Kinks-Deluxe/dp/B004E9OLZ8
* https://www.amazon.co.uk/Essential-Kinks/dp/B00MA7GABO

### Home & Extras
**Sources**:
* Website Icon - https://fontawesome.com/icons?d=gallery&q=guitar
* Subscribe Icon - https://fontawesome.com/icons/pen?style=solid
* Store Icon - https://fontawesome.com/icons/cart-arrow-down?style=solid

### Footer
**Sources**:
* Facebook Icon - https://fontawesome.com/icons/facebook-square?style=brands
* Twitter Icon - https://fontawesome.com/icons/twitter-square?style=brands
* YouTube Icon - https://fontawesome.com/icons/youtube-square?style=brands


[//]: # (Below are the reference links used in the body of the README file)
[here]: <https://selinaerhabor.github.io/ucfd-milestone-project/>
[HTML]: <https://html.com/> 
[CSS]: <https://https://en.wikipedia.org/wiki/Cascading_Style_Sheets> 
[Bootstrap (3.3.7)]: <https://getbootstrap.com/docs/3.3/components/> 
[Cloud 9]: <https://docs.c9.io/docs>
[AllMusic]: <https://www.allmusic.com/artist/the-kinks-mn0000100160/biography>
[Keno]: <http://www.keno.org/classic_rock/kinks_bio.htm>
[Kastoffkinks]: <http://kastoffkinks.co.uk/>
[Official Merchandise Store]: <https://thekinks.backstreetmerch.com/>
[Browsershots.org]: <http://browsershots.org/>
[Home]: <https://selinaerhabor.github.io/ucfd-milestone-project/index.html>
["Thanks for Subscribing"]: <https://selinaerhabor.github.io/ucfd-milestone-project/subscribed.html>
[About]: <https://selinaerhabor.github.io/ucfd-milestone-project/about.html>
[Music]: <https://selinaerhabor.github.io/ucfd-milestone-project/music.html>
[Photos]: <https://selinaerhabor.github.io/ucfd-milestone-project/photos.html>
[Events]: <https://selinaerhabor.github.io/ucfd-milestone-project/events.html>
["Thanks for completing our Events form"]: <https://selinaerhabor.github.io/ucfd-milestone-project/event-submitted.html>
[Store]: <https://selinaerhabor.github.io/ucfd-milestone-project/store.html>
[Ents24]: <https://www.ents24.com/uk/tour-dates/the-kast-off-kinks>
[Tube2mp3]: <https://www.tube2mp3.com/>
[itunes]: <https://itunes.apple.com/ca/artist/the-kinks/1179227>
[Font Awesome]: <https://fontawesome.com/>
[Fjalla One]: <https://fonts.google.com/specimen/Fjalla+One?selection.family=Fjalla+One>
[Sunny Afternoon The Musical]: <https://sunnyafternoonthemusical.com/>
[JQuery]: <https://jquery.com/download/>
[Twitter]: <https://twitter.com/TheKinks>
[Facebook]: <https://www.facebook.com/TheKinksOfficial>
[YouTube]: <https://www.youtube.com/user/TheKinksOfficial>