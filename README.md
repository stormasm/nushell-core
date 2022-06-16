
This is up and running for nushell 0.64.0

The job of this repo is to call into a minimal set of commands
where nu-command is the starting point and then we pare things
back from there...

A barebones example of nu-command is
[nu-command-core](https://github.com/stormasm/nu-command-core)
which is just the core-commands and nothing else...

With this crate as the basis you can build up crates from
here that add additional commands commands.  The following
crates are a superset of nu-command-core...
