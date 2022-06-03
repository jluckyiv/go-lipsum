# Go-lipsum

This is a Go port of [node-lipsum](https://github.com/traviskaufman/node-lipsum/)

### CLI options
```shell
usage: node-lipsum [-h] [-v] [-s] [-w {paras,words,bytes}] [-a AMOUNT]

The CLI for the NodeJS Lorem Ipsum Service

Optional arguments:
  -h, --help            Show this help message and exit.
  -v, --version         Show program's version number and exit.
  -s, --start-with-lipsum
                        Whether or not the text should start with "Lorem 
                        Ipsum dolor sit amet...".
  -w {paras,words,bytes}, --what {paras,words,bytes}
                        The type of each text structure that will be returned.
                         Choose from "paras" (paragraphs), "words", or "bytes"
  -a AMOUNT, --amount AMOUNT
                        The number of text structures that will be returned. 
                        Defaults to 5.
```

### URL samples
```
https://lipsum.com/feed/json?start=yes&what=paras&amount=2
https://lipsum.com/feed/json?start=yes&what=words&amount=2
https://lipsum.com/feed/json?start=yes&what=bytes&amount=2
https://lipsum.com/feed/json?start=yes&what=lists&amount=2

```
