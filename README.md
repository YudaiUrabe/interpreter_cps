# interpreter_cps

* Install `dune` and `ppx_inline_test`: `opam install dune ppx_inline_test`

* Create the project: `dune init proj interpreter_cps`

* Directory Structure
```
interpreter_cps/
├── bin/                 # Directory for execution files
│   ├── main.ml          # Entry point
│   └── dune
├── lib/                 # Directory for interpreter
│   ├── interpreter.ml   # Define functions like eval here
│   └── dune
├── test/                
│   ├── test.ml
│   └── dune
├── dune-project         # Project configuration file
├── interpreter_cps.opam  # opam configuration file
└── .gitignore           # Git configuration
```
* add modules to `lib/`
* `dune build`
* `dune test`

