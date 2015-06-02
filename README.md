ilastik-meta

Small repo for tracking compatible versions of the ilastik subprojects via git submodules.

Initialize with:

```
#!bash
git submodule init
git submodule update --recursive
git submodule foreach "git checkout master"
```

