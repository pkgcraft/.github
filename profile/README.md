## [Pkgcraft][blog]

Pkgcraft is a highly experimental tooling ecosystem for Gentoo targeting
efficiency and versatility that aims to support many languages leveraging a
shared, core implementation.

Compatibility with the official [package management specification][pmspec] is
aimed for, but not always adhered to. See the list of known [deviations] for
details.

Repos using custom profile-formats extensions are not supported for tools that
deal with profiles, see the [related issue][profile-formats] for details.

More information about the project can be found on its [FAQ] and
[development blog][blog].

### Core components

- [scallop]: bash library
- [pkgcraft]: core library
- [pkgcraft-tools]: command-line tools
- [pkgcruft]: QA library and tools
- [arcanist]: package-building daemon

### Language bindings

- [C]
- [Python]
- [Go]
- [Ruby]
- [Perl]

[faq]: <https://pkgcraft.github.io/about/>
[blog]: <https://pkgcraft.github.io/>
[scallop]: <https://github.com/pkgcraft/pkgcraft/tree/main/crates/scallop>
[pkgcraft]: <https://github.com/pkgcraft/pkgcraft/tree/main/crates/pkgcraft>
[pkgcraft-tools]: <https://github.com/pkgcraft/pkgcraft/tree/main/crates/pkgcraft-tools>
[pkgcruft]: <https://github.com/pkgcraft/pkgcraft/tree/main/crates/pkgcruft>
[arcanist]: <https://github.com/pkgcraft/pkgcraft/tree/main/crates/arcanist>
[pmspec]: https://wiki.gentoo.org/wiki/Project:Package_Manager_Specification
[deviations]: https://github.com/orgs/pkgcraft/discussions/134
[profile-formats]: https://github.com/pkgcraft/pkgcraft/issues/251

[c]: <https://github.com/pkgcraft/pkgcraft/tree/main/crates/pkgcraft-c>
[python]: <https://github.com/pkgcraft/pkgcraft-python>
[go]: <https://github.com/pkgcraft/pkgcraft-go>
[ruby]: <https://github.com/pkgcraft/pkgcraft-ruby>
[perl]: <https://github.com/pkgcraft/pkgcraft-perl>
