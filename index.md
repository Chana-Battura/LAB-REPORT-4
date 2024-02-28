# CSE 15L Lab Report 2
### by Charan Battula A17750911

---
## STEP FOUR: Log into ieng6

#### Key Pressed: `<ctrl-r>s<enter>`

#### Screenshot of Output:
![image](https://github.com/Chana-Battura/LAB-REPORT-4/assets/39713790/92cad83c-7139-4c43-aba6-2764e0f1244b)

> Description:
> The `<ctrl-r>` command searches through bash history, when I typed `s`, I was able to see the command `ssh srbattula@ieng6.ucsd.edu` and pressed enter to run it


## STEP FIVE: Clone your fork of the repository from your Github account

#### Key Pressed: `<ctrl-r>cl<enter>`

#### Screenshot of Output:
![image](https://github.com/Chana-Battura/LAB-REPORT-4/assets/39713790/415e612c-3f65-4028-9875-f958180278fc)

> Description:
> The `<ctrl-r>` command searches through bash history, when I typed `cl`, I was able to see the command `git clone https://github.com/Chana-Battura/lab7.git` and press enter to run it. The command clones the repository.

## STEP SIX: Run the tests, demonstrating that they fail

#### Key Pressed: `<ctrl-r>la<enter>`

#### Screenshot of Output:
![image](https://github.com/Chana-Battura/LAB-REPORT-4/assets/39713790/3dd176ae-6175-44cc-bbba-6914f36e97c3)

> Description:
> The `<ctrl-r>` command searches through bash history, when I typed `la`, I could see the command `cd lab7/ && bash test.sh` and press enter to run it.  The first part of the command enters the repository directory and the second command executes the testing script.

## STEP SEVEN: Edit the code file to fix the failing test

#### Key Pressed #1: `<ctrl-r>v<enter>`

#### Screenshot of Output #1:
![image](https://github.com/Chana-Battura/LAB-REPORT-4/assets/39713790/1e2faf23-45b5-46eb-ba8b-d05acef62f52)

> Description:
> The `<ctrl-r>` command searches through bash history, when I typed `v`, I could see the command `vim ListExamples.java` and press enter to run it.  The command opens the file `ListExamples.java` in vim.

#### Key Pressed #2: `?i<enter>cwindex2<esc>:wq`

#### Screenshot of Output #2: 
![image](https://github.com/Chana-Battura/LAB-REPORT-4/assets/39713790/8b7e0a77-5ebd-4352-a85e-7726b86341aa)

> Description:
> The `?` does a search from the end of the file and after searching for `i`, I found the section to change so pressed enter to get to the place.  Then, the command `cw` deletes the word and opens for insertion, where I typed in `index2`.  To save my changes, I went to normal mode with `<esc>`, and run `:wq`.

## STEP EIGHT: Run the tests, demonstrating that they now succeed

#### Key Pressed: `<ctrl-r>b<enter>`

#### Screenshot of the Output:
![image](https://github.com/Chana-Battura/LAB-REPORT-4/assets/39713790/69834afe-1d03-4ec4-b2d0-36a82759996c)

> Description:
> The `<ctrl-r>` command searches through bash history, when I typed `b`, I could see the command `bash test.sh` and press enter to run it.  The command executes the testing script

## STEP NINE: Commit and push the resulting change to your GitHub account

#### Key Pressed: `<ctrl-r>p<enter>`

#### Screenshot of the Output:
![image](https://github.com/Chana-Battura/LAB-REPORT-4/assets/39713790/84aa1602-a49b-49f4-94a2-7f9a97a289cd)

> Description:
> The `<ctrl-r>` command searches through bash history, when I typed `p`, I could see the command `git add . && git commit -m "fixed error" && git push` and pressed enter to run it. The first part adds all changes in the current directory to the staging area, the second part commits the staged changes with the message "fixed error", and the final part pushes the committed changes to the remote repository.
