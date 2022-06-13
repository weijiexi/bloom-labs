---
layout: default
---

# Code signal Arcade

```
rm -rf labs-arcade
rm .gitmodules
rm -rf .git
git init
git branch -M gh-pages
git remote add origin git@github.com:rjgeng/bloom-labs.git

git add .
git commit -m 'first commit'
git push origin gh-pages --force
```
