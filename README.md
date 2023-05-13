# Smoking Guns.

I created a website for a movie which I produced in 2016, the site contains a few of the festival nominations and an award which the film won, images, videos, a review of the movie and a link to buy the movie on Amazon and Youtube aswell as what television stations the film plays on. The aim of the site is to act as promotion for the film.

![responsive](https://user-images.githubusercontent.com/90483176/231429240-5adf36cc-c594-4e7f-b0bb-5366567dccb1.png)


## Features.

### Navigation.

* The film name is in the top left hand corner in a font commonly used for film promotional material and also acts as a link back to the home page, beneath which is information on where to buy and watch the film. 
* There are links to other sections of the webiste such as the media page and the review page aswell as the home page on the right hand side.

### Front Page

* The main body of the front page contains some of the film festival laurels along with one of the awards that the film won.  
* The films logo set as the background and links to buy the film.

![front](https://user-images.githubusercontent.com/90483176/230976497-e7a686c0-8b4f-4a4b-82b1-63cb0cafb11b.jpg)


### Media Page

The media Page contains the official trailer along with eight promotional posters which were used to advertise the film at festivals.

![trailer](https://user-images.githubusercontent.com/90483176/230976570-013a6c61-0476-450b-ad61-408a550ab919.jpg)

### Review page

The review page contains one of the reviews of the film which was written by Mark Bartlett for Britflicks website along with a video of interviews with three of the cast members also for Britflicks website.=, the heading here links to the review on the britflicks website.

![review](https://user-images.githubusercontent.com/90483176/230976665-cc7dd213-f5ab-49f9-b1c1-3f0b5c8b356f.jpg)


### Footer

The footer contains links to all the films social media (Twitter, Facebook) as well as the IMDB page.

## Testing

* I tested the site worked in different browswers, eg Firefox, Edge and Chrome.

* I confirmed the site is responsive and works on all device types, i found the font I chose for the logo reverts to the secondary choice on some browsers and devices.

* I confirmed the links to outside sites are all correct and in working order.
* I confirmed that the videos play as intended and the user has control over when the videos play and can open them in full screen.

## Bugs

### solved

* When i first deployed the website to github pages the Festival laurels were just showing the alt text. 

I solved this by removing a forward slash (/) from the front of the image file path, also by renaming the images and removing spaces from the file names.

* When i resized the images not all of the images were loading

* I solved this by renaming the images so there were no spaces in the file names.

## validator Testing

### HTML

I ran the code through the W3C checker and found the following error Error: Stray end tag i.From line 66, column 210; to line 66, column 213 526;"></i></i></a>

I solved this by deleting this tag.

### CSS

* I ran the code through the W3C CSS Validator and found the following error 213	#photos	wrap is not a flex value : wrap

I solved this by changing  flex: wrap ; to flex-wrap: wrap;

* 320	.trailer iframe	Value Error : width only 0 can be a unit. You must put a unit after your number : 512

I solved this by adding the unit "px" 

http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fandrewneo82.github.io%2Fsmoking-guns%2F&usermedium=all&vextwarning=&warning=1





### Accessability

Running lighthouse confirmed that the colours and fonts were accesible and easy to read.

![lighthouse](https://user-images.githubusercontent.com/90483176/230979099-94499596-9d77-488c-9017-8c5bad418156.jpg)

## Deployment
The site was deployed to github pages. The steps to depoloy were as follows.


* In the Github repository navigate to the settings tab.
* From the source section drop-down menu, select the Master Branch.


The live link can be found here https://andrewneo82.github.io/smoking-guns/

## Credits   

### Content

* The code for the footer was taken from the CI Love Running walkthrough project.
* For the videos I used youtubes embed html code as when i tried to upload the videos the files were too big, i added controls to this and made the iframe size responsive with CSS.

## Media

The review and associated interviews are courtesy of britflicks.com.

The icons are from fontawesome.com.

All other media is owned my myself and my partners.
