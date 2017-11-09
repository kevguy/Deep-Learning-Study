# Deep-Learning-Study
Study notes

## How Bow Dah Study Group:
 - Kev Lai (Email: kevlai22@uw.edu, Github: [kevguy](https://github.com/kevguy))
 - Christopher Chiu
 - Anakin Yuen
 - Sam Wong
 - Yoyo Wong

## Setup to sync with both Overleaf and Github:
First, clone this project:

```
git clone https://github.com/kevguy/Deep-Learning-Study.git
```

Rename `origin` to `github`:

```
git remote rename origin github
```

Add Overleaf:

```
git remote add overleaf https://git.overleaf.com/11098063wbshnmgsqxst
```

## How to pull updates and commit your changes:
```
git pull overleaf master
git pull github master
```

```
git add -A :/
git commit -am "Your commit message"
```

Push to Github:

```
git push github master
```

Push to Overleaf:

```
git push overleaf master
```

## How to commit your changes the lazy way:
Setup:
```
git remote add both https://git.overleaf.com/11098063wbshnmgsqxst
git remote set-url --add --push both https://git.overleaf.com/11098063wbshnmgsqxst
git remote set-url --add --push both https://github.com/kevguy/Deep-Learning-Study.git
```

Commit and push the changes:
```
git commit -am "Your commit message"
git push both
```

## Reference
- https://ineed.coffee/3454/how-to-synchronize-an-overleaf-latex-paper-with-a-github-repository/
