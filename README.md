# What is CSS Notes

- CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.

- CSS can be used for very basic document text styling — for example changing the color and size of headings and links. It can be used to create layout — for example turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation. 

- CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

- CSS properties have different allowable values, depending on which property is being specified. 

- As there are so many things that you could style using CSS, the language is broken down into modules. You'll see reference to these modules as you explore MDN and many of the documentation pages are organized around a particular module. 
## How to add CSS

- There are three ways of inserting a style sheet:

- External CSS

- Internal CSS

- Inline CSS

- With an external style sheet, you can change the look of an entire website by changing just one file!

- Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

- An external style sheet can be written in any text editor, and must be saved with a .css extension.

- The external .css file should not contain any HTML tags.

- An internal style sheet may be used if one single HTML page has a unique style.

- The internal style is defined inside the <style> element, inside the head section.
  
- An inline style may be used to apply a unique style for a single element.

- To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.


