<p align="center">
  <a href="https://github.com/joelpurra/jqnpm"><img src="https://rawgit.com/joelpurra/jqnpm/master/resources/logotype/penrose-triangle.svg" alt="jqnpm logotype, a Penrose triangle" width="100" border="0" /></a>
</p>

# [jq-tools](https://github.com/ekho/jq-tools)

experimental jq tools

This is a package for the command-line JSON processor [`jq`](https://stedolan.github.io/jq/). Install the package in your jq project/package directory with [`jqnpm`](https://github.com/joelpurra/jqnpm):

```bash
jqnpm install joelpurra/jq-tools
```



## Usage


```jq
import "joelpurra/jq-tools" as Tools;

# Tools::myFirstFunction
"World" | Tools::myFirstFunction		# "Hello World!"
```



---

## License
Copyright (c) 2016 Boris Gorbylev <http://ekho.name>
All rights reserved.

When using **jq-tools**, comply to the MIT license. Please see the LICENSE file for details.
