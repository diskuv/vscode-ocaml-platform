# Developing

## Quick Start

FIRST, install the OCaml dependencies and generate the OCaml -> Javascript
artifacts:

```bash
opam install gen_js_api js_of_ocaml jsonoo opam-file-format promise_jsoo
make build
```

SECOND, press F5 in VS Code to launch the "Extension Development Host".

## Code Hygiene

```bash
esy
yarn
make fmt
make test
```
