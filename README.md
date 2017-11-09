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

(Optional: for lazy asses like [kevguy](https://github.com/kevguy))
```
git remote add both https://git.overleaf.com/11098063wbshnmgsqxst
git remote set-url --add --push both https://git.overleaf.com/11098063wbshnmgsqxst
git remote set-url --add --push both https://github.com/kevguy/Deep-Learning-Study.git
```

## How to pull updates and commit your changes:
### For changes made on Overleaf
Let's say you've made some changes on Overleaf, then locally:
```
git pull

# OR
git pull overleaf master
git pull github master
```

If you did the lazy setup, run this and you are done:
```
git push both
```

Otherwise, push to Github:

```
git push github master
```

Then push to Overleaf:

```
git push overleaf master
```

### For changes made locally
```
git pull

# OR
git pull overleaf master
git pull github master
```

Then commit your code:
```
git add -A :/
git commit -am "Your commit message"
```

If you did the lazy setup, run this and you are done:
```
git push both
```

Otherwise, push to Github:

```
git push github master
```

Then push to Overleaf:

```
git push overleaf master
```

## Reference
- https://ineed.coffee/3454/how-to-synchronize-an-overleaf-latex-paper-with-a-github-repository/
