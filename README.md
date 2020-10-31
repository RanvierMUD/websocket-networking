This bundle is a _very_ basic sample implementation of using websockets
instead of telnet.

To enable, replace `"telnet-networking"` bundle in `ranvier.json` with
`"websocket-networking"`.

An example websockets client compatible with this bundle can be downloaded
from [github.com/ranviermud/neuro](https://github.com/ranviermud/neuro).

When using `websocket-networking` it is suggested that you set the
`playerTickFrequency` and `entityTickFrequency` configurations in `ranvier.json`
to faster than the default 100ms to allow for smoother rendering of data on
the client.
