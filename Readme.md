# Git-flow workflow
It is a version of code used in large projects where a code control is very important, below follows a flow of how it should be:<br /><br /><br /><br />

![alt text](https://github.com/dev-felipe/gitflow-workflow/blob/master/imgs-flowcharts/gitflow-workflow1.png)<br /><br /><br />

## master branch:<br />

This branch has all the ultimate version of the project, the project wich is on production, from master branch, we 
created new branchs for work, the master branch should be merged with new release branches that are ok.<br /><br />


## feature branch:<br />

This branch is about new tasks, new tasks was defined by arquiteture team should be maded in the feature branch, and 
one new task should be has one new feature branch, we can have various features branchs in project.<br /><br />


## develop branch:<br />

Develop branch should be receive merge from new features, for test by development squad, if the tests that are ok, then
develop branch can merge on new release branch, else, return to feature and should be fixed.