# Cryfs Blocks

This program was written to test the size of the blocks generated by [Cryfs](https://www.cryfs.org/). It was based on the [issue #70](https://github.com/cryfs/cryfs/issues/70). These tests are performed with different sizes of the blocks:

  - Standard size block (32 kb, quoted in Example 1)
  - Block size of (4 mb / 4096 kb, quoted in Example 2)
  - Block size of (1 mb / 1024 kb)
  - Solution 2 (dynamic blocks with a pre-set table by the user)
  - Solution 3 (dynamic blocks and randm size, with a pre-set table by the user)
  - Solution 4 (dividing blocks into pieces of different sizes. **favorited by me**)

To make these simple tests was used the following technologies:

  - [Lazarus](http://www.lazarus-ide.org/) (version 1.6.0, fpc-3.0.0, 64bits)
  - [Sqlite](https://www.sqlite.org/) (version 3.14.2, Precompiled Binaries for Windows)
