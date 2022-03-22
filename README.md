# How to Host and Format a Resume

A guide on how to host and format a resume using [Markdown](https://www.markdownguide.org/cheat-sheet/) and [GitHub pages](https://pages.github.com/).

# Getting Started

## Prerequisites
* A [GitHub](https://github.com/) account and a working repository.
* Your resume in Markdown.
* A [Markdown](https://www.markdownguide.org/cheat-sheet/) editor.

## Instructions

These instructions will guide you on how to create and host your own Markdown formatted resume on GitHub Pages.

    Once you have logged in to GitHub:

1. **Create** a [__new public__ repository](https://github.com/new).
2. **Name** the new repository as _username_.github.io where *username* is your GitHub username.
3. After the creation of the repository, press the "**Add file**" drop down 
4. Click "**Create new file**":

![img](https://i.imgur.com/95sauQi.png)

> You will be sent to a new page after clicking the Create new file option.

5. Above the big text box, **name** the new file we created as **index.md** 

6. **Click** the **Commit changes** to save the file on our repository.

> This will be the homepage of our GitHub page.

7. Now, we can create our resume by typing it down on the *index.md* file that we have just created with the appropriate [Markdown](https://www.markdownguide.org/cheat-sheet/) formatting.

> As mentioned by [Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) on his book, Markdown is a wonderful and widely used markup language in the world. Markdown is popular and is also used by simple web-based system, such as GitHub pages. Learning Markdown syntax would be very beneficial.

> If we want to add Jekyll styles to our GitHub page that hosts our resume, proceed with the next steps:

8. **Add** another file by using **Create new file**.

9. **Name** the new file as **_config.yml**.
> This file will contain the theme that we would prefer to use on our GitHub page.

10. **Click** the *_config.yml* file that we just created.

11. On the main page, **click** the pencil icon to edit the file we just created.

![img](https://i.imgur.com/d0vBkLk.png)

12. **Add** the line "theme: " and then put the preferred style that we prefer. 

> For this guide, we can just **add** the following line: "theme: jekyll-theme-slate"

> As [Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) mentioned in his book, many static site generators exist and Jekyll is one of them. We can use Jekyll to get various designs that we prefer for our static website that will have our resumé.

13. After adding our preferred style, **click** the **Commit changes** to save and update the file on our repository.

14. **Done!** We can now view our hosted resume at *username*.github.io

![img](https://github.com/Leiven/Leiven.github.io/blob/main/resume.gif?raw=true)

## More Resources
* [Modern Technical Writing: An Introduction to Software Documentation Kindle Edition](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

* [A handy guide](https://www.markdownguide.org/cheat-sheet/) for Markdown formatting.

* [A Jekyll guide](https://jekyllrb.com/) if you want fancier themes and more customized webpage designs.

## Authors and Acknowledgements

**Author**: Raven Mico Carencia

**Special Thanks (Groupmates)**:

* Kyle Calinisan

* Scott Jodoin

* Tahmidul Zidaan

* Hao Qin


## FAQs
* Why is Markdown better than a word processor?

> [Markdown](https://daringfireball.net/projects/markdown/) is very efficient in that it converts plain text formatting into HTML to generate different and diverse content. It makes our writing style transferrable between web pages without having to worry about the processing that a word processor does when switching platforms.

* Why is my resume not showing up?

> * Make sure that your resume is properly formatted in the `index.md` file in the repository.
> * Make sure that your *username*.github.io repository is set to public.
> * There could be a service failure at GitHub Pages. We can check for GitHub status [here](https://www.githubstatus.com/.).
> * There may be delay when GitHub pages update (this usually takes up to 5 minutes).
