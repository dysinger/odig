
- Drop `mtime` package dependency.
- `metagen` and `linkable` binaries are gone.
- Drop the data-driven toplevel loaders. Use the `omod` project for this.
- Drop the `guess-deps` and `graph` commands.
- Drop the best-effort `ocamldoc` support and corresponding command.
- Drop the `help` command. Documentation is now in `odig`'s API docs
  to make it referencable and web linkable. This is where the tutorial and
  the packaging conventions now live. See `odig doc odig`.

v0.0.3 2017-10-31 Zagreb
------------------------

- Fix obscure build bug on 4.06.0 (#32)

v0.0.2 2017-05-31 Cambridge (UK)
--------------------------------

- Added experimental data-driven toplevel loaders.
- The `odoc` API documentation is shown by default on `odig doc`.
- The `mli`, `cmi`, `cmo`, `cmti`, `cmx` and `cmt` commands are grouped in
  the `cobjs` command.
- Track latest cmdliner and mtime.

v0.0.1 2016-09-23 Zagreb
------------------------

First release. The ocamldoc release.
