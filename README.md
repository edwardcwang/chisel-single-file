# chisel-single-file
Single-file Chisel design demo.

This repo is a demo of a single-file Chisel design. For more complex designs, we recommend using [chisel-template-lite](https://github.com/edwardcwang/chisel-template-lite) or [chisel-template](https://github.com/freechipsproject/chisel-template) as it provides more standardized testing and build infrastructure.

# Requirements
* JRE. On Debian/Ubuntu this can be installed with:`sudo apt-get install openjdk-8-jre`
* Ammonite in your path. You can run `source sourceme.sh` to pull it locally for demonstration purposes if you'd like.

# Usage
1. (optional if you have `amm` in your `$PATH` already) Run `source sourceme.sh` to download and put Ammonite in your path.
2. Run `./GCD.scala` to elaborate the GCD Chisel design.
3. Open `GCD.v` and examine the elaborated Verilog.
