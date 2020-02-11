Here's a condensed version of the GitHub work flow and the corresponding Bash/Terminal commands:

## Starting Up

### Scenario 1. Starting your own repo
> If you are creating a new project, create your repo in the GitHub UI. Otherwise you can skip this step.

### Scenario 2. Contributing to an existing repo where you are not a collaborator
Fork an existing repo

## Local Repo Work Flow

1. Clone the repository you will be working with
> If you are working with a Fork, be sure to clone that repo!

```
git clone <URL from the GitHub UI>
```

2. Create a new branch
```
git checkout -b <branch name>
```

3. Add changes
> Perform this after editing/creating files in your local repo

To add all changes:
```
git add *
```

To add specific changes:
```
git add <path to file>
```

4. Commit changes
```
git commit -m "<Informative message about the changes>"
```

5. Push the changes to create a Pull Request
```
git push origin <Branch Name>
```

6. Use GitHub UI to open the Pull Request and review/approve/merge it

## Other Commands

* Check the changes made to your files in a local repo
```
git status
```

* Get the latest state of a remote repo's branch
```
git master
```

* Switch to another local branch
```
git checkout <Branch Name>
```

* Get changes from a source branch into a different branch 
> e.g. bring updates from master into another branch
```
git merge master
```