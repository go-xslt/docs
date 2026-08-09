# go-xslt

Pure-Go XSLT.

go-xslt is a pure-Go (CGO_ENABLED=0) XSLT processor: it applies XSL transformations over a pure-Go XML DOM (go-nokogiri), with no libxslt and no cgo.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target. Licensed BSD-3-Clause.

## Packages

<div class="pk-grid" markdown>
<a class="pk-card" href="packages/xslt.md"><code>xslt</code><br><small>XSLT processor over a pure-Go XML DOM (go-nokogiri) — no libxslt, no cgo.</small></a>
</div>
