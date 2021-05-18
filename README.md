# git_common_operations
## Reset
* Remove last commit, keep the index tree, and keep the changes: `git reset --soft HEAD^`
* Remove last commit, remove the index tree, and keep the changes: `git reset HEAD`

Ref: [1](https://stackoverflow.com/questions/24568936/what-is-difference-between-git-reset-hard-head1-and-git-reset-soft-head#:~:text=Let's%20find%20out!-,soft,commit%20you%20%22removed%22%20before.)

* ignore files that have already been committed to the repo: https://www.git-tower.com/learn/git/faq/ignore-tracked-files-in-git/
