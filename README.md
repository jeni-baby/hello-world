# hello-world
I document my learnings from the https://guides.github.com/activities/hello-world/ guide here.

## Surprise between "'Create a Repository' and 'Create a Branch'" steps.
1. I complete the *To create a new repository* steps including:
- Completing a web form with values for Repository name, *hello-world*, and value for Description *I document my learnings from the https://guides.github.com/activities/hello-world/ guide here.* (I suppose this was the description of the repository - a concept I'm yet to truly appreciate.)
- I check the *Initialise this repository with a README* checkbox.
- I select the *Create repository* button.
2. I observe the https://github.com/jeni-baby/hello-world/tree/master page that loads after creating a repository, noting:
- I saw the description I had entered. I saw the URL was rendered clickable.
- I noticed the jeny-baby/hello-world thing. I don't quite know what this means. Is jeny-baby a namespace in which the hello-world project exists?
- There's a dropdown in for branches. It contained only master branch at this time.
- **I did not notice the number of commits, nor the number of branches at this time**
3. I complete the *To create a new branch* steps including:
- I click on the Branch dropdown to see a dropdown list containing a lot of detail, including:
-- an input box watermarked *Find or create a branch*. 
-- a dropdown list item labelled master. I assume this is how existing branches are displayed. You can use the input box to find existing branches using the input as a search, or use it to create a new branch name.
- I enter the branch name suggested, "readme-edits".
- I see the dropdown item labelled master is not there
- I see a new dropdown item labelled *Create branch: readme edits (from master)*
- I select that dropdown item. 
4. I observe I am now on https://github.com/jeni-baby/hello-world/tree/readme-edits 
- I see the branch dropdown now has readme-edits in context, instead of master.
- I observe nothing different from the master branch except:
-- There is something saying there are two branches. 
-- **There is something saying there's one commit!**
Who made that commit?

## Could it be that the flow is as follows:
1. On click of create repo a repo is created with a default branch master
2. A README.md file is created and has the values of repo name and description into the README.md flile with some formatting
3. The README.md file is committed and pushed to master on Create of repo.
If this is the case then I could have seen the number of commits before I created a branch. I might have to retest this.
