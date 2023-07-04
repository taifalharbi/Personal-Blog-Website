# Personal Blog Website
This is repo for Personal Blog Website (1st project of Udacity Font End Web Developer Course)
With this project, I have done some rubrics as follow:

## I. Structure
### 1. CSS Separate From HTML
  1. Portfolio completely separates structure from design/style.
  2. There are no attributes present in the body of the document.
  3. There are no elements in the document.
### 2. CSS Imports
There should be at least 3 imported files in the main CSS file, but the student is welcome to break it down even further if that makes it easier for them.
### 3. Directories & Files
Files are organized with a directory structure that separates files based on page and functionality.
### 4. Links
There is an intentional user flow on each page with appropriate links as needed.

## II. Design
### 1. Custom Design
Custom images, layout, and styling.

### 2. Foundations/Building Blocks
- Typography: Custom design for typography with at least 3 unique properties for each typography selector
  - Headers (h1 to h3 at minimum) &lt;h1&gt;
  - Paragraph Text <p>
  - Links <a>
  - Quotes
- Colors: At least 3 colors are used.

### 3. Components
The following are used in the webpage:
- Image(s)
- Image caption
- Buttons
- Card

### 4. Patterns
I have created some pages as follow
- Blog Homepage: (File index.html)
  + Navbar
  + Blog Post Card
    + Card
    + Image
    + Buttons
  + SideBar
    + About me info
    + Recent blog posts
  + Footer
    + Social Sharing
      + LinkedIn
      + GitHub

- Blog Post: (File html/blog-post-Riyadh.html  and html/blog-post-Qatar.html)
  + Header
  + SideBar
    + Author of the post
    + Introduction
  + Main Content
    + Footer
    + Social Sharing
      + LinkedIn
      + GitHub

- About page: same with SideBar in the Home page. (File html/about.html)

- Blog post List: same with list Blog Post Card in the Home page. (File html/blog-post-list.html)

### 5. Pages
The following pages should be present:

- Blog Homepage (File index.html)
- Blog Posts (File html/blog-post-Riyadh.html  and html/blog-post-Qatar.html)
- Blog Posts List page (File html/blog-post-list.html)
- About page (File html/about.html)

## III. Layout
### 1. Flexbox Based Layout
Flexbox was used in two posts: Welcome to Qatar post and Riyadh Tours post and both was setup by blog-post.css

### 2. Grid Based Layout
Grid layout was used in two posts: Welcome to Qatar post and Riyadh Tours post and both was setup by blog-post.css

## IV. Responsiveness
### Multi-Device Web Design
Pages are mobile-friendly and display correctly on all display sizes (mobile, tablet, desktop).

## V. Quality
### 1. Valid HTML
- HTML5 semantic tags such as &lt;header&gt;, &lt;footer&gt;, &lt;article&gt;, &lt;section&gt;, etc. are used to add meaning to the code.
- No div or section selectors are without a CSS class or id.

### 2. HTML Formatting Rules
- All code is lowercase
- The code does not have trailing white spaces.
- Indentation is consistent (2 spaces).
- Code uses a new line for every block, list or table element and indent every such child element (it is acceptable to put all elements in one line).
- When quoting attribute values, code uses consistent quotation marks (single vs. double).

### 3. HTML Style Rules
- HTML documents HTML5 <!doctype html>
- Code omits type attributes for style sheets and scripts.
- [Optional] Code does not use entity references unless necessary e.g. characters with special meaning (like < and &) as well as control or “invisible” characters (like no-break spaces).

### 4. CSS Formatting Rules
- The code does not have trailing white spaces.
- Indentation is consistent (2 spaces).
- Code indents all content, that is rules within rules as well as declarations to reflect hierarchy and improve understanding.
- The code uses a semicolon after every declaration for consistency and extensibility reasons.
- Code always uses a space after a property name's colon, but no space between property and colon, for consistency reasons.
- Code always uses a single space between the last selector and the opening brace that begins the declaration block. Code always start a new line for each selector and declaration.
- Code always put a blank line (two line breaks) between rules.
- Code uses consistent quotation marks for attribute selectors or property values (single vs. double).

### 5. CSS Style Rules
- The code uses meaningful or generic ID and class names that are as short as possible, but as long as necessary.
- The code does not use element names in conjunction with IDs or classes.
- The code uses shorthand properties where possible.
