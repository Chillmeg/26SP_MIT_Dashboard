# Terminal shortcuts for semester repos

## Add to ~/.zshrc

Set your semester root path, then define helper commands.

```sh
export SEM_ROOT="/Users/qilmegdoudatcz/26_spring"

c() { cd $SEM_ROOT/$1/repo; }
s() { cd "$SEM_ROOT"; }
clist() { ls -1 "$SEM_ROOT"; }
```
