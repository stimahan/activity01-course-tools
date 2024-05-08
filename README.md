Activity 01 - Course Tools
================

This activity is intended to be completed in over one week, including
outside of class preparation work and two class meetings. Note that if
you are a “dark mode” web browser user, some of the icons in this and
future documents may not be easily viewable to you - I am exploring ways
to fix this.

In this repository/directory, you should see the following items:

- `README-img` - a folder containing images that I am embedding within
  this `README.md` file. You do not need to do anything with this.
- `.gitignore` - a file that is used to specify what Git can ignore when
  pushing to GitHub. You do not need to do anything with this.
- `README.md` - the document you are currently reading.
- `day01-github-rstudio` - a folder that contains items for you to
  complete during the first class meeting.
- `day02-rstudio-rmarkdown` - a folder that contains items for you to
  complete during the second class meeting.

We will explore most of these items over these next class sessions.
Before doing that, you will first make your own copy of this repository.
Note that I will often refer to “repositories” as “repos” (or a single
“repository” as a “repo”) for the rest of the semester.

Before we get too far, I wanted to share with you our tentative schedule
for the semester. I will include this information in your weekly tasks
so you do not need to remember all of this.

## STA 631 Content Schedule

| Week | Topic            | *ISLR* Content                         | *DF* Content |
|------|------------------|----------------------------------------|--------------|
| 1    | Goal Setting     |                                        |              |
| 2    | Course Tools     | (This week)                            | Introduction |
| 3    | SLR              | Ch 1, Sec 2.1 & 2.2, and Sec 3.0 & 3.1 | Ch 1         |
| 4    | MLR              | Sec 3.2 (Mon: Memorial Day Recess)     |              |
| 5    | MLR              | Sec 3.3                                | Ch 2         |
| 6    | Logistic         | Sec 4.0 - 4.2                          | Ch 3         |
| 7    | Logistic         | Sec 4.3.0 - 4.3.4                      |              |
| 8    | Multinomial      | Sec 4.3.5                              | Ch 4         |
| 9    | GLM              | Sec 4.4.0 - 4.4.2                      |              |
| 10   | GLM              | Sec 4.6 - 4.7                          | Ch 5         |
| 11   | Cross-Validation | Sec 5.0 - 5.2                          | Ch 6         |
| 12   | Model Selection  | Sec 6.0 - 6.2, 13.0 - 13.5             | Ch 7         |
| 13   | Portfolio Work   |                                        | Conclusion   |
| 14   | **Finals Week**  |                                        |              |

## Day 1

If you would like more information about GitHub and Markdown, here are
two resources:

