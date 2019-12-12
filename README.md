# hello-world
I document my learnings from the https://guides.github.com/activities/hello-world/ guide here.

## Surprise between "'Create a Repository' and 'Create a Branch'" steps.
1. I complete the *To create a new repository* steps including:
    1. Completing a web form with values for Repository name, *hello-world*, and value for Description *I document my learnings from the https://guides.github.com/activities/hello-world/ guide here.* (I suppose this was the description of the repository - a concept I'm yet to truly appreciate.)
    1. I check the *Initialise this repository with a README* checkbox.
    1. I select the *Create repository* button.
1. I observe the https://github.com/jeni-baby/hello-world/tree/master page (I've noticed that https://github.com/jeni-baby/hello-world is the page that shows the number of commits. I'm not sure what that means about this observation.) that loads after creating a repository, noting:
    1. I saw the description I had entered. I saw the URL was rendered clickable.
    1. I noticed the jeny-baby/hello-world thing. I don't quite know what this means. Is jeny-baby a namespace in which the hello-world project exists?
    1. There's a dropdown in for branches. It contained only master branch at this time.
    1. **I did not notice the number of commits, nor the number of branches at this time**
1. I complete the *To create a new branch* steps including:
    1.I click on the Branch dropdown to see a dropdown list containing a lot of detail, including:
        1. an input box watermarked *Find or create a branch*. 
        1. a dropdown list item labelled master. I assume this is how existing branches are displayed. You can use the input box to find existing branches using the input as a search, or use it to create a new branch name.
    1. I enter the branch name suggested, "readme-edits".
    1. I see the dropdown item labelled master is not there
    1. I see a new dropdown item labelled *Create branch: readme edits (from master)*
    1. I select that dropdown item. 
1. I observe I am now on https://github.com/jeni-baby/hello-world/tree/readme-edits 
    1. I see the branch dropdown now has readme-edits in context, instead of master.
    1. I observe nothing different from the master branch except:
        1. There is something saying there are two branches. 
        1. **There is something saying there's one commit!**
Who made that commit?

## Could it be that the flow is as follows?
1. On click of create repo a repo is created with a default branch master
2. A README.md file is created and has the values of repo name and description into the README.md flile with some formatting
3. The README.md file is committed and pushed to master on Create of repo.
If this is the case then I could have seen the number of commits before I created a branch. I might have to retest this.
