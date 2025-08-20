# io.github.orontee.Argos #

This is a technical repository to publish
[Argos](http://github.com/orontee/argos) through
[Flathub](http://flathub.org).

To validate manifest before publishing:

``` bash
$ flatpak run --command=flatpak-builder-lint \
          org.flatpak.Builder \
		  manifest io.github.orontee.Argos.json
```

Usefull links:

- [Argos sources](http://github.com/orontee/argos)
- [Argos flathub page](https://flathub.org/apps/details/io.github.orontee.Argos)
- [Flathub wiki](https://github.com/flathub/flathub/wiki)
