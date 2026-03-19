# Website: terry-artwork.github.io

2026-03-19: This informational README.md file is not linked to on the website. i.e. It is hidden from the public.

## Terry's Artwork Website

The initial design of this website has four webpages: Home, Contact, About, and Galleries.

The tree diagrams below show all the directories and files in the source code that the Nikola application uses to create the website. 

The diagrams are repeated but with differents sets of comments so its easy to see which files should get changed and by whom.

This tree diagram displays the 8 x directories and the 16 x files that make up the src branch.

```text

src <-- Source code for the website
│
├── pages
│   ├── about.md
│   ├── contact.md
│   └── index.rst
│
├── galleries
│   ├── index.txt
│   ├── metadata.yml
│   ├── tesla_1.jpg
│   ├── tesla_2.jpg
│   ├── tesla_3.jpg
│   ├── tesla_4.jpg
│   └── tesla_5.jpg
│
├── images
│   ├── favicon-cat.svg
│   ├── logo.svg
│   └── tree_painting.jpg
│ 
├── conf.py
├── files
│   └── assets
│       └── css
│           └── custom.css
└── .github
    └── workflows
        └── main.yml
```

This tree highlights the directories

```text

src <-- Source code for the website
│
├── pages                   <-- Directory for webpages
│   ├── about.md            <--
│   ├── contact.md          <--
│   └── index.rst           <--
│
├── galleries               <-- Directory for the gallery of images
│   ├── index.txt           <--
│   ├── metadata.yml        <--
│   ├── tesla_1.jpg         <--
│   ├── tesla_2.jpg         <--
│   ├── tesla_3.jpg         <--
│   ├── tesla_4.jpg         <--
│   └── tesla_5.jpg         <--
│
├── images                  <-- Directory for images
│   ├── favicon-cat.svg     <--
│   ├── logo.svg            <--
│   └── tree_painting.jpg   <--
│ 
├── conf.py                 <--
├── files                   <-- Directory for files
│   └── assets              <-- Sub-Directory for Cascade Style Sheets
│       └── css             <-- Sub-Sub-Directory for Cascade Style Sheets  
│           └── custom.css  <-- 
└── .github                 <-- Directory for workflow
    └── workflows           <-- Sub-Directory for workflow
        └── main.yml        <--   
```

This tree highlights the files

```text

src <-- Source code for the website
│
├── pages
│   ├── about.md            <-- About webpage. Written in Markdown. 
│   ├── contact.md          <-- Contact webpage. Written in Markdown.
│   └── index.rst           <-- Home webpage. Written in ReStructuredText (reST).
│
├── galleries
│   ├── index.txt           <-- Text file to display any text on the Photo Gallery web-page
│   ├── metadata.yml        <-- A yaml meta data file to provide the file names and captions for each photo.
│   ├── tesla_1.jpg         <-- Photo 1
│   ├── tesla_2.jpg         <-- Photo 2
│   ├── tesla_3.jpg         <-- Photo 3
│   ├── tesla_4.jpg         <-- Photo 4
│   └── tesla_5.jpg         <-- Photo 5
│
├── images
│   ├── favicon-cat.svg     <-- Image of cat that is displayed in the Browser tab
│   ├── logo.svg            <-- Image of cat that is the logo in the webpage header
│   └── tree_painting.jpg   <-- Featured photo of painting used in the home webpage
│ 
├── conf.py                 <-- Python programming language website configuration file.
├── files
│   └── assets
│       └── css 
│           └── custom.css  <-- Cascade Style Sheet file to customize this website
└── .github
    └── workflows
        └── main.yml        <-- The yaml file that runs the Nikola website building application. 
                                Runs after every change to the website is made.   
```

This tree highlights the files that are normally changed by Terry and files that are normally changed by Ian.
Ian doesn't normally have to change any files once the website is in use. 

