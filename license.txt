# Trongate on Ice

A stability-focused edition of the [Trongate](https://github.com/trongate/trongate-framework) PHP framework.

Trongate on Ice gives you a dependable, consistent foundation to build on, without the framework changing underneath you.

## What is Trongate on Ice?

Trongate on Ice was forked from Trongate version **2.2026.1019**, the latest version of the original framework at the time. Unlike the main Trongate repository, it does not routinely receive new features, refactoring or general development updates. It is maintained conservatively and changes only when there is a compelling reason.

It remains part of the Trongate ecosystem. It is based on the original framework, uses the same conventions, and works the same way, so existing Trongate knowledge and documentation still apply.

## Why does it exist?

Software that keeps evolving is not always what you want. Sometimes you want something that stays put.

Imagine following a tutorial series on building an online shop. With a fast-moving framework, returning to that tutorial two or three years later can mean discovering that the code no longer behaves as it did. Trongate on Ice exists to reduce that risk. A tutorial written against it should still make sense, and still work, long after it was written.

## Who is it for?

- Authors of tutorials, courses and books who need a framework that will not shift under their readers.
- Students and teachers working through educational projects.
- Developers building applications where long-term stability matters more than new features.

If you want the latest features and ongoing development, use the [main Trongate framework](https://github.com/trongate/trongate-framework) instead.

## How it differs from the main Trongate framework

| | Trongate (main) | Trongate on Ice |
|---|---|---|
| Priority | Ongoing development | Stability and predictability |
| New features | Added over time | Generally not added |
| Refactoring and cosmetic changes | Part of normal development | Generally excluded |
| Keeping pace with the main branch | Yes | No |
| Approach to change | Active | Conservative |

Trongate on Ice is based on Trongate version **2.2026.1019**.

## Maintenance policy

Trongate on Ice should change only when there is a compelling reason. Changes may be made to address:

- **Security vulnerabilities** or other significant security concerns.
- **Compatibility issues** arising from changes to PHP or other fundamental underlying technologies.
- **Critical defects** that undermine the reliability or intended functionality of the framework.

The following should generally be excluded:

- New features.
- Cosmetic improvements.
- Routine refactoring.
- Changes made merely to keep pace with the main Trongate development branch.

The priority is long-term stability, predictability and reliability rather than continuous development. This does not mean the framework will never change. Security, compatibility and critical defect fixes remain possible, and where changes are made, they are intended to be minimal and carefully considered.

## Why Trongate?

- High performance ([benchmarks](https://trongate.io/benchmarks))
- Stability-focused
- Zero dependencies
- No Composer

## Requirements

- PHP 8+
- `gd` module loaded in `php.ini` (for image uploader)
- `intl` module loaded in `php.ini` (for `url_title()` string helper)
- MariaDB or MySQL

## Resources

[Documentation](https://trongate.io/documentation)

[Discussion Forums](https://trongate.io/forums)

[Main Trongate framework repository](https://github.com/trongate/trongate-framework)

## Contributing

Contributions that fit the [maintenance policy](#maintenance-policy) are welcome: security fixes, compatibility fixes and fixes for critical defects. Please open an issue to discuss your proposed change before submitting a pull request.

Feature requests and general improvements are better suited to the [main Trongate framework](https://github.com/trongate/trongate-framework), as they fall outside the scope of this repository.

## Licence

Released under the [MIT License](http://opensource.org/licenses/MIT). See `license.txt` for more details.