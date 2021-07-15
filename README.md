# Formula-Founder

You could install specific version formula in brew.

Simultaneously, you could select specific tap.

Don't use the [git checkout hash] to find previous version formula in homebrew-core.

Perhaps, it will make some errors.

```Shell

sh install_specific_version_formula.sh [formula name] [version] [specific tap, defaut is homebrew/cask]

```

or

```Shell

bash <(curl -s -S -L https://raw.githubusercontent.com/2016321/Formula-Founder/main/install_specific_version_formula.sh) [formula name] [version] [specific tap, defaut is homebrew/cask]

```
