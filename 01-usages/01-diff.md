
1. **Compare 2 files from different commits**

    ```
    git diff BRANCH:PATH OTHER_BRANCH:OTHER_PATH
    
    //examples:
    git diff branch_a:file_a.txt branch_b:file_b.txt
    git diff HEAD:file.txt a09127a:file.txt
    git diff HEAD:file.txt branchname:file.txt

    // Same as above, but with shortcut-syntax for the currently checked-out commit:
    git diff :file.txt branchname:file.txt


    ```
