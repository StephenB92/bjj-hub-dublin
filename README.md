# BJJ Hub - Dublin

## Project Overview

The aim of this project is to be used as a hub of information on Brazilian jiu-jitsu clubs based in Dublin city centre. The project also includes basic information on the history of the sport and some inspiration for newcomers to begin their jiu-jitsu journey! As the project includes information on clubs based in Dublin along with their address and links to social media, it is also intended to be used by people who have trained elsewhere before and have recently moved to Dublin and are looking for nearby gyms where they can train.

For future updates to the project, I would like to include a news section that includes up to date information on clubs based in Dublin and upcoming competitions. I would also like to include a news section that relates to the global BJJ community, to include upcoming matches with popular grapplers and also sales on instructional videos online. I would also like to include a section including articles written by the wider BJJ community on subjects such as conditioning and nutrition.

## User Experience (UX)

### User Stories

1. First Time User Goals
    * As a first time user, I want to easily understand the main purpose of the site and learn more about BJJ as a hobby.
    * As a first time user, I want the site to be intuitive and user friendly so I can easily navigate the site and obtain the information I need easily.
    * As a first time user, I want information on BJJ clubs in Dublin. A brief note on the club itself along with their address and links to their social media so I can make an informed decision as to what club I would like to join. 

2.  Returning User Goals
    * As a returning user, I would like to see information on new clubs opened in Dublin.
    * As a returning user, I would like to have a platform where I can ask questions regarding clubs to better inform my decision.
    * As a returning user, I would like the up to date information on clubs. For example if a club has changed location.

3. Frequent User Goals
    * As a frequent user, I want to receive up to date news on any seminars, upcoming competitions or open mats taking place in Dublin.
    * As a frequent user, I want to be able to read articles written by the wider BJJ community on subjects such as conditioning and nutrition.
    * As a frequent user, I want to receive up to date news on the wider, global BJJ community. For example, upcoming matches of interest I can watch online or, sales on instructional videos online.

### Design

1. Colour Scheme
    * The colour scheme represents the five belt levels in Brazilian Jiu Jitsu; white, blue, purple, brown, black. It starts at white in the header, then sections in the order of blue, purple and brown with the footer being black.

2. Typography
    * The Roboto-Condensed family is used in the header text and section titles with Nunito being used in the individual section content. Sans-serif is set as the fallback font in every case in case the other fonts cannot be imported correctly. Roboto-Condensed and Nunito are used as they are clean, sleek and modern looking.

3.  Imagery
    * An image of a diverse BJJ class is used as the main hero image on the home page which is intended to be more attractive and welcoming to new visitors and of course people considering beginning to train in BJJ. Images used in the "History of BJJ" section are to give users a better sense of the history of the martial art.

4. Video
    * A video embedded from YouTube displaying a diverse range of BJJ practitioners competing. The song playing over the video is "Don't Let Me Down" by The Chainsmokers feat. Daya. The reason behind this video being included is to function as a sort of "highlight reel" to show people what they will be learning should they begin training themselves
    
### Wireframes

#### Desktop

1. Please find the desktop version wireframe for the home page [here.](/assets/wireframes/desktop/home.png)
2. Please find the desktop version wireframe for the  clubs in dublin page [here.](/assets/wireframes/desktop/clubs-in-dublin.png)
3. Please find the desktop version wireframe for the history of bjj page [here.](/assets/wireframes/desktop/history-of-bjj.png)
4. Please find the desktop version wireframe for the inquiries page [here.](/assets/wireframes/desktop/inquiries.png)
5. Please find the desktop version wireframe for the  thank you page [here.](/assets/wireframes/desktop/thank-you.png)

#### Mobile

1. Please find the mobile version wireframe for the  home page [here.](/assets/wireframes/mobile/home-mobile.png)
2. Please find the mobile version wireframe for the mobile clubs in dublin page [here.](/assets/wireframes/mobile/clubs-mobile.png)
3. Please find the mobile version wireframe for the history of bjj page [here.](/assets/wireframes/mobile/history-mobile.png)
4. Please find the mobile version wireframe for the inquiries page [here.](/assets/wireframes/mobile/inquiries-mobile.png)
5. Please find the mobile version wireframe for the  thank you page [here.](/assets/wireframes/mobile/thanks-mobile.png)


### Features

##### Navigation Bar

##### Home page with quotes from BJJ practitioners

##### Clubs in Dublin 

##### History of BJJ

##### Inquiries


### Bugs and Fixes

- As seen in the "Love Running" CI project - I encountered that issue where my nav elements had their order reversed when i set the items to float right. After some googling, I found that the fix was to float the parent of the listed nav items to the right and then, set the li elements beneath to float to the left. 

- I encountered an issue when inserting the small black belt logo appearing under the nav bar whereas the background did not blend well with the site background. In order to maintain the page layout (starting from white through blue, purple, brown and black) I researched different shades of white using hex values until I found the perfect shade.

### Credit

- Credit to https://www.sitepoint.com/community/t/navigation-bar-tabs-displaying-backwards/7904/4 where I found the fix to the issue I had regarding the styled navigation elements appearing in reverse order.

- Jiu-jitsu images were acquired on Google images.
    - Image of bjj class  in hero image acquired from https://static.wixstatic.com/media/4ef5b5_878c01c7e7cf48a78eba4c4e8c9ba076.jpg/v1/fill/w_960,h_640,al_c,q_90/4ef5b5_878c01c7e7cf48a78eba4c4e8c9ba076.jpg
    - Image of black belt appearing under nav bar: https://www.nicepng.com/png/detail/80-801279_bjj-jiu-jitsu-black-belt-jiu-jitsu-belt.png

- YouTube video on home page uploaded by Culture Cafe'. All rights belong to WME-IMG and Viacom - No copyright infringement intended - the video is entermainment purposes only.

- Quotes from renowned BJJ practitioners taken from a website called Fightersmarket.

- Quotes regarding the benefits of traning obtained from O Athletic.com and The Guardian website

- Credit to the Code Institute Love Running project for code used in respect of hero image and the styling of the text overlapping the hero image.

- Credit to the Code Institute Love Running project for code used in respect of the benfits of running page which inspired my section on "why train bjj".

- Credit to the Code Institute Love Running project for code used in respect of the "active" class underlining the page the user is currently on.

- Credit to the Code Institute Love Running project for code used to style the form elements on the inquiries page.

- Credit to [Stack Overflow](https://stackoverflow.com/questions/8605516/default-select-option-as-blank) where I found the following code which allowed me to start my form "gender" datalist at a neutral option but still ensure it was required in order to submit the form. "<option disable selected value> -- Select an Option</option>"