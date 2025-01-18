# Git Features?
- Decentralized / distributed repository but can be centralized as well
- Awesome scale
- Superfast as most operations are local
- Free and open source
- Huge community
- Wide adoption for version control

# Git Basics

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
<br>

To add a multiline commit message, we can use the above command without the `-m` tag to open an editor:
```
git commit
```

## View All Commits
To view all commits, use this command:
```
git log
```
<br>

The above command prints a lot of information. I found this command more useful than the above one as it only prints commit id and commit message for all commits.
```
git log --oneline
```