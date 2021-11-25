# HTML Basics
  * All HTML documents must contain `<!DOCTYPE html>` at the beginning of the file.This is called **document type declaration**.
  * The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.
  * The HTML document begins with `<html>` tag and ends with `</html>` tag.
  
  ### Headings
  * HTML headings are defined with the `<h1>` to `<h6>` tags. `<h1>` defines the most important heading. `<h6>` defines the least important heading.
  ```
  <h1>This is heading 1</h1>
  <h2>This is heading 2</h2>
  <h3>This is heading 3</h3> 
  ```

  ### Paragraphs
  * HTML paragraphs are defined with the `<p>` tag.
  ```
  <p>This is paragraph 1.</p>
  <p>This is paragraph 2.</p> 
  ```

  ### Links
  * HTML links are defined with the `<a>` tag.
  ```
   <a href="https://ce.ieu.edu.tr/en">Click here to go my university's website.</a> 
  ```
  * The link's destination is specified in the `href` attribute. 


  ### Images
  * HTML images are defined with the `<img>` tag.
  ```
  <img src="ozanyucel.jpg" alt="github.com/ozanyucell" width="104px" height="142px"> 
  ```
  * The source file (src), alternative text (alt), width, and height are provided as attributes.
  * `px` is basically pixels.

  # Attributes
  * Attributes are used to provide additional information about HTML elements.
  * Every HTML element can have an attribute.
  * Attributes provide additional information about the elements.
  * These must always be provided in the start tag.
  * Some of these are; `src`, `width`, `height`, `alt`, `style`, `lang` (used to define the language of the page), `id`, `class`, `title`, etc.
  
  Here is an example from above:
  ```
  <a href="https://ce.ieu.edu.tr/en">
  ```
  `href` is an attribute here.
  #
  * See you on the next document!