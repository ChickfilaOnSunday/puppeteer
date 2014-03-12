# puppeteer

It's time for a framework for super l337 exploit development!

We spent a lot of time, and a lot of implementation effort, making programs dance the way we want them. Why not automate some of that?

## Features

- targeted read
- targeted write
- printf stuff

- PLT redirection
- callsite preparation

## TODO

- stack overwrite
- command injection
- blind command injection

- return addr overwrite
- library dumping
- stack frame dumping
- environment dumping
- information leak (ASLR)
- execute command
- read file(s)
- dump out process maps?

- maybe have some idalink support for determining more stuff automatically?
- rop stuff (at least find the cleanup gadgets automatically)
- identify the base address of libc, or just dump it
- implement the pwntools library searching stuff
