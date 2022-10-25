# Useful Commands

* MONITOR: outputs (almost) all commands sent by clients. (however can slow performance - probably don’t run carelessly in production)
* SLOWLOG GET <N>: the slowlog tracks slow commands in memory, where you configure what is slow (and how many commands to keep), IIUC this is relatively safe? Don’t quote me.
* INFO ALL : outputs a bunch of info. I used MONITOR on staging and this command is being called already, so I guess its trivial
* LOLWUT: prints version and a new image every time. amazing
