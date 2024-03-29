# Rocks Off Climbing Gym 

This is a webiste for the newly opened Rocks Off Climbing Gym. The aim of the website is to convey a welcoming tone to whilst also providing important information. The site also allows users to contact Rocks Off whilst also providing basic information about themselves and their climbing experience. 
![RocksOff](docs/responsive-rocksoff.jpg)

## User Experience

### User Stories

1. As a user I want to find information which will aid me in organising a visit to the climbing centre. 
   
2. As a user I want to be able to contact the centre to gain further information.  

3. As a user I want to know what facilities the centre provides. 


### Design 
 - #### Colour Scheme

 - The colour pallette was found on the [coolors](https://coolors.co/) site and was used as it used natural, earthy tones which indicate the site's purpose as a rock climbing facility. 

 - The text colour was used as it provided good contrast on darker backgrounds. 

 - #### Typography 
 - The **Inter** font was used as the main font for the site. This was because it is easily readable and is good for responsive display.  

   
## Features 


### Existing Features 

**Navigation Bar**

![Rocks Off Nav Bar](docs/nav-bar-rocksoff.jpg)


- The navigation bar allows easy access around the site and includes links to the sections: About Us, Times and Prices, and Contact Us. 
- As the website is a single page which scrolls the links take the user to the relevant section. 


**Landing Page Image**

![Landing Page](docs/landing-page-rocksoff.jpg)

- The landing includes the name of the gym and brief welcome message.

- There is an eyecatching image of a woman bouldering to help emphasise the purpose of the website.



**General Information Section**

![About Section](docs/about-rocksoff.jpg)

- There is an 'about us' section which gives information about the centre. This section aims to answer some questions which users may have whilst also exciting an interest in using the facilities. 

- There is a 'story' section that gives a bit of a story about the centre's background. The 'walls' section gives specific information about what climbing there is available. Then the final section is about the general facilities that the club has on offer. These are facilities that will increase convenience and comfort of users and so are good to mention here. 

- The background image is a close up of hands belaying. This is to again reinforce the purpose of the page. It also serves to emphasise that Rocks Off is not just a bouldering centre, but also has roped climbing opportunities. 



**Opening Times and Prices Section**

- This section lays out the opening times and prices information in tables. 

- The information is clearly laid out and the tables are close together, which allows for ease of use. 

- This section could be updated as times change or as more membership options become available. 

![Rocks Off Opening Times Table](docs/opening-rocksoff.jpg)


**Contact Us Section**

-Users are requested to input their name and email. This is to ensure that communications can be responded to effectively. 

- Radio buttons are used to gain more information about what sort of query the user is messaging about. 

- There is a selector to find out more about the user's climbing experience. This will allow Rocks Off to provide coaching offers that are relevant to the experience level of users. 

- There is a feedback text area so that the user can type their message. 

- The button to send the form has the text 'send it' this is to fit with the climbing vernacular further emphasising the purpose of the site. 

- For further information the club phone number and address are below the form. This information is of benefit to the user so that they can contact with more specific or urgent enquiries. This will allow aid users in finding Rocks Off when they visit.
  
![Contact Form](docs/contact-rocksoff.jpg)


**The Footer**

- The footer has links to social media and a copyright notice. The links open the social media pages in a different link so that the user can remain on the Rocks Off page. 

- This is of use to the user as it helps them to engage with Rocks Off on other media. 

- Having links to social media allows the centre to market to, and communicate with, users. 

![Footer](docs/footer-rocksoff.jpg)


### Features left to implement 

- The site could also include a gear shop online in the fuuture. This would complement the on-site gear shop mentioned in the facilities box in the about us section. 

- Social media links direct to the social media main page as there are no social media addresses for teh site. 

-The form action is set to email@rocksoff.com because there is nowhere for the data to be sent to. 



## Testing

The code was validated through the W3C HTML Validator, W3C CSS Validator, and JSHint. These were used to ensure that syntax errors or omissions were rectified prior to submission.
 - (https://validator.w3.org/)
 - (https://jigsaw.w3.org/css-validator/)
 - (https://jshint.com/)

HTML Validation
 - The HTML passed the validator with no issues. 

 CSS Validation
 - One of the reasons that the project failed initially was becuase an error in the CSS code which was picked up in the validator testing. Removal of an extra bracket solved this issue.


### Lighthouse 

![Testing Image](docs/lighthouse-rocksoff.jpg)

Lighthouse was used to check for accesibility and performance. 

Text contrast was found to limit the accessibility score as the contrast between text and background was not effective for some users. To rectify this I changed the background colour of the site to a darker shade of green. This fixed the issue. 

There was also an issue with the aria labels for the navigation a elements. The aria label didn't match exactly with the text displayed on the screen e.g. Aria label read: **Return to the top of the page** but the text displayed on screen read: **Back to top** Lighthouse said that this can lead to confusion for users who use screen readers. I made the change so that aria labels matched the text displayed and the issue was resolved.  After changes the accesibility was improved from 80% to 94%

### Devices 
- The site was tested on **Chrome** and **Safari**
- Devices used for testing were and iPhone SE, a MacBook Air and an iPad. 

### Testing User Stories

1. As a user I want to find information which will aid me in organising a visit to the climbing centre. 
    - There are sections which list the opening times and prices. The address of the centre is included in the contact us section of the site. 

2. As a user I want to be able to contact the centre to gain further information. 
    - A contact form is available for users to get in touch. There are also links to the social media sites. 

3. As a user I want to know what facilities the centre provides. 
    - There is a section with information about the facilities available to the user when they visit. This includes climbing specific information and more general facilities such as coffee shop and toilets.  

### Fixed Bugs

- There was an issue with page scroll on some devices. I had initially tried to fix this with by setting the scroll on the x axis as hidden in the CSS. My mentor advised me that this was bad practise and that by adapting the layout of the footer in the media query would help with this issue. 
- Prior to validator and lighthouse testing some bugs were evident in preview. I was having issues with the layout of boxes on the screen. The issue seemed to be related to the box borders. I found advice on (https://forum.freecodecamp.org/t/setting-a-right-border-breaks-my-html-and-css-layout/183473) from user **hadrienalllemon** which indicated that I could use border box to bring the child inside the parent. There was also advice to include different box-sizing for different browsers e.g. moz-box-sizing and webkit-box-sizing. Including this in the code solved the issue. 
- 

### Functionality

- All buttons were tested and directed the user as expected. 
- The contact form was tested to ensure that radio buttons and dropdown work as expected. 

### Validator Testing 

Html and CSS were tested on W3C HTML code validator (https://validator.w3.org/) and W3C CSS code validator(https://jigsaw.w3.org/css-validator/). 


### Unfixed Bugs

Lighthouse still brings up issues with performance. It asks me to 'avoid chaining critical requests' at present this is beyond my knowledge set and I will need to research to rectify this issue. Lighthouse also states that I should avoid large layout shifts. I think this is in reference to the changes I made to ensure that content remains readable on smaller screens. With more time I would look more into the responsive features and make site use more easy across different screen sizes. At present I have one media query for smaller screens which changes the site layout at max width 1090 px . I think there should probably be more flexibility to this. There is also an aesthetic issue in the deployed site which I am unable to fix. The tables move to the left of the page on the deployed site when I look at it on my iphone SE phone. The issue is not present in dev tools preview and I have made a number of attempts to fix it to no avail. 


## Deployment 

 The site was deployed through GitHub pages. Once code was written it was commited and pushed to GitHub. The following steps outline how to deploy using GitHub Pages. 

 1. Go to the repository A-Hebbes/Project-1-Rocks-Off
 2. In side navigation select 'Pages'
 3. In the dropdown select 'None'
 4. Click on 'Master' 
 5. Click 'Save'
 6. Site is now live at: (https://a-hebbes.github.io/Project-1-Rocks-Off/) 



## Credits 

Code help and advice came from many sources. 

###

**Code Institue**

As this is my first introduction to coding, I used the 'Coder's Coffeehouse' project as a key source of inspiration and direction for my own site. Coder's Coffeehouse provided a good basis from which to apply my learning. I believe this especially for the HTML, however initial overrelaince on the CSS code led to issues further down the process. In hindsight, I should have used the guidance on CSS from Coders Coffeehouse more judiciously. My inital plan was to copy CSS from Coffee House into my style sheet so that I could see the structure and layout. This proved at times to be somewhat of a hindrance as I was finding bugs and issues that I hadn't actually coded in myself so finding them was difficult at times. 

**Simen Daehlin**

Simen helped outline the approach to the process and this was useful. He gave good information on the use of (https://coolors.co/) as a place to help with design choices. He gave me solid advice on how to approach the project and timeframes. Various factors limited my use of this advice which is a shame, but factors outside of my control led me to take a more rushed approach to the project. On reflection, I would use his advice more. For example, I am writing the readme after the project completion, but his advice was to do it prior to coding. This will be especially useful in completion of my next project as it will allow for a smoother design and development process. 

**Ollie Grubb**

At the outset of my project I was struggling with the IDE and GitHub. I was unable to effectively save work and was losing hope in ever getting the project together at all. Ollie took the time to talk me through the process and was able to help me solve the issues I was having. I also had an issue with deployment and Ollie helped me to sort this out as well. 

**Chat GPT**

When I was having issues with the code I would seek advice from Chat Gpt as if it were a mentor. The advice was not always directly useful but more than once helped point me in the right direction. 

**Border Code To Improve Layout**

Code found at (https://forum.freecodecamp.org/t/setting-a-right-border-breaks-my-html-and-css-layout/183473) given by **hadrienallemon** was used to help sort layout in relation to borders. 

**Box Shading Guide**

I looked at the article at (https://css-tricks.com/snippets/css/css-box-shadow/) to see how to add shade to my boxes.  I changed the pixels in the code to REM equivalent for responsivity and used a color shade that is more in keeping with my site aesthetic.

**Educational Sites and Fora**

Listed below are more sites that I used to gain understanding of issues I was having or insights into best practice. 

(https://www.thoughtco.com/)

(https://stackoverflow.com/)

(https://www.w3schools.com/)

(https://developer.mozilla.org/en-US/)

(https://forum.freecodecamp.org/)

(https://nekocalc.com/px-to-rem-converter)

(https://alistapart.com/)

(https://webflow.com/blog/fonts-for-web-design)



### Content

  
- The coders coffee house project served as inspiration for layout and approach to coding the site.   


### Media 


- Images came from (https://unsplash.com/)












