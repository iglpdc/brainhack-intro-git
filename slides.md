class: center, middle, inverse

# Intro to Git & GitHub

---

# Agenda

- Configure `git`
- Create a local repo for your project
- Share your repo on GitHub
- Contribute to a project on GitHub

---
class: center, middle, inverse

# Configure `git`

---

Identify yourself

```
$ git config --global user.name "your_name"
$ git config --global user.email "your_email"
```

On macOS and Linux

```
$ git config --global core.autocrlf input
```

On Windows

```
$ git config --global core.autocrlf true
```

Choose an editor for commit messages

```
$ git config --global core.editor "nano -w"
```

More editor choices in [this page](http://swcarpentry.github.io/git-novice/02-setup/)
---

# Exercise

Check your configuration with:

```
$ git config --global
```

---
class: center, middle, inverse

# Create a local repo

---

Initial setup
```
$ mkdir my_project
$ cd my_project
$ git init
```

Commit cycle
```
[ Create files and make changes ]
$ git add (some files)
$ git commit - "Message describing changes"
[ Make more changes and repeat ]
```

Check things
```
$ git status
$ git diff
$ git log
```

---

# Exercise

- Add a new ingredient and modify the recipe
- Create a new commit with these changes
- Use `git log`, `git status`, `git diff` to check things

---
class: center, middle, inverse

# Share your repo on GitHub

---
class: center, middle, inverse

# Contribute to a project on Github

---

# Exercise

- Fork https://github.com/brainhack-boston/brainhack-boston.github.io
- Clone your fork to your `Desktop` and add `upstream` remote
- Create a new branch `your_name-bio`
- In that branch, create a small file `./people/your_name.md` with your name & interests
- Commit and push to your fork
- For GitHub interface, submit a pull request

---

# Resources

- [git-novice](https://github.com/swcarpentry/git-novice)
- [the Git Book](https://git-scm.com/book/en/v2)
