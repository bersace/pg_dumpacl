# Contributing

## Releasing a new version

- Increment version in `pg_dumpacl.spec`
- Add a changelog entry in `pg_dumpacl.spec`
- Commit changes in `master` with message `Version X.Y`.
- Tag commit with `X.Y`.
- Push tag and commit in upstream repository.
- Build rpms with `make rpms`. RPM files are in `rpms/x86_64`.
