# BigchainDB Server

BigchainDB is the blockchain database. This repository is for _BigchainDB Server_.


```text
git clone https://github.com/bigchaindb/bigchaindb.git
cd bigchaindb
make run
```

BigchainDB should be reachable now on `http://localhost:9984/`.

There are also other commands you can execute:

* `make start`: Run BigchainDB from source and daemonize it (stop it with `make stop`).
* `make stop`: Stop BigchainDB.
* `make logs`: Attach to the logs.
* `make test`: Run all unit and acceptance tests.
* `make test-unit-watch`: Run all tests and wait. Every time you change code, tests will be run again.
* `make cov`: Check code coverage and open the result in the browser.
* `make doc`: Generate HTML documentation and open it in the browser.
* `make clean`: Remove all build, test, coverage and Python artifacts.
* `make reset`: Stop and REMOVE all containers. WARNING: you will LOSE all data stored in BigchainDB.

To view all commands available, run `make`.



