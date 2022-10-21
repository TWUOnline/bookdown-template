# About this Site

This is a minimal example of a course site based on R Markdown and **bookdown** (<https://github.com/rstudio/bookdown). Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" for how to compile this example into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here <https://bookdown.org/yihui/bookdown/build-the-book.html>.

[You can find the preview of this example here.](https://twuonline.github.io/bookdown-template)

## Benefits of Bookdown for hosting course sites

- All of your course content is composed in plain text files and styled with Markdown, making your course materials highly interoperable with multiple web applications.
- Your course content is in a decentralized version control system meaning that all changes are tracked and conflicts, if they arise, are managed manually. This means that you, as the author of your content, can determine which content to keep in the event of conflicting updates.
- You are able to edit your course files locally (offline, on your own computer), then syncronize when you are ready and have online access.
- You have the option of rendering your content in a variety of formats, giving you flexibility in how you share your content. Commons formats include HTML, PDF, MS Werd, ePub, and the original Markdown files. This can allow you to send your course as a single file through email, allow users to download the file for offline use, and keep snapshots of different versions of your course.
- Collaboration is built-in to the GitHub workflow, so if you are working with a team, everyone has access to the most up-to-date version of the content.
- GitHub has robust and improving project management tools including issues and highly customizable projects with embedded metadata such as labels, milestones, the ability to assign issues, task lists, and the ability to create custom metadata fields.
- Markdown files are inherently more accessible because everything is tagged with a style, rather than having text formats applied to mimic styles.
- Your course site comes with accessibility tools allowing users to customize their own experience (light and dark themes, text size, text style)
- Ability to embed multi-media directly from popular sites like YouTube and Vimeo, but also indirectly through embedly.com.
- You are able to embed your course book in other web tools such as learning managememnt systems or WordPress.
- Host your course site for free with Github Pages.
- Host private course sites (your site is only accessible to members of the repository) if you have a Pro, Team, Enterprise Cloud, or Enterprise Server account.
- [Inline or blocked LaTeX](https://bookdown.org/yihui/bookdown/markdown-syntax.html#math-expressions) equations are supported.
- [Embed R code chunks or inline R code](https://bookdown.org/yihui/bookdown/r-code.html#r-code) to create dynamic, automatically-updating tables and figures.


## Using this Template

You are free to use this site as a template to build your own course site using Bookdown. There is some work up front, but we have found the payoff to be significant.

### Requirements

- A GitHub account
  - If you are using a free GitHub account, you will only be able to create a public repository and site.
- Working knowledge of creating content formatted in Markdown, or a willingness to learn...it's pretty easy.
- Basic knowledge of how to use GitHub for version control.
- Current version of [R](https://cran.r-project.org/) and [RStudio Desktop (Open Source Edition)](https://www.rstudio.com/products/rstudio/).
  - Note that you don't need to know or learn any R programming to use this template. You will need to install a couple of plugins, and be able to click a button every once in a while.

### Recommendations

- [GitHub Desktop](https://desktop.github.com/)
- [Good] a plain text editor (NotePad, TextEdit, Typora...)
- [Better] a plain text editor that has built-in Git functionality (VSCode, Atom)

### Clone the Template

![Screenshot of the green 'Use this template' button in GitHub.com](assets/readme/clone.png)