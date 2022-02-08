### How to get the source code of a repository?

There are many ways to get the source code of a repository, this guide shows three methods to work with repositories.

### Git

- [Download](https://git-scm.com/downloads)

Git is a verson control system which you can basically use to manage all the changes of your project. While Git can be used in many other ways, it supports Github which means you can connect to a repository and do stuff with it. So, we are basically going to use Git to download the source code of a repository.

(Bash, Bash is something that you get after installing the Git)
```
git clone <URL>
```
`<URL>`: String - Github repository link that you want to clone or get the source code of. You can get the link by going to the repository home page e.g. github.com/username/repository and you will see "Code" button, click on it and copy the HTTPS link and paste it in the place of `<URL>` e.g. `git clone https://github.com/LegendaryEmoji/random-guides.git`
That's pretty much it.

### Normal zip

Github also supports downloading the whole project with the use of zip files. To download, just go to home page of the repository e.g. [random-guides home](https://github.com/LegendaryEmoji/random-guides) & you will see `Code` button, click on it and you will see the option to download the zip file.
You have to use some kind of extractor to extract files from `.zip` file, you can either use your default operating system extractor or some third-party software like Winrar & 7zip.

### Website Github cloning

If you are using website like [REPL](https://replit.com/), [Glitch](https://glitch.com/), etc. They supports repository cloning by default.
For example, for REPL, when creating a new repl, just click on `Import from Github` then you can copy and paste the normal URL of the repository and there you go.

- This might get updated in the future.
