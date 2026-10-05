<!-- tyhp-readme:start -->
# tyhpdef/spatie-error-solutions

Tyhp type definitions for `spatie/error-solutions` `1.1.3`.

```bash
composer require --dev tyhpdef/spatie-error-solutions:1.1.3
```

This is a metapackage. Composer also installs `tyhpdef/spatie-error-solutions-impl` (type files).
Require **this** name, not `tyhpdef/spatie-error-solutions-impl`.

See https://tyhplang.com.

## Maintain `spatie/error-solutions`? Ship the types yourself

If you are a Packagist maintainer of `spatie/error-solutions`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/spatie-error-solutions-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `spatie/error-solutions` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/spatie-error-solutions": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `spatie/error-solutions` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `spatie/error-solutions` with a real constraint,
   `"replace": { "tyhpdef/spatie-error-solutions": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `spatie/error-solutions` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/spatie-error-solutions` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
