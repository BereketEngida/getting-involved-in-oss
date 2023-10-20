# Git

Git is a version control system that allows us to track changes, collaborate with other, undo mistakes and manage code history.

## Common Git Operations

[Initialization] -> [Staging] -> [Committing]

**Initialization**

```sh
git init
```

Initialize a new git repository. It'll create a hidden .git folder that'll hold our code history.

**Staging**

```sh
git add .
```

Prepares our changes to be committed. The "." is to specify to stage the whole directory.

**Committing**

```sh
git commit -m "first commit"
```

Commits the changes we made to the git history. the `-m "first commit"` is to specify a commit message.

**Remote**

```sh
git remote add origin git@github.com/example/example.git
```

Adds a remote location where we can push and pull our repository.

**Push**

```sh
git push -u origin main
```

This let's push changes to remote repository.

**Pull**

```sh
git pull
```

This let's us pull changes from a remote repository.

**Branch**

```sh
git branch
```

Allows you to change a code and push changes within a repository without affecting other branches.
