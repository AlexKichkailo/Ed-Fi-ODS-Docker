# Ed-Fi Web Gateway Sandbox
Provides docker deployment for nginx as a proxy for the Ed-Fi ODS/API, along with the SwaggerUI, and the Sandbox Admin tool.

## Image Links
- [2.2.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.2.0/Web-Gateway-Sandbox/Alpine/Dockerfile)
- [2.1.4](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.4/Web-Gateway-Sandbox/Alpine/Dockerfile)
- [2.1.3](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.3/Web-Gateway-Sandbox/Alpine/Dockerfile)
- [2.1.2](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.2/Web-Gateway-Sandbox/Alpine/Dockerfile)
- [2.1.1](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.1/Web-Gateway-Sandbox/Alpine/Dockerfile)
- [2.1.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.1.0/Web-Gateway-Sandbox/Alpine/Dockerfile)
- [2.0.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v2.0.0/Web-Gateway-Sandbox/Alpine/Dockerfile)
- [1.1.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v1.1.0/Web-Gateway-Sandbox/Dockerfile)
- [1.0.0](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/v1.0.0/Web-Gateway-Sandbox/Dockerfile)

## Image Variants
The only supported image at this time is an Alpine-based implementation using [nginx](https://hub.docker.com/_/nginx).

`edfialliance/ods-api-web-gateway-sandbox:<version>`

## Supported Environment Variables
```
ODS_VIRTUAL_NAME=<virtual name for the ods endpoint>
SANDBOX_ADMIN_VIRTUAL_NAME=<virtual name for the sandbox admin endpoint>
```

## License Information
View [license information](https://github.com/Ed-Fi-Alliance-OSS/Ed-Fi-ODS-Docker/blob/main/LICENSE) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc. from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
