# Contributing

Feel free to create an issue, or a pull request.

## Release process

Perform test first

```shell
mvn clean package -Pnative
```

1. Maven release
```
mvn clean release:prepare release:perform
```
2. Wait till [Deploy to registries](https://github.com/websitecd/content-git/actions?query=workflow%3A%22Deploy+to+Registries%22) completes.
3. Create a [Github release](https://github.com/websitecd/content-git/releases) based on the latest tag and document the release.
