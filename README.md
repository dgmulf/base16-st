# Base16 ST

A Base16 patch templates to configure the colors for the
[simple terminal](https://st.suckless.org/). See the
[Base16 repository](https://github.com/chriskempson/base16) for more
information.

There are two versions of patches: the basic ones modify only 16 ANSI colors
keeping the 256 colorspace intact, while the \*-256 instead use colors 17-21 for 
additional base16 colors, just as
[Base16 Shell](https://github.com/chriskempson/base16-shell) does.

## Installation

Use `patch` to apply the .diff file corresponding to your chosen color
scheme in the `diffs/` directory to `config.def.h`, as per standard suckless
patching protocol.
