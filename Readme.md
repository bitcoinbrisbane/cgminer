Building
```
./autogen.sh
CFLAGS="-O2 -Wall -march=native" ./configure --enable-blockerupter --enable-icarus
make
./cgminer -o stratum+tcp://pool.bitcoinbrisbane.com.au:3256 -u 1DugongACGcyyvvgvcy8skYyezsx5jy3aV -p Test --api-allow 127.0.0.1 --api-listen
```

Run API client
