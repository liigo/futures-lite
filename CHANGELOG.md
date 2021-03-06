# Version 1.0.0

- Add `StreamExt::map()`.
- Add `StreamExt::count()`.
- Add `StreamExt::filter()`.
- Add `StreamExt::filter_map()`.
- Rename `future::join()` to `future::zip()`.
- Rename `future::try_join()` to `future::try_zip()`.

# Version 0.1.11

- Update `parking` to v2.0.0

# Version 0.1.10

- Add `AssertAsync`.

# Version 0.1.9

- Add `FutureExt::or()`.
- Put `#[must_use]` on all futures and streams.

# Version 0.1.8

- Fix lints about unsafe code.

# Version 0.1.7

- Add blocking APIs (`block_on()` and `BlockOn`).

# Version 0.1.6

- Add `boxed()`, `boxed_local()`, `Boxed`, and `BoxedLocal`.

# Version 0.1.5

- Add `fold()` and `try_fold()`.

# Version 0.1.4

- Add `future::race()`.
- Fix a bug in `BufReader`.

# Version 0.1.3

- Add `future::join()`, `future::try_join()`, and `AsyncWriteExt::close()`.

# Version 0.1.2

- Lots of new APIs.

# Version 0.1.1

- Initial version
