# mystmd
Repository to test features of MySTmd in a Codespace

## quickstart with this repo
1. Create Codespace from this repository
2. In terminal execute command `./start.sh`
4. Confirm popup to MyST-static files in browser

After editing files a reload of the webpages shows the result, `start.sh` automatically rebuilds html.

Output is shown in terminal. In case anything crashed, manually start `./start.sh` again, old processed will be killed.

## how this repo was created
1. Create repository
2. Add devcontainer
3. Follow MyST Quickstart on https://mystmd.org/guide
4. Add deployment on github pages using terminal command `myst init --gh-pages` (first move book from subdir to root of repo)
5. Change some github and vscode settings to make is easier for novice programmers to work with

Not done yet:
1. add LaTex for pdf (this can be done by adding a feature to the devcontainer)

