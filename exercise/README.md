<h1>
  <span class="headline">Intro to HTML & CSS Lab</span>
  <span class="subhead">Exercise</span>
</h1>


## Exercise

Build a personal portfolio page using HTML and CSS.

This page should look like a simple professional website - [check out this portfolio page for a guideline](https://seb-bh.github.io/intro-to-html-portfolio-example/). It should help someone quickly understand who you are, what you are learning, and how to contact you.

You will not receive starter code for the page layout. Use the required elements and sections below to plan and build your own version.

---

## Learning Objectives

By the end of this lab, you will be able to:

* Create a complete HTML page
* Use semantic HTML to organize content
* Connect a CSS file to an HTML file
* Style a page using element, class, and ID selectors
* Use basic CSS properties to improve spacing, color, and readability
* Build a small portfolio page from a set of requirements

---

## Requirements

Your page must include the following sections:

1. Header
2. About
3. Skills
4. Projects
5. Contact
6. Footer

---

## Part 1: Header

Create a `header` at the top of the page.

Your header should include:

* Your name
* A short professional title or tagline
* Navigation links

Example tagline ideas:

```text
Junior Web Developer
```

```text
Software Engineering Student
```

```text
Future Front-End Developer
```

Your navigation links should connect to the main sections of the page.

Example section links:

* About
* Skills
* Projects
* Contact

---

## Part 2: About Section

Create an About section.

This section should include:

* A heading
* An image
* A short paragraph about yourself
* One or two sentences about your goal as a developer

Use a `figure` element for the image.

Your image must include an `alt` attribute.

Example ideas to write about:

* Why you are learning web development
* What kind of websites or apps you want to build
* What kind of company or team you hope to work with
* How you want to use technology to solve problems

---

## Part 3: Skills Section

Create a Skills section.

This section should include a list of at least 5 skills.

Example skills:

* HTML
* CSS
* GitHub
* Problem solving
* Debugging
* Reading documentation
* Team communication

Use a `ul` and `li` elements for this section.

---

## Part 4: Projects Section

Create a Projects section.

This section should include at least 3 projects.

Each project should include:

* A project name
* A short description
* One skill used in the project

Use an `article` element for each project.

Your projects can be real or imagined.

Example project ideas:

* A landing page for a local cafe
* A portfolio page for a designer
* A notes page for a coding student
* A homepage for a small Bahrain business
* A simple information page for an event
* A profile page for a professional speaker

---

## Part 5: Contact Section

Create a Contact section.

This section should include:

* An email link
* A GitHub link
* Your location or availability

Example:

```text
Location: Manama, Bahrain
Available for junior developer opportunities
```

Your email should use a [`mailto:` link](https://w3schoolsua.github.io/html/html_links_en.html#gsc.tab=0).

Example:

```html
<a href="mailto:student@example.com">student@example.com</a>
```

---

## Part 6: Footer

Create a `footer` at the bottom of the page.

Your footer should include:

* Your name
* The current year
* A link back to the top of the page

---

## Required HTML Elements

Your HTML must include:

* `header`
* `nav`
* `main`
* `section`
* `article`
* `footer`
* `h1`
* `h2`
* `h3`
* `p`
* `a`
* `ul`
* `li`
* `figure`
* `img`

---

## Required CSS

Your CSS must style the following parts of the page:

### Whole Page

Style the `body` with:

* `background-color`
* `color`
* `font-family`
* `margin`

---

### Header

Style the `header` with:

* `background-color`
* `color`
* `text-align`
* `padding`

---

### Navigation

Style the navigation links with:

* `color`
* `margin`
* `font-weight`

---

### Sections

Style your sections with:

* `background-color`
* `border`
* `padding`
* `margin`

---

### Text

Style at least two heading types.

For example:

* `h1`
* `h2`
* `h3`

Use at least:

* `font-size`
* `color`

---

### Image

Style the image with:

* `width`
* `border`

---

### Links

Style links with:

* `color`

You may also use:

* `text-decoration`

---

## CSS Selector Requirements

Your CSS must include:

* At least 3 element selectors
* At least 2 class selectors
* At least 1 ID selector

Example element selectors:

```css
body {
}

h1 {
}

p {
}
```

Example class selectors:

```css
.card {
}

.subtitle {
}
```

Example ID selector:

```css
#about {
}
```

---

## Challenge Options

Choose at least 3 of the following:

* Add navigation links that jump to each section (remember #id)
* Give each major section a different background color
* Create a styled project card
* Make the footer match the header
* Add a paragraph explaining your developer goals
* Add a `Back to top` link in the footer

---

## Submission

Submit your GitHub repository link.

Your repository should include:

* `index.html`
* `css/style.css`
* `assets/`
