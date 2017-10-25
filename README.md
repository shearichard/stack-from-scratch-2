# Stack from Scratch Sandbox #
## Overview ##
My sandbox for investigating https://github.com/verekia/js-stack-from-scratch/blob/master/tutorial/01-node-yarn-package-json.md#readme

## Notes about the polo dev env ##
On polo both yarn and Node are installed in a slightly odd way. Long term it would be good to deinstall both and install them properly

== Notes about React / Redux ==
react-redux connects a Redux store with React components. With react-redux, when the Redux store changes, React components get automatically updated. They can also fire Redux actions.
```
     ------------------------
     |                      |
     |                      |
     |  React Components    |
     |                      |
     |                      |
     ------------------------
                ^
                |
                |
                |
                |
     ------------------------
     |                      |
     |                      |
     |    React / Redux     |
     |                      |
     |                      |
     ------------------------
                ^
                |
                |
                |
                |
     ------------------------
     |                      |
     |                      |
     |     Redux Store      |
     |                      |
     |                      |
     ------------------------
```
