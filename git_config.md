# Git config

### Generate ssh keys
```
$ ssh-keygen 
```

### Global name and e-mail config
```
$ git config --global user.name "Yevhen Radionov"
$ git config --global user.email "eugene.radionov@gmail.com"
```

### Global gitignore
1. Create the file at ~/.gitignore_global
2. Add rules
3. run `$ git config --global core.excludesfile ~/.gitignore_global` to set up the rules

### Alias for pretty `git log`
```
$ git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
```
