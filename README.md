# Nimblesite Scoop Bucket

[Scoop](https://scoop.sh/) bucket for [Nimblesite](https://nimblesite.co) command-line tools on Windows.

## Usage

Add the bucket once:

```powershell
scoop bucket add nimblesite https://github.com/Nimblesite/scoop-bucket
```

Then install any of the tools:

```powershell
scoop install dart_mutant
# scoop install basilisk     # coming soon
# scoop install forge        # coming soon
```

To upgrade:

```powershell
scoop update
scoop update dart_mutant
```

## Available manifests

| App | Description | Repo |
|---|---|---|
| `dart_mutant` | Mutation testing tool for Dart | [Nimblesite/dart_mutant](https://github.com/Nimblesite/dart_mutant) |

## Updating

Each project's `release.yml` workflow updates its own manifest in this bucket
on every tagged release. Do not edit manifests by hand unless you know what
you're doing.

## Layout

```
scoop-bucket/
└── bucket/
    └── dart_mutant.json
```

Manifests live in `bucket/` per the [Scoop bucket template
convention](https://github.com/ScoopInstaller/BucketTemplate).

## License

Each manifest's license matches its upstream project. Bucket metadata is MIT.
