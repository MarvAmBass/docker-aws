# docker-aws
alpine based aws-cli container [x86 + arm]

this is a multiarch build.

## Usage

```
docker run --rm -ti -v "$HOME/.aws:/root/.aws" marvambass/aws sh
```

or use the `docker-compose.yml` with `docker-compose`
