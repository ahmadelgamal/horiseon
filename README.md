# Code Refactor Starter Code

## Developer:
Ahmad El Gamal

## Deployment URL:
https://ahmadelgamal.github.io/horiseon/

## GitHub repository URL:
https://github.com/ahmadelgamal/horiseon/

## Scope:
This project is the Week 1 Challenge at the UC Berkeley Extension, full-time, blended, coding bootcamp.

## Project Description:
This week's assignment is to take existing code and:
1. Make the codebase follow **accessibility standards**.
2. Apply the **Scout Rule** to it.
So that the site is optimized for seach engines.

## Acceptance Criteria:
GIVEN a webpage meets accessibility standards:
1. WHEN I view the source code
   THEN I find semantic HTML elements | **DONE**
2. WHEN I view the structure of the HTML elements
   THEN I find that the elements follow a logical structure independent of styling and positioning | **DONE**
3. WHEN I view the image elements
   THEN I find accessible alt attributes | **DONE**
4. WHEN I view the heading attributes
   THEN they fall in sequential order | **DONE**
5. WHEN I view the title element
   THEN I find a concise, descriptive title | **DONE**

## Screenshot of Mock-UP:
![Screenshot of Mock-Up](./assets/images/01-html-css-git-homework-demo.png)

## Remaining work:
1. Check function of `clear: both` declaration under `.benefits` selector.
1. Check font discrepancy, especially in the `h2` elements under `.services` class.
1. Apply **DRY** principle to font selection.
1. Apply some responsive rules because text gets messed up when screen width is under 1,012 pixels.
1. Apply more commenting to index.html.

## Questions for Staff:
1. The demo is missing the footer, so should we assume that it will have the same look as what’s in the original repo (DEVELOP folder)?
1. Are we expected to deploy on GitHub Pages only or another webhost, like GoDaddy?
1. `font-family: ‘Trebuchet MS’, ‘Lucida Sans Unicode’, ‘Lucida Grande’, ‘Lucida Sans’, Arial, sans-serif;`, `font-family: ‘Gill Sans’, ‘Gill Sans MT’, Calibri, ‘Trebuchet MS’, sans-serif;`. Why are `Arial` and `Calibri` not in quotes? Is it because they are each a `font-family` like `sans-serif`? How do we know this when writing future code?
1. Some self closing tags do not have a backslash by default in VS Code, such as `img`. Do I need to manually type it in, or is it good practice to keep it without the backslash?