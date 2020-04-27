# ocaml-rust-starter

An example project using [ocaml-rs](https://github.com/zshipko/ocaml-rs).

## New project checklist

- [ ] Update `README.md`
- [ ] Update the project name in `dune-project`
- [ ] Update the crate name in `Cargo.toml`
- [ ] Update `src/dune` and `test/dune` with the name of your project in place of `ocaml_rust_example`/`ocaml-rust-example`
- [ ] Rename `ocaml-rust-starter.opam` to match the name of your project
- [ ] Remove `src/ocaml_rust_example.ml` and `src/ocaml_rust_example.mli` and add your own OCaml files
- [ ] Edit `src/lib.rs`
- [ ] Add your tests to `test/test.ml`

## Building

    dune build

to run the tests:

    dune runtest


