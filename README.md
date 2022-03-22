# One-way ANOVA Exercise

A video demonstration for this assignment is available here: https://youtu.be/GIYdna5kde0

## Summary of steps to complete

- [X] Fork this repository so you have your own copy to work on.
- [X] Clone the repository on your local machine. 
- [X] Read through the .rtf answer sheet included in this repository. (It's probably best to complete the steps of the assignment using that answer sheet.)
- [X] Complete the steps of the tutorial.
- [X] Push your updated file to your GitHub repository.

## Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/exerGitPractice
* This can also be done directly in RStudio
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In RStudio - File - New Project... - Version Control - Git 
  * Paste the URL in the Repository URL: field.
  * Click Browse... and navigate to your folder.
  * Click Create Project.
  * Be patient. RStudio will clone the repository and create a new project.
  * When it is complete you should see the files from the repository in the Files pane at the bottom right of the window.
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.

## Follow along with this tutorial

### Data sets

This assignment is based on an example in Andy Field's text Discoverint Statistics Using IBM SPSS Statistics 5th Edition. [Amazon link](https://www.amazon.com/Discovering-Statistics-Using-IBM-SPSS/dp/1526419521/ref=sr_1_4?dchild=1&keywords=discovering+statistics&qid=1602801958&sr=8-4) Sage makes the datasets used in that text available at https://edge.sagepub.com/field5e/student-resources/datasets . A zip file with the datasets can be downloaded at http://study.sagepub.com/sites/default/files/spss_files_0.zip .

### Data Cleaning and Exploration

Data needs to be examined and any problems fixed before analysis can be done. This process of checking data before proceeding with a statistical analysis is often called data cleaning. The steps for data cleaning outlined in this tutorial are discussed in the following videos. You don't need to watch the videos to complete this assignment, but I list them here should you have interest in listening to the original lectures.

* Data screening 1 accuracy (40 min) (optional): https://www.youtube.com/watch?v=_wl5wLEnG7I&t=0s&index=145&list=PLw93TUuxrFAbWrTsvaDsn7Y32l8LHJJXn
* Data screening 2 missing (37 min) (optional): https://www.youtube.com/watch?v=9a3CW8fKA3k&t=0s&index=147&list=PLw93TUuxrFAbWrTsvaDsn7Y32l8LHJJXn
* Data screening 3 outliers (22 min) (optional): https://www.youtube.com/watch?v=zL66kiX5VZg&list=PLw93TUuxrFAbWrTsvaDsn7Y32l8LHJJXn&index=148&t=0s

In statistics, we focus on four areas. (Summarized from the videos above.)

1. Data accuracy
    + make sure data types are correct
    + check for typos
    + check for nonsensical data
    + check categories make sense
    + correct problems if possible or delete
    + reverse code items if needed
    + score instruments if needed
    + keep track of what you do so you can be transparent
2. Missing data
3. outliers
4. Statistical assumptions

### One-way ANOVA

One-way ANOVA is used to compare means for an outcome variable from two or more groups. (A one-way ANOVA using just two groups is equivalent to conducting a t-test for those two groups.) ANOVA is an omnibus test which assesses if a difference exists between at least two of the groups, but it does not show where the difference exists. Post-hoc analyses between different combinations of group pairings are usually conducted after a significant ANOVA to assess where the differences lie.

### Jamovi part

* Open Jamovi
* Complete the steps outlined in the assignment. (See the assignment answer sheet file included in this repository.)
* The file menu looks like 3 horizontal lines at the top left of the Jamovi window.
* File - Open - Browse
* Navigate to your assignment folder where the files for this assignment are, select the file, and click Open.
* After you complete the steps of the assignment, save a Jamovi file (.omv).
* File - Save As - Browse
* Navigate to your assignment folder where the files for this assignment are and click Save.
* You should now have a .omv file in your assignment folder.
  
### RStudio part

* In RStudio open the R markdown file (.Rmd) by clicking on it in the Files pane.
* Complete the steps outlined in the assignment. (See the assignment answer sheet file included in this repository.)
* Create a markdown (.md) document by clicking the Knit button. Make sure the markdown file gets saved in the same folder as the R markdown file so it will get pushed back to your GitHub repository.
  
## Push your updated files to your GitHub repository

* This can be done in RStudio.
  * Be patient as you complete these steps. RStudio can be a bit slow to respond.
  * Click on the Git tab in the top right section of the window.
  * You should see the files in your repository in the window.
  * Click in the checkbox in the Staged column to stage the changes you made.
  * Click on the Commit button. (Just above the Staged, Status, Path labels at the top of the pane.)
  * A new window will open which is titled RStudio: Review Changes.
  * Enter a commit message in the field on the right side of the window and click Commit.
  * Another popup should come up while the commit it made. You can close it when it's done.
  * Click the Push button on the top right of the window.
  * Another popup should come up while the push is done. You can close it when it's done.
  * If you check your GitHub repository, your new files or changes should be there.
* This can be done in VSCode.
  * In VSCode click on the Source Control button.
  * You should see the files that had changes. (Mine has the original file which shows an M next to it and a new file which says checkpoint in the name. You really only need to push the original file, but if you push both it shouldn't hurt anything.)
  * Hover over the changed file. Click the + sign to stage the change.
  * Enter a commit message in the message field and click the checkmark to commit the change.
  * Click on the 3 dots for more actions and select Sync. This will push the updated file to your GitHub repository.
* You can also directly add files to your GitHub repository online.
  * Navigate to your GitHub repository in a browser.
  * Click on the Add File button and select Upload Files. (It's right next to the Code button where you copy the URL for the repository when you clone it.)
  * Drag the files to the window or browse for them.
  * Remember to scroll to the bottom of the window and commit your changes or your file(s) won't be saved.
* Submit the link to your GitHub repository on Canvas.
