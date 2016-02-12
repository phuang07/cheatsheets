### Some notations
```
HEAD - The current commit
^ - Refers to the commit before; therefore HEAD^ means the commit before the current commit
```

### Uncommit files
```bash
# Just the act of uncommit 
git reset --soft ^HEAD

# The act of uncommit and unstage
git reset ^HEAD

# Resetting everything to the previous commit
git reset --hard ^HEAD
```