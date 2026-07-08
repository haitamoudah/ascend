# faq

## where is my data?

everything lives in a single sqlite database on your machine, at `%APPDATA%/Ascend/ascend.db` on windows. nothing leaves your computer.

## how do backups work?

a snapshot of the database is written every day on launch, and the newest 7 are kept. an extra snapshot is taken before any import or restore. you can restore a snapshot from settings > data, and a full json export and import lives there too.

## is there telemetry?

no. no analytics, no crash reporting, no accounts, no network calls of any kind.

## can i contribute code?

the project is closed to external code contributions. bug reports and feature requests are welcome in [issues](https://github.com/haitamoudah/ascend/issues).

## why does windows warn me during install?

the installer is not code-signed, so smartscreen may show a prompt. choose "more info", then "run anyway". you can verify the download against the sha256 listed in the release notes.