```text

src <-- Source code for the website
│
├── pages
│   ├── about.md            <-- *Ian* About webpage. Written in Markdown. 
│   ├── contact.md          <-- *Ian* Contact webpage. Written in Markdown.
│   └── index.rst           <-- *Terry* When changing featured photo in Home webpage.
│
├── galleries
│   ├── index.txt           <-- *Ian* Text file to display any text on the Photo Gallery web-page
│   ├── metadata.yml        <-- *Terry* When adding or removing photos from the gallery.
│   ├── tesla_1.jpg         <-- *Terry* Add or remove photo
│   ├── tesla_2.jpg         <-- *Terry* Add or remove photo
│   ├── tesla_3.jpg         <-- *Terry* Add or remove photo
│   ├── tesla_4.jpg         <-- *Terry* Add or remove photo
│   └── tesla_5.jpg         <-- *Terry* Add or remove photo
│
├── images
│   ├── favicon-cat.svg     <-- *Ian* Image of cat that is displayed in the Browser tab
│   ├── logo.svg            <-- *Ian* Image of cat that is the logo in the webpage header
│   └── tree_painting.jpg   <-- *Terry* Featured photo of painting used in the home webpage
│ 
├── conf.py                 <-- *Ian* Python programming language website configuration file.
├── files
│   └── assets
│       └── css 
│           └── custom.css  <-- *Ian* Cascade Style Sheet file to customize this website
└── .github
    └── workflows
        └── main.yml        <-- *Ian* The yaml file that runs the Nikola website building application. 
```
  
The files that Terry will change every time a painting photo is added or removed, or there is a change to the price, etc.

```text

src <-- Source code for the website
│
├── pages
│   ├── about.md            
│   ├── contact.md          
│   └── index.rst           <-- *Terry* When changing featured photo in Home webpage.
│
├── galleries
│   ├── index.txt           
│   ├── metadata.yml        <-- *Terry* When adding or removing photos from the gallery.
│   ├── tesla_1.jpg         <-- *Terry* Add or remove photo. E.g. New image could be called "blue-dots.jpg"
│   ├── tesla_2.jpg         <-- *Terry* Add or remove photo. E.g. New image could be called "terrys-cat.jpg"
│   ├── tesla_3.jpg         <-- *Terry* Add or remove photo. E.g. New image could be called "tree_painting.jpg"
│   ├── tesla_4.jpg         <-- *Terry* Add or remove photo. Note that replacement photos dont need to have numbers in the filename.
│   └── tesla_5.jpg         <-- *Terry* Add or remove photo.
│
├── images
│   ├── favicon-cat.svg     
│   ├── logo.svg            
│   └── tree_painting.jpg   <-- *Terry* Featured photo of painting used in the home webpage
│ 
├── conf.py                 
├── files
│   └── assets
│       └── css 
│           └── custom.css  
└── .github
    └── workflows
        └── main.yml        
   
```
## Summary.

Ian changes some files, but mostly this is done when creating the website. After that these files don't normally need changing.

Terry edits or removes files whenever he wants to change the featured picture in the home page, or change the pictures in the gallery.


## Metadata.yml file

The metadata.yml file in `src/galleries/` directory needs to be edited after changing photo images. This file provides the captions that go at the bottom of each enlarged image.

The metadata.yml file on the website is currently as show below.

Notes: 

* The three hyphens "---" between information about each image must be kept.
* The filenames do not have to include any numbering. E.g. *tesla_1.jpg* could be named *tesla_tower.jpg*.
* The caption can not start with a number. E.g. Can not have: *caption: 1. The Big Tower*. 


**metadata.yml**

```yaml

---
name: tesla_1.jpg
caption: No.1. The Big Tower. Acrylic on canvas. 30cm x 50cm. $20
---
name: tesla_2.jpg
caption: No.2. The Man with a Moustache. Acrylic on canvas. 40cm x 80cm. $50
---
name: tesla_3.jpg
caption: No.3. Three Generators. Acrylic on canvas. 60cm x 45cm. $40
---
name: tesla_4.jpg
caption: No.4. A Skinny Tower. Acrylic on canvas. 60cm x 45cm. $40
---
name: tesla_5.jpg
caption: No.5. Man with a Light Bulb. Acrylic on canvas. 60cm x 45cm. $40
---

```
