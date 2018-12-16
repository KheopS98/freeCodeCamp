<h1>Getting started with HTML</h1>
<br>
<h3>Modul_1 Notes</h3>
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>MDN HTML Introduction</title>
  </head>
  <body>
    <!--Paragrafs-->
    <p>This is a paragraf</p>
    <em>This Text is empatized italic</em>
    <hr>
    <!--Anatomy of HTML elements
        <opentag>Content</closetag>
        <tagname>ContentM</tagname> ->> opentag + content + closetag == HTML element-->

    <!--Nestings elements
        <strong> tag is like <em> tag but have a semnatic strong importance
        and fost is bold. -->
        
   <p>My cat is <strong>very</strong> grumpy.</p>
   <br>
   <hr>
    <!--Block Elements vs Inline Elements
    Block Elements: start a new line , donsen t matter of elements before or after
    Block Elements: can`t be nasted with inline elemnets but can be nasted with other Block-level Elements
    Block Elements Tags: <div> <p> <form>
    Block Elements: take all avasible with
    Inline Elements: dont start on a new line.
    Inline Elements: cant be nasted with Block-level elements.
    Inline Elements: take only the necessary width
    Inline Elements tags: <span> <img> <em>
    Here is an example:
   -->
   <em>first</em>
   <em>second</em>
   <em>three</em>
   <p>first</p>
   <p>second</p>
   <p>three</p>
   <br>
   <hr>
   
   <!--Empty Elements
      *Not all elemnets follow the pattern of <tagname>Content</tagname>
      *Usually empy elements used to insert/embed something in the document
      *Example of <img src="" alt="" width="" height=""> - don`t have an closing tags
      *Empy Elements are also called void Elements.
    -->
    <p>Lets take an example of who to insert an image in HTML</p>
    <img src="images/firefox.jpg" alt="MDN logo" width="30%" height="30%">
    <hr>
    <br>

    <!--HTML Atributes
        Atributes: contain extra information about the element.
        Atributes should have:
          -A space between it and the element.
          -The atribute name followed by an equal sign.
          -An atribute value between " ".
      -->

    <!--Adding atributes to an element
        Lets take the <a> element witch means "anchor"->>Crate HyperLinks
        <a href=" " title=" " target=" ">
        *href - specify the web adress what we want to link
        *title - can be used as a tooltip
        *target - specify where is this link open(on a new tab? or self tab?)
      -->
   <p>Will make next paragraf an HyperLink</p>
   <p>This links goes to <a href="https://mozilla.org/" title="Mozilla FireFox Home Page" target="_blank">MDS</a></p>
   <hr>
   <br>

    <!--Boolean Atributes
      Are atributes with no value
      They  are perfecty allowed
      Take the disable atribute
    -->
   <input type="text" name="text" value="" disabled="disabled">
   <p>and</p>
   <input type="text" name="text" value="" disabled>
   <input type="text" name="" value="">

    <!--HTML White Space
      - HTML dosen`t care about white space
   -->
   <p>Dogs are silly.</p>
   <p>Dogs
      are
              silly.
   </p>
   <p>They will be displayed the same.</p>
   <hr><br>

   <!--HTML special caracters
    < - &lt;
    > - &gt;
    " - &quot;
    ` - &apos;
    & - &amp;
  -->
  <p>This is a &lt;p&gt;</p>


