---
title: Pushing all branches
date: 2015-09-02
author: Jojo Hall
tags: git
---

Say you want to push up an existing repository to a new remote on your favourite repository hosting service. You can use the following command if you want to make sure you include all branches:

```
git push <REMOTE-NAME> --all
```

This is especially helpful when you want to immediately create some PRs!

To push all tags:

```
git push <REMOTE-NAME> --tags
```


