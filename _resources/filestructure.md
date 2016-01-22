---
layout: default
title: File Structure | COM402 | Advanced Web Design and Development
---


<header>
	<h1>File Structure and Naming</h1>
</header>
      	
Organizing your files for this class, and web design in general, is particularly important. Every web page you create will point to other web pages and resources using file paths. If you move files around or rename them, these pointers will break. Broken links are pretty easy to fix, but you’ll save yourself a *lot* of headache in the long run by being organized.



##File Naming

URLs (web addresses) are **case sensitive**, and only understand certain characters.

Allowed Characters:

`
    A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
    a b c d e f g h i j k l m n o p q r s t u v w x y z
    0 1 2 3 4 5 6 7 8 9 - _ . ~
`
Reserved Characters (don’t use):

    ! * ' ( ) ; : @ & = + $ , / ? % # [ ]

Accented letters, non-latin symbols, and the reserved characters should always be avoided.

The most conspicuous thing missing from the list of legal characters is spaces. **Avoid using spaces** in your file and folder names. `dashes-and_underscores` are a great substitute.

When creating a new web site, your first file should always be `index.html`. This is the first file a browser looks for when visiting a web site.

Folder Structure
----------------

Set up your folder structure for this class as follows (We’ll walk through setting this up initially):

    COM402/
    ├── assignments/
    │   ├── 01-assignment-name/
    │   └── 02-assignment-name/
    │        ├── img/
    │        ├── css/
    │        ├── js/
    └── classwork/
        ├── cc01/
        │    ├── index.html
        └── cc02/
    └── notes/
        ├── topic-name/
        └── topic-name/

Note the trailing forward slash `/` at the end is not part of the folder name - it just indicates a folder as opposed to a file.

<ul>
<li>
`assignments/` - each homework assignment or project gets a numbered folder. These are the folders you’ll turn in with each assignment.
</li>
<li>
`classwork/` - a folder where you can create and work on coding challenges.
</li>
<li>
`notes/` - a folder for your own reference. You can put a copy of the syllabus here, or other documents you find useful.
</p>

Character Sets
--------------

All of our HTML files will include a meta tag like this:

    <meta charset="UTF-8">

And all of our CSS files will include this line at the top:

    @charset "UTF-8";

This is a bit of an aside, and you don’t need to know all of the (really boring) details about character sets and text encoding, but I should explain the basic idea since you’ll see this a lot.

At their lowest level, computers handle everything in binary (0s and 1s). But humans read in l

</article>