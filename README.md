# Front End Website Development Educational Assignments

Resources: 

- [Free Code Camp](https://www.freecodecamp.org) / [My Notes for Free Code Camp]

- MDN Web Docs: [Front-end web developer Guide](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer) / [My Notes for MDN Web Docs]

- Web Coding & Development a book by Paul McFedries: [Link to Book here](https://www.paulmcfedries.com/books/book.php?title=web-coding-dev-aio-fd) / [My Notes for Web Coding & Dev Book]

- Full Stack Web Development course by The App Brewery [Link here](https://appbrewery.com/p/the-complete-web-development-course) / [My Notes for Full Stack Web Dev by London App Brewery]

- [CodeCademy](https://www.codecademy.com)'s Front End Engineer Path / [My Notes for Code Cademy]

- [Teaching Notes]

See this repository as a website [here](https://laurenc2022.github.io/web-dev-edu/). 

The purpose of posting educational assignments in a repository is to reference code snippets and completed projects i have done. I expect this repo will help with recall when I am stuck on a simple project or want to quickly remember how code renders on a browser.  

## Free Code Camp 

### Responsive Web Design
#### Section 1
- [Cat Photo App](https://laurenc2022.github.io/web-dev-edu/free-code-camp-assignments/responsive-web-design-assignments/section1/1-cat-photo-app/cat-photo-app-index.html) 
- [Cafe Menu](https://laurenc2022.github.io/web-dev-edu/free-code-camp-assignments/responsive-web-design-assignments/section1/2-cafe-menu/cafe-menu-index.html)
- [Colored Markers](https://laurenc2022.github.io/web-dev-edu/free-code-camp-assignments/responsive-web-design-assignments/section1/3-colored-markers/colored-markers-index.html)
- [Registration Form](https://laurenc2022.github.io/web-dev-edu/free-code-camp-assignments/responsive-web-design-assignments/section1/4-Registration-form/registration-form-index.html)
- [Certification Project 1: Survey Form](https://laurenc2022.github.io/web-dev-edu/free-code-camp-assignments/responsive-web-design-assignments/section1/5-cert-proj-registration-form/survey-form-index.html)
#### Section 2
- [Rothko Painting](https://laurenc2022.github.io/web-dev-edu/free-code-camp-assignments/responsive-web-design-assignments/section2/6-rhothko-painting/rothko-painting-index.html)
- [Photo Gallery](https://laurenc2022.github.io/web-dev-edu/free-code-camp-assignments/responsive-web-design-assignments/section2/7-photo-gallery/photo-gallery.html)
    - **Flexbox:** has a main and cross axis. The main axis is defined by the flex-direction property, which has four possible values:
        - **row:** (default): horizontal axis with flex items from left to right
        - **row-reverse:** horizontal axis with flex items from right to left
        - **column:** vertical axis with flex items from top to bottom
        - **column-reverse:** vertical axis with flex items from bottom to top
        - **Note:** The axes and directions will be different depending on the text direction. The values shown are for a left-to-right text direction.
    - The flex-wrap property determines how your flex items behave when the flex container is too small. nowrap (default) will prevent your items from wrapping and shrink them if needed
    - The justify-content property determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them.
    -  The align-items property positions the flex content along the cross axis. In this case, with your flex-direction set to row, your cross axis would be vertical

    - Step 16: Give your .gallery selector a padding property set to 20px 10px to create some space around the container.
        - Then, give it a max-width of 1400px and add a margin of 0 auto to center it
    - Rather than setting each aspect ratio individually, you can use the object-fit property to determine how images should behave.
        - Give your .gallery img selector the object-fit property and set it to cover. This will tell the image to fill the img container while maintaining aspect ratio, resulting in cropping to fit Try the different values to see how they affect the layout.
    - The gap CSS shorthand property sets the gaps, also knowns as gutters, between rows and columns. The gap property and its row-gap and column-gap sub-properties provide this functionality for flex, grid, and multi-column layout. You apply the property to the container element

    -Step 20: The ::after pseudo-element creates an element that is the last child of the selected element. You can use it to add an empty element after the last image. If you give it the same width as the images it will push the last image to the left when the gallery is in a two-column layout. Right now, it is in the center because you set justify-content: center on the flex container.

        Code Snippet: .container::after {
            content: "";
            width: 860px;
        }

When you are done, set an explicit flex-direction of row on the .gallery element.
- Nutrition Label
- Building a Quiz 
- Certification Project 2: Tribute Page

## MDN Web Docs

### Semantics and structure with HTML
#### Introduction to HTML 
- Getting Started with HTML 
    - [Practice Browser Output](https://laurenc2022.github.io/web-dev-edu/mdn-web-docs/intro-to-html/1-getting-started-with-html/title-example.html)
- What's in the Head? Metadata in HTML
    - [Practice Browser Output](https://laurenc2022.github.io/web-dev-edu/mdn-web-docs/intro-to-html/2-whats-in-th-head-metadata-in-html/meta-example.html)
- HTML Text Fundamentals 
    - [Practice Browser Output](https://laurenc2022.github.io/web-dev-edu/mdn-web-docs/intro-to-html/3-html-text-fundamentals/text-start.html)
        - Test your skills: HTML text basics 
            - [Practice 1](https://laurenc2022.github.io/web-dev-edu/mdn-web-docs/intro-to-html/3-html-text-fundamentals/test-your-skills/basic-text1-download.html): Practice with html paragraph and semantic headings 
            - [Practice 2](https://laurenc2022.github.io/web-dev-edu/mdn-web-docs/intro-to-html/3-html-text-fundamentals/test-your-skills/basic-text2-download.html): Practice with 
            - [Practice 3](https://laurenc2022.github.io/web-dev-edu/mdn-web-docs/intro-to-html/3-html-text-fundamentals/test-your-skills/basic-text3-download.html): Practice with strong importance and emphasis, **semantic elements** 

## Web Coding & Development a book by Paul McFedries

IMPORTANT:
- [Link to Code Source](https://www.paulmcfedries.com/webcodingfordummies/) 
- Web Coding & Development a book by Paul McFedries: [Link to Book here](https://www.paulmcfedries.com/books/book.php?title=web-coding-dev-aio-fd). 
- [The Webdev Workshop by Paul McFedries](https://webdev.mcfedries.com)
- Below is my playground. I use this code for educational purposes only. All code here is openly avaliable at the "Link to Code Source" above and at The Webdev Workshop by Paul McFedries. In the below code, I may or may not have altered the original text by Paul McFedries for learning purposes only. Please see book, Link to Code Source and WebDev Workshop by Paul McFedries for more information.  

### Book 2: Coding the Front End, Part 1: HTML & CSS
#### Chaper 3: Sizing and Positioning Page Elements 
1. Learning About the CSS Box Model: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/1-pg104-learning-about-the-css-box-model.html)

    - Padding: space around the content within the box
    - Margin: Space outside of the border seperating the box from other boxes 
    - border: surrounding the box padding and content
 
2. Styling Element Sizes: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/2-pg105-styling-element-sizes.html)
 
    - Block-level elements (ex: header, div) have width of their parent element. Body element width is set to browser's content area 
    - Block element's size is content only, excludes padding, boarders and margins
    - [**Box-sizing: border-box**](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/my-playgrounds/1-box-sizing-my-playground.html) is a CSS property which redefines element's size to include padding, and border 
    - Best practice: set width and heights for all box elements, so nothing is left up to chance and website always looks the way it is designed
    - inline element can be made to behave like a block element
        - Method 1 with CSS: 
            - dispay: inline-block; 
            - gives inline element block related properties, but still is inline 
        - Method 2 with CSS: 
            - display: block; 
            - turns inline elements into block elements, inline element will behave exactly like a box element 

3. Adding Padding: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/3-pg107-adding-padding.html)
4. Collapsing margins ahead! (part one): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/4-collapsing-margins-ahead-p1.html)
5. Collapsing margins ahead! (part two): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/5-Collapsing-margins-ahead-p2.html)
6. Getting a Grip on Page Flow: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/6-Getting-a-Grip-on-page-flow.html)
7. Floating Elements (part one): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/7-floating-elements-p1.html)
8. Floating Elements (part two): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/8-floating-elements-p2.html)
9. Clering your floats (part one): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/9-clering-your-floats-p1.html)
10. Clearing your floats (part two): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/10-clearing-your-floats-p2.html)
11. Collapsing containers ahead! (part one): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/11-collapsing-containers-ahead-p1.html)
12. Collapsing containers ahead! (part two): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/12-collapsing-containers-ahead-p2.html)
13. Collapsing containers ahead! (part three): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/13-collapsing-containers-ahead-p3.html)
14. Using relative positioning: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/14-using-relative-positioning.html)
15. giving absolute positioning a whirl: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/15-giving-absolute-positioning-a-whirl.html) 
16. Trying out fixed positioning: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch3-sizing-and-positioning-page-elements/16-trying-out-fixed-positioning.html)

#### Chaper 4: Creating a Page Layout
    - **There are 4 options for page layout:** Foats, inline blocks, flexbox, CSS grid 

1. Laying Out Page Elements with Floats: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/1-Laying-out-page-elements-with-floats.html)
2. Laying Out Page Elements with Floats (second example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/2-Laying-out-page-elements-with-floats-ex2.html) 
3. Laying Out Page Elements with Inline Blocks: [Link to Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/3-Laying-out-page-elements-with-inline-blocks.html) 
4. Laying Out Page Elements with Inline Blocks (second example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/4-Laying-Out-page-elements-with-inline-blocks-ex2.html)   
5. Setting up the flex container: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/5-Setting-up-the-flex-container.html)        
6. Aligning flex items along the primary axis: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/6-Aligning-flex-items-along-the-primary-axis.html) 
7. Aligning flex items along the secondary axis: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/7-Aligning-flex-items-along-the-secondary-axis.html)
8. Centering an element horizontally and vertically: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/8-Centering-an-element-horizontally-and-vertically.html)
9. Laying out a navigation bar with flexbox: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/9-Laying-out-a-navigation-bar-with-flexbox.html) 
10. Allowing flex items to grow (first example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/10-Allowing-flex-items-to-grow-ex1.html) 
11. Allowing flex items to grow (second example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/11-Allowing-flex-items-to-grow-ex2.html)
12. Allowing flex items to grow (third example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/12-Allowing-flex-items-to-grow-ex3.html)
13. Allowing flex items to grow (fourth example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/13-Allowing-flex-items-to-grow-ex4.html)
14. Allowing flex items to shrink (first example: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/14-Allowing-flex-items-to-shrink-ex1.html)
15. Allowing flex items to shrink (second example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/15-Allowing-flex-items-to-shrink-ex2.html)
16. Allowing flex items to shrink (third example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/16-Allowing-flex-items-to-shrink-ex3.html)
17. Allowing flex items to shrink (fourth example): [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/17-Allowing-flex-items-to-shrink-ex4.html) 
18. Laying content columns with flexbox: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/18-Laying-content-columns-with-flexbox.html)
19. Specifying the grid rows and columns: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/19-Specifying-the-grid-rows-and-columns.html)
20. Creating grid gaps: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/20-Creating-grid-gaps.html) 
21. Assigning grid items to rows and columns: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/21-Assigning-grid-items-to-rows-and-columns.html)
22. Laying content columns with Grid: [Link to My Playground](https://laurenc2022.github.io/web-dev-edu/web-coding-and-development-by-paul-mcfedries/book-two-coding-front-end-p1/ch4-creating-a-page-layout/22-Laying-content-columns-with-Grid.html)

## CodeCademy's Front End Engineer Path 


## If I taught web development:

- Quick Lesson: Note takeing options with ability to run code snippets 
- Quick Lesson: run down of what a repo is and 3 commands to learn to start using it 
- Quick lesson: how to have computer read selected text, the page and turn most webpages into an easy to read format. This allows you to look away if needed to rest your eyes, helps those with learning dissabilities and helps to take notes while progressing through the reading
Quick Lesson: Where to find help and how to google something you know nothing about/ problem solving with google (maybe give a highly technical sentence and have students break down the sentence by work and figure out what it means. Do 1 to 3 examples first). Students will need to be taught where to look for help: forums, MDN docs, CSS Tricks, https://www.w3schools.com or https://devdocs.io, discord groups. 
- Quick lesson: 
- Lesson 6: 
- Using any combination of the resources listed above would be better than using one alone 
- each day's lesson should have summary activities during the lesson and after the lesson. I will summaries to key points for the students and the students will complete an "exit ticket" for sorts to summaries their learning 

### CodeCademy's Front End Engineer Path 
- CodeCademy does a few things well: The content is clearly brocken into sections and lessons. Lessons include readings, videos and active learning materials. **Major key**: Reviews or recaps of information covered is frequent within the lesson and at the end of the lesson. Two books are listed as suggested readings during the course. **Major Key**: Includes check for understanding.
- Part of lesson: Lecture/direct instruction, independent practice, optional assigned reading 
- CodeCademy has all parts of a lesson in one place and is very structured into lesson plans for the user. This is a whole classroom on the internet when completed with the suggested readings. Using Free Code Camp as a warm up would work nicely with CodeCademy and I highly suggest these two for complete beginners. The CodeCademy's Front End Engineer Path is behind a pay wall and cost upwards of $112 a year or a monthly fee to access. Though worth the money, this might not be the best option for someone on a budget. Other free resources listed above are excellent options as well for learning Front End Web development. 

### MDN Web Docs
- MDN does a few things well: The content is thorough. Detailed explanations are given throughout each lesson. Active learning is incorporated. MDN is excellent for students who want to know more and ask why. **Major Key**: Includes check for understanding.
- Part of lesson: textbook reading and independent practice 

### Free Code Camp 
- Free Code Camp does a few things well: Content is easy to start doing without any prior knowledge and no insturctor is required to complete the work. Free Code Camp would be an excellent option as a daily warmup or transition activity for a group who may finish an assignment at different times. Students will need to be taught where to look for help: FCC Forums, MDN docs, CSS Tricks, https://www.w3schools.com or https://devdocs.io. Con: full solutions can be found online
- Part of lesson: warm up 

### Web Coding & Development a book by Paul McFedries
- Web Coding & Development for Dummies does a few things well: Content is explained in a straight forward and applicable way. While no practice problems are given, this is a great textbook resource. Code snippets are provided to use in direct instruction/ teacher lead activity or to use as an example. 
- Part of lesson: textbook reading 