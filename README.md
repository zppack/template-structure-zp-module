# template-structure-zp-module

A template to create a zp module for initialization.

This zp module itself is of type `template-structure`.

## Features

- [x] input template type
- [x] generate file directory structure
- [x] generate zp module config directory and files

## Project directory structure

```bash
.
├── /template-structure/           # main template directory of zp module
│   ├── /.zp/                      # zp module config files directory
│   │   ├── /.zp-module.toml       # zp module config
│   │   └── /.zp-vars.toml         # zp module middleware config
│   ├── README.md                  # template file
│   └── package.json               # template file
├── [files not important]
├── package.json
└── README.md
```

## Recently changes

See the [change log](CHANGELOG.md).

## License

[MIT](LICENSE)
