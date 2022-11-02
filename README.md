# Devengers

Collaborators head to the Github Repo page, Git clone the project, and cd into the directory. 

**DO NOT FORK IT!**

What does forking do?

Forking copies a new Repo to your Github page. 

You do not want that - you want to collaborate on the same Github Repo with us.

# Getting Set up

```
**clone with SSH**
git clone git@github.com:deesclouds/Devengers.git

**clone with HTTPS**
git clone https://github.com/deesclouds/Devengers.git

cd Devengers/
```

# Collaborating

**THE MAIN BRANCH SHOULD ALWAYS BE DEPLOYABLE**

The best way to keep the main branch deployable is to create new branches for new features and merge them into Main when they're completed.

# Making a Branch

Branches should always represent features.

ex: ability for user to login should create a branch called 'user_authentication' and that branch should only update what we need to enable a user login.

**Important not to overlap code**

We shouldn't all be working on a 'user_login' branch at the same time someone is working on a 'user_logout' branch since chance are high the code will overlap.

# Create a new branch
```
git co -b create_user

```

```co``` is short for 'checkout' used to switch between branches. Adding the '-b' and a name at the end creates a new branch and then moves into that new branch for us.

Verify this with:
```
git branch
```

***Git add frequently and git commit when finished***

```
git commit -m "Added function to allow Users to say 'Hello World"
```

# Submitting Pull Requests

First determine who's in charge of handling merging. 

Push your branches
```
git branch
```

On the Repo page, you should see the branch you pushed up in a yellow bar at the top of the page with a button to 'Compare & pull request'.

Also can select the branch in the drop-down 'Branch:' menu and select the branch you've just pushed up. Then you'll have a 'Pull request' and 'Compare' button on the right hand side.

