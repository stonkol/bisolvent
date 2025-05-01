# bisolvent
binary problem solver, for complex and simple routine decisions

### Technical

### Libraries may use


1. For interactive TUI elements:
    - Use **[tview](https://pkg.go.dev/github.com/rivo/tview)** instead of bubble tea
    - Advanced CLI features, really popular: Use [Cobra](https://github.com/spf13/cobra) for  (subcommands, flags)

1. Use one of these libraries:
    - Go’s built-in [`flag`](https://pkg.go.dev/flag) for simple needs.
    - For more advanced libraries like [`docopt`](https://github.com/docopt/docopt.go) (It is useful for more human-friendly and flexible CLI designs.) or [`getopt`](https://pkg.go.dev/github.com/pborman/getopt/v2) for complex command-line parsing-rather than writing your own parser from scratch. This ensures your CLI handles flags and arguments reliably and consistently across platforms.
