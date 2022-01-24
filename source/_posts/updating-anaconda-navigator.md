---
title: Updating Anaconda Navigator
tags:
  - anaconda
  - conda
id: '63367'
categories:
  - - note to self
date: 2021-03-25 14:50:33
---

For whatever reason my installations of Anaconda Navigator always refuse to update through the GUI. No matter how many times I click the Yes to upgrade, nothing happens.

So finally I found 15 seconds where I was both tired of this situation and had the clarity of thought to do something about it.

```
conda deactivate
conda update anaconda-navigator
```

Problem solved. Sigh.

_Source: [Updating Navigator — Anaconda documentation](https://docs.anaconda.com/anaconda/navigator/update-navigator/)._