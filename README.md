[![Maven Package](https://github.com/stornado/jurest/actions/workflows/maven-publish.yml/badge.svg)](https://github.com/stornado/jurest/actions/workflows/maven-publish.yml)

# JuRest

```bash
cp archetype-catalog.xml ~/.m2/repository/archetype-catalog.xml
cp aliyunmaven.xml ~/.m2/settings.xml
```

```bash
mvn archetype:generate \
    -DarchetypeGroupId=com.zxytech.jurest \
    -DarchetypeArtifactId=jurest-modules-archetype \
    -DartifactId=jurest-examples \
    -DgroupId=com.zxytech.jurest.examples
```

## Example

```bash
git clone --depth=1 https://github.com/stornado/jurest-examples.git
```

## License

[Apache License](LICENSE)
