# 3.2.0

- Added RemoteExecutionError, CancelExecutionError

[https://github.com/91team/computer/pull/16](https://github.com/91team/computer/pull/16)

# 3.1.0

- Allow workers to pull from queue on creation.

[https://github.com/91team/computer/pull/12](https://github.com/91team/computer/pull/12)
# 3.0.0

- **Breaking change:** The old instance factory method (`Computer()`) has been replaced with `Computer.shared()`
- You can now create new instances of the `Computer` by using `Computer.create()` this allows for specific instances for specific tasks groups

# 2.0.0

- Migrated to nullsafety

# 1.1.1

- Formatted source code according to dartfmt

# 1.1.0

- **BREAKING**: `areLogsEnabled` renamed to `verbose`
- Added docs to public API
- Updated Readme
- Bumped minimum dart version to 2.4.0
- Added new tests

# 1.0.2

- Fixed typos & turnOn()

# 1.0.1

- Added README, fixed pub package troubles

# 1.0.0

- Published package
