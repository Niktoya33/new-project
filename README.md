# new-project

Instructions for setting up a repository.

1. Create an **empty** repository on a GitHub.
2. Copy repository link under a **Code** button.
3. Navigate to your local working directory.
4. Type the following to the command line, one-by-one:
```
git init new-project
cd new-project
git remote add origin <insert-repository-link>
git branch development
git checkout development
```
5. After making and staging a couple changes you may commit and push them with
```
git commit -m "<enter-message-here>"
git push -u origin development
```
