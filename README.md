# Things bitvm needs
A todo list for making bitvm great

# Implementations

- [ ] Create github repos for more implementations of the BitVM
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
- [ ] Make a high level programming language that compiles programs down to the "bristol formatted" logical circuits that bitvm currently uses

# DevEd

- [ ] Make youtube videos documenting how you write apps for BitVM
- [ ] Make text tutorials documenting how you write apps for BitVM
