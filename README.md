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
- [ ] My current toolchain: find a bristol circuit, test it using a tester I wrote in js, give up if I can't make it work as expected, otherwise convert it to a tapleaf circuit using the procedure outlined [here](https://github.com/supertestnet/tapleaf-circuits/), do a final test, and add a button for it on [this site](https://supertestnet.github.io/tapleaf-circuits/)
- [ ] Make a high level programming language that compiles programs down to the "bristol formatted" logical circuits that bitvm currently uses
- [ ] Make an IDE to help developers design apps by "hooking together" logic circuits that already work in bitvm
- [ ] Contribute to [the chess app](https://github.com/mcbagz/LogicGates/tree/main)
- [ ] Contribute to [the python toolchain](https://twitter.com/rot13maxi/status/1713731080912527404)

# Functions

- [ ] Make a 32 bit multiplier in bitcoin script
- [ ] Make a bunch of functions that help with making a sha256 implementation, such as:
- [ ] Make a function for doing 6 "right rotations" on a 32 bit string (e.g. if the string was 00000000000000000000000111110000, a right-rotation by 6 digits would turn it into 11000000000000000000000000000111 -- it shifts everything over by 6 and moves stuff that "falls off the end" over to the start)
- [ ] Make a function for doing 2 right rotations
- [ ] Make a function for doing 7 right rotations
- [ ] Make a function for doing 10 right rotations
- [ ] Make a function for doing 11 right rotations
- [ ] Make a function for doing 13 right rotations
- [ ] Make a function for doing 17 right rotations
- [ ] Make a function for doing 18 right rotations
- [ ] Make a function for doing 19 right rotations
- [ ] Make a function for doing 22 right rotations
- [ ] Make a function for doing 25 right rotations
- [ ] Make a function for doing 3 "right shifts" on a 32 bit string (e.g. if the string was 00000000000000000000000001111100, a right-shift by 3 digits would turn it into 00000000000000000000000000001111 -- it shifts everything over by 3 and discards anything that "falls off the end")
- [ ] Make a function for doing 10 right shifts
- [ ] Make a sha256 function that "pads" inputs to a multiple of 512 bits

# DevEd

- [ ] Contribute to [this playlist](https://github.com/supertestnet/bitvm_deved_videos) of youtube videos documenting how to write apps for bitvm
- [ ] Make text tutorials documenting how to write apps for bitvm
- [ ] Contribute to [the FAQ](https://github.com/PraiseTheMithra/BitVm-FAQ) -- it should have less tech-talk and focus more on a high level overview of what we're doing (this will help devs AND everyone else too)
- [ ] Help me improve the visual look and feel of [this showcase](https://supertestnet.github.io/tapleaf-circuits/) of bitvm apps (fork it [here](https://github.com/supertestnet/tapleaf-circuits/), make it better, do a PR)

# Money

- [ ] Devs can be either *attracted* to a project or *hired* for a project, or both. If you can't contribute via code, consider giving money so Robin can *hire* devs to work on bitvm: bc1qf5g6z0py2t3t49gupeqrlewga0qz2etalu4xf9

# Meta

- [ ] Contribute to this todo list with other ideas for making bitvm great (click the Fork button above and do a PR with your changes)