- This [Preparation](https://github.com/gvsu-sta518/preparation01) from
  the last time I taught STA 518 has videos that provide more details on
  what Git and GitHub are - though somewhat dated (our world changes so
  much in 3 years), the concepts/ideas remain the same.
- This short (5-10 minutes) interactive [Markdown
  tutorial](https://commonmark.org/help/tutorial/). Note that if you
  took STA 518 with me or have used Markdown to author documents
  extensively in the past, this will be a refresher to you.

### Task 1: Forking the Repository

Read these directions **first**, then work your way through them. Take
things slow and ask questions of your neighbors or me. In this GitHub
repo (i.e., my repo):

1.  Click on the ![fork](README-img/fork-icon.png) **Fork** icon near
    the upper-right-hand corner. You will be taken to a **Create a new
    fork** screen.
2.  Verify that your GitHub username is selected under **Owner** and
    that the **Repository name** is `activity01-course-tools` with a
    green check mark (this verifies that you do not already have a
    GitHub repository with this name).
3.  You may provide a **Description** if you would like. This is a way
    to provide some additional, more descriptive, meta information
    related to the things you did. I like to provide a brief description
    of what happened.
4.  Verify that **Copy the `main` branch only** is selected.
5.  Click on the green **Create fork** button at the bottom of this
    page.

You should be taken a copy of this repo that is in your GitHub account.
That is, your page title should be `username/activity01-course-tools`,
where `username` is replaced with your GitHub username. Directly below
this, you will see the following message:

> forked from
> [gvsu-sta631/activity01-course-tools](https://github.com/gvsu-sta631/activity01-course-tools)

You will complete the rest of this activity in **your** forked copy of
the `activity01-course-tools` repo.

![check-in](README-img/noun-magnifying-glass.png) **Check in**

Take a moment to reflect on what this process is like compared to other
methods you have used for sharing documents with others. Talk through
these with your neighbors.

- Can you sketch out a diagram that relates that previous method/process
  to this GitHub method?
- What was easier about this GitHub method?
- What was more difficult about this GitHub method?

### Task 2: Exploring a GitHub Repository

For our work this semester, we will not worry about Branches or Issues -
though we can look into when working on collaborative items, if you so
desire.

When you view repos on github.com, most will have a similar set up.
There are a lot of icons, text, regions, etc. in every repo and it can
be confusing what exactly you need to do. Whenever we will use a new
feature on GitHub, I will provide you with details of what to do and
what is happening. For the time being, you can focus on two regions of
your new repo.

First, if you are currently reading this text that means that you are
viewing the `README.md` file of this repo. Folk use these files to
[describe the
contents](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)
of their repo in some fashion. For example, all of posit’s package
repositories have a [similar
structure](https://github.com/tidyverse/ggplot2) that at least provide
an overview, installation directions, and usage examples I will use
`README.md` files in STA 631 to describe what is in the repo and provide
directions for how you should interact with it. README files take
information written in Markdown (`.md` files) and formats it to look
nice on a webpage.

Second, directly above the displayed `README.md` document you like saw
an area that looks similar to a folder/directory that you would interact
with on your computer. In fact, once we start to work between RStudio
and GitHub, your directory will be identical to your repo! I like to
think of a GitHub repo as a folder system that others can view/copy/edit
(with permission) rather than needing to zip up an entire folder on my
computer and then send it to another person to work with. Repos can
contain multiple types of files that use various syntax/text and also
include subfolders, sub-subfolders, etc.

Read these directions first, then work through them. Do your best to
complete the tasks/directions by **11:59 pm (EST) on Wed, Jan 17**.

- In your `activity01-course-tools` repo folder/directory, locate and
  click into the `day01-github-rstudio` subfolder.
- In the `day01-github-rstudio` subfolder, you will be greeted by a new
  `README.md` file with your tasks/directions to complete.

The rest of this `README` document contains tasks/directions for the
next class meeting.

## Day 2

**Do not proceed in this document until you have affirmed**…

(Note that you do not need to do any of the exercises in these links - I
am providing them as resources)

- What the main uses for each region/pane in RStudio:
  <https://r4ds.had.co.nz/introduction.html#rstudio>.
- What an Rmarkdown file is, how to run code in an Rmarkdown file or
  Console, and how RStudio helps notify you of potential problems in
  your code: <https://r4ds.had.co.nz/workflow-scripts.html> and
  <https://r4ds.had.co.nz/r-markdown.html> .
- What RStudio Projects are, determining where things “live” in RStudio,
  and the benefits of beginning each R session from a “vanilla”
  (sessions that do not retain information from previous sessions):
  <https://r4ds.had.co.nz/workflow-projects.html>.

### Task 1: Force a clean RStudio session

To help us reduce as many unnecessary issues as possible, we will
instruct RStudio to not preserve any information between sessions. This
is a good standard practice. Read these directions first, then work
through them.

1.  In an RStudio session, click on the Tools dropdown menu (along the
    top) and select “Global Options…”
2.  In the Options pop-up window, ensure you are on the General screen
    (left-hand menu item).
3.  In the General screen, **uncheck** the box next to the item that
    specifies to “Restore .RData into workspace at startup”.
4.  Also in the General screen, for the item that specifies to “Save
    workspace to .RData on exit:” select **Never**.
5.  At the bottom of the General screen, click on Apply (to save your
    changes) and OK (to close the pop-up window).

Note that you will need to do this on each “machine” you use RStudio -
the posit Workbench is one machine and if you have RStudio installed on
your personal computer that is another machine.

### Task 2: The activity

Read these directions first, then work through them. Do your best to
complete the tasks/directions by **11:59 pm (EST) on Mon, Jan 22**.

- In your `activity01-course-tools` repo folder/directory, locate and
  click into the `day02-rstudio-rmarkdown` subfolder.
- In the `day02-rstudio-rmarkdown` subfolder, you will be greeted by a
  new `README.md` file with your tasks/directions to complete.

## Attribution

This document is based on David Keyes’ tutorial at [R for the Rest of
Us](https://rfortherestofus.com/2021/02/how-to-use-git-github-with-r/)
and [Happy Git with R](http://happygitwithr.com/) by Jenny Bryan et al.
