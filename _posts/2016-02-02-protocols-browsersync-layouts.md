---
layout: post
title:  February 2, 2016 - Protocols, Browsersync, Fluid & Fixed
date:   2016-02-02
permalink: lesson-05/
---

## Lesson Plan

1. Review and test out using Emmet
2. Discuss web protocols
3. Discuss normalize.css and browser resets
4. Introduce Browser-sync
5. Class activity

### Emmet

During Thursday's class I introduced a way to quickly write HTML code.  I've created a resource about this, and linked it from our resources page.  I've also created a one-page guide for you about using Emmet.  Let's take a look at this and try it out.

### Web Protocols

How many people were having difficulties embedding their Codepens?  Does anyone have any idea why?

The current standard for designing and developing websites is to deliver your content using HTTP.  This is quickly changing, and even Google now is giving a better page rank to pages that have an HTTPs delivery.

"HTTPS (Hypertext Transfer Protocol Secure) is an internet communication protocol that protects the integrity and confidentiality of your users' data between the user's computer and the site. For example, when a user enters data into a form on your site in order to subscribe to updates or purchase a product, HTTPS protects that user's personal information between the user and the site. Users expect a secure online experience when providing data via a website. We encourage you to adopt HTTPS in order to protect your users' connection to your website." [(From Google)](https://support.google.com/webmasters/answer/6073543?hl=en)

Lots of resources below, but if you take nothing else away, know that the **protocol** for serving web content is generally HTTP or HTTPs, and that HTTPs is becoming more widely used and is becoming the industry standard.

- [Protocol Relative URLs](http://billpatrianakos.me/blog/2013/04/18/protocol-relative-urls/)
- [Why Use Protocol Relative URLs](http://stackoverflow.com/questions/28446314/why-use-protocol-relative-urls-at-all)
- [TutsPlus HTTP: The Protocol Every Web Developer Must Know - Part 1](http://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
- [Let's Encrypt](https://letsencrypt.org/)
- [Why Your Site Should Be Using HTTPs](https://www.chapterthree.com/blog/why-your-site-should-be-using-https)


### CSS Resets

Browsers like to apply their own basic styling to HTML elements.  For example, your browser will likely give your H1 tags a larger font size than your H2 tags.  UL list items will have bullets and be intended.

This can be desirable, and allows you to have a launching point when setting up your own styling.  However, one challenge is that elements are not always styled in the same way in different browsers.  Browsers have small inconsistencies when styling elements, and these inconsistencies can cause issues when viewing your pages in different browsers.

Web designers and developers will often utilize a **CSS Reset** to make browsers behave more consistently.  A CSS Reset is a small file that someone (or a group of people) has developed over time that will target browser inconsistencies and even them out, so that your CSS styles will look more similar on different browsers.

The CSS Reset I prefer to use is called [normalize.css](http://necolas.github.io/normalize.css/).  Normalize is nice because it does not strip away styling (some resets will strip all styling, for instance - making `strong` and `em` tags look like normal text).  To use Normalize, you will need to download it from the Normalize website, and then include the CSS file **before** any other stylesheets in your `header`.

** More Information **

- [What is a CSS Reset](http://www.cssreset.com/what-is-a-css-reset/)

### Browser-Sync

One of the reasons we were running into issues before is that when you preview your local files on your computers, your computer is serving the files up through the **file** protocol.  And, since we were trying to get the codepen information over a **Protocol Relative URL**, the url attempted to use the **file protocol** (like your pages were!).

There are a few ways to avoid this.

First, you can host your website on a live web server (for example, upload your files to your Reclaim Hosting space using FTP, and then view them on the internet).

Or, you can set up a **local server**.  There are hundreds of different ways to do this - including installing your own local server using software such as [MAMP](https://www.mamp.info/en/), or just "spinning up" a temporary server using some special code.

**Atom** offers lots of various servers, including a package called **atom-live-server**.  You can install this package and play around with it, if you want.  We are going to use **browser-sync** in this class (we already installed it).

Open a **terminal** window (or a command line window, if you are on Windows).

Navigate to a folder that has an index.html file in it.  To easily do this, drag and drop a folder that has an index.html file in it right on top of your terminal icon.

Now type `browser-sync start --server` (the double - before server is important!).

### Activity

I will hand out instructions for an activity you should work on on your own.  If you finish, please hand the paper back to me, and begin working on the homework below.

### Assignments

**Read**

- [Article about Color Contrast](https://viget.com/inspire/color-contrast)

**Do**

- [Interactive Guide to Blog Typography](http://www.kaikkonendesign.fi/typography/) - Work through each section!

**Look Through**

- [Google Type](http://femmebot.github.io/google-type/)
- [Typekit - Selecting Type for Body Text](http://practice.typekit.com/lesson/selecting-typefaces-for-body-text/)
- [Typekit - USING SHADES for eye-catching emphasis](http://practice.typekit.com/lesson/using-shades/)

**Think**

- What things can I add to my toolkit that will help me to ensure my web content is readable?