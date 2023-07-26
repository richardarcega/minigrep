# minigrep

A miniature version of the classic command line search tool `grep` (**g**lobally search a **r**egular **e**xpression and
**p**rint). In the simplest use case, `grep` searches a specified file for a specified string. Minigrep takes as its 
arguments a string and a file path. It then reads the file, finds lines in that file that contain the string argument, 
and prints those lines.

## Usage
To run minigrep, execute the binary with the search string and the file to search:
```bash
$ ./minigrep text file.txt
```

## Build
```bash
$ cargo build
```

## Test
```bash
$ cargo test
```

## License

Copyright 2023 Richard Arcega

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
