# doc-contrib

Third-party PHP extension documentation.

This repository receives documentation for PHP extensions migrated *out of* [php/doc-en](https://github.com/php/doc-en) — primarily abandoned or unmaintained PECL extensions that no longer belong in the core manual. It mirrors the structure and tooling of [php/doc-en](https://github.com/php/doc-en).

## Background

This repository is the outcome of the [Separation of Third-Party Extension Documentation RFC](https://wiki.php.net/rfc/third-party_code), accepted in June 2026. Documentation for bundled PHP extensions remains in [php/doc-en](https://github.com/php/doc-en).

This repository is intended to be transferred to the php organization once the migration workflow is validated on the first batch of extensions.

## Translations

Currently, only English documentation is hosted here. Translation support and directory structure (`lang/` folders) are under discussion and will be addressed before broader adoption.

## Contributing

Contribution guidelines follow [php/doc-en](https://github.com/php/doc-base/blob/master/docs/contributing.md). Join the discussion on the [phpdoc mailing list](mailto:phpdoc@lists.php.net).

## Local setup

```bash
git clone https://github.com/php/doc-contrib en
git clone https://github.com/php/doc-base
php doc-base/configure.php --disable-libxml-check --with-lang=en
```
