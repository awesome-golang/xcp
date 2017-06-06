xcp
====

The cross application, network and os copy-paste w/ web-browser view

USAGE
-----

    xcp [<name>]
    -p <port>
    -v verbose

Use `-p` to specify a port number, and `-v` to turn on logging to stdout. If no `<name>` is specified, then one will automatically be generated.

Start xcp on one machine then start on another machine, and copy paste to the xcp commandline or open a browser to on a machine running xcp and view the contents in a web browser.

    http://localhost:<port>/<name>

If multicast is setup then things will work across the network, otherwise a TCP host will need to be setup. The second server will need the same port and name to connect to directly. A browser can only be used between two or more connections.