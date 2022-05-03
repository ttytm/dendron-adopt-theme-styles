# dendron-adopt-theme-styles

_Related to the open dendron issue: [2812](https://github.com/dendronhq/dendron/issues/2812)_

Make dendron adopt styles of a vscode theme.<br>
This repo currently does this post installation.<br>
It mainly removes colors set by dendron's styles so vscodes / the themes colors are not overwritten.

If one wants to use it this way, change the given styles in the extensions directory.

E.g. on linux the default is:

~/.vscode-_oss*_/extensions/dendron.dendron-_[version]_/

\*-oss when using codium

It would be great if someone helped to create a pull request that implements those styles on a core level.
