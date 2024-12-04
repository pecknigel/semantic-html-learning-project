**This project is a working draft. It is not complete. Please make use of it. Feedback is appreciated.**

# Semantic HTML Learning Project

This is a learning project to learn semantic HTML elements, along with some light CSS.

You are provided with a template that you implement in HTML along with the supporting CSS.

Guidance is provided on what elements and CSS to use to achieve it.

## Getting Started

If you are totally new, or just to maybe learn something new, check out the Getting Started Modules from MDN Curriculum:

- [1. Soft Skills](https://developer.mozilla.org/en-US/curriculum/getting-started/soft-skills/)
- [2. Environment Setup](https://developer.mozilla.org/en-US/curriculum/getting-started/environment-setup/)

If you are new to HTML and CSS, you should probably look at the following resources before getting in to semantic HTML:

- [MDN Web Docs: Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)
- [MDN Curriculum: Core Modules: 1. Web Standards](https://developer.mozilla.org/en-US/curriculum/core/web-standards/)

## Semantic HTML Elements

### Layout

The following semantic HTML elements should be used:

- main
- header
- footer
- section
- article
- aside
- nav
- menu

At the top level, a page can have a `header`, `main` and `footer`. The `main` element should contain the main content of the page, with the header and footer outside of it.

The `main` part of the page can contain `section` and `article` elements to contain different part of the page, or simply have all the content within `main` (if there is only a single topic or point).

Each section or article can have its own `header` and `footer` elements.

Along with the primary content separated into `section` and `article` elements, you can also have `nav` and `aside` elements to contain navigation and side content.

For menu lists, you can use the `menu` element instead of `ul`. It works exactly the same except with the extra semantics of being a menu.

### Headings

You should make use of heading elements. The six available heading elements are:

- h1
- h2
- h3
- h4
- h5
- h6

Every page should have a `h1` describing the primary topic of the page, followed by `h2`, `h3`, etc. as appropriate for sections within the page.

You will usually have a heading element at the top of each `header`, `section` or `article`.

### Further Learning

Check out our [class notes for Semantic HTML](https://docs.prescriptionfree.academy/class-notes/semantic-html) to find a comprehensive set of resources covering this topic.

- [MDN Curriculum: Core Modules: 2. Semantic HTML](https://developer.mozilla.org/en-US/curriculum/core/semantic-html/)
- [MDN Web Docs: Glossary: Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [Semrush: Semantic HTML5 Guide](https://www.semrush.com/blog/semantic-html5-guide/)
