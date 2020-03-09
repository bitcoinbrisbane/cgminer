## Building
```bash
./autogen.sh
CFLAGS="-O2 -Wall -march=native" ./configure --enable-blockerupter --enable-icarus
make
./cgminer -o stratum+tcp://pool.bitcoinbrisbane.com.au:3256 -u 1DugongACGcyyvvgvcy8skYyezsx5jy3aV -p Test --api-allow 127.0.0.1 --api-listen
```

## Running the miner
`./cgminer -o stratum+tcp://pool.bitcoinbrisbane.com.au:3256 -u 1DugongACGcyyvvgvcy8skYyezsx5jy3aV -p Test --api-listen --api-allow W:192.168.1.0/24`

Run API client
