# Explanations

**.editorconfig**:  
EditorConfig helps maintain consistent coding styles for multiple developers working on the same project across various
editors and IDEs. The EditorConfig project consists of a file format for defining coding styles and a collection of text
editor plugins that enable editors to read the file format and adhere to defined styles. EditorConfig files are easily 
readable and they work nicely with version control systems.

**.eslintrc.js:**
ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making 
code more consistent and avoiding bugs. 

**.gitattributes:**
A gitattributes file is a simple text file that gives attributes to pathnames. In this particular repository,
the purpose of the file is to 'automatically normalize line endings for all text-based files'.

**.gitignore:**
A gitignore file specifies intentionally untracked files that Git should ignore.

**jscsrc:**
JlCSC inter in which WebStorm lets you verify your JavaScript code.

**.travis.yml:**
this file makes use of continuous Integration, which is the practice of merging in small code changes frequently -
rather than merging in a large change at the end of a development cycle. The goal is to build healthier software by
developing and testing in smaller increments. This is where Travis CI comes in.

**CHANGELOG.MD:**
All notable changes to this project are documented in this file,such as bug fixes, new features, etc.

**gulpfile.babel.js:**
Gulp is a tool that helps you out with several tasks when it comes to web development. It's often used to do front end 
tasks like: Spinning up a web server; reloading the browser automatically whenever a file is saved; Optimizing assets 
like CSS, JavaScript, and images. Babel is a transpiler for JavaScript that has the ability to turn ES6 or ES7 into 
code that can run on your browsers and devices.

**LICENSE.txt:**                      
Text file which converys the terms under which the repository is distributed.

**modernizr-config.json:**
Modernizr is a useful JavaScript library to detect user browser capabilities on websites. Command Line Config helps to
automate the process, backed up by a Modernizr NPM module. 

**package.json:**
This file can contain a lot of meta-data about the project. But mostly it will be used for two things:
Managing dependencies of the projectScripts ; Scripts, that helps in generating builds, running tests and other stuff
in regards to the project.

**README.MD:** A README file contains information about other files in a directory or archive of computer software. 
A form of documentation, it is usually a simple plain text file.

**Examining index.html**
<!doctype html> : simplified HTML5 doctype declaration.

<html class="no-js" lang=""> : When Modernizr runs, it removes the "no-js" class and replaces it with "js". This is a
way to apply different CSS rules depending on whether or not Javascript support is enabled.

<head>: The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the
<body> tag.

<meta charset="utf-8">: The charset attribute specifies the character encoding for the HTML document. Apparently, if
the charset isn’t declared within the first 512 bytes of your HTML document, your site is vulnerable to malicious code
and hijacking!. ( 	A character in UTF8 can be from 1 to 4 bytes long. UTF-8 can represent any character in the
Unicode standard. UTF-8 is backwards compatible with ASCII. UTF-8 is the preferred encoding for e-mail and web pages)

<title></title>: The <title> element defines the title of the document, and is required in all HTML/XHTML documents.
The <title> element: defines a title in the browser tab; provides a title for the page when it is added to favorites;
displays a title for the page in search engine results

<meta name="description" content="">: The meta description is a snippet of up to about 155 characters – a tag in HTML:
which summarizes a page's content. Search engines show the meta description in search results mostly when the
searched-for phrase is within the description.

<meta name="viewport" content="width=device-width, initial-scale=1">": Used for responsive site or site for mobile;
It’s basically a message to the mobile browser that says, “Render me differently, I’m designed for mobile screens too!”

<link rel="manifest" href="site.webmanifest">:  
The web app manifest provides information about an application (such as its name, author, icon, and description) in a 
JSON text file. The manifest informs details for websites installed on the homescreen of a device, providing users with
quicker access and a richer experience. Web app manifests are part of a collection of web technologies called
progressive web apps, which are websites that can be installed to a device’s homescreen without an app store, along 
with other capabilities like working offline and receiving push notifications.

 <link rel="apple-touch-icon" href="icon.png">: specifies an icn for the entire websie (every page on the website).

 <!-- Place favicon.ico in the root directory -->: Favicon stands for "Favorites Icon". It's the little icon beside your 
site's name in the favorites list, before the URL  in the address bar and bookmarks folder and as a bookmarked website
on the desktop in some operating systems. This line of code specifies for the favicon to go in the root directory.

 <link rel="stylesheet" href="css/normalize.css">: “Normalize.css makes browsers render all elements more consistently                    
 and in line with modern standards.  It precisely targets only the styles that need normalizing.”

<link rel="stylesheet" href="css/main.css">: The <link> tag defines a link between a document and an external resource.
The <link> tag is used to link to external style sheets.

<meta name="theme-color" content="#fafafa">: Selects the theme color of website.

</head>: Puts an end to the start of <head> explained earlier. 

<body>: The <body> tag defines the document's body.
The <body> element contains all the contents of an HTML document, such as text, hyperlinks, images, tables, lists, etc.

 <!--[if IE]>
    <p class="browserupgrade">You are using an <strong>outdated</strong> browser.
     Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
  <![endif]--> :Informs site visitor that their choice of browser is antiquated/outdated.

 <!-- Add your site or application content here -->: Allows user to input their application content.

 <p>Hello world! This is HTML5 Boilerplate.</p> : Text within a parragraph.

<script src="js/vendor/modernizr-{{MODERNIZR_VERSION}}.min.js"></script>
<script src="https://code.jquery.com/jquery-{{JQUERY_VERSION}}.min.js" integrity="{{JQUERY_SRI_HASH}}" crossorigin="anonymous"></script>
<script>window.jQuery || document.write('<script src="js/vendor/jquery-{{JQUERY_VERSION}}.min.js"><\/script>')</script>
<script src="js/plugins.js"></script>
<script src="js/main.js"></script>: 
Modernizr is a small piece of JavaScript code that automatically detects the availability of next-generation web
technologies in your user's browsers. Rather than blacklisting entire ranges of browsers based on “UA sniffing,”
Modernizr uses feature detection to allow you to easily tailor your user's experiences based on the actual capabilities 
of their browser.
