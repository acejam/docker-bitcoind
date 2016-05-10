# Bitcoin Pruning

To enable pruning pass the `-prune=xxxx` option to the command line.

Example with only 5GB used for data:

    docker run --volume bitcoind-data:/bitcoin --rm  -it kylemanna/bitcoind btc_oneshot -prune=5000

