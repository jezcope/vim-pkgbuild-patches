Author: Jez Cope <j.cope@erambler.co.uk>

This is a set of patches I use to build a customised version of vim on
ArchLinux.

1. Install [quilt][];
2. Get the vim PKGBUILD and associated files from ABS;
3. Clone this repository into the vim PKGBUILD directory as patches;
4. Do "quilt push -a";
5. Run makepkg and install the result.

[quilt]: http://mybravenewworld.wordpress.com/2007/11/13/quilt-patch-management/
