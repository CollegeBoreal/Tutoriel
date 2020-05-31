# Installation

## :a: Install with Package Managers

:pushpin: Windows

```
PS > choco install ghc haskell-stack
```

:pushpin: Apple

```
$ brew install ghc cabal-install haskell-stack
```
  
:strawberry: ou :penguin: Linux

```
$ sudo apt-get install haskell-platform
```


## :ab: Manual Install

### :m: Install

```
% curl https://get-ghcup.haskell.org -sSf | sh
```

### :m: Env Variable (~/.bashrc or ~/.zshrc)

```
[ -f "${GHCUP_INSTALL_BASE_PREFIX:=$HOME}/.ghcup/env" ] && source "${GHCUP_INSTALL_BASE_PREFIX:=$HOME}/.ghcup/env"
```