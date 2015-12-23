# banacorn/agda

## How to run this with agda-mode

1. Set `docker` as the path of Agda
2. Add the following line as arguments for `docker` (replace `/Users/banacorn/` with the path where you want to mount your files)

```
run -i --rm -v /Users/banacorn/:/Users/banacorn/ banacorn/agda agda
```

For example, the Settings in [agda-mode for Atom](https://atom.io/packages/agda-mode)
![settings](http://i.imgur.com/OuNqtD5.png "Settings in agda-mode for Atom")
