# aarch64 (arm64) / amd64 (x86\_64) wheels

## sources

* [SQLite source code](https://www.sqlite.org/download.html)
* [pysqlite3 source code](https://github.com/coleifer/pysqlite3/tags)
* [pysqlite3 project page on PyPI](https://pypi.org/project/pysqlite3)

## targets

| Python version | arch                          | libc version     |
| -------------- | ----------------------------- | ---------------- |
| cp311          | x86\_64 (`-march=nehalem`)    | manylinux2014    |
| cp311          | aarch64 (`-mcpu=neoverse-n1`) | manylinux2014    |
| cp312          | x86\_64 (`-march=nehalem`)    | manylinux\_2\_28 |
| cp312          | aarch64 (`-mcpu=neoverse-n1`) | manylinux\_2\_28 |

