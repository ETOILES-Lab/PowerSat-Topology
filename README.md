# PowerSat-Topology

## Requirements
1. Install [fprime-layout](https://github.com/fprime-community/fprime-layout) (FPL) and all dependencies. Add to path.
    * Read the wiki in this repository for information on the FPL syntax
2. Install [fprime-visual](https://github.com/fprime-community/fprime-visual) and all dependencies.

## How to run
1. Clone the repository using `git clone git@github.com:ETOILES-Lab/PowerSat-Topology.git`
2. Run `./convert` to convert the text files into json files
3. Run `nodemon /path/to/fprime-visual/server/index.js ./.fpv-env`
4. Type `localhost:3000` into your browser to use the visualization tool!
