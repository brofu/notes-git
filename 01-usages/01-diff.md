
1. **Compare 2 files from different commits**

    ```
    git diff BRANCH:PATH OTHER_BRANCH:OTHER_PATH
    
    //examples:
    git diff branch_a:file_a.txt branch_b:file_b.txt
    git diff HEAD:file.txt a09127a:file.txt
    git diff HEAD:file.txt branchname:file.txt

    // Same as above, but with shortcut-syntax for the currently checked-out commit:
    git diff :file.txt branchname:file.txt

    git diff :file.txt HEAD~4:file.txt

    git diff :file.txt remotes/origin/master:file.txt
    git diff :file.txt remotes/bar/foo~4:file.txt


    or even:

    // diff between main:file1 and current working copy
    git diff main:file1.txt file2.txt

    ```
