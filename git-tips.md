## ignore changes to specifc files only on current machine when commit

https://hashrocket.com/blog/posts/ignore-specific-file-changes-only-on-current-machine-in-git

- ignore changes to specifc files only on current machine when commit
`git update-index --skip-worktree [filechanges]` for example `git update-index --skip-worktree README.md`

- list all files ignored on current machine
`git ls-files -v` the file marked with `s` are 

- track change of a file
`git update-index --no-skip-worktree [filechanges]` for example `git update-index --no-skip-worktree README.md`


