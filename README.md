# title

woah man nice bod

what to do when you gotta make some changes:

1) make the goddamn changes
2) save them on vs code
3) "git add ."
4) "git commit -m ${message} -m ${message description}"
5) "git push origin master"
    5.5) if origin causes an error -> "git remote add origin ${git ssh url}"

# trials

how to merge: terminal -> git merge ${name of branch you want to merge with the branch you're on}
how to save to current branch: terminal -> git push --set-upstream origin ${the branch you're on}

## branches

# how to find out which one you're @
terminal -> "git branch"

# how to add a brand-new never before seen unique as crip branch
terminal -> "git checkout -b '${descriptive af branch name}' "

# how to snake between branches
terminal -> "git checkout ${the name of the branch you want to go to}"

# after merging (on github)
terminal -> "git pull origin master" / "git pull" (if you already have an upstream on)

# delete a branch
terminal -> git branch -d ${name of the branch you want to delete}