# Practical Work II - Personal Website (FCE)

## Description of your work
This project consists of a personal static website developed with HTML and CSS to document what I have learned in the subject Fundamentals of Infromatical Engineering (FCE).

The website follows the required structure:
- `index.html` is located in the root folder.
- All other pages are located in the `public/` folder:
  - `about.html`, `contact.html`, `net.html`, `degree.html`, `fce.html`, `topic.html`
- A global stylesheet is stored in `css/styles.css` and is shared by all pages.
- All images used on the website are stored in the `images/` folder.
- A CV is included as a PDF file and linked/embedded from the About page.

The website has been deployed using a public GitHub repository and published with GitHub Pages.

## Problems during the development
- **Project structure and paths:** Because `index.html` is in the root folder and the rest of pages are in `public/`, some links and CSS/image paths were initially broken. This was solved by using correct relative paths (for example, `../css/styles.css` from pages inside `public/`).
- **Git workflow rules:** The assignment required a separate push when adding each new HTML page. To follow this rule, commits were organized per page and pushed frequently to keep a clear history.
- **Static contact form limitations:** The contact form had to be created without scripts, so it does not send or store information. The solution was to implement only the HTML form structure with the essential fields.
- **GitHub push/network issues:** During development, some pushes failed due to network connection resets. Retrying the push and checking the remote URL helped to continue uploading changes.

## Conclusions
This practical work helped me understand how to organize a small software project, not only by writing HTML and CSS, but also by respecting a folder archetype and maintaining consistent navigation across multiple pages.