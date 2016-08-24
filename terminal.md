# Terminal tips


> *160824*

### Open a file in root directory:
```
atom ~/<file-name>
```
Example: (opens ZSH config file)
```
atom ~/.zshrc
```

### Run ESLint
(Put this inside terminal config file (`~/.zshrc` or `~/.bash_profile`)):
```
alias lint="./node_modules/.bin/eslint ./src ./test"
```
