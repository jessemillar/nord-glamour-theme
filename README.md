# Nord Theme for Glamour

[`glamour`](https://github.com/charmbracelet/glamour) is the Markdown renderer used by the [GitHub CLI](https://github.com/cli/cli). I'd like the colors used when rendering Markdown to match [Nord](https://www.nordtheme.com/) (my color theme of choice).

[`nord.json`](nord.json) represents an attempt at creating a `glamour` theme that matches Nord as closely as possible. `glamour` does not currently have full color support and converts hex colors to the closest 256 color theme.

The GitHub CLI currently does not have a way to set the `glamour` theme that is used. I'll likely have to create a PR to add that functionality.
