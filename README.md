# How to Host and Format a Resume by Software Stack
## Purpose
A README file includes important information, instructions, helps, or details for users about the software, code, or project.  
In this case, the README file will teach CS students how to host and format a resume by Markdown, Jekyll, and Github Pages. Meanwhile, the README file will also introduce the general principles of technical writing that included in Andrew Etter's book.
## Contents

## Prerequisites
#### Install a Markdown editor or use a online editor
* [Markdown editors](https://www.oberlo.ca/blog/markdown-editors/)
* [Online editors](https://techwiser.com/online-markdown-editor/)

#### Markdown tutorial
* [Markdown basic syntax](https://helloacm.com/markdown-markup-language-quick-tutorial/)
* [Markdown tutorial](https://www.markdowntutorial.com/)

#### Instal Jekyll
* [Jekyll official site](https://jekyllrb.com/)

#### Have Github and Github Pages
* [Github](https://github.com/)
* [Github Pages](https://pages.github.com/)

#### Example of resume in Markdown
* [My resume](https://liao4869.github.io/)


## Instructions
### Build your own .md file for your resume
Andrew Etter suggests that a lightweight markup language is a better choice than XML for programmers. As a result, Markdown can be the good choice for a new programmer who need a lightwegith markup language. Markdown is easy to learn and use with a bunch of good online examples, and these characteristics can answer why Markdown is used so widely in the world. Now, let's start doing your first resume file in Markdown.

1. Open a Markdown editor (for OS or online)
2. Type relative words about your resume in right syntax of Markdown
3. Save the file in ".md" format
4. Change the file name to "index.md" (recommended for building online resume web page in the future)

After the above steps, you have a resume in Markdown.

### Set up a repository for your resume
For developers, a durable strategy for storing and updating documentations and works is the most significant issue that they need to consider. It's not safe to store and update all works in local personal computers. If personal computers have unpredictable issues and errors, developers may lose all their works that they are processing. Meanwhile, if a project will be done by several developers, it's difficult to synchronize all progress of different developers in traditional way. So, the distributed version control system (DVCS) was created to handle this task. Github is one of the most famous service providers who can provide DVCS service for free to individual users. So, I highly recommend all new programmers use github to maintain their documentations, codes, projects, and works. The following steps can teach new users how to use Github for the first time.

1. Go to [Github](https://github.com/)
2. Sign up a new Github account
3. Log into the Github account just registered before
4. Click the icon in the top right corner and choose "Signed in as xxxxxx"
5. Click "Respositories", and then click "New"
6. Fill the form for creating a new repository
7. Click "Create repository" to finish
8. Upload your resume in Markdown to this repository by clicking "Add file" and "Upload files"

For now, a new repository with your Markdown resume file was created.

_**Tip 1**_: if you want to create a repository for building your own web page by Github, your repositroy name should be "username.github.io". This detail is very **important** for building your own Github page.

_**Tip 2**_: installing Github Desktop will help you host your works on Github.

### Set up your resume page by Github Pages
Andrew Etter claims the static website is a good choice to be fast, simple, and safe. So, you'd better use a static website to host your resume page. My recommendation is using Github Pages to complete this task. Github Pages provides a easy way to host and format a static personal web page for starters. Github Pages also provides several Jekyll themes for the web page, and this is a good news for starters. Many starters know little about Jekyll like me. Using Jekyll themes that provided by Github Pages can decrease the difficulties about using Jekyll for starters.

If you do the following steps, you will have a personal page with pretty Jekyll theme.

1. Enter the repository (username.github.io) created in the previous steps
2. Click "Settings"
3. Click "Pages" listed in the left side
4. Click "Learn how to add a Jekyll theme to your site"
5. View the website just opened in the previous step to learn how to use Jekyll theme
6. Click [Supported Theme](https://pages.github.com/themes/) in the website
7. Choose one theme you like and click its link
8. Read the README.md file in the theme's repository so that you know how to use the theme
9. Add all useful files that mentioned in the README.md file to your repository for web page
10. Add a README.md file to state information about your repository for web page

_**Tips**_: for most of supported theme that provided by Github Pages, you only need to add a file named "\_config.yml" to let the theme works. You need to add some codes in the blank "\_config.yml" file. The codes that you need to use should be provided in the README.md file of the theme repository. The theme's README.md file will teach you how to use and cutomize the theme for you personal web page as you want.

Now, a README.md file and a index.md file for your resume should be in your web page repository with the theme's files. Github will run progress to produce your personal web page for your resume.

### View your resume page
When you arrive at this step, your personal resume page should be created.

To view your web page, you need to:

1. Go to the repository that host your web page
2. Click "github-pages"
3. Click "View deployment"

_**Or**_

1. Enter "your_username.github.io" by your browser

### Additonal instructions about Jekyll
Jekyll is a good static web page and blog generator. It's usually used with Markdown and Github Pages together to create personal website. If you want to make your own static website from 0, I suggest use it as a starting point.

Windows OS is not officially supported by Jekyll. However, you still can install and use Jekyll on Windows OS. You need to intall Ruby before installing Jekyll.

* [Here is an article on Jekyll official website about using Jekyll on Windows.](https://jekyllrb.com/docs/installation/windows/#installation-via-bash-on-windows-10)
* ["How to Install Jekyll on Windows 10 Example"](https://www.youtube.com/watch?v=7QVGUzjqdKE) is a video tutorial about installing Jekyll on Windows 10

If you follow the above instructions, you should have Jekyll in you computer.

##### _**[My resume page](https://liao4869.github.io/) demo:**_

![demo](https://media3.giphy.com/media/IdohCTNOYPR6ol6lZP/giphy.gif?cid=790b76116bee6fcc6922d54e09ff2c8a889b3b19885fd0c5&rid=giphy.gif&ct=g)


### More Resources

## Authors and Acknowlegements
**Author**
* Gongyu Liao



## FAQs
