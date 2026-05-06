[My](https://github.com/gruns) [Espanso](https://espanso.org/) configuration.

The goals of these expansions are collectively to:

  * Improve typing speed through commonly used abbreviations. E.g. `abt` -> `about`, `impltn` -> `implementation`, etc.
  * Use more emojis in conversation. Emojis better convey emotion, tone, and empathy. 🙂
  * Minimize typos by minimizing the number of keypresses.
  * Correct common typos. E.g. `teh` -> `the`.

These expansions are categorized by type, one category per file:

  * [phrases.yml](phrases.yml): Common text expansions for speed. E.g. `abt` -> `about`.
  * [emoji.yml](emoji.yml): Shorthand for commonly used emojis. E.g. `/)` for 🙂.
  * [typos.yml](typos.yml): Fixes for common typos. E.g. `teh` -> `the`.
  * [software-engineering.yml](software-engineering.yml): Software expansions. For nerds. E.g. `sfw` -> `software`.
  * [flags-emoji.yml](flags-emoji.yml): Country flag emojis. E.g. `/swe` for 🇸🇪.

And for more robust abbreviation completion, add these additional word separators to your Espanso configuration file in `~/Library/Application Support/espanso/config/default.yml`:

  * `word_separators: [" ", ",", ".", "?", "!", ")", "}", "]", ">", "\r", "\n", "\t", "\'", "\"", "\x0c", ":", ";"]`