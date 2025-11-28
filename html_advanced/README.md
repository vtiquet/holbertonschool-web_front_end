<div align="center"><img src="https://github.com/vtiquet/holbertonschool-resources/blob/main/image/Holberton-Logo.svg" width=40% height=40%/></div>

# Resources

## Table of Contents :

  - [0. Create your first webpage](#subparagraph0)
  - [1. Structure your webpage](#subparagraph1)
  - [2. The head - meta charset, viewport, title, description, favicons](#subparagraph2)
  - [3. Simple header, main, footer](#subparagraph3)
  - [4. Aside](#subparagraph4)
  - [5. Section](#subparagraph5)
  - [6. Work, News, Testimonial articles](#subparagraph6)
  - [7. Navigation](#subparagraph7)
  - [8. Level 1 headings](#subparagraph8)
  - [9. Level 2 headings](#subparagraph9)
  - [10. Level 3 headings](#subparagraph10)
  - [11. styleguide](#subparagraph11)
  - [12. Paragraphs](#subparagraph12)
  - [13. styleguide paragraphs](#subparagraph13)
  - [14. Span](#subparagraph14)
  - [15. Div](#subparagraph15)
  - [16. Structure your sections](#subparagraph16)
  - [17. Comments](#subparagraph17)
  - [18. link your logo](#subparagraph18)
  - [19. Create new pages](#subparagraph19)
  - [20. Add links](#subparagraph20)
  - [21. Add social media links](#subparagraph21)
  - [22. "Button" links](#subparagraph22)
  - [23. Services, Works, Latest news links](#subparagraph23)
  - [24. List the links](#subparagraph24)
  - [25. Secondary navigation menu](#subparagraph25)
  - [26. Examples of lists for the styleguide](#subparagraph26)
  - [27. Separate content](#subparagraph27)
  - [28. Horizontal rule example](#subparagraph28)
  - [29. Client quotes](#subparagraph29)
  - [30. Examples of quotes](#subparagraph30)
  - [31. Address and latest news authors](#subparagraph31)
  - [32. Typography section - using the correct tags](#subparagraph32)
  - [33. Table](#subparagraph33)
  - [34. Details](#subparagraph34)
  - [35. Replace text logo with image logo](#subparagraph35)
  - [36. Add images to your sections](#subparagraph36)
  - [37. Social icons](#subparagraph37)
  - [38. Add a video player in the styleguide](#subparagraph38)
  - [39. Add an audio player in the styleguide](#subparagraph39)
  - [40. Add a iframe example in the styleguide](#subparagraph40)

## Resources
### Read or watch:
* [HTML 5.2](/rltoken/vKPDYmtKXaKCHn5lpZXz7w)
* [HTML: HyperText Markup Language | MDN](/rltoken/ZSMZYbNUWEhTarg4x5syCQ)
* [HTML Reference - A free guide to all HTML elements and attributes](/rltoken/hPxzkJUCKscaZ1YgG0Xaig)
* [Can I use… Support tables for HTML5, CSS3, etc](/rltoken/C1sjK7n4YYmXjzgN07LgUg)
* [HTML Cheat Sheet - WebsiteSetup](/rltoken/33djKxCai7mwDufKGL7eCg)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
* Which guidelines to follow for HTML
* How to create the skeleton of an HTML5 page
* How to use semantic HTML tags to structure a web page
* Which use cases to usedivvsspan
* The semantic value’s ofheader,main,footer,article,nav,section,aside
* How to use headings (and why it’s important to follow the hierarchical order)
* How to make lists in HTML
* The differences between medias (SVG, GIF, PNG, JPG)
* How to structure data in a table
* How to integrate a video in a webpage
* How to integrate an audio file in a webpage
* How to embed external content
* How to correctly structure an HTML page

## Requirements
### General
* AREADME.mdfile at the root of the folder of the project is mandatory
* Your code should be W3C compliant and validate withW3C-Validator
* Techiumwill be the name of the company we will use across our webpages.

## Task
### 0. Create your first webpage <a name='subparagraph0'></a>

Create your first HTML file <code>0-index.html</code> with:

* Add the doctype on the first line (without any comment)
* After the doctype, open and close a <code>html</code> tag
* Add the language tag, specify English for <a href="/rltoken/qFNHsNpEOoe4uGFKqVa6-Q" target="_blank" title="ISO language code">ISO language code</a> and add the direction tag (ltr or rtl) on the <code>html</code> tag.
* Open your file in your browser (the page should be blank)

<strong>W3C won’t pass - you can ignore it</strong>

---

### 1. Structure your webpage <a name='subparagraph1'></a>

Copy the content of <code>0-index.html</code> into <code>1-index.html</code>

<strong>Create the head and body sections</strong>

* inside the <code>html</code> tag, create the <code>head</code> and <code>body</code> tags (empty) in this order

<strong>W3C won’t pass - you can ignore it</strong>

---

### 2. The head - meta charset, viewport, title, description, favicons <a name='subparagraph2'></a>

Copy the content of <code>1-index.html</code> into <code>2-index.html</code>

<img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2019/11/2ba3a0d7878316de5aaa.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T124114Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=1b7c48ce7b246f0b56149e587cacc967c79892321434f8a84f189a333796e09a" style=""/>

<strong>Meta charset:</strong>

* add a <code>meta</code> tag inside the <code>head</code>:


  * add the <code>charset</code> attribute with the value <code>utf-8</code>

<strong>Viewport:</strong>

* add a <code>meta</code> tag inside the <code>head</code>:


  * add an attribute <code>name</code> on the tag and specify that it is the meta <code>viewport</code>
  * add the key <code>width</code> with the value <code>device-width</code>
  * add the key <code>initial-scale</code> with the value <code>1.0</code>
  * add the key <code>viewport-fit</code> with the value <code>cover</code>

<strong>Title:</strong>

* add the <code>title</code> tag just after the meta viewport with value: <code>Homepage - Techium</code>

<strong>Description:</strong>

* add a <code>meta</code> tag inside the <code>head</code> section


  * add an attribute <code>name</code> on the tag and specify that is the meta <code>description</code>
  * add another attribute called <code>content</code>
  * add the following description: <code>Techium is a digital agency</code>

<strong>Favicons:</strong>

* download the image above to use as a favicon
* Use the tool at <a href="/rltoken/MgBwcigOAB1UoLrRml5XAg" target="_blank" title="https://realfavicongenerator.net/">https://realfavicongenerator.net/</a> to generate all the favicon formats
* take the <code>favicon.ico</code> and <code>favicon.png</code> and place these at the root of your project directory, so that it is siblings with your <code>[0-9]+-index.html</code> files.
* inside the <code>head</code>, create 2 <code>link</code> tags with these 3 attributes: <code>rel</code>, <code>type</code>, and <code>href</code>.


  * the first <code>link</code> tag:


    * rel: <code>icon</code>
    * type: <code>image/x-icon</code>
    * href: <code>./favicon.ico</code>
  * the second <code>link</code> tag:


    * rel: <code>icon</code>
    * type: <code>image/png</code>
    * href: <code>./favicon.png</code>

---

### 3. Simple header, main, footer <a name='subparagraph3'></a>

Copy the content of <code>2-index.html</code> into <code>3-index.html</code>

<strong>Header:</strong>

* create the <code>header</code> of your page between the open and close <code>body</code> tag
* put the text <code>Header</code> inside the header

<strong>Main:</strong>

* create the <code>main</code> tag after the <code>header</code> tag


  * put the text <code>Main content</code> inside your <code>main</code> tags

<strong>Footer:</strong>

* create the <code>footer</code> tag after the <code>main</code> tag


  * put the text <code>Footer</code> inside the <code>footer</code> tags

---

### 4. Aside <a name='subparagraph4'></a>

Copy the contents of <code>3-index.html</code> into <code>article.html</code>

* change the <code>&lt;title&gt;</code> to put: <code>Article - Techium</code>
* inside the <code>main</code> tags


  * after the text, create the <code>aside</code> tags with text <code>Aside</code>

---

### 5. Section <a name='subparagraph5'></a>

Copy the content of <code>3-index.html</code> into <code>5-index.html</code>

* inside your <code>&lt;main&gt;</code> section


  * remove the text in <code>main</code>, create these sections:

<ol>
<li>create first section and put the text <code>Hero section</code> inside</li>
<li>create second section and put the text <code>Services section</code> inside</li>
<li>create third section and put the text <code>Works section</code> inside</li>
<li>create fourth section and put the text <code>About section</code> inside</li>
<li>create fifth section and put the text <code>Latest news section</code> inside</li>
<li>create sixth section and put the text <code>Testimonials section</code> inside</li>
<li>create seventh section and put the text <code>Contact section</code> inside</li>
</ol>

<strong>Does not need to pass W3C</strong>

---

### 6. Work, News, Testimonial articles <a name='subparagraph6'></a>

Copy the content of <code>5-index.html</code> into <code>6-index.html</code>

<strong>Work articles:</strong>

* inside the section <code>Works section</code>

  * add 3 <code>article</code> tags


    * inside each <code>article</code> write <code>Work #</code> where the hashtag will be the ordered number (1, 2, or 3)

<strong>News articles:</strong>

* inside the section <code>Latest news section</code>

  * add 3 <code>article</code> tags


    * inside each <code>article</code> write <code>Article #</code> where the hashtag will be the ordered number (1, 2, or 3)

<strong>Testimonial articles:</strong>

* inside the section <code>Testimonials section</code>

  * add 3 <code>article</code> tags


    * inside each <code>article</code> write <code>Testimonial #</code> where the hashtag will be the ordered number (1, 2, or 3)

<strong>W3C won’t pass - you can ignore it</strong>

---

### 7. Navigation <a name='subparagraph7'></a>

Copy the content of <code>6-index.html</code> into <code>7-index.html</code>

* remove the <code>Header</code> text inside the <code>&lt;header&gt;</code>
* create the <code>nav</code> tag inside the <code>header</code> tag


  * it should remain empty for now

<strong>Does not need to pass W3C</strong>

---

### 8. Level 1 headings <a name='subparagraph8'></a>

Copy the content of <code>7-index.html</code> into <code>8-index.html</code>

* create the level 1 heading inside your <code>main</code> before your sections


  * put text <code>Homepage</code> in your heading tag

<strong>Does not need to pass W3C</strong>

---

### 9. Level 2 headings <a name='subparagraph9'></a>

Copy the content of <code>8-index.html</code> into <code>9-index.html</code>

* in the <code>section</code> tag with the the text <code>Hero section</code>, remove the text and create a level 2 heading with text <code>We help you build your brand!</code>
* in the <code>section</code> tag with the the text <code>Services section</code>, remove the text and create a level 2 heading with text <code>Services</code>
* in the <code>section</code> tag with the the text <code>Works section</code>, remove the text and create a level 2 heading with text <code>Works</code>
* in the <code>section</code> tag with the the text <code>About section</code>, remove the text and create a level 2 heading with text <code>About Us</code>
* in the <code>section</code> tag with the the text <code>Latest news section</code>, remove the text and create a level 2 heading with text <code>Latest news</code>
* in the <code>section</code> tag with the the text <code>Testimonials section</code>, remove the text and create a level 2 heading with text <code>Testimonials</code>
* in the <code>section</code> tag with the the text <code>Contact section</code>, remove the text and create a level 2 heading with text <code>Contact</code>

<strong>W3C won’t pass - you can ignore it</strong>

---

### 10. Level 3 headings <a name='subparagraph10'></a>

Copy the content of <code>9-index.html</code> into <code>10-index.html</code>

<strong>Services headings:</strong>

* Inside the section containing the <code>h2</code> heading <code>Services</code>, add these elements right after the <code>h2</code>:


  * create a level 3 heading with text <code>Design &amp; Concept</code>
  * create a level 3 heading with text <code>Digital Strategy</code>
  * create a level 3 heading with text <code>Content Strategy</code>
  * create a level 3 heading with text <code>UX Design</code>
  * create a level 3 heading with text <code>Web Development</code>
  * create a level 3 heading with text <code>Social Media</code>

<strong>Works headings:</strong>

* Inside the section containing the <code>h2</code> heading <code>Works</code>:


  * in the first <code>article</code>, replace the text with a level 3 heading with text <code>Interior Design</code>
  * in the second <code>article</code>, replace the text with a level 3 heading with text <code>Web Development</code>
  * in the third <code>article</code>, replace the text with a level 3 heading with text <code>Personal Brand</code>

<strong>About Us headings:</strong>

* Inside the section containing the <code>h2</code> heading <code>About Us</code>, after the <code>h2</code> heading, create these elements in this order:


  * a level 3 heading with text <code>Who are we</code>
  * a level 3 heading with text <code>Our culture</code>
  * a level 3 heading with text <code>How we work</code>

<strong>Latest news headings:</strong>

* Inside the section containing the <code>h2</code> heading <code>Latest news</code>:


  * in the first <code>article</code> replace the text with a level 3 heading with text <code>Hoc loco tenere se Triarius non potuit.</code>
  * in the second <code>article</code> replace the text with a level 3 heading with text <code>Ut alios omittam, hunc appello, quem ille unum secutus est.</code>
  * in the third <code>article</code> replace the text with a level 3 heading with text <code>Bestiarum vero nullum iudicium puto.</code>

<strong>W3C does not need to pass here</strong>

---

### 11. styleguide <a name='subparagraph11'></a>

Copy the content of <code>3-index.html</code> into <code>11-styleguide.html</code>

* change the title to <code>Styleguide - Techium</code>
* remove the text from <code>header</code>, <code>main</code>, and <code>footer</code>
* create a new <code>&lt;section&gt;</code> inside your <code>main</code> tag


  * create a <code>header</code> in this <code>section</code>

    * in the <code>header</code> add a level 2 heading with text <code>Headings</code>
  * after the <code>header</code>:


    * add a level 1 heading with text <code>Heading level 1</code>
    * add a level 2 heading with text <code>Heading level 2</code>
    * add a level 3 heading with text <code>Heading level 3</code>
    * add a level 4 heading with text <code>Heading level 4</code>
    * add a level 5 heading with text <code>Heading level 5</code>
    * add a level 6 heading with text <code>Heading level 6</code>

---

### 12. Paragraphs <a name='subparagraph12'></a>

Copy the content of <code>10-index.html</code> into <code>12-index.html</code>

<strong>About Us paragraphs:</strong>

* in the <code>About Us</code> section


  * after the first <code>h3</code> (who are we) create a paragraph with the text: <code>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</code>
  * after the second <code>h3</code> create a paragraph with the text: <code>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</code>
  * after the third <code>h3</code> create a paragraph with the text: <code>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</code>

<strong>Latest news paragraphs:</strong>

* in the <code>Latest news</code> section


  * in the first <code>article</code>

    * create a paragraph with text <code>Career</code> before the heading
    * create a paragraph with text <code>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?</code> after the heading
  * in the second <code>article</code>

    * create a paragraph with text <code>Digital Life</code> before the heading
    * create a paragraph with text <code>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tum mihi Piso: Quid ergo? Tum ille: Ain tandem? Non autem hoc: igitur ne illud quidem. Sed quod proximum fuit non vidit. Nos commodius agimus. An nisi populari fama?</code> after the heading
  * in the third <code>article</code>

    * create a paragraph with text <code>Social</code> before the heading
    * create a paragraph with text <code>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non igitur bene. Quid enim est a Chrysippo praetermissum in Stoicis? Pugnant Stoici cum Peripateticis. Prioris generis est docilitas, memoria; Apparet statim, quae sint officia, quae actiones.</code> after the heading

<strong>Contact paragraph:</strong>

* in the <code>Contact</code> section after the heading


  * create a paragraph with the text: <code>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?</code>

<strong>Additional paragraphs:</strong>

* below the level 2 <code>Services</code> heading add a paragraph with text <code>We work with you</code>
* below the level 2 <code>Works</code> heading add a paragraph with text <code>Take a look in our portfolio</code>
* below the level 2 <code>About Us</code> heading add a paragraph with text <code>Everything about us</code>
* below the level 2 <code>Testimonials</code> heading add a paragraph with text <code>We are more than a digital company</code>
* below the level 2 <code>Contact</code> heading add a paragraph with text <code>We like to know new people</code>

<strong>Does not need to pass W3C</strong>

---

### 13. styleguide paragraphs <a name='subparagraph13'></a>

Copy the contents of <code>11-styleguide.html</code> into <code>13-styleguide.html</code>

* After the existing section containing <code>Headings</code>, create a new <code>section</code> in <code>main</code>

  * in this section create a <code>header</code>

    * Inside the header, create a level 2 heading with text <code>Paragraph</code>
  * after the <code>header</code> add a level 2 heading with text <code>Heading with a subtitle</code>
  * after the level 2 heading, add a paragraph with text <code>This is my subtitle</code>
  * after the last paragraph, add another paragraph with text: <code>Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.</code>

---

### 14. Span <a name='subparagraph14'></a>

Copy the contents of <code>12-index.html</code> into <code>14-index.html</code>

In the very first <code>&lt;header&gt;</code>,

* before the <code>nav</code>, create a <code>span</code> with the text <code>Techium</code>

<strong>Does not need to pass W3C</strong>

---

### 15. Div <a name='subparagraph15'></a>

Copy the contents of <code>14-index.html</code> into <code>15-index.html</code>

* Wrap the contents of the <code>header</code> element with a <code>div</code>
* Wrap the content of each <code>section</code> element within a <code>div</code>
* Finally, wrap the contents of the <code>&lt;footer&gt;</code> tag with a <code>div</code>

<strong>W3C does not need to pass</strong>

---

### 16. Structure your sections <a name='subparagraph16'></a>

Copy the contents of <code>15-index.html</code> into <code>16-index.html</code>

* in the <code>div</code> in the Services <code>section</code>

  * create a <code>header</code> tag that wraps the <code>h2</code> and the <code>p</code>
  * create a <code>div</code> sibling to the <code>header</code> that wraps the rest of the content
* in the <code>div</code> in the Works <code>section</code>

  * create a <code>header</code> tag that wraps the <code>h2</code> and the <code>p</code>
  * create a <code>div</code> sibling to the <code>header</code> that wraps the rest of the content
* in the <code>div</code> in the About Us <code>section</code>

  * create a <code>header</code> tag that wraps the <code>h2</code> and the <code>p</code>
  * create a <code>div</code> sibling to the <code>header</code> that wraps the rest of the content
* in the <code>div</code> in the Latest news <code>section</code>

  * create a <code>header</code> tag that wraps the <code>h2</code>
  * create a <code>div</code> sibling to the <code>header</code> that wraps the rest of the content
* in the <code>div</code> in the Testimonials <code>section</code>

  * create a <code>header</code> tag that wraps the <code>h2</code> and the <code>p</code>
  * create a <code>div</code> sibling to the <code>header</code> that wraps the rest of the content
* in the <code>div</code> in the Contact <code>section</code>

  * create a <code>header</code> tag that wraps the <code>h2</code> and the first <code>p</code>
  * create a <code>div</code> sibling to the <code>header</code> that wraps the rest of the content

<strong>W3C does not need to pass</strong>

---

### 17. Comments <a name='subparagraph17'></a>

Copy the content of <code>16-index.html</code> into <code>17-index.html</code>

* before the <code>header</code> add a line break and a comment saying <code>Header</code> to help with scanning your code
* before the <code>main</code> add a line break and a comment saying <code>Main</code> to help with scanning your code
* before the <code>footer</code> add a line break and a comment saying <code>Footer</code> to help with scanning your code
* before the <code>Hero section</code> add a line break and a comment saying <code>Hero section</code>
* before the <code>Services section</code> add a line break and a comment saying <code>Services section</code>
* before the <code>Works section</code> add a line break and a comment saying <code>Works section</code>
* before the <code>About Us section</code> add a line break and a comment saying <code>About Us section</code>
* before the <code>Latest news section</code> add a line break and a comment saying <code>Latest news section</code>
* before the <code>Testimonials section</code> add a line break and a comment saying <code>Testimonials section</code>
* before the <code>Contact section</code> add a line break and a comment saying <code>Contact section</code>

<strong>Does not need to pass W3C</strong>

---

### 18. link your logo <a name='subparagraph18'></a>

Copy the content of <code>17-index.html</code> into <code>18-index.html</code>

* in the <code>header</code>, wrap the <code>span</code> with a link that redirects to the page at the root of your folder (<code>/</code>)
* wrap the link with a <code>div</code>

<strong>W3C does not need to pass</strong>

---

### 19. Create new pages <a name='subparagraph19'></a>

Copy the content of <code>18-index.html</code> into <code>about.html</code>, <code>latest_news.html</code> and <code>contact.html</code>

* change the title of <code>about.html</code> to replace <code>Homepage</code> with <code>About</code>
* change the title of <code>latest_news.html</code> to replace <code>Homepage</code> with <code>Latest news</code>
* change the title of <code>contact.html</code> to replace <code>Homepage</code> with <code>Contact</code>

<strong>Does not need to pass W3C</strong>

---

### 20. Add links <a name='subparagraph20'></a>

Copy the content of <code>18-index.html</code> into <code>20-index.html</code>

* in your <code>nav</code> tags


  * create a link to <code>/</code> with the text <code>Home</code>
  * create an anchor to <code>services</code> with the text <code>Services</code>
  * create an anchor to <code>works</code> with the text <code>Works</code>
  * create an anchor to <code>about</code> with the text <code>About</code>
  * create an anchor to <code>latest_news</code> with the text <code>Latest news</code>
  * create an anchor to <code>testimonials</code> with the text <code>Testimonials</code>
  * create an anchor to <code>contact</code> with the text <code>Contact</code>

For now, the anchor links will not work. We will make them work in the CSS project.

<strong>Does not need to pass W3C</strong>

---

### 21. Add social media links <a name='subparagraph21'></a>

Copy the content of <code>20-index.html</code> into <code>21-index.html</code>

* in the <code>div</code> in the <code>footer</code>

  * remove any text you have
  * create a link to <code>https://www.facebook.com/HolbertonSchool/</code> with the text <code>Facebook</code>
  * create a link to <code>https://twitter.com/holbertonschool</code> with the text <code>Twitter</code>
  * create a link to <code>https://www.instagram.com/holbertonschool/</code> with the text <code>Instagram</code>

<strong>W3C won’t pass - you can ignore it</strong>

---

### 22. "Button" links <a name='subparagraph22'></a>

Copy the content of <code>21-index.html</code> into <code>22-index.html</code>

* in the Hero <code>section</code>, after the heading


  * create a link to <code>#</code> with the text <code>Get started</code>
* in the About Us <code>section</code>, after the <code>div</code> containing the level 3 headings and paragraphs


  * create a link to <code>about.html</code> with the text <code>Learn more about us</code>
* in the Contact <code>section</code>, after the <code>div</code> containing the paragraph


  * create a link to <code>contact.html</code> with text <code>Get in touch</code>

<strong>Does not need to pass W3C</strong>

---

### 23. Services, Works, Latest news links <a name='subparagraph23'></a>

Copy the content of <code>22-index.html</code> into <code>23-index.html</code>

* in the Services <code>section</code>

  * in each level 3 heading, create a link to <code>#</code> around the text already in the heading
* in the Works <code>section</code>

  * in each level 3 heading, create a link to <code>#</code> around the text already in the heading
* in the Latest news <code>section</code>

  * in each level 3 heading, create a link to <code>#</code> around the text already in the heading

<strong>Does not need to pass W3C</strong>

---

### 24. List the links <a name='subparagraph24'></a>

Copy the content of <code>23-index.html</code> into <code>24-index.html</code>

* in the <code>nav</code>

  * create an unordered list, put each anchor tag (Home, Services, Works, …) as an individual list item
* in the <code>div</code> in the <code>footer</code>

  * create an unordered list and put each anchor tag (Facebook, Twitter, …) as an individual list item

<strong>W3C does not need to pass</strong>

---

### 25. Secondary navigation menu <a name='subparagraph25'></a>

Copy the content of <code>24-index.html</code> into <code>25-index.html</code>

* inside the <code>footer</code>, after the <code>div</code>

  * create a new <code>div</code>
  * in the new <code>div</code> create an unordered list with the following links:

<ol>
<li>link to <code>#</code> with text <code>Terms of Use</code></li>
<li>link to <code>#</code> with text <code>Privacy Policy</code></li>
<li>link to <code>#</code> with text <code>Cookie Policy</code></li>
</ol>

---

### 26. Examples of lists for the styleguide <a name='subparagraph26'></a>

Copy the content of <code>13-styleguide.html</code> into <code>26-styleguide.html</code>

<strong>Example of unordered list:</strong>

* inside <code>main</code> after Paragraph <code>section</code>, add :


  * a new line and a comment with text <code>Lists</code>
  * after, create a new <code>section</code> with inside:


    * create a <code>header</code> with inside a level 2 heading with the text <code>Lists</code>
    * after the new <code>header</code>, create a <code>div</code> with inside:


      * a level 3 heading with text <code>Unordered</code>

        * under it, add an unordered list with these items: <code>Dolor pulvinar etiam magna etiam.</code>, <code>Sagittis adipiscing lorem eleifend.</code>, <code>Felis enim feugiat dolore viverra.</code>

<strong>Example of ordered list:</strong>

* after previous unordered list, in the same <code>div</code>

  * add a level 3 heading with text <code>Ordered</code>

    * add an ordered list with these items:

<ol>
<li><code>Dolor pulvinar etiam magna etiam.</code></li>
<li><code>Sagittis adipiscing lorem eleifend.</code></li>
<li><code>Felis enim feugiat dolore viverra.</code></li>
</ol>

<strong>Example of definition list:</strong>

* after previous ordered list, in the same <code>div</code>

  * add a heading level 3 with text <code>Definition</code>
  * add a definition list with these items:

<ol>
<li>Term: <code>Definition List title</code>, Definition: <code>Definition text.</code></li>
<li>Term: <code>Startup</code>, Definition: <code>A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.</code></li>
<li>Term: <code>Water</code>, Definition: <code>A colorless, transparent, odorless liquid that forms the seas, lakes, rivers, and rain and is the basis of the fluids of living organisms.</code></li>
</ol>

---

### 27. Separate content <a name='subparagraph27'></a>

Copy the content of <code>25-index.html</code> into <code>27-index.html</code>

* in the <code>footer</code> between the two <code>div</code>s:


  * add a horizontal rule
  * after the horizontal rule add a paragraph with text <code>© 2020 Techium, made with ♥ by students at Holberton School.</code>

<strong>W3C does not need to pass.</strong>

---

### 28. Horizontal rule example <a name='subparagraph28'></a>

Copy the content of <code>26-styleguide.html</code> into <code>28-styleguide.html</code>

* in <code>main</code> after Lists <code>section</code>

  * add a new line and a comment with the text <code>Horizontal rule</code>
  * create a new <code>section</code>

    * create a <code>header</code> and inside it add a level 2 heading with the text <code>Horizontal rule</code>
    * after the <code>header</code> create a <code>div</code> and put a horizontal rule in it

---

### 29. Client quotes <a name='subparagraph29'></a>

Copy the content of <code>27-index.html</code> into <code>29-index.html</code>

* in the Testimonials <code>section</code>

  * in the first <code>article</code>

    * replace the text with a blockquote with text <code>I am completely blown away. Thanks to Techium, we've just launched our 5th website!</code> and cite author <code>Yuri Y.</code>
  * in the second <code>article</code>

    * replace the text with a blockquote with text <code>Thank you so much for your help. Techium company is awesome!</code> and cite author <code>Dorrie S.</code>
  * in the third <code>article</code>

    * replace the text with a blockquote with text <code>I love your system. Definitely worth the investment. I'd be lost without Techium company.</code> and cite author <code>Sven H.</code>

<strong>W3C does not need to pass</strong>

---

### 30. Examples of quotes <a name='subparagraph30'></a>

Copy the content of <code>28-styleguide.html</code> into <code>30-styleguide.html</code>

<strong>Example of inline quote:</strong>

* inside <code>main</code> after Horizontal rule <code>section</code>

  * add a new line and a comment with text <code>Blockquotes</code>
  * create a new <code>section</code>

    * in the <code>section</code> create a <code>header</code>, in the <code>header</code> create a level 2 heading with text <code>Blockquotes</code>
    * after the <code>header</code>, create a <code>div</code>

      * in the <code>div</code> add a level 3 heading with the text <code>Inline quote</code>
      * add an inline quote with the text <code>Stay hungry. Stay foolish.</code>

<strong>Example of blockquote:</strong>

* after the inline quote <code>div</code>, create another <code>div</code>

  * in the new <code>div</code> add a level 3 heading with the text <code>Blockquote</code>
  * add a multiline quote with the text <code>I will be the leader of a company that ends up being worth billions of dollars, because I got the answers. I understand culture. I am the nucleus. I think that’s a responsibility that I have, to push possibilities, to show people, this is the level that things could be at.</code> and cite <code>Kanye West, Musician</code>

---

### 31. Address and latest news authors <a name='subparagraph31'></a>

Copy the content of <code>29-index.html</code> into <code>31-index.html</code>

* in the <code>footer</code>

  * right after open <code>footer</code> tag, put the following address: <code>234 Washington Street</code> (line-break) <code>Urbana, Illinois</code>
* in the Latest news <code>section</code>

  * in the first <code>article</code>, after the last paragraph, add the author name in small print: <code>By Kelly D.</code>
  * in the second <code>article</code>, after the last paragraph, add the author name in small print: <code>By William A.</code>
  * in the third <code>article</code>, after the last paragraph, add the author name in small print: <code>By Frances J.</code>

<strong>W3C does not need to pass</strong>

---

### 32. Typography section - using the correct tags <a name='subparagraph32'></a>

Copy the content of <code>30-styleguide.html</code> into <code>32-styleguide.html</code>

* <p>inside <code>main</code> after the Blockquotes <code>section</code></p>

  * add a new line and a comment with text <code>Typography</code>
  * <p>create a new <code>section</code></p>

    * in the section create a <code>header</code> and inside it add a level 2 heading with the text <code>Typography</code>
    * after the <code>header</code> create a <code>div</code>, inside the <code>div</code> add this text with the correct HTML tag: <code>320 Stewart Avenue, Unit 12 (line break) New York City NY 10001</code>, the city, state, and postal code should be on a separate line
    * create another <code>div</code>, in the new <code>div</code> nest this code block using the <code>pre</code> HTML tag:


<pre><code> &lt;code&gt;
     &lt;h2&gt;My title&lt;/h2&gt;
     &lt;p&gt;Proin lacus turpis, feugiat sit amet sollicitudin non, volutpat in libero. Aenean hendrerit ultrices nulla ac lobortis. Vestibulum consectetur nibh vel ante rhoncus faucibus.&lt;/p&gt;
 &lt;/code&gt;
</code></pre>

    * create another <code>div</code>, in the new  <code>div</code> add this paragraph of text with the correct HTML tag: <code>Curabitur sit amet turpis cursus massa mollis highlighted. Duis finibus leo massa, eget dapibus erat finibus sed. Aenean condimentum sapien magna, eleifend highlighted mi consequat ut. Cras nec quam sed sapien ultricies highlighted ut sed metus.</code> Each occurrence of the word <code>highlighted</code> should be highlighted.

<strong>W3C does not need to pass</strong>

---

### 33. Table <a name='subparagraph33'></a>

Copy the content of <code>32-styleguide.html</code> into <code>33-styleguide.html</code>

* inside <code>main</code> after Typography <code>section</code>

  * add a new line and a comment with text <code>Table</code>
  * create a new <code>section</code>

    * in the <code>section</code> create a <code>header</code>, in the <code>header</code> add a level 2 heading with the text <code>Table</code>
    * after the <code>header</code>, create a <code>table</code>, reproduce in HTML the visual below

<img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2019/10/1348f88f2d78a5dee5d0.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T124114Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=24c925117d855b8ea739de970fbd724b85f408d918232ce55337ad3193c84e20" style=""/>

The <code>&lt;th&gt;</code> tags containing <code>Title, Director, Release Date</code> should have a <code>scope</code> attribute set to <code>col</code>
The <code>&lt;th&gt;</code> tags containing the names of the movies should have a <code>scope</code> attribute set to <code>row</code>

<strong>Due to previous task, does not have to pass W3C</strong>

---

### 34. Details <a name='subparagraph34'></a>

Copy the content of <code>33-styleguide.html</code> into <code>34-styleguide.html</code>

* in <code>main</code> tag after Table <code>section</code>

  * add a new line and a comment with text <code>Details</code>
  * create a new <code>section</code>

    * create a <code>header</code>, in the <code>header</code> add a level 2 heading with the text <code>Details</code>
    * after the <code>header</code> create a <code>div</code>

      * in the <code>div</code> add a level 3 heading with text <code>Default</code>
      * add a details element and specify <code>Show/Hide me</code> in the <code>summary</code>
      * add this text after the <code>summary</code>: <code>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</code>
    * create another <code>div</code>

      * add a level 3 heading with text <code>Open</code>
      * add a details element that is open by default and specify <code>Always open</code> in the <code>summary</code>
      * add this text after the <code>summary</code>: <code>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</code>

<strong>Due to earlier task, does not have to pass W3C</strong>

---

### 35. Replace text logo with image logo <a name='subparagraph35'></a>

<img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2019/11/06f32e89f2a82582234e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T124114Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=251d3368fc663dc825df0d684e43b068f7cd579af7d78ea7f72cf66abbf13a21" style=""/>

Copy the content of <code>31-index.html</code> into <code>35-index.html</code>

* in <code>header</code>

  * find the <code>span</code> with the name of the website
  * replace it with the image above
  * make sure the image is in the same directory as all of your other files and that the file name is <code>logo-black.png</code>
  * alt: <code>Techium logo</code>
  * don’t forget to specify width of <code>160</code> and height of <code>40</code>
* in <code>footer</code>, after the opening tag and before the address


  * insert the logo image
  * alt: <code>Techium logo</code>
  * don’t forget to specify the width and height (same as in header)

<strong>W3C does not need to pass</strong>

---

### 36. Add images to your sections <a name='subparagraph36'></a>

Copy the content of <code>35-index.html</code> into <code>36-index.html</code>

You can use image generators to get images for this task. For avatar images you can download them on <a href="/rltoken/3QYgWo4ISo138DbTkldkdg" target="_blank" title="UI Faces">UI Faces</a>. Just make sure you rename your images to match the task requirements.

<strong>Add three images in the Works section:</strong>

* in the Works <code>section</code>

  * before the first level 3 heading create a <code>div</code>

    * add <code>images/pic-work-01.jpg</code> inside the <code>div</code>
    * alt: empty
  * before the second level 3 heading create a <code>div</code>

    * add <code>images/pic-work-02.jpg</code> inside the <code>div</code>
    * alt: empty
  * before the third level 3 heading create a <code>div</code>

    * add <code>images/pic-work-03.jpg</code> inside the <code>div</code>
    * alt: empty

<strong>Add one image in the About Us section:</strong>

* in the About Us <code>section</code> before the first level 3 heading inside the <code>div</code>

  * add the image <code>images/pic-about-us.jpg</code>

    * alt: empty
    * width: <code>460</code>
    * height: <code>447</code>

<strong>Add three images in the Latest news section:</strong>

* in the Latest news <code>section</code>

  * in the first <code>article</code>, before the first paragraph, create a <code>div</code>

    * in the <code>div</code> add the image <code>images/pic-blog-01.jpg</code>
    * alt: empty
    * width: <code>305</code>
    * height: <code>205</code>
  * in the second <code>article</code>, before the first paragraph, create a <code>div</code>

    * in the <code>div</code> add the image <code>images/pic-blog-02.jpg</code>
    * alt: empty
    * width: <code>305</code>
    * height: <code>205</code>
  * in the third <code>article</code>, before the first paragraph, create a <code>div</code>

    * in the <code>div</code> add the image <code>images/pic-blog-03.jpg</code>
    * alt: empty
    * width: <code>305</code>
    * height: <code>205</code>

<strong>Add three images in the Testimonials section:</strong>

* in the Testimonials <code>section</code>

  * in the first <code>article</code> before the quote, add the image <code>images/pic-person-01.jpg</code>

    * alt: <code>Yuri Y. avatar</code>
    * width: <code>100px</code>
    * height: <code>100px</code>
  * in the second <code>article</code> before the quote, add the image <code>images/pic-person-02.jpg</code>

    * alt: <code>Dorrie S. avatar</code>
    * width: <code>100px</code>
    * height: <code>100px</code>
  * in the third <code>article</code> before the quote, add the image <code>images/pic-person-03.jpg</code>

    * alt: <code>Sven H. avatar</code>
    * width: <code>100px</code>
    * height: <code>100px</code>

<strong>Does not need to pass W3C</strong>

---

### 37. Social icons <a name='subparagraph37'></a>

Copy the content of <code>36-index.html</code> into <code>index.html</code> (the final file!)

* <p>inside the <code>footer</code></p>

  * replace the text <code>Facebook</code> with the SVG icon code and add width of <code>25px</code> and height of <code>25px</code> to the SVG tag:


<pre><code>&lt;svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"&gt;
&lt;title&gt;
Facebook icon
&lt;/title&gt;
&lt;path d="M23.998 12c0-6.628-5.372-12-11.999-12C5.372 0 0 5.372 0 12c0 5.988 4.388 10.952 10.124 11.852v-8.384H7.078v-3.469h3.046V9.356c0-3.008 1.792-4.669 4.532-4.669 1.313 0 2.686.234 2.686.234v2.953H15.83c-1.49 0-1.955.925-1.955 1.874V12h3.328l-.532 3.469h-2.796v8.384c5.736-.9 10.124-5.864 10.124-11.853z"/&gt;
&lt;/svg&gt;
</code></pre>

  * replace the text <code>Twitter</code> with the SVG icon code and add width of <code>25px</code> and height of <code>25px</code> to the SVG tag:


<pre><code>&lt;svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"&gt;
&lt;title&gt;
Twitter icon
&lt;/title&gt;
&lt;path d="M23.954 4.569a10 10 0 0 1-2.825.775 4.958 4.958 0 0 0 2.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 0 0-8.384 4.482C7.691 8.094 4.066 6.13 1.64 3.161a4.822 4.822 0 0 0-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 0 1-2.228-.616v.061a4.923 4.923 0 0 0 3.946 4.827 4.996 4.996 0 0 1-2.212.085 4.937 4.937 0 0 0 4.604 3.417 9.868 9.868 0 0 1-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 0 0 7.557 2.209c9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63a9.936 9.936 0 0 0 2.46-2.548l-.047-.02z"/&gt;
&lt;/svg&gt;
</code></pre>

  * replace the text <code>Instagram</code> with the SVG icon code and add width of <code>25px</code> and height of <code>25px</code> to the SVG tag:


<pre><code>&lt;svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"&gt;
&lt;title&gt;
Instagram icon
&lt;/title&gt;
&lt;path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913a5.885 5.885 0 0 0 1.384 2.126A5.868 5.868 0 0 0 4.14 23.37c.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558a5.898 5.898 0 0 0 2.126-1.384 5.86 5.86 0 0 0 1.384-2.126c.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913a5.89 5.89 0 0 0-1.384-2.126A5.847 5.847 0 0 0 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227a3.81 3.81 0 0 1-.899 1.382 3.744 3.744 0 0 1-1.38.896c-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421a3.716 3.716 0 0 1-1.379-.899 3.644 3.644 0 0 1-.9-1.38c-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678a6.162 6.162 0 1 0 0 12.324 6.162 6.162 0 1 0 0-12.324zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405a1.441 1.441 0 0 1-2.88 0 1.44 1.44 0 0 1 2.88 0z"/&gt;
&lt;/svg&gt;
</code></pre>

<strong>W3C does not need to pass</strong>

---

### 38. Add a video player in the styleguide <a name='subparagraph38'></a>

Copy the content of <code>34-styleguide.html</code> into <code>38-styleguide.html</code>

* in <code>main</code> after the Details <code>section</code>

  * add a new line and a comment with text <code>Video</code>
  * create a <code>section</code>

    * in the <code>section</code> create a <code>header</code>, in the <code>header</code> add a level 2 heading with the text <code>Video</code>
    * after the <code>header</code> add the following video: <code>https://intranet-projects-files.s3.amazonaws.com/webstack/BigBuckBunny.mp4</code>
    * add controls to the video
    * ensure that the video does a loop
    * display <code>https://intranet-projects-files.s3.amazonaws.com/webstack/thumbnail.jpg</code> when the video is downloading
    * provide an alternative text: <code>Sorry, your browser doesn't support HTML5 video</code>

<strong>Due to an earlier task, does not need to pass W3C</strong>

---

### 39. Add an audio player in the styleguide <a name='subparagraph39'></a>

Copy the content of <code>38-styleguide.html</code> into <code>39-styleguide.html</code>

* in <code>main</code> after Video <code>section</code>

  * add a new line and a comment with text <code>Audio</code>
  * create a <code>section</code>

    * in the <code>section</code> create a <code>header</code>, in the <code>header</code> add a level 2 heading with the text <code>Audio</code>
    * after the <code>header</code> add the following audio file: <code>https://intranet-projects-files.s3.amazonaws.com/webstack/TroubleChapter8_64kb.mp3</code>
    * add controls to the audio player
    * provide an alternative text: <code>Sorry, your browser doesn't support audio element</code>

<strong>Due to an earlier task, does not need to pass W3C</strong>

---

### 40. Add a iframe example in the styleguide <a name='subparagraph40'></a>

Copy the content of <code>39-styleguide.html</code> into <code>styleguide.html</code>

* in <code>main</code> after the Audio <code>section</code>

  * add a new line and a comment with text <code>Iframe</code>
  * create a <code>section</code>

    * in the <code>section</code> create a <code>header</code>, in the <code>header</code> add a level 2 heading with the text <code>Iframe</code>
    * after the <code>header</code> add a <code>div</code>

      * inside the <code>div</code>, create an <code>iframe</code>

        * title: <code>Holberton School</code>
        * width: <code>350px</code>
        * height: <code>200px</code>
        * source: <code>https://www.youtube.com/embed/41N6bKO-NVI</code>
        * fallback text: <code>Holberton Sally</code>

<strong>W3C does not need to pass</strong>

And you are done!

---


## Authors
vtiquet - [GitHub Profile](https://github.com/vtiquet)
