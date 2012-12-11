The `Xenbigarray` module is equivalent to the standard Bigarray module in the
OCaml standard library, with the exception that the UNIX-specific function
calls are removed (specifically, the `map_file` family of `mmap` functions).

Note that installing this module will *remove* the existing Bigarray module,
and so this is really designed to be used as a hidden dependency from within
OPAM.  Be careful if you're installing it outside of an OPAM switch.

Anil Madhavapeddy
