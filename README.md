<h1 align="center">0x09. Implement a design from scratch</h1>


<h2>Content</h2>

- [Concepts](#concepts)
- [Requirements](#requirements)
- [**Tasks**](#tasks)
  - [0. Read and be familiar with Figma](#0-read-and-be-familiar-with-figma)
  - [1. Header](#1-header)
  - [2. "What we do..." section](#2-what-we-do-section)
  - [3. "Our results" section](#3-our-results-section)
  - [4. Contact us](#4-contact-us)
  - [5. Footer](#5-footer)
  - [6. Replace background image with... code!](#6-replace-background-image-with-code)
  - [7. Let's animate items](#7-lets-animate-items)
  - [8. And SASS??](#8-and-sass)

# Concepts
For this project, students are expected to look at this concept:

* [Implement a design](https://intranet.hbtn.io/concepts/220)

<p>In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.</p>

<p>You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.</p>

Here the final result:

<img src="images/1.jpg">  

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip)


# Requirements

* you are not allowed to import external CSS framework (like Bootstrap)
* you are not to use Javascript

# **Tasks**
## 0. Read and be familiar with Figma  

Create an account in [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg) and open this [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw) and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A)

<img src="image/../images/2.png">

Important notes with Figma:

if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/wltHny-KZP3B8JFRvpmVjA) and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Qb96K4nTPQJO1paP_OBELw)
some values are in float - feel free to round them
For this task, please write an amazing [README.md](README.md)

**Interactions note:**

+ the web page must switch to the mobile version when the screen width is 480px or less
+ links hover/active: #FF6565
+ button hover/active: opacity: 0.9
+ max width of the content: 1000px centered in the page  

Repo:

GitHub repository:  
holberton-headphones  
File: [README.md](README.md)
 
## 1. Header
uilding a web page the right way, is not easy - expect if you put in place strong foundations:

+ reset CSS styling
+ use variables
+ simple/“as generic as you can” CSS selectors
+ avoid using super specific CSS selectors as much as possible
+ simple HTML structure - <text style="color: red;">div</text> containers are your friend!  
  
Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.

Now, your turn!

For this first task: **create the header/hero piece**

Here an archive of all assets needed: [images_0x09.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210823T184417Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=eb2657cdd36e8c5e0a8456702107ef789886ba24753b565a8aa3ed6d04d4c70a)

Desktop:

<img src="images/01.gif">

Mobile:

<img src="images/02.gif">

Repo:

GitHub repository:  
holberton-headphones  
File: [0-index.html](0-index.html), [0-styles.css](0-styles.css)
 
## 2. "What we do..." section
Copy files from the previous task.

For this second task: **create the “What we do…” section**

In this section, you will need custom font icons. Here the archive of it: [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210823T184417Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=ead8b6cc8e4443e1b90bc1e17ad38bb0a9590a23f47818a9e9228f9691632152) Inside you will find demo page of how to use it.

**Important:** try to build as generic as you can… you will probably need some components in next section.

Repo:

GitHub repository:  
holberton-headphones  
File: [1-index.html](1-index.html), [1-styles.css](1-styles.css)
 
## 3. "Our results" section
Copy files from the previous task.

For this third task: **create the “Our results” section**

Now you can reuse components form the previous task!

Repo:

GitHub repository:   
holberton-headphones
File: [2-index.html](2-index.html), [2-styles.css](2-styles.css)
 
## 4. Contact us
Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.

Repo:

GitHub repository: holberton-headphones
File: [3-index.html](3-index.html), [3-styles.css](3-styles.css)
 
## 5. Footer
Copy files from the previous task.

Last piece of the page… the Footer!

When you are done, here the result:

**Desktop:**

<img src="images/03.gif">

**Mobile:**

<img src="images/04.gif">

And you are done!

**Good job!**

Repo:

GitHub repository:  
holberton-headphones  
File: [4-index.html](4-index.html), [4-styles.css](4-styles.css)
 
## 6. Replace background image with... code!  
#advanced  
In the section “Our results”; without the use of an image file, draw each pentagon using HTML and CSS.

Repo:

GitHub repository:  
holberton-headphones  
File: [100-index.html](100-index.html), [100-styles.css](100-styles.css)
 
## 7. Let's animate items  
#advanced
From [4-index.html](4-index.html) and [4-styles.css](4-styles.css), add fun animations to “What we do…” and “Our results” sections items row. Either all the time, either when hover.

Scaling, opacity, rotation, bouncing… many options!

Repo:

GitHub repository:  
holberton-headphones  
File: [101-index.html](101-index.html), [101-styles.css](101-styles.css)
 
## 8. And SASS??  
#advanced  
Take your 101-styles.css file and create a 102-styles.scss that will be the SASS version of it.

$ sass 102-styles.scss > 101-styles.css
Repo:

GitHub repository:  
holberton-headphones  
File: [102-styles.scss](102-styles.scss)
 