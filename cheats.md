Git Cheat Sheet

(1)  git init      : Tell git to start version controlling the files in a directory
                     (initialises git in a directory)
(2)  git status    : Tell git to print the status of the files in the version 
                     controlled directory.
(3)  git add       : Tell git to start monitoring (tracking) the versions of a new
                     file, e.g. `git add README.md` will tell git to track `README.md`   
(4)  git commit -a : Tell git to save a new snapshot version of all of the tracked
                     files in the directory. The `-a` means "all files". You can
                     commit new versions of individual files if you want, but this
                     is not recommended.
(5)  git diff      : Tell git to show the differences between the files in the working
                            directory and the last saved version in the git repository. This will
                            show the differences for all tracked files. Use
                            `git diff FILENAME` to limit to only the file `FILENAME`
(6) git checkout main FILENAME : Tell git to revert a file back to the last version of `FILENAME` 
                                 saved in the repository
(7)  git log       : Print a log of the versions in the repository. Use `git log -n N`
                             to limit to the last `N` versions. You may need to use `q` to exit
                             from the text viewer if there are a lot of versions to print.
(8)  git mv OLD NEW  : Rename a file from name `OLD` to name `NEW`.
(9)  git rm FILENAME : Remove the file `FILENAME` from the working directory (it still exists
                             in the repository). Will only work if the file is tracked by
                             git and doesn't have any changes. Use `-f` to force removal of files. 
