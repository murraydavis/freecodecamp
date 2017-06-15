## Log of my activities with Free Code Camp

### Preamble

I decided to enroll in the freeCodeCamp's Front End Development Certificate (FEDC) in order to sharpen my skills that would be needed to develop my website at [murraydavis.ca](https://murraydavis.ca).

#### June 4th

* registered with freeCodeCamp's FEDC and Udemy's Web Developer course (paid $15).
* completed first few challenges

#### June 5th

* setup a github.com repos called: freecodecamp.
* completed one or two challenges from the HTML5 and CSS section
* created local folder ~/githubrepos and created a local code for the freecodecamp github repos

#### June 6th

* updated the Atom package on MacOSX
* installed these Atom packages: minimap, atam linter, remoteFTP, git plus, css comb, jacascript snippets
* reviewed the previous challenges

#### June 7th

* reviewed documentation on the Markdown syntax
* generated RSA pub key for github site for my Mac
* troubleshot and resolved why the 'git plus' package did not work
* troubleshot and resolved why 'git push' did not work from the terminal
* both above involved changes to .git/config file
* setip gist site on github.com for my Linux System Administration work

#### June 8th

* changed my.log to log.md
* began composing log.md
* created secure local folder for the freecodecamp project, not in project folder, but in root of githubrepos
* used git plus to refresh changes## Log of my activities with Free Code Camp
* encountered issue with Mac's .DS_Store local file in root of freecodecamp directory and .gitignore file not working, I had the file in ~/.git/.gitignore. I moved it to ~/githubrepos/freecode camp, and that resolved the issue

Here is the current code of .gitignore

```
.DS_Store
*.lock
*.swp
*.out
*.gitignore
```

The git commands that I used were similar to the following...

```
git add .
git commit -m "Another commit"
git push
git status
```

* further change, I had to specify that my .gitignore file was global and then remove .DS_Store from the cache and then push the change.

```
git config --global core.excludesfile ~/githubrepos/freecodecamp/.gitignore
git rm --cached .DS_Store
git add .
git commit -m "DS"
git push
git status
```

* spent a considerable amount of time setting up Anaconda 2.7 and Anaconda 3.6 on my Mac...somewhat off channel, I suppose.

#### June 9th

* I took a day off...

#### June 10th

* Wrote ahead titles in my html5_css.md document and completed a few lessons. Added a few days ahead in this document.

#### June 11th

* Set up clone of my Githubrepos/Linux System Administration on my MacOSX.
* Minor edits to Evernote. Created new stack for my Githubrepos.

#### June 12th - June 13

* No activity

#### June 14th

* Cloned Spellbook of Modern Web Development, launch from command line: open -a safari README.md. However, it opened as a text file. Researched the issue. First, I installed the open source package, MacDown. It worked well, but could not install Plugins or the Terminal extension.

* Also, found the Markdown Preview within Atom, unfortuately the shift-ctrl-M combination does not work, but the Packages/Markdown Preview menu toggle does work.

* I disabled Markdown Preview and installed Markdown Preview Plus...better rendering to HTML.

* The issue with shift-ctrl-M was a conflict with the Emmet package. I added the following code to keymap.cson, the (Atom/Keymap...).

```
'.editor:not(.mini)':
    'ctrl-shift-M': 'markdown-preview-plus:toggle'
```

#### June 15th

*

#### June 16th

*

#### June 17th

*

#### June 18th

*

#### June 19th

*

#### June 20th

*

#### June 21th

*

#### June 22th

*

#### June 23th

*

#### June 24th

*

#### June 25th

*

#### June 26th

*
