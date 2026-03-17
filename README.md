# Website: terry-artwork.github.io

Terry's Artwork Website

The initial design of this website has four webpages: Home, Contact, About, and Galleries.

The tree diagrams below show all the directories and files in the source code that the Nikola application uses to create the website. 
The diagrams are repeated but with comments removes so its easy to see which files should get changed and by whom.

These are the directories and files in the src code 
```
src <-- Source code for the website
│
│
├── pages
│   ├── about.md
│   ├── contact.md
│   └── index.rst
│
├── galleries
│   ├── index.txt
│   ├── metadata.yml
│   ├── tesla_1.jpg
│   ├── tesla_2.jpg
│   ├── tesla_3.jpg
│   ├── tesla_4.jpg
│   └── tesla_5.jpg
│
├── images
│   ├── favicon-cat.svg
│   ├── logo.svg
│   └── tree_painting.jpg
│ 
├── conf.py
├── files
│   └── assets
│       └── css
│           └── custom.css
└── .github
    └── workflows
        └── main.yml
```

These are the directories
```
src <-- Source code for the website
│
├── pages                   <-- Directory for webpages
│   ├── about.md            <--
│   ├── contact.md          <--
│   └── index.rst           <--
│
├── galleries               <-- Directory for the gallery of images
│   ├── index.txt           <--
│   ├── metadata.yml        <--
│   ├── tesla_1.jpg         <--
│   ├── tesla_2.jpg         <--
│   ├── tesla_3.jpg         <--
│   ├── tesla_4.jpg         <--
│   └── tesla_5.jpg         <--
│
├── images                  <-- Directory for images
│   ├── favicon-cat.svg     <--
│   ├── logo.svg            <--
│   └── tree_painting.jpg   <--
│ 
├── conf.py                 <--
├── files                   <-- Directory for files
│   └── assets              <-- Sub-Directory for Cascade Style Sheets
│       └── css             <-- Sub-Sub-Directory for Cascade Style Sheets  
│           └── custom.css  <-- 
└── .github                 <-- Directory for workflow
    └── workflows           <-- Sub-Directory for workflow
        └── main.yml        <--   
```

These are the Files 
```
src <-- Source code for the website
│
├── pages
│   ├── about.md            <-- About webpage. Written in Markdown. 
│   ├── contact.md          <-- Contact webpage. Written in Markdown.
│   └── index.rst           <-- Home webpage. Written in ReStructuredText (reST).
│
├── galleries
│   ├── index.txt           <-- Text file to display any text on the Photo Gallery web-page
│   ├── metadata.yml        <-- A yaml meta data file to provide the file names and captions for each photo.
│   ├── tesla_1.jpg         <-- Photo 1
│   ├── tesla_2.jpg         <-- Photo 2
│   ├── tesla_3.jpg         <-- Photo 3
│   ├── tesla_4.jpg         <-- Photo 4
│   └── tesla_5.jpg         <-- Photo 5
│
├── images
│   ├── favicon-cat.svg     <-- Image of cat that is displayed in the Browser tab
│   ├── logo.svg            <-- Image of cat that is the logo in the webpage header
│   └── tree_painting.jpg   <-- Featured photo of painting used in the home webpage
│ 
├── conf.py                 <-- Python programming language website configuration file.
├── files
│   └── assets
│       └── css 
│           └── custom.css  <-- Cascade Style Sheet file to customize this website
└── .github
    └── workflows
        └── main.yml        <-- The yaml file that runs the Nikola website building application. 
                                Runs after every change to the website is made.   
```
Files that are normally changed by Terry and files that are normally changed by Ian.
Ian doesn't normally have to change any fiels once the website is in use. 

```
src <-- Source code for the website
│
├── pages
│   ├── about.md            <-- *Ian* About webpage. Written in Markdown. 
│   ├── contact.md          <-- *Ian* Contact webpage. Written in Markdown.
│   └── index.rst           <-- *Terry* When changing featured photo in Home webpage.
│
├── galleries
│   ├── index.txt           <-- *Ian* Text file to display any text on the Photo Gallery web-page
│   ├── metadata.yml        <-- *Terry* When adding or removing photos from the gallery.
│   ├── tesla_1.jpg         <-- *Terry* Add or remove photo
│   ├── tesla_2.jpg         <-- *Terry* Add or remove photo
│   ├── tesla_3.jpg         <-- *Terry* Add or remove photo
│   ├── tesla_4.jpg         <-- *Terry* Add or remove photo
│   └── tesla_5.jpg         <-- *Terry* Add or remove photo
│
├── images
│   ├── favicon-cat.svg     <-- *Ian* Image of cat that is displayed in the Browser tab
│   ├── logo.svg            <-- *Ian* Image of cat that is the logo in the webpage header
│   └── tree_painting.jpg   <-- *Terry* Featured photo of painting used in the home webpage
│ 
├── conf.py                 <-- *Ian* Python programming language website configuration file.
├── files
│   └── assets
│       └── css 
│           └── custom.css  <-- *Ian* Cascade Style Sheet file to customize this website
└── .github
    └── workflows
        └── main.yml        <-- *Ian* The yaml file that runs the Nikola website building application. 
```
  
Files That Terry will change every time a painting photo is added or removed, or there is a change to the price, etc. Ian will help do this.
```       
src <-- Source code for the website
│
├── pages
│   ├── about.md            
│   ├── contact.md          
│   └── index.rst           <-- *Terry* When changing featured photo in Home webpage.
│
├── galleries
│   ├── index.txt           
│   ├── metadata.yml        <-- *Terry* When adding or removing photos from the gallery.
│   ├── tesla_1.jpg         <-- *Terry* Add or remove photo. E.g. New image could be called "blue-dots.jpg"
│   ├── tesla_2.jpg         <-- *Terry* Add or remove photo. E.g. New image could be called "terrys-cat.jpg"
│   ├── tesla_3.jpg         <-- *Terry* Add or remove photo. E.g. New image could be called "tree_painting.jpg"
│   ├── tesla_4.jpg         <-- *Terry* Add or remove photo. Note that replacement photos dont need to have numbers in the filename.
│   └── tesla_5.jpg         <-- *Terry* Add or remove photo.
│
├── images
│   ├── favicon-cat.svg     
│   ├── logo.svg            
│   └── tree_painting.jpg   <-- *Terry* Featured photo of painting used in the home webpage
│ 
├── conf.py                 
├── files
│   └── assets
│       └── css 
│           └── custom.css  
└── .github
    └── workflows
        └── main.yml        
   
```
