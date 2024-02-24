# mern-basics

node-js basic app with react and mongodb

## To run submodules

If both node-basics and react-basics are part of your single project and you've added them as submodules in your mern-basics repository, you can manage them as part of your project. Here's how you can work with them:

Clone your mern-basics repository: If you haven't already, clone your mern-basics repository to your local machine.

    bash

`git clone <url-to-mern-basics>`

Initialize and update submodules: After cloning, initialize and update the submodules to fetch their contents.

bash

`git submodule init`
`git submodule update`

Navigate to the submodule directories: You can now navigate to the submodule directories (node-basics and react-basics) and work on them as part of your project.

`cd node-basics`

- work on node-basics

`cd ../react-basics`

- work on react-basics

Make changes and commit: Make changes to your submodules as needed. Remember, changes made within the submodule directories need to be committed separately from the main repository.

Update submodules in the main repository: If you make changes to the submodules and want to update the main repository to reflect those changes, you need to commit the changes in the submodule and then update the main repository.

`git add .`
`git commit -m "Made changes in submodules"`
`git push origin main`

Pulling changes in submodules: If there are changes in the submodules that you want to pull into your main repository, you can do so by updating the submodules and then committing the changes in the main repository.

`git submodule update --remote`
`git add .`
`git commit -m "Updated submodules"`
`git push origin main`

By managing your project with submodules, you can keep your frontend and backend codebases separate while still working on them as part of the same project.
