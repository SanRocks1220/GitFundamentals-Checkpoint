# Git Fundamentals Checkpoint
### By santiago Andrés Rocha

## git stash list output
stash@{0}: WIP on master: 64389b1 JS y README añadidos


## Conflict 1 on JS
error: Your local changes to the following files would be overwritten by merge:
        main-code.js
Please commit your changes or stash them before you merge.
Aborting
Updating 64389b1..48b43ed

## Conflict 2 on JS
Auto-merging main-code.js
CONFLICT (content): Merge conflict in main-code.js
Automatic merge failed; fix conflicts and then commit the result.

## Conflict Messages
<<<<<<< HEAD
console.log("Hello, World!");
console.log("This will fail!");
=======
console.log("Hello World, Galaxy, Universe!");
>>>>>>> feature-branch

<<<<<<< HEAD
console.log("Hello, World!");
console.log("This will fail!");
=======
console.log("Hello World, Galaxy, Universe!");
>>>>>>> feature-branch