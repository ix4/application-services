**See [the release process docs](docs/howtos/cut-a-new-release.md) for the steps to take when cutting a new release.**

# Unreleased Changes

## General

- Updated NSS to version 3.48. ([#2379](https://github.com/mozilla/application-services/issues/2379))

## Logins

### Breaking Changes

- `LoginsStorage.getByHostname` has been removed ([#2152](https://github.com/mozilla/application-services/issues/2152))

### What's new

- `LoginsStorage.getByBaseDomain` has been added ([#2152](https://github.com/mozilla/application-services/issues/2152))

## Logins

### What's new

- Added ability to rekey the database via `rekeyDatabase`. [[#2228](https://github.com/mozilla/application-services/pull/2228)]

[Full Changelog](https://github.com/mozilla/application-services/compare/v0.43.1...master)

- Removed hard deletion of `SyncStatus::New` records in `delete` and `wipe` logins database functions. ([#2362](https://github.com/mozilla/application-services/pull/2362))