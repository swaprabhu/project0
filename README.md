# HAPPY BABY AND MOM

   I have designed a website name “Happy baby and mom”. In this website, I am telling about food items for babies from 6 months to toddler.  
	This website contains 5 html pages, 2 css files and one scss file.

### Common  to all Pages
* In all the pages, I have implemented “@media” mobile-responsive query(once the screen size is lesser than 1000px, background image will change), which i have defined in “styles1.css” file.
* Also having CSS selector - “id” and also linked .css file to this page for implementing styling properties.
* I have also used CSS Properties- text-align, border-top-width, border-right-width, border-bottom-width, border-left-width, border-top-style, padding-top, overflow and many others.
* By using “href” I have linked the top of the page by referring an id.
* I have added SCSS file which provides the common font style to all the headers, paragraph, footer, body, which given a CSS file, imported by another CSS file by “@import”

### Main_Page.html
* This is the Primary page of this website, where you can find the purpose of this website. This page contains
* A form with a submit button, one Image with left aligned and the introduction of the website.
* Once click the Submit button, get to another Page “

### Index_page.html
* This page consists of index of foods for various stages of  babies.
* I have implemented ordered list, and some of the CSS properties and CSS selectors.
* I have also linked the 6mTo8m.html, 8mTo12m.html, From_12_months.html pages in this index page.

### 6mTo8m.html
* In this page, I have included 4 additional images, CSS selector “:: selection “ where one can see color change by clicking on the word or sentence.
* Also implemented Bootstrap 4 component - Alert “Success“ and “Danger” in “Don’t Worry!“ and the footer warning.
* I also have used an unordered list. By using “href” I have linked various section inside this page.
* I have used css selector “ul > li”, which applies the specified property of  parents to its immediate child.

### 8mTo12m.html
* In this page, I have used the Bootstrap 4  bordered Table for babies food items.
* Its so interactive when one can point the mouse over the column.
* By changing the class name, one can get another table layout.

### From_12_months.html
In this page I have implemented the following,
* Flexbox grid with Good eater, Moderate eater and Poor eater.
* Styled with different background color, font to be bolded, flex wrap - content will wrap vertically if necessary, so no content is lost when the width of the screen is shrunk.
* Ordered list with its immediate child gets Font color of “#900C3F”. and each class in the ordered list gets different background color which is styled in SCSS.
* Each item in the unordered list gets style, by defining it in the “ID=“list style”.
* In the SCSS file, nesting, inheritance are implemented. and the stylesheet having SCSS variables - $font_size, $font_color, $font_fam.
