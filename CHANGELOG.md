
<a name="v1.01"></a>
## [v1.01](https://github.com/rigred/sandsifter/compare/v1.0...v1.01) (2018-08-30)

sandsifter now requires the user to explicitly specify a path if they wish to store logs to non-volatile storage.
This additionally adds `is_valid_write_path(parser, arg)` function to validate if the data directory exists and is empty.

Changed global OUTPUT path variable to `/tmp/sandsifter/data`

Changed several messages to print output paths where they can be helpful.

Program searches for injector in `/usr/bin/injector` and `./injector`

<a name="v1.0"></a>
## v1.0 (2018-08-28)

### Injector

* fix array initializer

### Makefile

* Explicitly link as no PIE
* Add `-f` switch to `rm` to suppress errors

### Summarize

* fix collapse all

### Pull Requests

* Merge pull request [#1](https://github.com/rigred/sandsifter/issues/1) from ariscop/argparse

