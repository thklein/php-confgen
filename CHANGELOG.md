# Changelog

## 0.5.0 (2015-07-29)

*   BC break / Feature: Path to "templates" is relative to definition – other paths to PWD
    ([#22](https://github.com/clue/php-confgen/pull/22))

*   Fix: Apply proper file permissions (chmod mode)
    ([#20](https://github.com/clue/php-confgen/pull/20))

*   Maintenance: Refactor file system related functionality
    ([#21](https://github.com/clue/php-confgen/pull/21))

## 0.4.0 (2015-07-24)

*   Feature: Add confgen bin
    ([#13](https://github.com/clue/php-confgen/pull/13))

*   Feature: Optionally pass custom `Twig_Environment` and `JsonSchema\Validator` to `Factory`
    ([#17](https://github.com/clue/php-confgen/pull/17))

*   Feature: Use correct template name for template syntax Exceptions
    ([#14](https://github.com/clue/php-confgen/pull/14))

*   Improved documentation

## 0.3.0 (2015-07-21)

*   Feature: Add configuration definition
    ([#12](https://github.com/clue/php-confgen/pull/12))

*   Feature: Validate meta-data against JSON schema definition
    ([#11](https://github.com/clue/php-confgen/pull/11))

*   BC break / Feature: Consistent file handling and error reporting for Confgen
    ([#10](https://github.com/clue/php-confgen/pull/10))

## 0.2.0 (2015-07-20)

*   Feature: YAML front matter is optional
    ([#9](https://github.com/clue/php-confgen/pull/9))

*   Feature: "target" definition is now optional and defaults to template name
    ([#8](https://github.com/clue/php-confgen/pull/8))

## 0.1.0 (2015-07-19)

*   First tagged release
