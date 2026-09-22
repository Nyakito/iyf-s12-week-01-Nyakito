# DevTools Exploration Assignment

**Date:** 22 September 2026

---

## Website 1 — https://example.com

### 1. What HTML tags are used on the page?

The main page uses the following HTML elements:

* `<html>` — root element
* `<head>` — contains document metadata
* `<title>` — defines the page title
* `<meta>` — provides metadata
* `<body>` — contains the visible page content
* `<h1>` — main heading
* `<p>` — paragraph
* `<a>` — hyperlink

The visible page contains the heading **"Example Domain"**, an explanatory paragraph, and a **"Learn more"** hyperlink.

### 2. What is the page title?

**Example Domain**

### 3. How many headings are there?

There is **1 heading**, which is an `<h1>` element:

`<h1>Example Domain</h1>`

---

## Website 2 — https://developer.mozilla.org

### 1. Find the navigation menu — what tag is it wrapped in?

The navigation menu is wrapped in the semantic `<nav>` element.

The `<nav>` element contains navigation-related links and content.

### 2. How is the search bar structured?

The search functionality is structured using a search form and a search input.

The important elements include:

* `<form>` — used to submit the search
* `<input type="search">` — used to enter the search query

The search bar can therefore be inspected in DevTools by expanding the relevant `<form>` element and examining its child elements.

### 3. What happens when you hover over links?

The links have a CSS `:hover` pseudo-class that defines how their appearance changes when the mouse pointer is placed over them.

The hover effect can be inspected in DevTools by:

1. Selecting a link in the **Elements** panel.
2. Opening the **Styles** panel.
3. Selecting or forcing the `:hover` state.
4. Observing the CSS rules applied to the link.

---

## Website 3 — https://nyakito.github.io

The third website used for this exercise is the **Nyakito Noah portfolio website**. The page contains several sections, navigation links, projects, and a contact form.

### 1. Identify 5 different HTML elements

Five different HTML elements found on the page are:

* `<header>` — contains the page/hero header area
* `<nav>` — contains navigation links
* `<section>` — used to organize major sections of the page
* `<h1>` — contains the main page heading, **"Building the web, one idea at a time."**
* `<p>` — used for paragraph text

Other elements used on the page include:

`<h2>`, `<h3>`, `<a>`, `<form>`, `<input>`, `<textarea>`, `<button>`, `<ul>`, and `<li>`.

The page contains sections such as **"Who I Am," "What I Work With," "Things I've Built,"** and **"Let's Connect."**

### 2. Find a form element and list its inputs

The **Contact** section contains a form with the following fields:

| Field         | HTML element / control                                                 |
| ------------- | ---------------------------------------------------------------------- |
| Your Name     | `<input>` — placeholder: **Enter your name**                           |
| Email Address | `<input>` — placeholder: **[you@example.com](mailto:you@example.com)** |
| Subject       | `<input>` — placeholder: **What's this about?**                        |
| Message       | `<textarea>`                                                           |
| Submit        | `<button>` — **Send Message**                                          |

The form can be inspected in DevTools by locating the `<form>` element and expanding it to view its child input and control elements.

### 3. Screenshot of the Elements Panel

The screenshot below shows the website/form inspection:

![Website 3 screenshot](Images/website%203form%20screenshot.png)

---

## Conclusion

This exercise provided practical experience using browser **Developer Tools** to inspect webpage structure, identify HTML elements, examine forms and inputs, and inspect CSS styling such as the `:hover` state.

It also demonstrated how HTML elements are organized within a webpage and how the browser's **Elements** and **Styles** panels can be used to understand and troubleshoot a website.
