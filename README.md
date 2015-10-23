# Blackjack

A blackjack simulator in Haskell with support for generating an optimal policy of play using reinforcement learning..

GPLv2 license.

### Blackjack variation

This simulator plays one deck blackjack. The dealer always hits on
soft 17. Blackjack pays out 1.5x the original bet. Players may hit or
stand.

## Usage

$ ghc Blackjack.hs
$ ./Blackjack


## Exploration vs Exploitation

Supports epsilon-greedy and greedy algorithms.

