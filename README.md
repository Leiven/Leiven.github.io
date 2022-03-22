# How to Host and Format a Resume

A guide on how to host and format a resume using [Markdown](https://www.markdownguide.org/cheat-sheet/), [GitHub pages](https://pages.github.com/), and [Jekyll](https://jekyllrb.com/).

# Getting Started

## Prerequisites
* A [GitHub](https://github.com/) account and a working repository.
* Your resume in [Markdown](https://www.markdownguide.org/cheat-sheet/).
* A [Markdown](https://dillinger.io/) editor.

## Instructions

These instructions will guide you on how to create and host your own Markdown formatted resume on GitHub Pages.

> Etter suggests in their book the use of version control systems such as GitHub for collaborative contributions. This will in turn let developers create documentation and code that are easier to manage for future modifications. For this guide, we are using GitHub as per Etter's suggestion.

    Once you have logged in to GitHub:

1. **Create** a [__new public__ repository](https://github.com/new).
2. **Name** the new repository as `username.github.io` where `username` is your GitHub username.
3. Press the "**Add file**" drop down after creating your new repository.
4. Click "**Create new file**":

![img](https://i.imgur.com/95sauQi.png)

> You will be sent to a new page after clicking the Create new file option.

5. **Name** the new file we created as ``index.md``. 

6. **Click** the **Commit changes** to save the file on our repository.

> This will be the homepage of our GitHub page.

> Now, with our resume in Markdown, 

7. **Copy and paste** our resume to the ``index.md`` file that we have just created with the appropriate [Markdown](https://www.markdownguide.org/cheat-sheet/) formatting.

> As mentioned by [Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) on their book, Markdown is a wonderful and widely used markup language in the world. Markdown is popular and is also used by simple web-based system, such as GitHub pages. Learning Markdown syntax would be very beneficial.

> If we want to add Jekyll styles to our GitHub page that hosts our resume, proceed with the next steps:

8. **Add** another file by clicking **Create new file**.

9. **Name** the new file as ``_config.yml``.
> This file will contain the theme that we would prefer to use on our GitHub page.

10. **Click** the ``_config.yml`` file that we just created.

11. **Click** the pencil icon on the main page to edit the file we just created.

![img](https://i.imgur.com/d0vBkLk.png)

12. **Add** the line "theme: " and then put the preferred style that we prefer. 

> For this guide, we can just **add** the following line: "theme: jekyll-theme-slate"

> As [Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) mentioned in their book, many static site generators exist and Jekyll is one of them. We can use Jekyll to get various designs that we prefer for our static website that will have our resumé.

13. **Click** the **Commit changes** after adding our preferred style to save and update the file on our repository.

14. **Done!** We can now view our hosted resume at `username.github.io`.

![img](https://github.com/Leiven/Leiven.github.io/blob/main/resume.gif?raw=true)

## More Resources
* [Modern Technical Writing: An Introduction to Software Documentation Kindle Edition](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

* [A handy guide](https://www.markdownguide.org/cheat-sheet/) for Markdown formatting.

* [A Jekyll guide](https://jekyllrb.com/) if you want fancier themes and more customized webpage designs.

## Authors and Acknowledgements

**Author**: [Raven Mico Carencia](https://github.com/Leiven/)

**Special Thanks**:

* [Kyle Calinisan](https://github.com/kyl-dc)

* [Scott Jodoin](https://github.com/scottjodoin)

* [Tahmidul Zidaan](https://github.com/thzidaan)

* [Hao Qin](https://github.com/qinh3uofm)

* [PurpleBooth](https://github.com/PurpleBooth/) for the readme template.


## FAQs
* Why is Markdown better than a word processor?

> [Markdown](https://daringfireball.net/projects/markdown/) is very efficient in that it converts plain text formatting into HTML to generate different and diverse content. It makes our writing style transferrable between web pages without having to worry about the processing that a word processor does when switching platforms.

* Why is my resume not showing up?

> * Make sure that your resume is properly formatted in the `index.md` file in the repository.
> * Make sure that your *username*.github.io repository is set to public.
> * There could be a service failure at GitHub Pages. We can check for GitHub status [here](https://www.githubstatus.com/.).
> * There may be delay when GitHub pages update (this usually takes up to 5 minutes).
