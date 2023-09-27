# Git - Getting Started

```sh
> mkdir test
> cd test
> git init

Initialized empty Git repository in test/.git/
```

At this point you may notice a new, hidden directory created
in the current folder. Let's take a look.

```sh
> ls -F .git

HEAD
branches/
config
description
hooks/
info/
objects/
refs/
```

Hopefully by the end of this guide some of those files
won't seem so cryptic, and you will know what they do.

## Terminology

- The `.git` folder is referred to as the "repository" or
  **"local repository"**
- The directory above the `.git` folder, where you edit your
  actual files, is called the "working directory" or **"workspace"**
- Refer to [Git Lifecycle diagram](images/git-transport.png)

## Summary of commands

```sh
mkdir -p test; cd test;
git init; ls -F .git;
```

## Warning

For the purposes of this guide we will be poking
around in this folder from time to time. Given that we just
created this repository, and we're not using it for anything
real, it's completely safe.
In fact, it's even _encouraged_ - there's no better way to
learn how Git works. :)

That said, in general it is _highly_ recommended not to
touch anything in this folder normally, as it may result in
data loss or corruption.

## Next

Let's start by learning about [commits](commit.md).
