### 1.0.11

* TagOptions now defaults to strip=False (see #7). list and quote tags have been set to strip=True, as they are typically block-level elements anyway.
* A new "drop_unrecognized" option was added to the Parser. If set to True, unrecognized tags will be dropped (the default is to render them as regular text).

### 1.0.10

* Small bugfix concerning render_embedded (see #6).

### 1.0.9

* Escape quotes correctly to prevent XSS (see #4).

### 1.0.8

* Fixed a bug where escaping and cosmetic replacements were incorrectly performed on URLs (f6e0c11).
