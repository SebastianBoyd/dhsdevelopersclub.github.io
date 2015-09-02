# dhsdevelopersclub.github.io

This is the repository for the Drake Developers Club website.  We are a club at Drake High School that focuses on spreading knowledge and passion for software development and coding.  Contact us at [drakedevelopersclub@gmail.com](mailto:drakedevelopersclub@gmail.com), or come to a meeting during lunch on Wednesday's in room 107.

## New Member Instructions

All new members should follow these steps to create their own unique homepage on the website.  If, as you go through this guide you encounter any problems, ask for help from a fellow club member or from Google.  Both are happy to help and can probably get you sorted out.  If any part of the instructions are out of date, confusing, or incomplete, it is also the task of the new member to edit this file and fix any issues with the instructions, once you have solved the issue for yourself.

### Step 1: Get the Software

Development requires software to edit and test your code.  Make sure you have all of the tools listed below.

- **Code Editor.** You will need a text editor to edit your code.  Try one of the ones listed below, or use your own favorite editor if you have one.
  - [Brackets](http://brackets.io/)
  - [Atom](https://atom.io/)
- **Git.** You will need git to upload your code to this online repository.  If you get the Windows or Mac version, make sure you click yes when it asks you if you want to install the command line tools.
  - Linux: Open a terminal and type in `sudo apt-get install git` to get the command line tools.
  - Mac: Download [GitHub for Mac](https://mac.github.com/).
  - Windows: Download [GitHub for Windows](https://windows.github.com/).
- **Node.js and NPM** You will need to install both node.js and npm to use the build tools and view the site.
  - Linux: Run `sudo apt-get install nodejs npm`
  - Mac: Install [MacPorts](https://www.macports.org/) then run `sudo port install nodejs npm`
  - Windows: Ask somone like Max or Duncan

### Step 2: Download the Repository

Open up a terminal and type in `mkdir github` (you are making a folder called "github") press enter, then type `cd github` (you are opening that folder).  If you already have a folder where you keep your projects, `cd` to that folder instead.

If you are using Windows and do not have access to a terminal, you can create a folder normally by right clicking in the directory you would like, and clicking create folder. Then skip the next to steps and see **.

Type in `git clone https://github.com/DHSDevelopersClub/dhsdevelopersclub.github.io.git` and press enter.  (you can use SSH too, if you like, it doesn't matter)

If you type in `ls` you should see a folder called `dhsdevelopersclub.github.io`.  If so type `cd dhsdevelopersclub.github.io` to open the repository folder. To download the additional files and tools you need run `sudo npm install && bower install` you may be asked to input your password. Now you are done with step #2!

** If you are on Windows or Mac, all of this can also be done through the user interface of the GitHub client you downloaded in step #1.

### Step 3: Make Your Very Own Folder

Open a file browser and find the project folder (remember it should be called `dhsdevelopersclub.github.io`).  Open it, then open the folder called `club-members`.  Inside, make a new folder with your first and last name.  No spaces allowed, use `_` instead, but keep the normal capitalization of your name.

For example, someone named "Bobby Smith-Rogers" would make a folder titled `Bobby_Smith-Rogers`.  Someone called "Joe McCandless" would make a folder called `Joe_McCandless`.

### Step 4: Make Your Home Page

Now open the folder with your name on it and make a new file inside it called `index.html`.  Open `index.html` with your favorite code editor, and use your HTML skills to make whatever kind of home page you want for yourself.[*](#restrictions)  If you have no HTML skills, copy and paste this example code into the file.  We will teach you to use HTML later so you can make something more orignal.

```html
  <!DOCTYPE html>
  
  <html>
    <head>
      <title>--Your Name Here--</title>
    </head>
    <body>
      Hi I'm --Your Name Here-- and I am a member of the Drake Developer's Club.
    </body>
  </html>
```

When you're done, save the file.

### Step 5: Testing Your Home Page

Open up a terminal/command line again.  Type in `cd /path/to/project` where `/path/to/project` is the location of the project.  If you followed step #2, the project should be at `~/github/dhsdevelopersclub.github.io`. Now type `gulp serve` into the command line.

If it works, you should see your web browser open and display the club website.

Now navigate to your page on the website.  You should be able to see you homepage.  Try modifying the index.html file, save.  You should see the changes you made to your code automaticly synced and reflected in the web browser.

### Step 6: Experiment

Mess around with your code.  If you are new to HTML, ask a fellow club member for help, or check out [http://www.w3schools.com/](http://www.w3schools.com/) for reference or some tutorials.  Feel free to check out other people's pages to see how their code works and manifests into a webpage.  Just don't mess with their files: it's rude, and we can all see if you do.  You can, however copy bits of their code (with their permission) and experiement with it on your own page. For some more in depth tutorials and advanced techniques, check out [http://www.codecademy.com/](http://www.codecademy.com/).

### Step 7: Add your profile Info

Once you're satisfied with your homepage, it's time to let the club know who you are. 
In the top level of your folder add an image called `profile.jpg` this is what will show up above your name so keep it clean!
Next add a `blurb.txt` with a little info about yourself, again, school appropriate.

When you are done, you will be ready to upload your changes to GitHub.

### Step 8: Upload Your Changes to GitHub

When you are finished, it is time to commit.  "Commit" is an action you can do with Git, it is a way to wrap up your changes into one tidy package with a message to describe what the changes are.  To commit, open a terminal/command line and type in `git add --all` (this flags all of your changes so the commit can scoop them up) then type in `git commit`.

You will be prompted to enter a commit message.  A commit message should be one sentence.  Keep it short, less than sixty letters, and use the imperative form for verbs.  Eg. `Add some images to my home page.` or `Update my index.html.` or `Completely redesign my home page.`  Make it descriptive.  **Do NOT do anything like this:** `Changed stuff` or `i added a title bar and then i added an image of a cat and then i added another image of a cat`.  If you need to add extra description, you can add it below the message.  For example:

```
  Completely redesign my home page.
  
  I added a header bar, replaced the logo, and changed up the color 
  scheme.  I also added a link to another page with a list of 
  projects I have completed.
```

Once you are done with your commit message, save and close the text editor you were using to edit the message.

Now that you have made your commit, it is time to upload your changes.  In the terminal/command line type `git push`.  That should synchronize your changes with this repository.

If you're not comfortable with console commands or prefer a GUI, check out [https://git-scm.com/downloads/guis](https://git-scm.com/downloads/guis) and find one that works for you.

### Step 9: Edit the README.md File

Make sure to improve this file if you run into any problems.  You can edit this file in much the same way that you edit your index.html.  You can also edit it from the GitHub website.

Happy coding, and welcome to the club!

------

<a name="restrictions"></a>
\* Certain restrictions apply: keep it PG and PC, no viruses or ads.  Club leadership reserves the right to make any changes we deem necessary to keep your page appropriate.