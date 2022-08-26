# sample
simple text documents for testing git commands

hello, local commit here

# get last 2 entries
git log -2

# after 1 local commit show that local main branch is pointing to a different ref than the remote
git show-ref main

# now push local to remote
git push
git show-ref main

# force a push, ignoring the remote changes
git push -f

# use git fetch to get remote changes and merge with local changes of there is a conflicts

you fetch and merge, then you push
git fetch
git merge
git push


you pull, then you push
pull = fetch and merge
git pull
git push

# rebasing with a remote
