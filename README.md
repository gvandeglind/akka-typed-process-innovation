# akka-typed-process-innovation
experiment with akka-typed-process

## Setup IRC server

git clone https://github.com/jrosdahl/miniircd.git

cd miniircd

./miniircd --debug --verbose

## Basic session

```
telnet localhost 6667 

USER ruben * * :Test
NICK ruben

telnet localhost 6667
USER gerard * * :Test
NICK rubendg
PRIVMSG gerard Hoi
```