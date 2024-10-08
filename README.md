# Infisical secret management platform

For more information about this product, please refer to
the [Infisical documentation](https://infisical.com/docs/documentation/getting-started/introduction).

This repository provides a Docker Compose setup to run Infisical in our
environment.

## Configuration

This repository includes a `.infisical.env` file. In any production setup, it
should be overridden with a `.env.docker.local` file. For detailed
information about configuration options, refer to
the [Infisical documentation on configuration environment variables](https://infisical.com/docs/self-hosting/configuration/envars).

Copy the content into your `.env` file and adjust the values as necessary.

```shell
cat .infisical.env >> .env.docker.local
```
