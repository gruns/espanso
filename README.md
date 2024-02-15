My experimental [Espanso](https://espanso.org/) configuration.

The goals of these expansions are collectively to:

  * Improve typing speed through commonly used abbreviations. E.g. `abt` -> `about`, `impltn` -> `implementation`, etc.
  * Use more emojis in conversation. Emojis better convey emotion, tone, and empathy. 🙂
  * Correct common typos. E.g. `teh` -> `the`.

These expansions are categorized by type, one category per file:

  * [phrases.yml](phrases.yml): Common text expansions for speed. E.g. `abt` -> `about`.
  * [emoji.yml](emoji.yml): Shorthand for commonly used emojis. E.g. `/)` for 🙂.
  * [flags-emoji.yml](flags-emoji.yml): Country flag emojis. E.g. `/swe` for 🇸🇪.
  * [typos.yml](typos.yml): Fixes for common typos. E.g. `teh` -> `the`.
  * [tests.yml](tests.yml): Miscellaneous expansion tests. Not meant for real-world usage.

And for more robust abbreviation completion, add these additional word separators to your Espanso configuration file in `~/Library/Application Support/espanso/config/default.yml`:

  * `word_separators: [" ", ",", ".", "?", "!", ")", "}", "]", ">", "\r", "\n", "\t", "\'", "\"", "\x0c", ":", ";"]`