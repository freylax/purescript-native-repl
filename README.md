# purescript-native-repl
demonstration of purescript-native-cpp repl

# How to build?

```bash
# Install Git
# Install Haskell Stack
# Install psc-package
# Install purescript native cpp transpiler 'pscpp'
# from git@github.com:andyarvanitis/purescript-native.git

# build 'purs' purescript compiler from 
# git@github.com:freylax/purescript.git
# this adds the native backend to the purs repl command

# check out this repo

git clone git@github.com:freylax/purescript-native-repl.git
git submodule init
git submodule update

cd purescript-native-repl

# Install the PureScript dependencies.
psc-package install

# launch the repl
make repl

> import Prelude
> 1 + 2

# this will build the executable and call it
