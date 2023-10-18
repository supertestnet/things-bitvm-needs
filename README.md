# Things bitvm needs
A todo list for making bitvm great

# Implementations

- [ ] Create github repos for more implementations of bitvm
- [ ] E.g. one in rust
- [ ] E.g. one in python
- [ ] E.g. one in typescript
- [ ] Improve [my javascript implementation](https://github.com/supertestnet/tapleaf-circuits/)
- [ ] Prototype a bisection protocol -- there are no implementations yet!
- [ ] "Translate" more circuit description formats so that bitvm isn't limited to "only" using bristol formatted circuits
- [ ] E.g. here are some other circuit description formats:
- [ ] “ABY format” (described [here](https://github.com/encryptogroup/ABY/blob/public/bin/circ/circuitformat.md), examples [here](https://github.com/encryptogroup/ABY/tree/public/bin/circ))
- [ ] “Fairplay’s Secure Hardware Definition Language (SHDL)” (examples [here](https://github.com/Ethsnarks/ethsnarks-sfdl))
- [ ] “Simple Circuit Description (SCD)” used by the TinyGarble compiler (described [here](https://github.com/esonghori/TinyGarble/tree/master/scd), I can’t find examples, but according to [this document](https://github.com/esonghori/TinyGarble) you can compile TinyGarble to find examples in bin/scd/netlists/).
- [ ] "Verilog Netlists" (pictured [here](https://www.researchgate.net/profile/Kundan-Nepal/publication/220405407/figure/fig3/AS:670715174985734@1536922367281/C17-schematic-and-structural-verilog-netlist.png))

# Programming

- [ ] Develop and document a toolchain for making bitvm applications
- [ ] One possible toolchain: write app in python, export for bitvm using "circuit" and "bfcl" libraries, test/debug/deploy
- [ ] Another possible toolchain: write app in C, export for bitvm using HyCC, test/debug/deploy
- [ ] My current toolchain: find a bristol circuit, test it using a tester I wrote in js, give up if it doesn't work, otherwise convert it to a tapleaf circuit using the procedure outlined [here](https://github.com/supertestnet/tapleaf-circuits/), do a final test, and add a button for it on [this site](https://supertestnet.github.io/tapleaf-circuits/)
- [ ] Make a high level programming language that compiles programs down to the "bristol formatted" logical circuits that bitvm currently uses
- [ ] Make an IDE to help developers design apps by "hooking together" logic circuits that already work in bitvm
- [ ] Contribute to [the chess app](https://github.com/mcbagz/LogicGates/tree/main)
- [ ] Contribute to [the python toolchain](https://twitter.com/rot13maxi/status/1713731080912527404)

# DevEd

- [ ] Make youtube videos documenting how to write apps for bitvm
- [ ] Make text tutorials documenting how to write apps for bitvm
- [ ] Help me improve the visual look and feel of [this showcase](https://supertestnet.github.io/tapleaf-circuits/) of bitvm apps (fork it [here](https://github.com/supertestnet/tapleaf-circuits/), make it better, do a PR)

# Meta

- [ ] Contribute to this todo list with other ideas for making bitvm great (click the Fork button above and do a PR with your changes)
