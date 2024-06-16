+++
title = 'Interactive websites without javascript'
date = 2024-06-16T17:19:59+02:00
draft = false
+++

### What is "hypermedia-driven"?
"Hypermedia-driven" refers to the traditional way of serving only HTML to the client.
The advantage is that it's lighter weight than JavaScript, and any significant changes are handled by the server instead of the client.

## What's the benefit to *me* as a developer?

- It's very easy to use.
- You can set up "templates" instead of using JavaScript for the rendering part.
- Templates are predefined elements in HTML, such as headings, navigation bars, lists, tables, buttons, etc.
- You can then take any elements you want, assemble them  and send them to the client.
- You can focus  on the server part, rather than learning and configuring the front-end in a whole other language.

There's one more small drawback, but it has an easy solution: Server-side rendering can't serve dynamic content. This was a common problem solved by **HTMX**.

### HTMX 

HTMX is a JavaScript library that allows developers to replace only parts of a website without reloading the site.
Furthermore, it allows users to manipulate any class in the HTML, not just forms and hrefs.

### Tailwind CSS 
Now for styles. There are many CSS frameworks available, such as Tailwind CSS.
The advantage of Tailwind CSS is that it allows you to style  elements in HTML.
When you launch Tailwind CSS, it will automatically generate the CSS for you and remove unnecessary classes from the HTML  if necessary.

## Overview 
This "stack" makes it extremely easy to code and deliver interactive, great looking websites, even if you have no idea how JavaScript works.
I myself have used it in a university software project, with Python Fast API on the backend and HTMX, Tailwind CSS and Daisy UI on the frontend, with good results.
> https: //openscience.sakura.pm 

####  *References* 
> https://htmx.org,
> https://hypermedia.systems 
> https://tailwindcss.com
> https://daisyui.com
