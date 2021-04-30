# Pure-FTPd configured in Docker with SFTP and PostgreSQL support

In this playground, I want to create a [Pure-FTPd](https://github.com/jedisct1/pure-ftpd/) Docker Image with [SFTP](https://github.com/jedisct1/pure-ftpd/blob/289f3b85c674a1d11082ad302024b6df9fa88db4/FAQ#L264) and [PostgreSQL Auth support](https://github.com/jedisct1/pure-ftpd/blob/master/README.PGSQL).

Some resources:

- [`stilliard/docker-pure-ftpd`](https://github.com/stilliard/docker-pure-ftpd)
- [`vgist/dockerfiles`](https://github.com/vgist/dockerfiles/tree/master/pure-ftpd)

## Start

```sh
$ ./scripts/up.sh
```
