# 4d-plugin-rsvg

#### fontconfig-2.13.91

``--enable-static``

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

```
The following surface backends:
  Image:         yes (always builtin)
  Recording:     yes (always builtin)
  Observer:      yes (always builtin)
  Mime:          yes (always builtin)
  Tee:           no (disabled, use --enable-tee to enable)
  XML:           no (disabled, use --enable-xml to enable)
  Xlib:          no (requires X development libraries)
  Xlib Xrender:  no (requires --enable-xlib)
  Qt:            no (disabled, use --enable-qt to enable)
  Quartz:        yes
  Quartz-image:  no (disabled, use --enable-quartz-image to enable)
  XCB:           no (requires xcb >= 1.6 xcb-render >= 1.6 https://xcb.freedesktop.org)
  Win32:         no (requires a Win32 platform)
  OS2:           no (disabled, use --enable-os2 to enable)
  CairoScript:   yes
  PostScript:    yes
  PDF:           yes
  SVG:           yes
  OpenGL:        no (disabled, use --enable-gl to enable)
  OpenGL ES 2.0: no (disabled, use --enable-glesv2 to enable)
  OpenGL ES 3.0: no (disabled, use --enable-glesv3 to enable)
  BeOS:          no (disabled, use --enable-beos to enable)
  DirectFB:      no (disabled, use --enable-directfb to enable)
  OpenVG:        no (disabled, use --enable-vg to enable)
  DRM:           no (disabled, use --enable-drm to enable)
  Cogl:          no (disabled, use --enable-cogl to enable)

The following font backends:
  User:          yes (always builtin)
  FreeType:      yes
  Fontconfig:    no=>yes (requires fontconfig >= 2.2.95)
  Win32:         no (requires a Win32 platform)
  Quartz:        yes

The following functions:
  PNG functions:   yes
  GLX functions:   no (not required by any backend)
  WGL functions:   no (not required by any backend)
  EGL functions:   no (not required by any backend)
  X11-xcb functions: no (disabled, use --enable-xlib-xcb to enable)
  XCB-shm functions: no (requires --enable-xcb)

The following features and utilities:
  cairo-trace:                yes
  cairo-script-interpreter:   yes

And the following internal features:
  pthread:       yes
  gtk-doc:       no
  gcov support:  no
  symbol-lookup: no (requires bfd)
  test surfaces: no (disabled, use --enable-test-surfaces to enable)
  ps testing:    no (requires libspectre)
  pdf testing:   no (requires poppler-glib >= 0.17.4)
  svg testing:   no (requires librsvg-2.0 >= 2.35.0)
```

#### harfbuzz-2.5.3

``--with-coretext=yes --enable-static``

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
	Graphite2:		false=>true

Platform shapers (not normally needed):
	CoreText:		true
	DirectWrite:		false
	Uniscribe:		false

Other features:
	Documentation:		no
	GObject bindings:	false
	Introspection:		false
```
