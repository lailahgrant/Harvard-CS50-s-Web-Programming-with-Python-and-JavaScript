# Harvard CS50’s Web Programming with Python and JavaScript

> This web programming course from Harvard University picks up where CS50x leaves off. It dives more deeply into the design and implementation of web apps with **Python**, **JavaScript**, and **SQL** using frameworks like **Django**, **React**, and **Bootstrap**.
>
> Topics include `database design`, `scalability`, `security`, and `user experience`.
>
> Will learn how to `write and use APIs`, create `interactive UIs`, and leverage `cloud services` like **GitHub** and **Heroku**.

[💻 Slides, source code, and more at](https://cs50.harvard.edu/web/)

> ✏️ **_Brian Yu_** teaches this course.

## ⭐️ Course Contents

-[x] Introduction
-[x] Lecture 0: HTML, CSS
-[x] Lecture 1: Git
-[x] Lecture 2: Python
-[x] Lecture 3: Django
-[x] Lecture 4: SQL, Models, and Migrations
-[x] Lecture 5: JavaScript
-[x] Lecture 6: User Interfaces
-[x] Lecture 7: Testing, CI/CD
-[x] Lecture 8: Scalability and Security

<hr>

-[x] Lecture 0: HTML, CSS

### Specificity in CSS

> The following shows the order of specificity in CSS from *highest to lowest*.
>
> The order followed for CSS styles to be taken.
>
> - Inline css is considered more than id.

- Inline
- id
- class 
- type

### CSS Selectors

| Selector | Meaning |
| :------- | :---------------------------: |
| a,b      | Multiple Element Selector  |
| a b      | Descendant Selector  |
| a > b    | Child Selector  |
| a + b    | Adjuscent Sibling Selector  |
| [a=b]    | Attribute Selector  |
| a : b    | Pseudoclass Selector  |
| a::b     | Pseudoelement Selector |


### Responsive Design

> Making sure the design is seamless across all devices.
>
> Want websites to adpat to different screens.

- viewport
- Media Queries
- Flexbox
- Grids

#### Viewport

> viewport - the visual part of the screen that the use can actually see.
>
> Meta tag (The meta data) below that can tell a page to change the *viewport* to be specifically the width of the device.
>
> ```<meta name="viewport" content="width=device-width, initial-scale=1.0" />```.

#### Media Queries

> Actual changes made to web pages to make them look better on different screens.
>
> Media Queries are all about controlling how webpages are going to look depending on how they're displayed.
>
> - Media Types: **print**, **screen**, ...
> 
> - Media Features: **height**, **width**, **orientation**, ...


### CSS Variables  -  Sass

- Install Sass on PC
- Use the CSS Variables using Sass
- Compile Sass into CSS
- `sass variables.scss:variables.css`
- Automate the Sass compilation
- `sass --watch sass variables.scss:variables.css`
- Sass allows **Nesting** of styles.