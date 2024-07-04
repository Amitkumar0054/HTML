# HTML   Notes
![html](https://github.com/Amitkumar0054/HTML/assets/128821680/b5a6de80-4a0d-4c94-9340-e1c3e9d68ef0)
                                                                 

# Table of contents

1. [What Is HTML](#what-is-html)
2. [Install Up VsCode](#install-Up-VsCode)
3. [First Html File](#first-html-file)
4. [HTML Tag](#html-tag)
5. [Basic HTML Page](#basic-html-page)
6. [Quick Points](#quick-points)
7. [Comments in HTML](#comments-in-html)
8. [HTML is NOT case sensitive](#html-is-nOT-case-sensitive)
9. [Basic HTML Tags](#basic-html-tags)
10. [Heading Tag](#heading-tag)
11. [Paragraph Tag](#paragraph-tag)
12. [Anchor Tag](#anchor-tag)
13. [Image Tag](#image-tag)
14. [Br Tag](#br-tag)
15. [Bold, Italic & Underline Tags](#bold-italic--underline-tags)
16. [Big and Small Tags](#big-small-tags)
17. [Hr Tag](#hr-tag)
18. [Page Layout Techniques](#page-layout-techniques)
19. [Revisiting Anchor Tag](#revisting-anchor-tag)
20. [Revisiting Image Tag](#revisiting-image-tag)
21. [Div Tag](#div-tag)
22. [List Div Tags](#list-div-tags)
23. [Tables in HTML](#tables-in-html)
24. [Select](#select)

# What Is HTML
 >Hyper Text Markup Language
HTML is the code that is used to
structure a web page and its content.
The component used to design the
structure of websites are called HTML tags.



# Install Up VsCode
- Step 1:- Search on Google or Chrome Download VsCode.
- Step 2:- click on the first link.
  
  - VsCode Download :-
  ![vs](https://github.com/Amitkumar0054/HTML/assets/128821680/73206f39-def8-4382-a62b-87852b84cbe3)

  


- Step 3:- After completion VS Code, Check your download Folder.
- Step 4:- Open Terminal in Linux or  for shortcut click (ctrl + alt + t)
- Step 5:- Check if the system up-to-date using following command :

    
                $ sudo apt update
- Step 6. After update system Now you can Install VS Code using the following command:

  
           $ sudo apt install vscode 

- Step 6. Open VS Code.          





   ![1](https://github.com/Amitkumar0054/HTML/assets/128821680/f181bcca-9f45-47e6-beda-5356498ac1b9)


- Step 6:- Create a new file.


# First Html File

              index.html


 - It is the default name for a website's homepage 

# HTML Tag            
- A container for some content or other HTML tags

           p> This is a paragraph </p>
            Note Point
            p   ----> Element
         This is a paragraph ---> Content   
# Basic HTML Page
              
                 <!DOCTYPE html>                       tells browser you are using HTML5
                    <html>                             root of an html document
                       <head>
                                                       container for metadata
                      <title>My First Page</title>
                                                       page title
                        </head>
                             < body>
                                <p>hello world</p>
                              </body>
                     </html>
                                                      contains all data rendered by the browser
                                                   

#  Quick Points

- Html tag is parent of head & body tag
- Most of html elements have opening & closing tags
- We can use inspect element/view page source to edit html



#  Comments in HTML
- This is part of code that should not be parsed.
-        <!-- This is an HTML Comment -->

#  HTML is NOT case sensitive

                       <html> = <HTML>
                        <p> = <P>
                       <head> = <HEAD>
                       <body> = <BODY>

#     Basic HTML Tags      

- `<html>`: Defines the root of an HTML document.
- `<head>`: Contains metadata about the document, like its title.
- `<title>`: Sets the title displayed in the browser tab.
- `<body>`: Encloses the main content visible on the web page.
- `<h1>` to `<h6>`: Headings of varying sizes.
- `<p>`: Paragraphs of text.
- `<a>`: Creates hyperlinks to other web pages or resources.
- `<img>`: Embeds images into the page.
- `<ul>` and `<ol>`: Create unordered and ordered lists, respectively.


#  Heading Tag
- Used to display headings in HTML
- h1                    (most important)
- h2
- h3
- h4
- h5
- h6                      (least important)

#  Paragraph Tag
- Used to add paragraphs in HTML
- <p> This is a sample paragraph </p>

#  Anchor Tag

- Used to add links to your page
-     <a href="https://google.com"> Google </a>

# Image Tag    

- Used to add images to your page
 
         <img src="/image.png" alt="Random Image">

#  Br Tag
- Used to add next line(line breaks) to your page
-     <br>

#  Bold, Italic & Underline Tags

- Used to highlight text in your page
-              <b> Bold </b>
               <i> Italic </i>
               <u> Underline </u>

#    Big & Small Tags
- Used to display big & small text on your page
-              <big> Big </big>
             <small> Small </small
#  Hr Tag
- Used to display a horizontal ruler, used to separate content
-     <hr>
#   Page Layout Techniques

- using Semantic tags for layout
- using the Right Tags
-     <header>
      <main>
      <footer>

#  Revisiting Anchor Tag
      
      <a href="img.jpg"></a>
      
#  Revisiting Image Tag  

      <img src="link" height=50px set height>
                                 
      <img src="link" width=50px set width>
                                  

#  Div Tag
- Div is a container used for other HTML elements
- Block Element (takes full width)

##  List Div Tags
      <address>       <fieldset>      <nav>
      <article>       <figcaption>    <noscript>
      <aside>          <figure>        <ol>
      <blockquote>     <footer>        <p>
      <canvas>         <form>         <pre>
      <dd>             <h1>-          <h6>  
      <dl>            <header>       <table>
      <dt>             <li>           <ul>
        <main>          <video>         <section>

# Tables in HTML      

- Tables are used to represent real life table data.
- <tr>used to display table row
- <td>used to display table data
- <th>used to display table header
### Tables in HTML
      <table>
         <tr>
            <th> Name </th>
            <th> Roll No </th>
         </tr>
         <tr>
            <td> Shradha </th>
            <th> 1664 </th>
         </tr>
      </table>

# Select
   <select name="city" id="city">
      <option value="Delhi"> Delhi </option>
      <option value="Mumbai"> Delhi </option>
      <option value="Banglore"> Delhi </option>
   </select>       

# Conclusion 
  - In conclusion, this document has highlighted the key aspects of our project, including its objectives, methodology, and significant findings. Through rigorous analysis and collaborative efforts, we have achieved our goals and provided valuable insights. The implications of our results extend beyond the immediate scope, suggesting avenues for future research and practical applications. We are confident that our work will contribute meaningfully to the field and serve as a foundation for ongoing innovation. Thank you for your time and consideration. We look forward to any questions or discussions regarding our work.   

# Reference Link  
<https://www.w3schools.com/html/>

# Thank You!
