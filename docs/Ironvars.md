Ironvars are runtime variables that can be referenced in several places in your config, 
then set using the IPC server (such as via the CLI) using the `set` command.

Any UTF-8 string *without whitespace* is a valid key. 
Any UTF-8 string is a valid value.

Reference values using `#my_variable`. These update as soon as the value changes.

You can set defaults using the `ironvar_defaults` key in your top-level config.