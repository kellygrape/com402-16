---
layout: default
title: Project 1 - HTML & CSS | COM402 | Advanced Web Design and Development
---

<header><h1>Project #1</h1></header>

**Due Tuesday, March 1, 2016**

This project is worth 20% of your final grade.  You will be graded on your technical coding skills, plus on your design sense.  Use what you have learned thus far in the class to create a compelling, attractive, easy to read web page.

**What You'll Learn**

This project will allow you to showcase your advanced HTML and CSS skills.

**What You'll Create**

You'll be creating a small, three-page website.  The pages should have a cohesive look (using the same styling), and a unified navigation bar (that links from each page to the others).  The pages content will be discussed below.

### Setup

- Create a folder in your `com402/assignments` folder called `project01`.
- Create three html files: `index.html`, `page1.html`, and `page2.html`.
- Create a CSS file named `style.css`.
- Create an `images` folder.

### On Every Page

Every page should include the following

- Appropriate, semantic markup
- Validated HTML and CSS (see below)
- A navigation bar (see below)
- Linked CSS files (no `<style>` tags in your head!)
- A responsive, flexible grid-based design
- Images that scale with your responsive design
- Thoughtful use of color, whitespace, and typography (utilize external fonts from Google Web Fonts or other web font resources as needed)
- A CSS Reset (we've used *normalize* already in class)

### Navigation Bar

You will need to include a horizontal navigation bar on your pages.  Walk through the sides about [**Horizontal Fixed Nav**](http://girldevelopit.github.io/gdi-featured-intermediate-html-css/#/43) from [Girl Develop It](https://www.girldevelopit.com/)'s curriculum.

The navigation bar should appear on all pages.

### Index Page

On your index page, write about your experience completing this project.  You do not have to answer the following questions exactly; use them as a starting point.  Your narrative should be 300-500 words, formatted well and easy to read.  This is an advanced level course, so although we aren't in ENG101, I expect that your writing will be grammatically correct and have words spelled correctly. 
  
  - What did you find challenging about this project?
  - What did you find interesting about this project?
  - Were there any techniques you learned by doing this project?
  - Did you use any resources to help you with this project?
  - Did you find any tutorials that, although they didn't seem to have anything to do with this project, you thought were kind of cool and you might want to check them out later?
  - Did you try anything out and have to delete it because it just wasn't working?
  - How would you improve a portion of this project (you **must** answer this question).
  
### Page 1

You'll be creating a web page that showcases 9-16 visual pieces of content, plus information about that content.

For example, you may choose to do a page about your 16 favorite hockey players of all time, or a storytelling piece that showcases 16 photos of your daily life.  Cats, TV shows, cool websites, personal projects - pick something that you find interesting.  You will not be graded on your choice of topic.

**Examples**

- [Ethan Marcotte's 'Victors & Villains'](http://alistapart.com/d/responsive-web-design/ex/ex-site-flexible.html)
- [A basic, bare-bones example I've created](../media/project1/index.html)

You should include some CSS transforms and transitions on your page.  Each piece of content should have two transforms or transitions (scaling bigger and rotating; scaling smaller and fading out).  The transitions or transforms should occur when the user hovers over the images.

- Make sure to correctly utilize vendor prefixes.  You can use a tool such as [pleeease](http://pleeease.io/play/) or [CSS3 Generator](http://css3generator.com/) to help you set up your transforms and transitions.  You can also run the `autoprefixer` tool in Atom.

### Page 2

Page 2 will include an embedded CodePen.

Read [A Beginner's Introduction to CSS Animation](http://webdesign.tutsplus.com/tutorials/a-beginners-introduction-to-css-animation--cms-21068).

Create a new Pen on Codepen and follow the tutorial.  Your finished product should look like the example.

**For Extra Credit**

Change the animation.  Make it go the other way.  Change the colors!  Do something to change the animation.


### Your HTML and CSS must validate.
  - [HTML Validation](http://validator.w3.org/)
  - [CSS Validation](http://jigsaw.w3.org/css-validator/)
  
To validate your document, copy and paste your HTML code into the HTML validator.  Do the same for your CSS code.

Validation helps you see errors in your code. Error messages should tell you the line of the error and will give you information about what the error is.  Start with the first error.  Once you have fixed an error, recopy and paste your code into the validator and re-validate.  Sometimes fixing one error will clear others. 

If you are stuck on an error and cannot figure it out, **leave a comment in your code that explains this**.

Unvalidated code without explanation will result in an automatic deduction of 10 points from your grade.

You don't need to validate your CodePen.

##Delivery 

When you have completed this project, push it up to Github as a new repository.  Send me a link to your repository.  We have not gone over Github in class, so if you need help or a refresher with this, please let me know **before the due date**.

If you do not submit code by the start of class Tuesday, March 1 (and have not reached out to me regarding issues), you will receive an automatic deduction of 10 points from your grade.