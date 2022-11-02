# How to Host and Format a Resume by using Markdown, Jekyll, and Github Pages

## Purpose
This README file will focus on teaching CS students how to host and format a resume by Markdown, Jekyll, and Github Pages. Additionally, this README file will also introduce the general principles of mordern technical writing as mentioned in Andrew Etter's book Modern Technical Writing.

## Prerequisites

#### _Markdown editors_
* [Markdown editors](https://www.oberlo.ca/blog/markdown-editors/)
* [Online Markdown editors](https://techwiser.com/online-markdown-editor/)

#### _Markdown tutorial_
* [Markdown basic syntax](https://helloacm.com/markdown-markup-language-quick-tutorial/)
* [Markdown tutorial](https://www.markdowntutorial.com/)

#### _Jekyll_
* [Jekyll official site](https://jekyllrb.com/)

#### _Github and Github Pages_
* [Github](https://github.com/)
* [Github Pages](https://pages.github.com/)



## Instructions

### Build your own .md file for your resume
Andrew Etter suggests that a lightweight markup language is a better choice than XML for programmers. For example, Markdown can be the good choice for a new programmer who needs a lightwegith markup language. Markdown is easy to learn and use with a bunch of good online examples. All these characteristics can answer why Markdown is used so widely in the world. Now, let's start writing your first resume in Markdown.

1. Open a Markdown editor. (you can find a editor by the links under "Prerequisites")
2. Write your resume by using Markdown with right syntax.
3. Save the file in ".md" format.
4. Change the file name to "index.md". (recommended for building online resume page in the future)

After following the above steps, you will have a resume in Markdown.

### Set up a repository for your resume
For developers, a reliable way for storing and updating documentations and works is the most significant issue that they need to consider. It's not safe to store and update all works in local personal computers. If personal computers have unpredictable issues and errors, developers may lose everything that they are working on in the computers. Furthermore, if a project will be done by several developers, it's difficult to synchronize all progress of different developers in traditional way.

So, the distributed version control system (DVCS) was created to handle these tasks. Andrew Etter suggests using DVCS for development works. Github is one of the most famous service providers who provide DVCS service to individual users for free. So, I highly recommend all new programmers use github to maintain their documentations, codes, projects, and works. The following steps focus on teaching new programmers how to use Github for the first time.

1. Go to [Github](https://github.com/).
2. Sign up a new Github account.
3. Log in with your new Github account.
4. Click the icon at the top right corner and choose "Signed in as xxxxxx".
5. Click "Respositories", and then click "New".
6. Fill in the form to create a new repository.
7. Click "Create repository" to finish.
8. Upload your resume in Markdown to this repository by clicking "Add file" and "Upload files".

Now, a new repository with your resume in Markdown is created.

_**Tip 1**_: 

if you want to create a repository for building your own web page by Github, your repositroy's name should be "username.github.io". This detail is very **important** for building your own Github page.

_**Tip 2**_: 

installing [Github Desktop](https://desktop.github.com/) will help you easily host your works on Github.

### Set up your resume page by Github Pages
Andrew Etter recommends using static websites because they are fast, simple, and safe. So, you'd better use a static website to host your resume page. My recommendation is using Github Pages to complete this task. Github Pages provides a easy way to host and format a static personal website for beginners. Github Pages include several Jekyll themes for web pages. This is a good news for beginners because lots of beginners know little about Jekyll like me. Using Jekyll themes provided by Github Pages can reduce the difficulties about using Jekyll for beginners.

If you follow all steps below, you will have a personal website with pretty Jekyll theme.

1. Enter the repository (username.github.io) created before.
2. Click "Settings".
3. Click "Pages" listed on the left side.
4. Click "Learn how to add a Jekyll theme to your site".
5. View the website just opened in the last step to learn how to use Jekyll theme.
6. Click [Supported Theme](https://pages.github.com/themes/) in the website.
7. Choose one theme you like and click its link.
8. Read the README.md file in the theme's repository so that you know how to use the theme.
9. Add all necessary files that mentioned in the README.md file to your repository for web page.
10. Add a README.md file to state important information about your repository for web page.

_**Tips**_: 

for most of supported theme provided by Github Pages, you only need to add a file named "\_config.yml" so that the theme will work. You need to add some codes in the blank "\_config.yml" file. The codes that you need to add should be provided in the README.md file among the theme's repository. The theme's README.md file will teach you how to use and customize the theme for you personal website as you want.

Now, a README.md file and a index.md file for your resume should be in your website's repository with the theme's files. Github will run these files to produce your personal resume website.

### View your resume page
When you arrive at this step, your personal resume page should be created successfully.

To view your web page, you need to:

1. Go to the repository hosts your personal website.
2. Click "github-pages".
3. Click "View deployment".

_**Or**_

1. Enter "your_username.github.io" in your browser.
2. Press "enter" to view your website.

### Additonal instructions about Jekyll
Jekyll is a good tool for generating static website or blog. It's usually used with Markdown and Github Pages together for creating personal website. If you start to make your own static website from nothing, I suggest use Jekyll as a starting point. You don't have to directly use Jekyll because supported themes of Github can help you do that. So, the following steps are for beginners who don't want to use Github's themes.

Windows OS is not officially supported by Jekyll. However, you still can install and use Jekyll on Windows OS. You need to intall Ruby before installing Jekyll.

* [Here is an article on Jekyll official website about using Jekyll on Windows.](https://jekyllrb.com/docs/installation/windows/#installation-via-bash-on-windows-10)
* ["How to Install Jekyll on Windows 10 Example"](https://www.youtube.com/watch?v=7QVGUzjqdKE) is a video tutorial about installing Jekyll on Windows 10


##### _**[My resume page](https://liao4869.github.io/) demo:**_

![demo](https://media3.giphy.com/media/IdohCTNOYPR6ol6lZP/giphy.gif?cid=790b76116bee6fcc6922d54e09ff2c8a889b3b19885fd0c5&rid=giphy.gif&ct=g)


### More Resources

## Authors and Acknowlegements
**Author**
* Gongyu Liao



## FAQs
