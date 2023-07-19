# :hammer_and_wrench: Git

### :pushpin: Daniel Felipe Hernández Mancipe

<br/>

1. Create a new repository 

2. Create a README file 

    - Create a new file called `README.md` and write your name in it. 

    - Create another called `main-code.js` and add some small piece of code (a hello-world or something like that)

    - Save the changes and commit it to your main branch

        ![first commit](../media/screenshot1.png?raw=true)

3. Create a new branch: 

    - Create a new branch named `feature-branch`. 

    - Switch to the newly created branch 

        ![feature-branch](../media/screenshot2.png?raw=true)

4. Make changes and commit: 

    - Open the `main-code.js` file and make a small change (change a variable name or a value). 

    - Save the changes and commit them to the `feature-branch`. 

        ![feature-branch commit](../media/screenshot3.png?raw=true)

5. Switch back to the main branch: 

    - Switch back to the `main` branch 

    - Open the `main-code.js` file again and make a small change. 

    - Save the changes but don't commit them.

        ![small change in master](../media/screenshot4.png?raw=true)

6. Stash some changes 

    - Stash the changes. 

    - Using `git stash list` copy the output and save it in the `README.md` file

       ![git stash list](../media/screenshot5.png?raw=true)

    - Unstash your stashed changes. 

        ![git stash pop](../media/screenshot6.png?raw=true)

6. Merge conflict resolution: 

    - Still on your main branch 

    - Merge the `feature-branch` into the `main` branch 

        ![merge conflict](../media/screenshot7.png?raw=true)

    - Resolve the merge conflict that arises in the `main-code.js` file. Copy the conflict part and add it to `README.md`. 

        ![resolving merge conflict](../media/screenshot8.png?raw=true)

7. Finalize and submit: 

    - Push your changes to your remote repository 

        ![push](../media/screenshot9.png?raw=true)

Optional: Add any issues your ran into or any comments you want into `README.md` and how you fixed them.

 - The command `git config --local --edit` had to be used to properly configure the credentials

 - The `media` branch is used to host the media files used by `README.md`
