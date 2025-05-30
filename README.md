# pixoo-openapi
OpenAPI implementation for Divoom Pixoo 64 devices

## Mission
Based on the documentation from Divoo, manually create an openapi specification file. 

Use the specification to generate client libraries for different languages following best practices

## Client libraries

First follow the install steps to install [openapi-generator-cli.jar](https://github.com/OpenAPITools/openapi-generator?tab=readme-ov-file#13---download-jar)

### Python, with asyncio support

    java -jar openapi-generator-cli.jar generate --input-spec .\openapi.yml --generator-name python --library asyncio --output python-asyncio

## Sources used

### Divoom
* https://divoom.com/apps/help-center#hc-pixoo64developeropen-sourcesdkapiopen-source

That gives us:
* http://doc.divoom-gz.com/web/#/12?page_id=89

Where the contact page:
* http://doc.divoom-gz.com/web/#/12?page_id=143

Send us to
* http://docin.divoom-gz.com/web/#/5/23

OLDER REFERENCES
* http://doc.divoom-gz.com/web/#/12
* http://doc.divoom-gz.com/web/#/7
* http://doc.divoom-gz.com/web/#/5

### openapi-generator
https://github.com/OpenAPITools/openapi-generator

### JSON 2 OpenAPI Generator
https://roger13.github.io/SwagDefGen/

