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

### PMD Check

check your case codes using PMD & CPD

![PMD](./assets/screenshot.pmd.result.png)

![CPD](./assets/screenshot.cpd.result.png)


### Cases Result

show your case results using Allure

![Allure](./assets/screenshot.allure.result.png)

## License

[Apache License](LICENSE)
