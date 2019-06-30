# 4d-plugin-rsvg

#### pixman-0.38.4

#### libxml2-2.9.9

#### freetype-2.10.0

```
Library configuration:
  external zlib: yes (pkg-config)
  bzip2:         yes (autoconf test)
  libpng:        yes (pkg-config)
  harfbuzz:      no=>yes (pkg-config)
```

#### cairo-1.16.0

#### harfbuzz-2.5.3

--with-coretext=yes --enable-static

```
Build configuration:

Unicode callbacks (you want at least one):
	Builtin			true
	Glib:			false
	ICU:			true

Font callbacks (the more the merrier):
	FreeType:		false=>true

Tools used for command-line utilities:
	Cairo:			false
	Fontconfig:		false

Additional shapers (the more the merrier):
	Graphite2:		false

Platform shapers (not normally needed):
	CoreText:		true
	DirectWrite:		false
	Uniscribe:		false

Other features:
	Documentation:		no
	GObject bindings:	false
	Introspection:		false
```
