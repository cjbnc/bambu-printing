# Bin dir

This is a helper script that copies my latest profile files from my user
directory into this repo. It uses the `.env` file located in the parent
directory to load the source path. I left an example file `.env.example`
with my personal info removed.

Usage:

```
bin/copy_from_bambu
git status
    - observe the files that have changed/added
git add profiles
git commit
git push
```

