# Usage

Run `python3 main.py` to run tests.
By default, the script will look for the tarball solution in the script's directory.

Optional arguments:
- `--save-subprocesses-outputs <name>` - writes verbose information to dump files `<name>.out` and `<name>.err`. This includes `insc_jvm`, `insc_llvm`, `java`, `lli` and `diff`
- `--tar-location` - tarball parent path or tarball itself

Handling of errors in Instant programs, such as:

- invalid syntax,
- division by zero,
- use of undeclared variables,
- int32 overflow,
- etc.

is not tested, as it is not required by the assignment.
