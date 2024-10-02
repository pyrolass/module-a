# module-a

## to clone the repo

```bash
git submodule add https://github.com/pyrolass/module-b.git
```

## removing the submodule

```bash
git submodule deinit -f module-b
```

```bash
git rm -f module-b
```

```bash
rm -rf .git/modules/module-b
```
