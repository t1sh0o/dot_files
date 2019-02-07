# My dot files

Put these lines in the `.zshrc` to load the other dot files:

```bash
if [ -f ~/.aliases ]; then
    source ~/.aliases
fi

if [ -f ~/.commands ]; then
    source ~/.commands
fi

export XDEBUG_CONFIG="idekey=VSCODE"
export CDPATH=~/projects
```
