<h1>
  <span class="headline">Portfolio Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

In this lab, you will create a personal portfolio page using HTML and CSS.

Your portfolio should introduce who you are, what you are learning, and how someone could contact you.

By the end of this setup, you should have:

* A project folder named `portfolio-page`
* An `index.html` file
* A `css/style.css` file
* An `assets` folder for your image
* HTML connected to CSS

---

## Create the project folder

In your terminal, move into the folder where you keep your labs.

Then run:

```bash
mkdir portfolio-page
cd portfolio-page
```

---

## Create the project files

Run:

```bash
mkdir css assets
touch index.html css/style.css
```

Your project should look like this:

```text
portfolio-page/
├── index.html
├── css/
│   └── style.css
└── assets/
```

---

## Open the project in VS Code

Run:

```bash
code .
```

---

## Add a profile image

Add an image to your `assets` folder.

You may use:

* A photo of yourself
* An avatar
* A placeholder image

Rename the image to:

```text
profile-photo.jpg
```

> 💡 If your image has a different file type, like `.png`, make sure your HTML uses the correct file name.

---

## Set up your HTML file

In `index.html`, add the basic HTML boilerplate.

Make sure your CSS file is connected inside the `head`.

Example file path:

```html
<link rel="stylesheet" href="./css/style.css">
```

---

## Test your setup

Add a test heading inside the `body`:

```html
<h1>Portfolio Page</h1>
```

Then add this test CSS inside `css/style.css`:

```css
body {
  background-color: red;
}
```

Open `index.html` in the browser.

You should see:

* The heading on the page
* A light gray background

If the background color appears, your CSS is connected correctly.

