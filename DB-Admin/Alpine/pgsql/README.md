# Ed-Fi Admin Databases

Provides docker deployment for **_EdFi_Admin_** and **_EdFi_Security_** database
implementations on PostgreSQL 13. The databases are installed when the image is
started for the first time.

**Note: This image does not include any pre-installed vendors and is suitable
for production use.**

## Image Links
- [2.2.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.2.0/DB-Admin/Alpine/pgsql/Dockerfile)
- [2.1.4](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.4/DB-Admin/Alpine/pgsql/Dockerfile)
- [2.1.3](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.3/DB-Admin/Alpine/pgsql/Dockerfile)
- [2.1.2](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.2/DB-Admin/Alpine/pgsql/Dockerfile)
- [2.1.1](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.1/DB-Admin/Alpine/pgsql/Dockerfile)
- [2.1.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.0/DB-Admin/Alpine/pgsql/Dockerfile)
- [2.0.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.0.0/DB-Admin/Alpine/pgsql/Dockerfile)
- [1.1.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v1.1.0/DB-Admin/Dockerfile)
- [1.0.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v1.0.0/DB-Admin/Dockerfile)

## Image Variants

The only supported image at this time is an Alpine-based implementation using
[PostgreSQL 13](https://hub.docker.com/_/postgres).

`edfialliance/ods-api-db-admin:<version>`

## Supported Environment Variables

``` none
API_MODE=<Sandbox | SharedInstance>
POSTGRES_USER=<default PostgreSQL database user>
POSTGRES_PASSWORD=<password for default PostgreSQL user>
```

## License Information

View [license
information](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/main/LICENSE)
for the software contained in this image.

As with all Docker images, these likely also contain other software which may be
under other licenses (such as Bash, etc. from the base distribution, along with
any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to
ensure that any use of this image complies with any relevant licenses for all
software contained within.
