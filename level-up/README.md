# 🎨 Portfolio Lab: Helpful HTML & CSS Tips

Here are a few tips to help you complete your portfolio. You'll need to decide where and how to use them in your own project!

## 1. 🖼️ Using Images from Your Computer

So far, we've used images from the internet by adding a URL to the `src` attribute.

We can also use images saved inside our project.

For example, imagine we have the following files:

```
portfolio/
├── index.html
├── style.css
└── assets/
    └── cat.jpg
```

To display `cat.jpg` in our HTML:

```
<img src="./assets/cat.jpg" alt="A cat">
```

The `./` tells the browser to start looking in the same folder as our HTML file.

> 💡 Your Turn: You've already added a profile photo to your `assets` folder. Use the example above to display it on your portfolio!

## 2. 🔗 Linking to Sections Using IDs

We can use links to jump to different parts of the same webpage.

First, give an HTML element an `id`:

```
<section id="services">
  <h2>Our Services</h2>
</section>
```

Then create a link using `#` followed by the ID:

```
<a href="#services">View Services</a>
```

Clicking this link takes the visitor directly to the Services section.

> 💡 Your Turn: Give each section of your portfolio a unique ID. Then use those IDs to create your navigation links. Don't forget your Back to Top link!

## 3. 🔗 Removing Underlines from Links

We can remove the default underline from links using CSS:

```
a {
  text-decoration: none;
}
```

We can also add the underline back when someone hovers over a link:

```
a:hover {
  text-decoration: underline;
}
```

## 4. 📋 Removing Bullet Points from Lists

We can remove the default bullet points from unordered lists:

```
ul {
  list-style: none;
}
```

We can also remove the default indentation:

```
ul {
  list-style: none;
  padding: 0;
}
```

## 5. 🎨 Choosing a Color Palette

Not sure which colors to use for your portfolio? Here are four color palettes you can try.

<img width="777" height="644" alt="Screenshot 2026-10-21 at 4 58 42 PM" src="https://github.com/user-attachments/assets/a6d5a593-0a4c-4d87-be63-0e3f5dd39517" />

You can also explore more palettes at [Coolors](https://coolors.co).

> 💡 Your Turn: Choose a color palette for your portfolio. Use the colors for your background, cards, headings, links, and text. Make sure everything is easy to read!

## 🎓 You Do

Use what you've learned to complete your portfolio:

- Display your profile photo from the `assets` folder.
- Make your navigation links jump to the correct sections.
- Add a Back to Top link.
- Customize your links and lists using CSS.
- Choose a color palette and apply it to your website.

Remember, these examples show you how to do something. It's up to you to decide where to use each technique in your portfolio!
