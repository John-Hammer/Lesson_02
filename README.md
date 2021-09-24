# Lesson_02: CSS

Hello class this lesson will focus on Cascading Style Sheets(CSS). This is known as a style sheet language that most commonly used with HTML (Hyper Text Markup Language). This allows a designer to customize the look and feel of a website.<br /> 

HTML is divided into diffent tags \<div>\</div>, \<section>\</section>, \<span>\</span> etc etc, and a lot of these tags do not do anything in themselves (a lot of them do do stuff, but we'll get to learn about that in time), but they do let you target your CSS to it. You can further target specific tags by adding "class" or "id" \<div class="hello">\</div>, \<span id="world">\</span>, \<section class="hello" id="world">\</section>. See the internalexample.html<br /> 

Now your CSS can be get rather long and complicated and in order to keep your html clean it is standard practise to keep your css in an external file (see css/style.css)

Let's talk a little bit about folder structure. If you open your finder(MacOS) or windows explorer (PC) you'll notice a bunch of folders and files. Now when representing folder structure there are two ways. Absolute path, and Relative path. Let's use this project as an example. <br /> 

    -In VS code open Terminal (Top bar > Terminal > new Terminal)
    -Right click on a file on the left side of VS code (ie externalExample.html) and select reveal in finder (macOS) or in windows Explorer (PC).
    -Drag the file over to the newly opened terminal.
    -For MacOS you will see a string like this:
    '/Users/johhamcarlssonsskola.se/Documents/GitHub/Lesson_01/Lesson_02/externalExample.html'
    -For PC you will see this:
    'C:\Users\johhamcarlssonsskola.se\Documents\GitHub/Lesson_01\Lesson_02\externalExample.html'
    -This represents the Absolute Path down from Root(MacOS/Linux/Unix), or your drive letter(Windows). WE DO NOT USE THIS WHEN DOING PROJECTS.
    
    Relative file path works like this, from the path of the file that I am looking at. so if we look at externalExample.html I am referencing style.css in the css folder. 
    <link rel="stylesheet" href="css/style.css"> If my websites where in a folder called html I would do this.
    <link rel="stylesheet" href="../css/style.css">
    Those two dots tell the the computer to go back one folder then look for the files.

Now saying all of this there are massive CSS libraries that we can use for our site that can do some really interesting things with standart class names, so that we do not have to create everything from scratch. <a href="https://getbootstrap.com/" target="_blank">Bootstrap</a> is such a library, now let's plug it into our webstie<br /> 

    Create a new folder called bootstrap.
    Go to getbootstrap.com, select Download > select the download button under "Compiled CSS and JS"
    Extract the files and copy the css and js folders to your project root folder.
    In a new website link 
    <link rel="stylesheet" href="bootstrap/css/bootstrap.css">
    <script type="text/javascript" src="bootstrap/js/bootstrap.js"></script>

Then you can copy examples over from bootstraps website and modify your site accordingly. 

Next lesson we will take a template and actually build a real website.