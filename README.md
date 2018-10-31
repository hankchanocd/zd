# zd

> A better `cd` and `z` that goes to directory with `fzf`

`z` is excellent at `cd` into the frequently visited paths, but it doesn't alway go to the directory you want to, especially when the desired directory is overshadowed by the more used directories with the same name. `zd` tries to tackle that by giving users all the results it can find with `fzf`.

But we also know traversing the whole machine is unrealistic, so we make `zd` traverse only the common paths by default. If unsatisfied with the traversed result, users can always add paths to `zd`'s considerations.

## Usage

```bash
$ zd Github
```

```bash
$ zd add path
$ zd add .
```
