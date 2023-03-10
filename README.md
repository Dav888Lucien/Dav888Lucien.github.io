# How to Host a Resume on GitHub Pages

This README tutorial goes over the steps on how to create a resume written in the Markdown markup language, and hosting it on GitHub pages. ![rusema](Gifs/resume.gif)
---
## Prerequisites
Prerequisites:

1. A resume formatted in Markdown
2. [A GitHub account](https://pages.github.com/)
3. [Markdown Tutorial](https://www.markdowntutorial.com/)


---
## Contents
* [Instructions](#Instructions)
   * [Create a Repository]()
* [Jekyll](#Jekyll)
  * [Download a Jekyll](#Download-a-Jekyll)
  * [Quick Theme](#Quick-Theme)

* [Publish Your Resume on GitHub Pages](#Publish-Your-Resume-on-GitHub-Pages)

* [Principles of Andrew Etter's book "Modern Technical Writing"](#Technical-writing)
* [FAQs](#FAQs)

--- 
# Instructions


#### Creating the Repository

1. Log into your [GitHub](https://GitHub.com) account.
2. At the top right corner of the website, click on the '**+**' symbol and select "**New Repository**".![creatNewre](Gifs/clickrepository.jpg)
3. Give your repository a name as"username.github.io". ![createNew](Gifs/createRepository.gif)
4. Choose "**Public**" visibility for your repository, and initialise the repository with a README file.![setpublic](Gifs/setPublic.jpg)
6. Finally, click on "**Create Repository**" to finish.photo![setre](Gifs/createre.jpg)
7. Clone the Repository
    *Open VS Code and click on "Clone Repository" on the welcome screen.
    *Enter the URL of the repository you just created and select a location on your computer to clone the repository to 
    ![seturl](Gifs/clone_to_vscode.gif)

---
# Jekyll
---
## Download Jekyll
1. Homebrew makes it easy to install development tools on a Mac.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```
2. Install chruby and the latest Ruby with ruby-install
```
brew install chruby ruby-install xz
```
3. Install the latest stable version of Ruby (supported by Jekyll):
```
ruby-install ruby 3.1.3
```
```
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.1.3" >> ~/.zshrc # run 'chruby' to see actual version
```
4. Install Jekyll
 ```
 gem install jekyll
 ```
5. make new file
# Quick Theme
6. go to [website](https://pages.github.com/themes/) choose one theme
![themeP](Gifs/themepage.jpg)

7. set on configure
![theme](Gifs/theme.jpg)

8. run static web on local device
```
bundle exec jekyll serve
```
![coderun](Gifs/coderun.jpg)
9. Open a web browser and go to http://localhost:4000 to preview your resume.

10. upload config to github
![config](Gifs/uploadconfig.gif)




---
# Publish Your Resume on GitHub Pages
---
 1. Commit upload file and push them to your repository.
 ![index](Gifs/upload_index.gif) 
 2. Go to your repository's settings and scroll down to the "GitHub Pages" section. ![page](Gifs/hostpage.gif)
 3. Your resume is now accessible at https://username.github.io.

---
# Technical writing
---
Use plain language: Technical writing should be clear and easy to understand. Avoid using jargon or technical terms that readers may not be familiar with.

1. Write for the web: Technical writing should be optimized for the web. Use short paragraphs, bullet points, and headings to make the content easy to scan and read.

2. Use a minimalist approach: Keep technical writing simple and straightforward. Avoid unnecessary words or details that don't add value to the content.

3. Use a structured approach: Use a structured approach when writing technical documentation. This can help readers find the information they need quickly and easily.

4. Use a version control system: Use a version control system to manage changes to technical documentation. This can help ensure that the most up-to-date information is always available to readers.

5. Write in Markdown: Markdown is a simple markup language that can be used to write technical documentation. It's easy to learn and can be converted to other formats, such as HTML or PDF.

6. Use screenshots and diagrams: Use screenshots and diagrams to illustrate technical concepts. This can help readers better understand complex information.



---
# FAQs
**Why is my resume not showing up?**
* Make sure Your resume must named ```index.md```.

**What tools can I use to create and edit Markdown files?**
* Online editors: Many websites offer online Markdown editors, such as Dillinger, StackEdit, and HackMD.
* Integrated development environments (IDEs): IDEs like Eclipse, PyCharm, and IntelliJ IDEA often have plugins or built-in support for Markdown editing.



---
## More Resources
* [Easy Markdown Tutorial](https://www.markdowntutorial.com)
* [GitHub Flavoured Markdown Reference Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
* ["Modern Technical Writing" by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

---

---
## Authors and Acknowledgements 
#### **Author**
* [Luxiang Lin](https://github.com/Dav888Lucien/Dav888Lucien.github.io)  
#### **Group Members/Peer Editors**
Anthony Phung 

---








