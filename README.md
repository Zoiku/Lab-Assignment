# Mark Zoiku's Web Development Portfolio

A static, multi-page portfolio created for Ashesi University's Web Development coursework in 2020. It presents a biography, skills, coursework, work experience, projects, and interests.

## View locally

Clone this repository and open `index.html` in a browser. There are no application dependencies, build commands, or backend services.

For an HTTP preview, serve the repository with your editor's static server. Keep the HTML files, `style.css`, and `assets/` together so relative links and images resolve.

## Repository guide

- `index.html`: homepage and biography.
- `skills.html`, `coursework.html`, `workexperiences.html`, `projects.html`, `interests.html`: portfolio sections.
- `style.css`: shared presentation.
- `assets/`: page images.
- `verify_install.sh`: original coursework environment-check script, separate from the website.

The shell script writes tool versions and Git identity information to `setupverify.txt`, or a filename supplied as its first argument. It requires Bash and checks VS Code, Git, Node.js, and npm; those tools are not required to view the website.

## Editing and checking

Edit the HTML and shared stylesheet directly. Open every page after a change and check navigation, image paths, and narrow-screen layout. The repository has no automated test suite.

This is a historical coursework portfolio; the biography reflects the period in which it was written.
