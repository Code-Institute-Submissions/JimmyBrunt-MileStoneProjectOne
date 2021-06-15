# MileStoneProjectOne

Code Academy Milestone Project One

A personal website highlighting my skills as a developer.

This three-section website highlights my competancies, along with the number of years experience per competancy, details what I can offer clients, and provides contact information.

A live version can be found here (https://jimmybrunt.github.io/MileStoneProjectOne/)

## UX

When I was designing this website, I wanted to make it as simple and artistic as possible, so I chose a one page layout, with different animated sections containing the three different elements.

- As a potential client, I want to be able to understand the competancies of any developer.
- As a potential client, I want to be able to understand the experiece of any developer.
- As a potential client, I want to be able to understand how the developer can help me.
- As a potential client, I want to be able to understand how to contact the developer.

Wireframes can be found here:

 - (http://www.jamesbrunt.co.uk/wireframe1.png)
 - (http://www.jamesbrunt.co.uk/wireframe2.png)
 - (http://www.jamesbrunt.co.uk/wireframe3.png)

## Features

Rather than having three separate pages, and a standard top navigation or hamburger menu, I decided to create a slick(?) sidebar navigation, and three sections that load in the parent container when triggered.

Each section has a different background image, which have been specifically chosen to be 'arthouse' and different, in an attempt to stand out from the crowd. H1 and P elements also fade in using animations, to add a little interest. I also added some meta for Twitter and OG as well as descriptions and keywords to help with SEO. The website is fully repsonsive and various media queries allow the content to be seen on devices of all sizes.

### Existing Features

- Section One

Includes a logo and a list of compentanices, which also includes the number of years experience per competancy.

- Section Two

Includes a brief statement highlighting what I can offer clients.

- Section Three 

Includes contact details; address, email and telephone, with clickable links.

### Features Left to Implement

- JavaScript contact form.
- Live chat function.
- Portfolio and examples of past work.

## Technologies Used

- HTML: Used for the structural elements of the site

- CSS : Used to style the HTML elements

- Font Awesome (https://fontawesome.com/) : Used for the social and navigation icons

- Balsamiq for Wireframes

- Linux Terminal to download Filezilla using: 

        sudo apt get install filezilla


- sFTP using Filezilla to push files to Gandi servers

- GIMP to edit tone and saturation of images

## Testing

The site was tested using two browsers, Google Chrome and Mozilla Firefox, on a laptop, where I utilised the DevTools in both browsers to check for compatibility issues on desktop, laptop and mobile devices. 

This did lead to CSS styling changes for smaller devices as certain elements were too large to display correctly. 

The site was also checked on Galaxy S9, Android 7.0, IPad, IPhone 6/7/8 IOS 11, and IPhone X/XS iOS 12, in all tests, both portrait and landscape views were analysed.

The only issue discovered during testing was that as the backgroud images for each section are landscape, and because I used 

        height: 100vh;

when this was viewed on smaller devices, whitespace was obvious below the images. So I utlised              
        
        min-height: 800px;
        
to ensure that the images still resized repsonsively, but didn't shrink too much, and additionally set the overflows to visible. This solved the problem.

The HTML code was validated here (https://validator.w3.org/)

- The results of this validation can be found here (http://www.jamesbrunt.co.uk/htmlvalidation.png)

The CSS code was validated here (https://jigsaw.w3.org/css-validator/)

- The results of this validation can be found here (http://www.jamesbrunt.co.uk/cssvalidation.png)

## Deployment

This site is hosted on Gandi servers, and is located here (http://www.jamesbrunt.co.uk/)

It is also be located in a GitHub repository here (https://github.com/JimmyBrunt/MileStoneProjectOne)

It can be deployed from the main branch. There are no differences between the development and deployed version.

To clone this repository to run locally, you can do the following:

- Create a new repository on Github
- Clone my repository with the following commands on your local machine:

    ```
    git clone https://github.com/JimmyBrunt/MileStoneProjectOne.git
    git remote rename origin upstream
    git remote add origin *URL TO NEW GITHUB REPO*
    git push origin master
    ```
    
- Deploy to Github Pages using the repository settings on Github

## Credits

### Content

- All code was written by me, drawing on my 20+ years of experience with HTML and CSS.
- The sidebar is something I have been using for a number of years on a number of projects.

### Media

- Images are all open-source, and qualify under fair use, due to nonprofit educational use.