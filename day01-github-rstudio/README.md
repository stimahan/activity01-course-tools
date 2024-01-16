Day 1 - GitHub and Markdown
================

In this repository/directory you should see two items:

- `README.md` - this document.
- `activity01-day01.pdf` - a PDF document that you will think critically
  about shortly.

## Task 1: View the PDF in GitHub

Read these directions first, then work through them.

1.  Locate and click on the `activity01-day01.pdf` file to view it. You
    might want to open this in a separate/new tab so that you can easily
    switch between this `README` file and the PDF document.
2.  On a piece of scrap paper or in a document on your computer, specify
    the different ways this document has been formatted using Markdown.
    Note that I tried to incorporate most of the Markdown skills that I
    use in my typical workflow. Can you identify them all?

![check-in](../README-img/noun-magnifying-glass.png) **Check in**

Take a moment to reflect on what this process is like compared to other
methods you have used for sharing documents with others.

- Did you identify 11 unique Markdown skills being used in the PDF? Try
  hovering your mouse over the text in the final bullet point in the PDF
  if you are only coming up with 10 skills.
- A more comprehensive guide to use Markdown syntax can be found on the
  [Markdown Guide](https://www.markdownguide.org/basic-syntax/) page
  along with best practices and cautions. What are two or three “Best
  Practices” that you weren’t aware of and will make an effort to pay
  attention to in your work for the next month?

## Task 2: Clone GitHub repo

In your preparation for today, you connected RStudio and GitHub. If you
are experiencing issues, get a hold of me or a classmate, or verify that
you have successfully set up RStudio and GitHub to communicate by
redoing [this
preparation](https://github.com/gvsu-sta518/preparation02). **Do not
move on in this activity until you have completed this prep.**

Now that RStudio and GitHub are communicating, we can clone your repo!
In GitHub language, *cloning* means to make a copy of your GitHub repo
on your local computer (i.e., your RStudio/RStudio Workbench session).

![check-in](README-img/noun-magnifying-glass.png) **Check in**

Answer each of these questions:

- What does *forking* in GitHub mean? Hint, it is not the prank you
  might have done in high school where you stuck a bunch of diningware
  forks into someone’s front yard.
- How do *forking* and *cloning* differ?

Now, follow these directions to clone your GitHub repo:

1.  In RStudio, click on the
    <img src="../README-img/rproj-icon.png" alt="RStudio Project" width = "20"/>
    icon (the icon below the Edit drop-down menu).
2.  Click on **Version Control** on the *New Project Wizard* pop-up.
3.  Click on **Git** and you should be on a “Clone Git Repository” page.
4.  Back to your `activity01-course-tools` GitHub repo (you might need
    to go back a page), click on the green **Code** button near the top
    of the page.
5.  Verify that **HTTPS** is underlined in orange/red on the drop-down
    menu, then copy the URL provided.
6.  Back in RStudio, paste the URL in the “Repository URL” text field.
7.  The “Project directory name” text field should have automatically
    populated with `activity01-course-tools`. If yours did not, click
    into this box and press Ctrl/Cmd (this is usually an issue on Macs);
8.  In the “Create project as subdirectory of” field, click on
    **Browse…**. Create a **New Folder** called “STA 631”, then within
    this folder, create a **New Folder** called “Activities”, think
    click **Choose**. Note that I am forcing you to use my opinionated
    file system management style.
9.  Click on **Create Project**.

Your screen should refresh and the **Files** pane should say that you
are currently in your `activity01-course-tools` folder that currently
has the same files and folders as your GitHub repo. If you are asked for
your GitHub credentials, provide your GitHub username and your PAT (not
your password).

## Task 3: Create, Edit, Commit, and Push

Next we will create a new file (well, open a new-to-you file) and see
how to commit these changes and view the commit history using RStudio’s
graphical user interface.

1.  In the **Files** pane in RStudio (lower right-hand pane), navigate
    to within the `day01-github-rstudio` folder and click on to open the
    Rmarkdown file named `activity01-day01-r.Rmd`.
2.  Follow the directions in the **Introduction** section of this
    Rmarkdown file, then return back to these steps and finish the
    process of committing and pushing to GitHub.

**You should currently be doing work in the `activity01-day01-r.Rmd`
file.**

3.  In the **Git** pane (upper right-hand pane), check the box next to
    **all** items listed (under the “Staged” column) and click on
    <img src="../README-img/commit-icon.png" alt="commit" width = "20"/>
    **Commit**.
4.  In the pop-up, provide an informative commit message, like
    `Adding some calculations`, then click on **Commit**.
5.  In this same pop-up, switch from **Changes** to **History**
    (upper-left corner). Reflect on how this way of looking through your
    commit history compares to GitHub. Feel free to add more to your R
    script, save, and commit.
6.  To update GitHub with these changes, in the **Git** pane of RStudio
    click on
    <img src="../README-img/push-icon.png" alt="push" width = "20"/>
    **Push**. When/if asked for your GitHub credentials, provide your
    GitHub username and GitHub PAT (not your password). This should,
    hopefully, be the last time you need your GitHub PAT, but I again
    encourage you to keep this in a secure place.
7.  Go back to your `activity01-course-tools` GitHub repo and verify
    that your `activity01-day01-r.Rmd` AND `activity01-day01-r.md` files
    are here (you knitted your document, correct?)

## What is next?

On **Day 2** of this activity, we will update this workflow to include
how we can work between GitHub and RStudio by creating a website.
