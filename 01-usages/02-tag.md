
1. **List Tags by Create Time**
    ```
    git tag --sort=-creatordate 

    ```
    or 
    ```
    git for-each-ref --sort=creatordate --format '%(refname) %(creatordate)' refs/tags
    ```
    
