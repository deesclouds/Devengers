# Devengers
# Devengers

If you're a collaborator, go to the Github Repo page, Git clone the project, and cd into the directory. 

**Don't fork it!**
Forking will copy it in a new Repo to your Github page, but you don't want that - you want to collaborate on the same Github Repo with your team.

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

Branches should alway represent features.

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