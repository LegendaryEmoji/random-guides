### How to get the source code of a repository?

There are many ways to get the source code of a repository, this guide shows three of those methods.  
Bad - Good

### Git

"Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows." - Wikipedia  
In simple words, a version control system, this is like a archive of your project. It has all the old changes & new changes, meaning if you mess something up, you can easily recover it.  
You may ask, but what a version control system has to do with getting the source code? Well, you can use this tool for working with Github, creating commits, push updates, etc. So, if you can do that, then you can also download whole repository using a single command.  
`<URL>`: String - Your github repository URL  
(In the bash, bash is something that you get after installing the Git)
```
git clone <URL>
```
That's it, you have a folder that has the name of repository and the whole code!
