#GIT Commands

### Create .git folder
```git init```

### Add origin
```git remote add origin {repoAddress}```

### Add file to git
```git add {fileName} or git add .```

### Commit file to git
```git commit -m 'first message'```

### See branches
```git branch```

### Create branch from another branch
```git branch {newBranchName} {oldBranchName}```

### Git auth by deploy key
```
ssh-keygen -t ed25519 -C "email@email.com"

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
#ssh-add /c/Users/USERNAME/.ssh/id_ed25519 - For Windows

#copy key by writing in terminal and 
#add it to Github->Settings->Deploy Keys
cat ~/.ssh/id_ed25519.pub
#cat /c/Users/USERNAME/.ssh/id_ed25519.pub - For Windows
```

### Push files to GIT
```git push origin {branchName}```

### Switch branches
```git checkout {branchName}```