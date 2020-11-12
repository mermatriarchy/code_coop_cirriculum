# Week One

Topics Covered: The Internet, Glitch tour, HTML

## Tools

This week we'll use [Glitch](https://glitch.com/) to learn about HTML & do some live-coding. It's free to use & you just need an email account to sign up.

## What is the internet, really?

The internet is basically one big file sharing network. That may be a bit of an oversimplification for what the internet is now, but that's how it started & its basic purpose still shows in the foundations of web development today.

The internet isn't one singular thing -- again, it's a network, so it's made up of a lot of moving parts including servers, routers & cables. It's a network that allows computers to "talk" to one another to share information.

## HTML

- HTML is one of the building blocks of the internet
- It gives a webpage structure
- HTML stands for Hypertext Markup Language
- Markup languages are different than programming languages
- Markup languages give your page structure, programming languages will make your pages interactive & process data (animations, form submissions & the like)
- It's the standard markup language for documents that are displayed on a webpage
- HTML files are saved with the .html extension

### HTML Topics Covered

- Elements & tags
- Common Elements
- Nesting Tags
- Attributes
- Formatting

#### Comments

Comments get their own section because they're important.

One of the most important things you'll learn about coding is to COMMENT YOUR CODE. Comments are text blocks that are not executed as part of your program, so they won't show up on your webpage, but instead allow you to add notes about different parts of the page or your program. They help you & other people understand what your code is supposed to be doing. Not every HTML element needs a comment, but if you end up coding a lot or working as a developer, you'll spend just as much time reading code as you do coding, especially if you're contributing to a big project with lots of other developers, so it's helpful to add a few notes as you go so other people can follow along.

In HTML you write a comment like this:
`<!-- This is a comment! -->`
You open it with the `<!--` & end it with `-->`

An example of how this might be useful is:

```
<!-- begin about html section -->
<section>
    <h2>About HTML</h2>
    <p>Here's some useful information about HTML!</p>
    <ol>
        <li>It's used to structure webpages</li>
        <li>Elements consist of an opening tag and a closing tag</li>
        <li>Browsers will display your content based on which HTML tags you use to mark up your page</li>
    </ol>
    <h3>Want to Learn More?</h3>
    <p>Visit <a href="https://w3schools.com/html/html_intro.asp">W3Schools</a> to read more about HTML.</p>
</section>
<!-- end about html section -->
```

As your HTML blocks get larger & your document gets longer, it's helpful to keep track of where some blocks start & end.

So again, COMMENT YOUR CODE. It's really important.

#### A few tips on structuring your HTML page

Pretty much EVERY HTML document starts & ends with the same basic tags.

Here is the basic DOCTYPE declaration for an HTML file via [W3 Schools](https://www.w3schools.com/tags/tag_doctype.asp):

```
<!DOCTYPE html>
<html>
<head>
<title>Title of the document</title>
</head>

<body>
The content of the document......
</body>

</html>
```

## More Resources

- [W3Schools HTML Docs](https://www.w3schools.com/html/default.asp)
- Harvard CS50 - What is the Internet? on YouTube
- Learn HTML on [codecademy](https://www.codecademy.com/learn/learn-html) (good practice)

## Practice Ideas

- Write a recipe in HTML - use an unordered list for ingredients, an ordered list for steps, start the page with a title, etc
  - If you don't want to write a recipe, write a post about how to do _anything_ you want -- how to build something, how to record music in the studio, how to fix a car -- the idea is to use good semantic HTML
- Start a webpage about yourself with a title and two different sections about you. Use sections to divide up the page, & use the appropriate header tags for each section

## Key Take Aways

- The internet is a big file sharing network
- HTML is a markup language that gives webpages structure
- Format your code properly for easy reading!!
- COMMENT YOUR CODE
