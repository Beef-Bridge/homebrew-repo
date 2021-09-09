# Beef-bridge Repo

## How do I install these formulae?
```sh
$ export TAP="Beef-Bridge/homebrew-repo"
$ export MODULE=...  # name of module you want to install, e.g. "php"
$ export VERS=... # version of $MODULE you want to install, e.g., "7.4.12"
$ brew tap-new $TAP
$ brew extract --version $VERS $MODULE $TAP
$ brew install $TAP/$MODULE@$VERS
````

### Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
