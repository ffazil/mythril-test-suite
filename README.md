# Installation

 - Docker Desktop

# Test suite

## Run first test

$ mkdir 001

$ git clone https://github.com/ffazil/mythril-test-suite.git

$ cd mythril-test-suite/

$ docker run -v $PWD/data:/data mythril/myth -v4 analyze /data/mythx-tests/05222022-25/SelfDestructMultiTxFeasible.sol