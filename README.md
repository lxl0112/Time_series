## Instructions for setting up your BP repo

You should only see this template if you have already gone through the Bookdown Example. 

You should set up this repo just like you did for the Bookdown Example, with just a few small changes: 
1. Name it with the name I email you (it will start with "bp" and then have random characters...that way even though the GitHub Pages part is public, no one should ever be able to find it)
2. Make this repo private. Because it is part of our Econ481f20 Organization, you can have it be private but still set up GitHub Pages.
3. For the links in the top of "_bookdown.yml", you should replace the "YOUR REPO NAME" with the repo name. The "YOUR GITHUB USERNAME" part is no longer applicable (because it is now our organization name, Econ481f20). 


Here are the original instructions written out again (with the few changes just mentioned):

For your later reference, if you want to learn more about bookdown, the official guide is https://bookdown.org/yihui/bookdown

Here are the steps to follow:

### 1. Copy this template

<ol type="a">
  <li>
Click the green "Use this template" button in GitHub. Give it your own name, something like BookdownExample. *Please make it a Private repo instead of public.* (You can still request a free Pro account if you haven't already as part of GitHub for education: https://education.github.com/discount_requests/student_application) 
  </li>
 </ol>
 
### 2. Set up GitHub Pages

<ol type="a">
  <li>
  On the home page of your repo, click Settings. Scroll down to the GitHub pages section and change **Source** to **master branch /docs folder**.  Above the **Source** line, a bar will appear with your book's URL. The bar will initially be blue and indicate that your book is *ready* to be published and will change to green once it is published. Copy the URL. (Note that sometimes there is a delay until your book actually appears at that URL. If it doesn't appear after a few minutes, make a change and commit it to trigger a GitHub Pages build.)
  </li>
  <li>
  Click the gear button near "About" on the home page of the repo and paste your book URL into the **Website** field that appears on the right.
  </li>
</ol>

### 3. Clone the repo to RStudio

<ol type="a">
  <li>
Clone your new repo with *File, New Project..., Version Control, Git* in RStudio, just like you did for [Ch 15 of Happy Git with R](https://happygitwithr.com/new-github-first.html)    
  </li>
 </ol>


### 4. Edit the few lines that are specific to you personally

<ol type="a">
  <li>
In the first example (the youtube video), you edited the book title and author in  index.Rmd`. For this book, you can leave the title and author as-is. Because it just says "481 Student" for author and is stored in the Econ481f20 organization, your name and username don't apear anywhere in the Pages part (so even if someone guesses the 14 random characters, they still won't know anything other than it's a book being written by someone in econ 481). 
  </li>
  <li>
In `_bookdown.yml`
  <ol type="i">
    <li>
    <del>change YOUR GITHUB USERNAME to your GitHub username in the three places it appears<del> (you no longer have to do this because now it's Econ481f20)
    </li>
    <li>
    change YOUR GITHUB REPO to your GitHub repo name in the three places it appears. (use the name I gave you with the 15 random characters)
    </li>
    <li>
    These three links set links that appear in your book, the "edit" one taking you to the GitHub page to edit the RMD file, the "view" one taking you to GitHub to view the RMD file, and the "history" one taking you to the GitHub page to view the history of edits/commits for the file. Having these links make it a lot easier to quickly look at your files without always having to pull everythign to my own computer. So please make sure to set them. 
    </li>    
  </li>
 </ol>




### 5. Build the book
  <ol type="a">
    <li>
        Install **bookdown** with `install.packages("bookdown")` (from either the Console or from an RMD file code chunk, but don't leave it in the RMD file after you've installed it)
    </li>
    <li>
    Click on the "Build Book" button on the Build tab (Build tab is next to the Git tab)
    </li>
   </ol>

### 6. Commit and Push to GitHub

<ol type="a">
  <li>
    When you're happy with it, commit everything (it's a lot of files, so make sure to select them all) and push to GitHub
  </li>
  <li>
    Check in GitHub to make sure everything is updated there. Click on that link from the second step to see the contents of your book on GitHub. 
  </li>
 </ol>


### 7. Do the BP
At this point, you're all finished learning about GitHub and bookdown. You can start the book project. You should also read "Book Project.pdf" in Moodle for more descriptions of the project (and links, etc). I will post the journal articles I'm having your replicate in Moodle. I'll also post data there and some other details about specific aspects of the replications. For the journal article replications, you will replicate some parts of the papers, not all of them (for example, one has a 66 page appendix...you're not replicating that part). So make sure to look in Moodle for those details. I am going to hold off on posting some details until people get to those parts so that I can modify things if needed. Remember that you are working via GitHub and you should @jrlhost in your commit messages or comments if you want me to check something out (e.g., help you figure out a problem, look at something you're finished with). 
