# Programming with Dependent Additive Pairs

Here you can find the accompanying implementation in the [Janus](https://github.com/svobot/janus) language.

The examples are split into multiple files:
* [Linear list paramorphism](paramorphism.jns) (section 5.1)
* [Linear partition operation with a proof](partition.jns) (section 5.2)
* [Linear insertion operation with a proof](insert.jns) (sections 5.1 and 5.2)
* [Additive inductive lists](additivelist.jns) (section 5.3)
* [Additive coinductive streams](stream.jns) (section 5.3)

## Build Instructions

* Install `ghc` and `cabal` using [GHCup](https://www.haskell.org/ghcup/)
* Download Janus [source code](https://github.com/svobot/janus)
* Build and run Janus by executing `cabal run janusc` in the directory that contains the `janus.cabal` file
* Load the code with `:load file`
  * If the examples are not in the working directory, replace `file` with a path
  * If your terminal has trouble with the Unicode characters, rerun Janus with `cabal run janusc -- --ascii`
* You can exit Janus with `:quit`
