# Homebrew tap for kwant

[kwant](https://kwant.si) is a self-hosted team of AI bots with handoffs, approvals and routines.
This tap installs `kwnt`, its server and command line, on macOS and Linux.

```sh
brew install alexsergivan/kwant/kwnt
kwnt --version
kwnt serve        # then open http://127.0.0.1:8799
```

Homebrew builds `kwnt` from the release's source tag, so the first install takes a few minutes
(it uses Node and Rust while building; both stay build-only).

- **Updates:** `brew upgrade kwnt`. Each kwant release updates `Formula/kwnt.rb` here.
- **The Mac app** (with the menu bar and the window) is the .dmg on the
  [releases page](https://github.com/alexsergivan/kwant/releases); it isn't in this tap.
- **Problems:** open an issue in [alexsergivan/kwant](https://github.com/alexsergivan/kwant/issues).

The formula's source copy lives in the kwant repo at `packaging/homebrew/kwnt.rb`.
