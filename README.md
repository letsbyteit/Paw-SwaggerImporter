[![Build Status](https://travis-ci.org/luckymarmot/Paw-SwaggerImporter.svg?branch=master)](https://travis-ci.org/luckymarmot/Paw-SwaggerImporter)

# Swagger Specification Importer (Paw Extension)

A [Paw Extension](http://luckymarmot.com/paw/extensions/) to import [Swagger](http://swagger.io/) Specification into Paw. (**JSON/YAML** supported)

#### Notice :

Only [Swagger schema 2.0 specification](https://github.com/swagger-api/swagger-spec/blob/master/versions/2.0.md) supported -> [Swagger 1.2 to 2.0 Migration Guide](https://github.com/swagger-api/swagger-spec/wiki/Swagger-1.2-to-2.0-Migration-Guide).

## How to use?

* In Paw, go to File menu, then Import...
* Pick the saved Swagger file, and make sure the Format is "Swagger Importer"

## Development

### Build & Install

install dependencies

```shell
npm install
```

in order to get the cake command, you might need to run

```shell
npm install -g coffee-script
```

then build and run with cake

```shell
cake build
cake install
```

### Watch

During development, watch for changes:

```shell
cake watch
```

## License

This Paw Extension is released under the [MIT License](LICENSE). Feel free to fork, and modify!

Copyright © 2014 Paw Inc.

## Contributors

See [Contributors](https://github.com/luckymarmot/Paw-SwaggerImporter/graphs/contributors).
