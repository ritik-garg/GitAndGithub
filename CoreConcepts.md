# Git Features?
- Decentralized / distributed repository but can be centralized as well
- Awesome scale
- Superfast as most operations are local
- Free and open source
- Huge community
- Wide adoption for version control

# Git Basics
## Initialisation
To create a new repository in local, use the following command:
```
git init <repositoryName>
```
<br>

If you are already in a folder, use this command to create a git repositry:
```
git init
```

## Check Status
This command returns the current state of the tracked files by git:
```
git status
```

## Add Files for Staging
This command add files for staging. Simple regex can also be used in place of *fileName*
```
git add <fileName>
```
<br>

To add all the files:
```
git add .
```

## Commiting a Change
```
git commit -m "<commitMessage>"
```