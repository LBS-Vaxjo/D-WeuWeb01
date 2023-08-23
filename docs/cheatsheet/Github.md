---
status: new
title: Github
---

# Github Cheatsheet

## Workflow

=== "Skapa Repository"
    
    När du skapar en ny repository, så behöver du göra det bara en gång, antingen lokalt och sen pusha till github, eller genom att clona en repository du redan skapat i github.
    
    === "init"
            $ git init (1)
        >   Ändra en Mapp som redan finns till en git repository
            Turn an existing directory into a git repository
    === "clone" 
    
            $ git clone [url]
        >   Clona (ladda ner) en repository som redan finns på Github,
            med alla dess filer, branches och commits
    Clone (download) a repository that already exists on Github,
    including all of the files, branches and commits
    ---
    When starting out with a new repository, you only need to do it
    once; either locally, then push to GitHub, or by cloning an
    existing repository.



=== "Sync Changes"
    === "Add"
        # git Add

        ```git
        git add {file/s}
        ```

    === "Commit"
        # git commit

        ```
        git commit -m "message"
        ```

    === "Push"
        # git push

        ```
        git commit -m "message"
        ```

    === "fetch"
        # git fetch

        ```
        git commit -m "message"
        ```


    === "pull"
        # git pull

        ```
        git pull
        ```
