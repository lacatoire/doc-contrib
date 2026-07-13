# doc-contrib

Third-party PHP extension documentation.

This repository hosts documentation for PHP extensions distributed outside the PHP core, primarily PECL extensions and other community-maintained packages. It mirrors the structure and tooling of [php/doc-en](https://github.com/php/doc-en).

## Background

This repository is the outcome of the [Separation of Third-Party Extension Documentation RFC](https://wiki.php.net/rfc/third-party-code), accepted in June 2026. Documentation for bundled PHP extensions remains in [php/doc-en](https://github.com/php/doc-en).

## Contributing

Contribution guidelines follow [php/doc-en](https://github.com/php/doc-base/blob/master/docs/contributing.md). Join the discussion on the [phpdoc mailing list](mailto:phpdoc@lists.php.net).

## Local setup

```bash
git clone https://github.com/php/doc-contrib en
git clone https://github.com/php/doc-base
php doc-base/configure.php --disable-libxml-check --with-lang=en
```
