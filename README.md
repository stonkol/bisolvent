# Bisolvent

Binary problem solver, for complex and simple routine decisions.

*The dissolvent that output a binary solution to your problems*

## 1. Intro



## 2. Related Packages

1. For interactive TUI elements:
    - Use **[tview](https://pkg.go.dev/github.com/rivo/tview)** instead of bubble tea
    - Advanced CLI features, really popular: Use [Cobra](https://github.com/spf13/cobra) for  (subcommands, flags)
    - [urfave/cli](https://github.com/urfave/cli): A simple, fast, and fun package for building command line apps. Great for straightforward tools and widely adopted.

1. Use one of these libraries:
    - Go’s built-in [`flag`](https://pkg.go.dev/flag) for simple needs.
    - For more advanced libraries like [`docopt`](https://github.com/docopt/docopt.go) (It is useful for more human-friendly and flexible CLI designs.) or [`getopt`](https://pkg.go.dev/github.com/pborman/getopt/v2) for complex command-line parsing-rather than writing your own parser from scratch. This ensures your CLI handles flags and arguments reliably and consistently across platforms.

1. Output styling – For coloring and styling your CLI output to improve user experience.
    1. [color](https://pkg.go.dev/github.com/gookit/color) - Terminal color rendering library, support 8/16 colors, 256 colors, RGB color rendering output, support Print/Sprintf methods, compatible with Windows.  (*zh*)
