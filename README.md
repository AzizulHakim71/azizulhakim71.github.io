How to host a resume on GitHub Pages
===

Purpose
---
The purpose of this README file is to demonstrates the steps required to host and format a resume in the *GitHub* repository. The steps consist of using a light markup language, a text editor, and a static site generator. In our case, we will be utilizing *Markdown*, *Atom*, and *Jekyll*. Finally, the resume will be hosted on the *Github* (a distributed version control system).

Prerequisites
---
As we are using a markup language called *Markedown*, it is recommended to be familiar with it before staring the process. Please follow the resources under More Resources section to learn more about Markdown. Secondly, you should have a resume prepared for your desired job postings. Your resume should also be in *Markdown* format. Finally, we should install a test editor where you will be able to write in markdown format. *Atom* is an excellent option for that.

Instructions
---
The steps outlined below is a brief set of instructions on how to host a resume on GitHub which also follows Andrew Etter's general process. The steps are:
- Sign up for a gitHub account if you don't have one. You can sign up from [here.](https://github.com/signup)
- Create a respository on GitHub. In order to create that, you need to click the "*+*" button next to you profile logo.

![image](https://user-images.githubusercontent.com/102190616/159597897-cf376b49-9563-4c7d-b31c-5e29463649b7.png)
- Name the repository in this format *username.github.io*. :warning: Make sure the username is correct and valid.
- Make the repository public, you can also add a README file from there and finally press to create the repository.
- Once the repository is ready, you can upload your resume which is in *Markdown* format by pressing the `Add File` button.
 
![image](https://user-images.githubusercontent.com/102190616/159599111-54da6f95-ecd6-47f5-949e-636e169ab26a.png)
- After adding the file, you have to rename the file name to `index.md`.
- Now, we need to create a static website using Jekyll theme. For that, click on `settings -> Pages -> Change theme -> Select your desired theme to confirm your selection`.
- Finally, wait a few minutes for gitHub to fully deploy your changes. Then, go to `username.github.io` or click on the published link to view your hosted gitHub page.

![gitHubPage](https://user-images.githubusercontent.com/102190616/159606423-5f1a0df3-4848-46bb-9ab0-04c256aaf546.gif)

More resources
---
* [Markdown Tutorial](https://www.markdowntutorial.com/)
* [Modern technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Jekyll theme cayman](https://pages-themes.github.io/cayman/)
* [Atom](https://flight-manual.atom.io/using-atom/sections/writing-in-atom/)

Authors and Acknowledgments
---
* Etter, Andrew. [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), 2016.
* Group Members: Joshua Smallwood, Deepta Mandal, Harshal Bhalerao

FAQs
---
1. Why is Markdown better than a word processor?
> One of the biggest reasons that Markdown is better than a word processor is its integration with version control. This is really important for technical documentation. Another reason is it's free to use. On the other hand, a word processor doesn't support version control and needs a license key to use.

2. Why is my resume not showing up?
> One of the main reasons is when someone forgets to update the file name to `index.md`, it doesn't show up. Another reason is the GitHub pages sometimes take time to update. In that case, you need to wait until the status of the `GitHub pages` change to `Active`. 

![image](https://user-images.githubusercontent.com/102190616/159609833-e1e749ca-9273-4ad2-9c6f-2d865b470c92.png)
