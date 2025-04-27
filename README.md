# bisolvent
binary problem solver, for complex and simple routine decisions

### Technical

### Libraries may use
Use [Cobra](https://github.com/spf13/cobra) for advanced CLI features (subcommands, flags) or BubbleTea for interactive TUI elements.

The recommendation is to use one of these libraries, starting with Go’s built-in [`flag`](https://pkg.go.dev/flag) for simple needs.

Or for more advanced libraries like [`docopt`](https://github.com/docopt/docopt.go) (It is useful for more human-friendly and flexible CLI designs.), or [`getopt`](https://pkg.go.dev/github.com/pborman/getopt/v2) for complex command-line parsing-rather than writing your own parser from scratch. This ensures your CLI handles flags and arguments reliably and consistently across platforms.
