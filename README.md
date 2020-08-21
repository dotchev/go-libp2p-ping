# go-libp2p-ping

Ping example using [go-libp2p](https://github.com/libp2p/go-libp2p)

Based on https://docs.libp2p.io/tutorials/getting-started/go/ with some improvements. ;)

## Running

```sh
go run .
```
Copy the address from the output.

In a separate console
```sh
go run . <address>
```
The second node will ping the first one and print the latency.

**Hint:** you can run it also against [js-libp2p-ping](https://github.com/dotchev/js-libp2p-ping)