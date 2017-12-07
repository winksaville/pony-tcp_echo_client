# Tcp echo client written in Pony

A [Pony](https://ponylang.org) TCP client that sends a
text message to a server over a TCP connection and
expects the server to echo the data back.

# Compile
```
$ cd tcp_echo_client
$ ponyc ../tcp_echo_client
```
# Run
Start server in one terminal window:
```
wink@wink-envy:~/prgs/ponylang/tcp_echo_client (master)
$ ../tcp_echo_server/tcp_echo_server

```
In another terminal window run the client:
```
wink@wink-envy:~/prgs/ponylang/tcp_echo_client (master)
$ ./tcp_echo_client 
GOT:hello world
```

# Acknowledgements
From the [actor TCPConnection](https://github.com/ponylang/ponyc/blob/master/packages/net/tcp_connection.pony) documentation in the [ponyc](https://github.com/ponylang/ponyc) repo.
