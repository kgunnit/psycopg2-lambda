psycopg2 module for lambda
==========================

psycopg2 module compiled on an Amazon Linux AMI for use in a lambda to connect to Redshift

### Files

- `psycopg2` - module compiled without ssl support
- `psycopg2-ssl` - module compiled with ssl support

### Use

Copy `psycopg2` to lambda zip for upload or copy `psycopg2-ssl` to lambda zip and rename to `psycopg2` for upload.

## Resources

[PostgreSQL source code](https://ftp.postgresql.org/pub/source/v9.4.3/postgresql-9.4.3.tar.gz)
[psycopg2 source code](http://initd.org/psycopg/tarballs/PSYCOPG-2-6/psycopg2-2.6.1.tar.gz)
