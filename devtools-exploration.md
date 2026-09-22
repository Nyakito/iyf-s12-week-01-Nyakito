DevTools Exploration assignment 

Date: 22 September 2026

**Website 1 — https://example.com**

1. What HTML tags are used on the page?

The main page uses these HTML elements:

<html> — root element

<head> — document metadata

<title> — page title

<meta> — metadata

<body> — visible page content

<h1> — main heading

<p> — paragraph

<a> — hyperlink

The visible page contains the heading “Example Domain”, explanatory paragraph text, and a “Learn more” link.

2. What is the page title?

Example Domain

3. How many headings are there?

There is 1 heading, an <h1> element: “Example Domain.”

**Website 2 — https://developer.mozilla.org**

1. Find the navigation menu — what tag is it wrapped in?

The navigation is wrapped in the semantic <nav> element.

The navigation contains links and navigation-related content. MDN uses semantic navigation markup, and the <nav> element is specifically intended for a section containing navigation links.

2. How is the search bar structured?

The search functionality is structured as a search form containing a search input. In HTML terms, the important structure is:

a search container / search landmark

<form> for submitting the search

<input type="search"> for entering the query

3. What happens when you hover over links (check the styles)?

The links have a dedicated CSS :hover pseudo-class state. When a link is hovered, its CSS can change its visual appearance.

In DevTools, this can be checked by selecting a link, opening the Styles panel, and forcing the :hover state.

**Website 3 — https://nyakito.github.io**

The third website was changed from the KRA iTax site to Nyakito Noah's portfolio site. The live page is accessible and contains multiple semantic sections, a project area, and a contact form. citeturn0view0

1. Identify 5 different HTML elements

Five HTML elements visible in the page structure are:

<header> — page/hero header area

<nav> — navigation links

<section> — major page sections such as About, Skills, Projects and Contact

<h1> — main page heading, “Building the web, one idea at a time.”

<p> — paragraph text used throughout the page

Other elements visible/used include <h2>, <h3>, <a>, <form>, <input>, <textarea>, <button>, <ul> and <li>. The page contains headings for sections such as “Who I Am,” “What I Work With,” “Things I've Built,” and “Let's Connect.” citeturn0view0

2. ### Find a form element and list its inputs

The Contact section contains a form with these fields:

Field

Input/control

Your Name

<input> — placeholder: Enter your name

Email Address

<input> — placeholder: you@example.com

Subject

<input> — placeholder: What's this about?

Message

<textarea>

Submit

<button> — Send Message

The screenshot from the page 

![Website 3 screenshot](Images/website%203form%20screenshot.png)