# Announcements

Important announcements will be posted here to avoid our inboxes getting clogged up.

If you have questions - direct them to us via [Slack](https://pp4rs.slack.com). There's a 'Direct Message' feature so you can contact us individually as needed, but where possible post messages to a channel that all participants can see.

!!! note "Example Final Assignment"
    *Date Posted: 2019-01-24*

    Lachlan has constructed an example final assignment.

    It uses only R packages that were taught in the course, or available in the additional material and a simplified Snakemake set up (particularly for the pdf generation).

    You can check it out [here](https://github.com/lachlandeer/angrist-krueger-1991) 

!!! bug "Final Assignment"
    *Date Posted: 2019-02-21*

    Detail about the course assignment:

    * Due date: Saturday, March 16 at 23:59.
    * Discuss with one of us your proposed assignment before you start
        * We can evaluate whether it is do-able within the time frame
        * Don't try and be too fancy, it's more important that it works
    * The assignment must:
        - Produce at least one figure and one table of results that are saved to file
        - Do some form of data cleaning / manipulation as part of the workflow
            - The initial "dataset" cannot be the one that generates the regression / figures
        - Use `Snakemake` to execute the workflow
    * Submission format: Invite @lachlandeer to collaborate on your GitHub repository by the due date. He will potentially allocate another instructor to assess your work.
        * This means, we expect well version controlled work.
        * Tag your final submission using the following git command `git tag -a v1.0 -m "submitted version"`
        * You must have a README.md in the main directory with instructions on how we can build the assignment & what it does.
    * Explictly document somewhere what packages we need to install so that your assignment runs on our machine with no issues.
        - *Even better*: use the scripts we provided in the Snakemake example to install needed packages for us
    * Your assignment must execute by us typing:
        * `snakemake` (preferred)
        * `snakemake all`
      into a terminal that is opened into your project's directory
    * To pass the course:
        *  Your code must build without errors (unless we find something really weird, then we will reach out to you)
        * Must be version controlled, with each contributor making commits. One final commit is not enough.
        * Inputs and outputs must be in separate folders

!!! note "Welcome Message"
    *Date Posted: 2019-01-21*

    Welcome to the course "Programming Practices for Research in Economics: Foundations.""

    Please take a look around the [course website](https://pp4rs.github.io/2019-foundations-uzh) before the course begins. All the latest information about the course contents, schedule and course locations (which vary day-by day!) are available on these pages.

    We particularly draw your attention to the:

    *  **[Installation Guide](https://pp4rs.github.io/foundations-installation-guide/)**. These pages walk you through the steps needed to install all the software for the course.
        * We expect you to have completed it before the course begins.
        <!-- * We are offering help to individuals struggling with the steps involved in the installation guide in a 'Help Session' before the course begins: Friday, August 25th, between 9.30 and 12.30 in [SOF-E-09](https://www.openstreetmap.org/way/33806996). -->
            * Note that we expect you have tried to complete the guide yourself, and we will not be there to do it all for you.
            * The guide is modular in nature - with most steps being independent of those before and after.
            * Learning to install software for scientific research on your own machine is an important task in itself - and we want to help you become self-sufficient in this regard.
    * **[Pre-Course Survey](https://goo.gl/forms/wtJZnHpzsDsYUYsR2)**.
        * Please fill this out before the course begins.

    To avoid clogging up everyone's inboxes with course email, all future important information will be posted on the course's [Announcements page](https://pp4rs.github.io/2019-foundations-uzh/announcements) - be sure to check in there regularly. Smaller pieces of information and course chat will take place inside a chat enviroment, called [Slack](https://www.slack.com). Sign up to join the conversation [here](https://pp4rs.slack.com).

    We look forward to seeing you on Wednesday, February 13th at 9.30am.

    Best,

    Lachlan and Julian



<!-- HERE IS AN EXAMPLE NOTE BOX -->
<!-- !!! note "YOUR NOTE NAME"
    *Date Posted: YOUR DATE*
    YOUR TEXT -->
